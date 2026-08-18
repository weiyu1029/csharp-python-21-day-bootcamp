# C# + Python 21 Day Bootcamp

這個 repository 是 21 天 C# 與 Python 學習計畫的練習空間。

## 開發環境

- .NET SDK 10
- Python 3.13（專案虛擬環境位於 `.venv`）
- Git
- Visual Studio Code
- C# Dev Kit、Python、Pylance 擴充套件

## 專案結構

```text
.
├── .venv/                    # Python 虛擬環境（不納入 Git）
└── csharp/
    └── Day01.HelloWorld/     # 第一個 C# Console 專案
```

## 開始使用

啟用 Python 虛擬環境：

```bash
source .venv/bin/activate
python --version
```

執行 C# Console 專案：

```bash
dotnet run --project csharp/Day01.HelloWorld
```

用 VS Code 開啟 repository：

```bash
code .
```

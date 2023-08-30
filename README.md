# Intro

Project to reproduce the `dotnet watch test` doesn't work bug.

```sh
dotnet --version
# 8.0.100-preview.7.23376.3

dotnet watch test --project Temp.Tests
```

There is not test failure message and the process restarts mutliple times without a file change.
# Golden-dotnet

This is my implementation of the [Getting started with .NET Core on macOS](https://docs.microsoft.com/en-us/dotnet/core/tutorials/using-on-macos) tutorial.

[![Build status](https://ydogandjiev.visualstudio.com/golden-dotnet/_apis/build/status/golden-dotnet%20-%20CI)](https://ydogandjiev.visualstudio.com/golden-dotnet/_build/latest?definitionId=9)

## Installing

```bash
git clone https://github.com/ydogandjiev/golden-dotnet.git
cd golden-dotnet
dotnet restore
```

## Running the app

```bash
dotnet run -p app/app.csproj
```

## Running the unit tests

```bash
dotnet test test-library/test-library.csproj
```

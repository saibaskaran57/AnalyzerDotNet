# AnalyzerDotNet  
[![Build Status](https://dev.azure.com/saibaskar57/saibaskar57/_apis/build/status/saibaskaran57.AnalyzerDotNet?branchName=master)](https://dev.azure.com/saibaskar57/saibaskar57/_build/latest?definitionId=2&branchName=master)
![Nuget](https://img.shields.io/nuget/v/AnalyzerDotNet)

.NET standard tooling build that leverages Roslyn analyzers, rulesets and additional configuration to be used for Code Analysis.

## Using AnalyzerDotNet

AnalyzerDotNet is recommended to be used on projects where you want to enforce code analysis & quality rules.

## Installation

AnalyzerDotNet can be installed using the NuGet command line or the NuGet Package Manager in Visual Studio 2019.

__Install using the command line:__
```
Install-Package AnalyzerDotNet
```

## Team Considerations
AnalyzerDotNet is recommended for Visual Studio 2019 analysis. If you use older versions of Visual Studio in addition to Visual Studio 2015 or Visual Studio 2017, you may still install these analyzers. They will be automatically disabled when you open the project back up in Visual Studio 2013 or earlier.

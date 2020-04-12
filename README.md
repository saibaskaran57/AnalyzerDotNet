# AnalyzerDotNet  
[![Build Status](https://dev.azure.com/saibaskar57/saibaskar57/_apis/build/status/saibaskaran57.AnalyzerDotNet?branchName=master)](https://dev.azure.com/saibaskar57/saibaskar57/_build/latest?definitionId=2&branchName=master)
![Nuget](https://img.shields.io/nuget/v/AnalyzerDotNet)

.NET standard tooling build that leverages Roslyn analyzers, rulesets and additional configuration to be used for Code Analysis.

## Objective

AnalyzerDotNet was designed to govern rules & standardize coding development as most of the ruleset may/may not be applicable. The project aims to add/remove rulesets from different providers to adjust based on agreed software development standards.

## Using AnalyzerDotNet

AnalyzerDotNet is recommended to be used on projects where you want to enforce code analysis & quality rules.

AnalyzerDotNet consumes the best practices from different rulesets(e.g. StyleCop, FxCop, SonarQube, etc) and here are the references:
1) [StyleCop Analyzer](https://github.com/DotNetAnalyzers/StyleCopAnalyzers/blob/master/DOCUMENTATION.md)
2) [SonarQube Analyzer](https://rules.sonarsource.com/csharp)
3) [FxCop Analyzer](https://github.com/dotnet/roslyn-analyzers/blob/master/src/Microsoft.CodeAnalysis.FxCopAnalyzers/Microsoft.CodeAnalysis.FxCopAnalyzers.md)
4) [Documentation Analyzer](https://github.com/DotNetAnalyzers/DocumentationAnalyzers/blob/master/DOCUMENTATION.md)

## Installation

AnalyzerDotNet can be installed using the NuGet command line or the NuGet Package Manager in Visual Studio 2019.

__Install using the command line:__
```
Install-Package AnalyzerDotNet
```

## Team Considerations
AnalyzerDotNet is recommended for Visual Studio 2019 analysis. If you use older versions of Visual Studio in addition to Visual Studio 2015 or Visual Studio 2017, you may still install these analyzers. They will be automatically disabled when you open the project back up in Visual Studio 2013 or earlier.

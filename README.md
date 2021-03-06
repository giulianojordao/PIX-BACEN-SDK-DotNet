# PIX (BACEN) .NET SDK

Brazilian instantly payments (PIX) powered by BACEN (Banco Central do Brasil) contracts ready to use for .NET projects.

PIX contracts available at: [bacen/pix-api](https://github.com/bacen/pix-api/) and [bacen/pix-dict-api](https://github.com/bacen/pix-dict-api)

[![GitHub license](https://img.shields.io/github/license/guibranco/PIX-BACEN-SDK-DotNet)](https://github.com/guibranco/PIX-BACEN-SDK-DotNet)
[![time tracker](https://wakatime.com/badge/github/guibranco/PIX-BACEN-SDK-DotNet.svg)](https://wakatime.com/badge/github/guibranco/PIX-BACEN-SDK-DotNet)

![PIX (BACEN)](https://raw.githubusercontent.com/guibranco/PIX-BACEN-SDK-DotNet/master/logo.png)

## CI/CD

| Branch | Build status | Last commit | Tests |
|--------|--------------|-------------|-------|
| Master | [![Build status](https://ci.appveyor.com/api/projects/status/epfv828r93depgv7/branch/master?svg=true)](https://ci.appveyor.com/project/guibranco/PIX-BACEN-SDK-DotNet/branch/master) | [![GitHub last commit](https://img.shields.io/github/last-commit/guibranco/PIX-BACEN-SDK-DotNet/master)](https://github.com/guibranco/PIX-BACEN-SDK-DotNet) | ![AppVeyor tests (branch)](https://img.shields.io/appveyor/tests/guibranco/PIX-BACEN-SDK-DotNet/master?compact_message) |
| Develop | [![Build status](https://ci.appveyor.com/api/projects/status/epfv828r93depgv7/branch/develop?svg=true)](https://ci.appveyor.com/project/guibranco/PIX-BACEN-SDK-DotNet/branch/develop) | [![GitHub last commit](https://img.shields.io/github/last-commit/guibranco/PIX-BACEN-SDK-DotNet/develop)](https://github.com/guibranco/PIX-BACEN-SDK-DotNet) | ![AppVeyor tests (branch)](https://img.shields.io/appveyor/tests/guibranco/PIX-BACEN-SDK-DotNet/develop?compact_message) |


## Code Quality
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/fb3b0b3876fb4e85a33ba9c891bfa3b3)](https://www.codacy.com/gh/guibranco/PIX-BACEN-SDK-DotNet/dashboard)
[![Codacy Badge](https://api.codacy.com/project/badge/Coverage/fb3b0b3876fb4e85a33ba9c891bfa3b3)](https://www.codacy.com/gh/guibranco/PIX-BACEN-SDK-DotNet/dashboard)
[![Codecov](https://codecov.io/gh/guibranco/PIX-BACEN-SDK-DotNet/branch/master/graph/badge.svg)](https://codecov.io/gh/guibranco/PIX-BACEN-SDK-DotNet)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=guibranco_PIX-BACEN-SDK-DotNet&metric=alert_status)](https://sonarcloud.io/dashboard?id=guibranco_PIX-BACEN-SDK-DotNet)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=guibranco_PIX-BACEN-SDK-DotNet&metric=coverage)](https://sonarcloud.io/dashboard?id=guibranco_PIX-BACEN-SDK-DotNet)

[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=guibranco_PIX-BACEN-SDK-DotNet&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=guibranco_PIX-BACEN-SDK-DotNet)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=guibranco_PIX-BACEN-SDK-DotNet&metric=ncloc)](https://sonarcloud.io/dashboard?id=guibranco_PIX-BACEN-SDK-DotNet)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=guibranco_PIX-BACEN-SDK-DotNet&metric=sqale_index)](https://sonarcloud.io/dashboard?id=guibranco_PIX-BACEN-SDK-DotNet)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=guibranco_PIX-BACEN-SDK-DotNet&metric=duplicated_lines_density)](https://sonarcloud.io/dashboard?id=guibranco_PIX-BACEN-SDK-DotNet)

[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=guibranco_PIX-BACEN-SDK-DotNet&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=guibranco_PIX-BACEN-SDK-DotNet)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=guibranco_PIX-BACEN-SDK-DotNet&metric=security_rating)](https://sonarcloud.io/dashboard?id=guibranco_PIX-BACEN-SDK-DotNet)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=guibranco_PIX-BACEN-SDK-DotNet&metric=code_smells)](https://sonarcloud.io/dashboard?id=guibranco_PIX-BACEN-SDK-DotNet)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=guibranco_PIX-BACEN-SDK-DotNet&metric=bugs)](https://sonarcloud.io/dashboard?id=guibranco_PIX-BACEN-SDK-DotNet)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=guibranco_PIX-BACEN-SDK-DotNet&metric=vulnerabilities)](https://sonarcloud.io/dashboard?id=guibranco_PIX-BACEN-SDK-DotNet)

---

## Installation

[![PIXBacen NuGet Version](https://img.shields.io/nuget/v/PIXBacen.svg?style=flat)](https://www.nuget.org/packages/PIXBacen/)
[![PIXBacen NuGet Downloads](https://img.shields.io/nuget/dt/PIXBacen.svg?style=flat)](https://www.nuget.org/packages/PIXBacen/)
[![Github All Releases](https://img.shields.io/github/downloads/guibranco/PIX-BACEN-SDK-DotNet/total.svg?style=flat)](https://github.com/guibranco/PIX-BACEN-SDK-DotNet)

Download the latest zip file from the [Release pages](https://github.com/guibranco/PIX-BACEN-SDK-DotNet/releases) or simple install from [NuGet](https://www.nuget.org/packages/PIXBacen) package manager.

NuGet URL: [https://www.nuget.org/packages/PIXBacen](https://www.nuget.org/packages/PIXBacen)

NuGet installation via *Package Manager Console*:

```ps

Install-Package PIXBacen

```
---

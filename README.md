---
description: Welcome to Terminaux!
---

# 👋 Welcome!

{% hint style="info" %}
Terminaux 5.x is currently under maintenance, but [under another branch](https://github.com/Aptivi/Terminaux/tree/x/oob/5.4.x). This series is supported until August 1st, 2026.

If you still use old versions of Terminaux in your projects, go to the below links:

[Terminaux 4.x - Manual](https://app.gitbook.com/o/fj052nYlsxW9IdL3bsZj/s/LICzQPcJvzuBfJRHqvLy/ "mention")

[Terminaux 3.x - Manual](https://app.gitbook.com/o/fj052nYlsxW9IdL3bsZj/s/OmlwECCRQY4XJQJZaeLc/ "mention")

[Terminaux 2.x - Manual](https://app.gitbook.com/o/fj052nYlsxW9IdL3bsZj/s/BAbXedIZJ6HPa9EGmSYt/ "mention")

[Terminaux 1.x - Manual](https://app.gitbook.com/o/fj052nYlsxW9IdL3bsZj/s/IcD1aLc5jxHMwvslhJIP/ "mention")
{% endhint %}

Terminaux is a library that contains all the common and the extra console tools that allow you to build productive console applications. Terminaux also provides a powerful color feature that lets you get an RGB color, convert color models, and so on.

To use this library, go to any page in the left side of the screen.

## Installation

This library is very easy to install. It's available at [NuGet](https://www.nuget.org/packages/TermRead/). Just follow these steps:

1. Open your project file (`.csproj` or `.fsproj`)
2. Place the `PackageReference` line on a property group like so:
   * `<PackageReference Include="Terminaux" Version="x.x.x" />`
   * ...where `Version` is the current version of the library
3. Run a package restore using `dotnet restore`

If you follow these steps correctly, you should be able to use the Terminaux functions.

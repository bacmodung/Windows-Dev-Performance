# Windows Developers' Issues

## Welcome to the Windows Developer (WinDev) Issues repo!

The purpose of this repo is to collect and catalog issues that affect / impact the inner loop of developers who work on Windows. The developer inner loop would include areas such as compile, run, build, test, debug, and commit. It doesn't matter if you're developing applications FOR Windows or applications that you plan to deploy on Linux, Android, IoT devices, servers, containers, or cloud - if you're building code ON Windows, we'd love to hear from you.

This repo is being driven and managed by a x-team, x-division group of PMs and engineers who're all passionate about improving developers' experience on Windows. We are already coordinating several streams of ongoing work with teams across the company and throughout the community, aiming to drive many issues to ground.

## Scope of this repo
Please take note of the current scope of this repo:

We are currently only accepting specific types of issues - those affecting / impacting the inner developer loop:
*compile
*run
*build
*test 
*debug
*commit

**[File an issue](https://github.com/microsoft/Windows-Dev-Performance/issues)**

### ✔ In Scope

At present we are accepting __developer-oriented performance issues__. Such issues include, for example:
* Dev tools (e.g. compilers, linkers, etc.) running slower on Windows than expected
* Runtime platforms (e.g. node, .NET, Python) running slower on Windows than other platforms
* Your apps experiencing file IO/networking/process-creation related perf issues
* Etc.

### ❌ Out of scope

If you have feedback/issues related to the following technologies, please file issues in their repos where the teams that own those technologies will be best able to help:

| Tech | Repo |
| --- | --- |
| Windows Terminal / Console / command-line | https://github.com/microsoft/terminal | 
| Windows Subsystem for Linux (WSL) | https://github.com/microsoft/wsl | 
| PowerShell | https://github.com/powershell/powershell | 
| PSReadLine - PowerShell's interactive command extensions | https://github.com/PowerShell/PSReadLine |
| OpenSSH for Windows | https://github.com/powershell/Win32-OpenSSH | 
| .NET Core runtime & libraries | https://github.com/dotnet/runtime |
| ASP\.NET Core | https://github.com/dotnet/aspnetcore |
| Roslyn (C# & Visual BASIC Compiler Platform) | https://github.com/dotnet/roslyn |
| Windows Presentation Foundation (WPF) | https://github.com/dotnet/wpf |
| WinForms | https://github.com/dotnet/winforms |
| WinUI | https://github.com/Microsoft/microsoft-ui-xaml |
| Winget package manager app | https://github.com/microsoft/winget-cli |
| Winget package repo | https://github.com/microsoft/winget-pkgs |
| PowerToys | https://github.com/microsoft/powertoys |
| Project Reunion | https://github.com/microsoft/ProjectReunion |

### Submit all other issues via Feedback Hub
If you have other out-of-scope feedback that you'd like to report/share, please submit via Windows' 10's [Feedback Hub](https://support.microsoft.com/en-in/help/4021566) which will route your feedback to the team that owns the technology you're experiencing issues with.

👉 Feedback Hub offers several very useful features that help us track-down complex issues, including the ability to record scenario-specific repro steps and traces. We may on occasion ask you to file an issue via Feedback Hub in order to collect these traces.

## Contributing
> We're not accepting PR's right now (currently, this is an issues-only repo), but if/when we do ...

Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

## Code of Conduct
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

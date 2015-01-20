# Steps to repro.

PM>  Get-Project Library | Install-Package Serilog.Extras.FSharp
Attempting to resolve dependency 'Serilog (= 1.4.128)'.
'Serilog.Extras.FSharp 1.4.128' already installed.
Adding 'Serilog 1.4.128' to ConsoleApp.
No exact match found for removing reference 'Serilog'. Trying case-insensitive search...
Failed to find match for removing reference 'Serilog'.
No exact match found for removing reference 'Serilog.FullNetFx'. Trying case-insensitive search...
Failed to find match for removing reference 'Serilog.FullNetFx'.
Install-Package : Failed to add reference to 'Serilog'.
At line:1 char:1
+ Install-Package Serilog.Extras.FSharp
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : NotSpecified: (:) [Install-Package], InvalidOperationException
    + FullyQualifiedErrorId : NuGetCmdletUnhandledException,NuGet.PowerShell.Commands.InstallPackageCommand

# Environment
Visual Studio 2013 on Windows Server 2012R2 w/latest F# PowerTools installed. 
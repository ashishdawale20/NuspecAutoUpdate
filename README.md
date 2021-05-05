# Nuspec Auto Update
A build script that can be included in TFS that update the versions of the dependencies in the '*.nuspec' file from the 'packages.config' file for every build.



How To Use
----
NuspecAutoUpdate.ps1 -NuspecPath "myPackage.nuspec" -PackagesConfigPath "packages.config"

NuspecAutoUpdate.ps1 -NuspecPath "C:\API\API.nuspec" -PackagesConfigPath "C:\API\packages.config"

Visual Studio Post Build Event
----
C:\WINDOWS\system32\windowspowershell\v1.0\powershell.exe  -ExecutionPolicy Unrestricted  -Command .'$(ProjectDir)..\PathToScirptLocation\NuspecAutoUpdate.ps1' -NuspecPath '$(ProjectDir)API.nuspec' -PackagesConfigPath '$(ProjectDir)packages.config'


<br><br>
**If you found this repository to be helpful, you can say "thank you" by clicking the "Star" button. Thanks :)**
[![Start Github|Solid](https://github.com/avrum/JenkinsFileFor.NETCore/blob/master/GithubClickStart.png)](https://github.com/avrum)


<br><br>
**"Sharing Is Caring" Please Contact Me For Merge Requests**
### Would appriciate if other developers and dev-ops will contribute this this project.



Contributions
----
* Aviram Fireberger (Me)
* Māris Krivtežs
* Ashish Dawale 

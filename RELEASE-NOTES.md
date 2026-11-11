Bayonet 0.1.44, built from 72c3615.

- **Update many NuGet packages at once:** after **Check for Updates**, the NuGet window shows **Update All** with the number of packages that have updates. Tick the ones you want to see **Update Selected** instead; the box in the header ticks or clears them all.
- **Package feeds:** the NuGet window's feed picker searches all enabled feeds or just one. **Manage Feeds** adds, edits, enables, disables and removes package sources, in your user settings or in the solution's `nuget.config`, the same way `dotnet nuget` does.
- **Open a solution or project:** **Open…** on the welcome screen and in the File menu now accepts a `.sln`, `.slnx` or `.csproj` as well as a folder. A solution opens its folder with that solution chosen; a project file inside an open solution opens in the editor.

macOS builds are not notarised yet: the first time, right-click Bayonet in Applications and choose **Open**.

- `Bayonet-Windows-Setup.exe`: Windows installer (version 0.1.43)
- `Bayonet-Windows.msi`: Windows MSI package (version 0.1.43)
- `Bayonet-macOS-AppleSilicon.dmg`: Apple Silicon
- `Bayonet-macOS-Intel.dmg`: Intel
- `Bayonet-Linux-amd64.deb`: Debian / Ubuntu (version 0.1.43)
- `Bayonet-Linux-x86_64.rpm`: Fedora / RHEL / openSUSE (version 0.1.43)

Installed copies update themselves: Bayonet checks for a newer version when it starts, and Help ▸ Check for Updates checks on demand. Download page: https://skuirrels.github.io/bayonet-releases/

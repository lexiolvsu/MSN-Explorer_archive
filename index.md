## About
The MSN Explorer Archive is a GitHub repository used to archive local versions of MSN Explorer that cannot be used today, along with it's servers. The specific versions are in the repository's branches, and also on [this webpage](https://lexiolvsu.github.io/MSN-Explorer_archive/versionlist/).

## Important
This is important information you must read before downloading anything from the MSN Explorer Archive.
### Virtual Machine Usage
You must use this in a virtual machine, or else none of these directions will apply.
### Compiling
A version from the MSN Explorer Archive is all contained inside of one `.MEZIP` file for compression purposes. In order to use a version, download the [MSN Explorer Extractor](https://github.com/lexiolvsu/MSN-Explorer_archive/tree/extractor), which you'll also need to open `.ME` files, as well as [MarEx](https://github.com/brz/MarEx) if you're using Version 6 or 7, just in case. MarEx is for `.MAR` files, which is a proprietary file format (`.MAR` means `MSN Archive`). Both are command-based tools.

1. Go to the releases of the MSN Explorer Extractor, and download the latest release.
2. Go into Command Prompt and do `mee d -i "<directory>" -o "<output>`.
3. Go to your output directory, and select the virtual machine you're using.
4. Select "VM" > "Settings", then go into the "Options" tab and select "Shared Folders".
5. Select "Always enabled", then click Add to add a shared folder. On Windows hosts, the Add Shared Folder wizard starts. On Linux hosts, the Shared Folder Properties dialog box opens.
6. Browse to, or type, the path on the host system to the directory to share, then specify the name of the shared folder as it should appear inside the virtual machine and click Next. Characters that the guest operating system considers illegal in a share name appear differently when viewed inside the guest. For example, if you use an asterisk in a share name, you see %002A instead of * in the share name on the guest. Illegal characters are converted to their ASCII hexadecimal value.
7. Select a shared folder attribute.
8. Click Finish to add the shared folder.
The shared folder appears in the Folders list. The check box next to folder name indicates that the folder is being shared. You can deselect this check box to disable sharing for the folder.
9. Click OK to save your changes.

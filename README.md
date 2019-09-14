# Path Editor

__This is a fork/mirror of the ultra-useful Path Editor by Masoom Shaikh, which appears to be unmaintained and was a victim of the CodePlex shutdown.__

Edit your PATH environment on Windows conveniently!

The default environment editor is not great at editing `PATH` if there are lot of entries and many of them are similar looking, or if your path is too long and it gives up entirely.

1. Implemented using Win32 API, does not depend on MFC or .NET
2. Missing folders are highlighted with different icon.
3. To edit System PATH, offers to be launched with elevated admin privilege, similar to "Run as Administrator"
4. Double clicking any path entry attempts to open in Windows Explorer.

![Path Editor usage](http://farm6.staticflickr.com/5528/9216019339_ea67407001_z.jpg)

## Download
See Releases tab.

## Building
1. Clone the repository.
2. Install Visual Studio 2017.  Make sure to add the "Desktop Development with C++" workload.
3. Open mak/PathEditor.sln
4. Build away!
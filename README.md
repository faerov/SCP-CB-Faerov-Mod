# SCP - CB Faerov Mod
SCP - Containment Breach Faerov Mod

The game is based on the works of the SCP Foundation community (http://www.scp-wiki.net/).

This game and the source code are licensed under Creative Commons Attribution-ShareAlike 3.0 License.

http://creativecommons.org/licenses/by-sa/3.0/

- ! Requirements: 
- • Blitz3D SMBF (https://github.com/faerov/Blitz3D-SMBF)
  
### How to build Blitz3D SMBF?

### Prepare

- Visual Studio Community 2022
  - Desktop development with C++
  - C++ MFC for latest v142 build tools (x86 & x64)
  - C++ ATL for latest v142 build tools (x86 & x64)
  - ASP.NET and web development

### Steps

1. Open `blitz3d.sln` in Visual Studio 2022.
2. Select Release or Debug config and rebuild the entire solution.
3. All done! You can find output files in the `_release` and `_release/bin` dirs. Feel free to delete `.pdb` and `.ilk` files here.

- **Note:** Blitz3D TSS uses the dynamic version of the fmod audio lib. 
  
  When redistributing programs built with Blitz3D SMBF, you will need to also include the `fmod.dll` file found in the `bin` directory with your programs. 
  
  This should be placed in the same directory as your program's executable.

- • Note: Blitz3D SMBF uses the dynamic version of the fmod audio lib.

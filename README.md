[Readme.md](https://github.com/user-attachments/files/24699085/Readme.md)

This project is licensed under the MIT License.

MIT License

Copyright (c) 2025 Cookiebaker2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

----------------------------------------------------------------------------------------------------------

Generate shortcuts from additional applications or external files with PEStartup (v1.1.7.0) or plugin. 
Together with StartAllBack and Explorer Shell Plugin.

<img width="1281" height="859" alt="Bkki6TFdHg" src="https://github.com/user-attachments/assets/68a8fac9-c4c2-47be-a4da-44b4bd7c4cb0" />

You can add shortcuts from files inside PhoenixPE or from external sources.

Inside PhoenixPE possible File Path is e.g.: 
%basedir%\Workbench\Additional\%SourceArch%\boot.wim\Program Files\Your Folder\Your.exe

Note: Not all programs are usable with shortcuts.
The C: drive cannot be used due to write restrictions of Windows.

There are two methods: PEStartup- and Extended shortcuts. PEStartup can set shortcuts after booting PhoenixPE.

Available drives for PEStartup will shown when pressing the button Check drive.

Select drive chooses the drive where PEStartup will be installed.
Be aware that there is no other folder called Program Files on external drive.

If PEStartup is not needed -> Select drive to: void.
If PEStartup should be on drive %drivexy% -> Select drive to: off.

PEStartup must be on the same drive as the applications whose shortcuts you want to use in PhoenixPE.

The settings can only be saved if PEStartup is on external drive."

# TextureExporter

This program transforms Texture (.tex) files used as textures by the game [Titan Quest](https://titanquestgame.com) to other formats:
* DDS (DirectDrawSurface)
* JPG (Joint Photographic Experts Group)
* PNG (Portable Network Graphics)
* PSD (Photoshop Document)
* TGA (Truevision Advanced Raster Graphics Adapter)

## A. How to use ?
1. Run the executable "TQTools - TextureExporter.exe"
2. Select a folder
    * All .tex files in this folder and subfolder will be transformed
    * All .tex files will be copied in the Exports folder located in the same folder as the executable
3. Choose the export format
    * All .tex files will be converted to the chosen format

## B. Requirements
*   Windows XP or newer operating system.

The releases provides 4 additional files that are necessary to run the program.
*   TextureViewer.exe (made by Max McGuire, see Help -> About)
    *   This file must not be moved. It must be in the same folder as "TQTools - TextureExporter.exe"

*   DevIL.dll (provided with the game files)
    *   This file must not be moved. It must be in the same folder as "TQTools - TextureExporter.exe"

*   msvcp71.dll
    *   This file can be moved in C:\Windows\System32 or be in the same folder as "TQTools - TextureExporter.exe"
    
*   msvcr71.dll
    *   This file can be moved in C:\Windows\System32 or be in the same folder as "TQTools - TextureExporter.exe"

## C. Issues
Use this repository Issues section using [ISSUE] as the header of your ticket's title.

## D. Features Requests & Suggestions
Use this repository Issues section using [REQUEST] as the header of your ticket's title.

*   The following requests are considered:
    *   Merge TextureViewer and TextureExporter. We are not in possession of TextureViewer source code. If you happen to have the source code, please contact us

*   The following request will not be made:
    *   Share the source code of TextureExporter

## E. Credits
This program is made in C++ using the Horae Library.

# Disclaimer
Not affiliated with THQ Nordic owner of the game and licence Titan Quest


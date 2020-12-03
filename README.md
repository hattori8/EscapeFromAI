C++で作っているゲーム(制作途中)
敵から逃げるゲームで、敵の動きにこだわったゲームを目指して作っています
→3Dにします
<img width="1022" alt="スクリーンショット 2020-12-02 17 11 21" src="https://user-images.githubusercontent.com/39850363/100846222-99499180-34c1-11eb-9b8a-939c4a94f122.png">

# GameProjectフォルダ
作っているゲームのコードが入っています
# Resourceフォルダ
gameprogcppのコード、変更はしてはならない
# WorkSpaceフォルダ
gameprogcppのコードと本をもとに実際作業するファイルが入っています
# Game Programming in C++ Code
This repository contains the source code for *Game Programming in C++* by Sanjay Madhav.

The source code for the chapters is released under the BSD 3-clause
license. See LICENSE for more detail. Note that this license does not apply to
the code in the External directory. Each External project is licensed separately.

# Building the Code
Each chapter's code is tested and works on both Microsoft Windows and Apple macOS.

To compile on Windows, install Microsoft Visual Studio 2017 Community
(https://www.visualstudio.com/downloads/). During installation, select the
"Game Development in C++" workflow. In each Chapter directory, there is a
corresponding ChapterXX-windows.sln file to open.

To compile on macOS, install Xcode from the App Store. Each chapter has
a corresponding ChapterXX-mac.xcodeproj file.

Code for Chapter 7 and beyond uses the FMOD API for audio. This requires
a separate installation from (https://www.fmod.com/download). Download
and install version 1.09.x of the FMOD Studio API (newer versions are untested).
On Windows, install FMOD to the default directory. On Mac, copy the contents
of the FMOD package into External/FMOD.

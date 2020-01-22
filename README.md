# Introduction

Mac OS X Catalina can only use 64-bit applications now. Unfortunately, it became incompatible with UMM which still requires some 32-bit code to work properly. This repo presents an temporary solution to use mods with Pathfinder:Kingmaker on a Mac.

# How

I have both Windows and Mac. All I did was install UMM on Windows following the documentation and then prepared the ZIP on this repo with the changed assets from that installation.

# Instructions

1. Create a folder /Applications/Mods. This is where you will have to manually unzip any mod you are considering to use.

2. Download ZIP file from this repo and copy contents into /Applications/Pathfinder Kingmaker/Contents/Resources/Data/Managed (ps: you might wanna first backup /Applications/Pathfinder Kingmaker/Contents/Resources/Data/Managed/UnityEngine.UIModule.dll as it gets overwritten in the process. This is the DLL UMM changes to install all required hooks and allow mods.

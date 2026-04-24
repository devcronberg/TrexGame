# T-Rex Runner (MonoGame implementation)

> **This is a fork of [Yeti47/TrexGame](https://github.com/Yeti47/TrexGame/) updated to run on .NET 10 with MonoGame 3.8.**
>
> The original game and all source code was written by [Yeti47](https://github.com/Yeti47). This fork was created by [Michell Cronberg](https://github.com/devcronberg) and updates the project to work with modern .NET.

A recreation of the T-Rex Runner game from Google Chrome, developed by Yeti47 using the MonoGame framework. All credits for the original game go to the Chromium team.

## Description
This is a MonoGame implementation of the T-Rex Runner game that is hidden as an easter egg in the Google Chrome browser. It is implemented in C# and was designed to be as close to the original as possible. The game was created by Yeti47 for a YouTube tutorial series, which can be found [here](https://www.youtube.com/playlist?list=PLG2i_rSSIXXoFdh3WCDtGumklyIXt4KiY).

### Original game:
![T-Rex Runner original](https://i.imgur.com/JWYfCy4.gif)

### Recreation:
![T-Rex Runner recreation](https://i.imgur.com/xaDLb0P.gif)

## Controls

Key | Action
----|-------
Space | Jump/Start Game
Down Arrow | Duck/Land
Escape | Exit Game
F12 | Toggle Window Size
F8 | Clear Highscore

## Getting Started

Follow these steps to run the game on your own machine.

### 1. Install the .NET 10 SDK

Download and install the .NET 10 SDK from Microsoft's official site:

👉 https://dotnet.microsoft.com/download/dotnet/10.0

Choose **Windows x64 – SDK Installer**, run it and follow the instructions.

Verify the installation by opening a terminal and running:
```
dotnet --version
```
You should see a version number starting with `10.`.

### 2. Install Visual Studio Code

Download VS Code here:

👉 https://code.visualstudio.com/

### 3. Install VS Code Extensions

Open VS Code and install these extensions (press `Ctrl+Shift+X` and search):

| Extension | Description |
|-----------|-------------|
| **C# Dev Kit** (Microsoft) | C# support, IntelliSense and debugging |

### 4. Install the MGCB Tool (MonoGame Content Builder)

MonoGame uses a content pipeline to compile game assets (images, sounds) into an optimised binary format at build time. The `dotnet-mgcb` tool is the compiler that does this work — without it the build will fail when it tries to process `Content.mgcb`.

Open a terminal and run:
```
dotnet tool install --global dotnet-mgcb
```

### 5. Clone the Repository

```
git clone https://github.com/devcronberg/TrexGame.git
cd TrexGame
```

### 6. Build and Run

```
cd TrexRunner
dotnet run
```

## Tutorial Series

The original game was built step by step in a YouTube tutorial series by Yeti47. If you want to understand how the game was made from scratch, check it out:

[![Tutorial Series](https://i.ytimg.com/vi/DJCQVJ83J1U/hqdefault.jpg?sqp=-oaymwEXCNACELwBSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLDBWqVd9wistTsGcd86-wLo_o-oNA)](https://www.youtube.com/playlist?list=PLG2i_rSSIXXoFdh3WCDtGumklyIXt4KiY)

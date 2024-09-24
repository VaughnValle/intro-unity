# Game Development with Unity

[Syllabus](/syllabus.pdf)

## Installation

-   Download [Unity Hub](https://unity.com/download)
-   Install Unity version `2021.3.16f1` [here](https://download.unity3d.com/download_unity/4016570cf34f/Windows64EditorInstaller/UnitySetup64-2021.3.16f1.exe)

## Dependencies

-   Unity Packages (ensure the ff. are checked in pkg manager)
    -   2D Sprite
    -   Visual Studio

## Setup

1.  Go to `Edit -> Preferences`
2.  Switch External Script Editor to Visual Studio
3.  Regenerate Project Files

## Chapters (by Week)

1. [Endless Runner](/endlessrunner.md)
2. []()
    - Vector2 vs Vector3
    - rigid bodies
    - Unity Scene Management
        - `using UnityEngine.SceneManagement;`
3. []()
    - effectors
        - onCollision
    - onTrigger
        - buoyancy
    - Questions:
        - prefab?
            - centralized assets
            - templates for gameObjects
4. [Unity UI](/unity-ui)

    - In Window -> Package Manager ensure the ff. are enabled
        - TextMeshPro
        - Unity UI
    - 2 Game Objects

        - Event System
            - Used to keep track of input and how the game reacts to different axes of input
        - Canvas, with the TMP as a child. Recommended settings:
            - Render mode: `Screen Space - Camera`
            - Drag Main Camera over to Render Camera
            - Change UI Scale Mode to: `Scale with Screen Size`
        - Create a Custom Script to handle UI element behavior via `Add Component`
        - Make sure to add the following libraries:
            - `using UnityEngine.UI`
            - `using TMPro`

    - Design `MainMenu` and `GameOver`
    - Sorting Layer
    - Work on MainMenu, GameOver, Win, and visually sync them together

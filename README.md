# Projectile Curve Visualizer In Unity

A plugin for rendering projectile paths in Unity.

## Description
Demo: https://youtu.be/Iza6R7ugU8U

This visualizer was implemented using pure C#, responsible for the visual part of projectile curve. The actual projectile prefab is also provided.

Demo scenes include:
1. Third-person projectile: Player can aim and throw projectiles.
2. Top-down tower defense(paper ball fight): Target position is already known, throwers will launch projectiles exactly to that point. Certain heuristic(thrower can predict the possible target location at real-time) is implemented for both moving thrower and moving target, which makes it more difficult to dodge.

## Technical details

Features:
* Lightweight
* Customizable
* Mobile friendly

\
Supported versions: Unity 2020.3.0f1 or newer

\
Supported Platforms:
* Windows
* macOS
* Linux
* Android
* iOS

\
Number of textures: 6

Texture dimensions: 512 x 512 pixels

Polygon count of ProjectileCurve

Minimum polygon count: 4

Maximum polygon count: 32

Number of meshes/prefabs: 2

Types of materials and texture maps: Mobile

\
Documentation: https://docs.google.com/document/d/1tq9zKovJtrqxcvQIZGkzpXpcLxjSe23Jig82o1fw8w0/edit?usp=share_link
+++
date = '2026-05-01T00:29:31-05:00'
draft = false
title = 'Aero Engine'
summary = "A raylib based game engine that allows for Lua scripting."
showDate = true
lastmod = '2026-05-01T00:29:31-05:00'
showReadingTime = true
featured = false
+++

## About The Project
This project was created for one of my college courses about programming different systems that tie together a game engine. This is the final product of this course, but I wanted to continue development of the project at some point, since it was one of the classes I had the most fun developing in.

The Aero project combines a C++ base with a Lua scripting interface to provide fast development timelines. The current implmentation of the engine has the following features:
- Currently written with mostly in C++ using Raylib as our base
- Small scale ECS GameObject system
- Custom scene file format
- Scripting capabilities using Lua

## Current State & Goals

The current implementation is very limited currently. There is no dedicated editor built to create scenes, there is only 2D capabilities, and limited physics integration. The project hopes to achieve these goals at the end of the development cycle:
- No C++ scripting from end-user
- Lots of different utilities for development
- Luau language Integration 
    - A language created for the ROBLOX game engine, but has been open-sourced for a while. It adds a lot of nice features for development within the Lua stack and is generally more feature-rich than regular Lua.
- Built out editor
- Outside library integrations
    - Jolt Physics Engine 
    - Either Vulkan Or DX12 Rendering Engine
    - FMOD Sound Engine
- Better IDE integration for properly referencing and documenting each class object and method

## [Repo Link](https://github.com/VG3O/AeroEngine)
I would like to import my project files into the repository soon when life is less busy to me. I will keep updating this article with more information about the state of the project when those happen.
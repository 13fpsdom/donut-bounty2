# Donut HUD (Fabric)

A lightweight client-side HUD starter for Minecraft Java 1.21.11 / Fabric.

## Features
- Coordinates (X / Y / Z)
- Facing direction
- FPS
- Current dimension
- Dark translucent panel with purple accent

This HUD is client-side only. It does not automate gameplay or change server state.

## Build
1. Install **JDK 21**.
2. Install IntelliJ IDEA or another Gradle-compatible Java IDE.
3. Open this folder as a Gradle project and allow it to sync.
4. Run `gradlew build` on Windows, or `./gradlew build` on Linux/macOS.
5. Copy the JAR from `build/libs/` into your Minecraft `mods` folder. Install Fabric API for the same Minecraft version too.

## Important
This source targets Minecraft 1.21.11 and uses the Fabric HUD registry API. I have not run a Gradle build in this environment, so treat it as source code to test in your local development setup. If Gradle reports an API or mapping mismatch, use the official Fabric HUD guide for the exact API version: https://docs.fabricmc.net/develop/rendering/hud

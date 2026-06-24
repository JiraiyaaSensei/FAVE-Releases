# F.A.V.E

**F.A.V.E — FFmpeg Audio & Video Encoder** is a Windows desktop application that provides an easy-to-use graphical interface for FFmpeg.

It is designed for users who want to encode, inspect, trim, and manage media files without manually writing FFmpeg commands.

## Download

Download the newest packaged version from the **Releases** section of this repository.

Under the release assets, download the file named similar to:

`FAVE-vX.X.X-Windows-x64.zip`

Do not download GitHub's automatically generated **Source code** archives. Those archives are not the complete F.A.V.E application package.

## Main Features

* Video, audio, subtitle, and attachment stream analysis
* Drag-and-drop media loading
* `libx264` and `libx265` software encoding
* `h264_nvenc` and `hevc_nvenc` NVIDIA hardware encoding
* Opus, AAC, FLAC, AC3 and libmp3lame audio encoding
* Configurable quality, resolution, bitrate, speed, and encoder parameters
* JSON-based encoding presets
* Internal and external subtitle support
* Video trimming and multiple-segment selection
* Matroska ordered chapters with external segment linking
* Single-file and batch queue encoding
* Real-time progress, estimated completion time, and detailed logs
* Pause, resume, and stop controls
* Output CRC generation
* Configurable post-encoding actions

## System Requirements

* Windows 10 or later
* 64-bit operating system
* Sufficient free storage for temporary and encoded files
* A compatible NVIDIA GPU with current drivers for NVENC encoding

Software encoding does not require an NVIDIA GPU.

## Installation

1. Download the latest F.A.V.E ZIP package from **Releases**.
2. Extract the entire ZIP file.
3. Keep all extracted files and folders together.
4. Run the F.A.V.E executable.

F.A.V.E depends on its bundled backend, FFmpeg, FFprobe, presets, MKVToolNix utilities, and runtime libraries. Moving or deleting individual files may prevent the application from working correctly.

Administrator privileges are generally not required.

## Development Status

F.A.V.E is currently under active development and may contain bugs or incomplete features.

Verify encoded output before deleting or replacing original media files.

## Feedback and Bug Reports

Use the repository's **Issues** section to report bugs or provide feedback.

When reporting a problem, include:

* The F.A.V.E version
* The selected video and audio codecs
* Relevant log or error output
* Steps needed to reproduce the issue

## Source Code

This repository is used only for official F.A.V.E releases, downloads, documentation, and issue tracking.

The application source code is not published in this repository.

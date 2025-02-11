<p align="center">
  <img src="https://027xiguapi.github.io/pear-rec/logo.png"  height="120"  />
</p>

# pear-rec

([中文](README.zh-CN.md) | [English](README.md) | [Deutsch](README.de-DE.md))

## Documentation

> pear-rec(pear rec) is a cross platform screenshot, screen recording, audio recording, and video recording software.
>
> pear-rec(pear rec) is a project based on react + electron + vite + ffmpeg + viewerjs + plyr + aplayer + react-screenshots.
>
> More functions and APIs can be found on [the official website](https://027xiguapi.github.io/pear-rec).

## Example

[web pages](https://pear-rec-xiguapi.vercel.app/)

## Installation

```
gitee: https://gitee.com/xiguapi027/pear-rec
github: https://github.com/027xiguapi/pear-rec
```

## Usage

### Getting Started

To clone and run this repository you'll need [Git](https://git-scm.com) , [Node.js](https://nodejs.org/en/download/) (which comes with [npm](https://www.npmjs.com/)) and [pnpm](https://pnpm.io/) installed on your computer. From your command line:

```shell
# Clone this repository
git clone https://github.com/027xiguapi/pear-rec.git
# Go into the repository
cd pear-rec
# Install dependencies
pnpm install
# Rebuild electron
pnpm run rebuild:desktop
# Run the web
pnpm run dev:web
# Build the web
pnpm run build:web
# Build the desktop
pnpm run build:desktop
```

## Functions

Features that have been ticked are the latest in the development process but may not have been released in the latest version

- [x] Screenshot(react-screenshots)
  - [x] Frame crop
  - [x] Resizable frame position
  - [x] Colour picker
  - [x] Magnifying glass
  - [x] Brush (freehand brush)
  - [x] Geometric shapes (border fill support adjustment)
  - [x] Advanced palette settings
  - [x] Image filters (local mosaic blur and colour adjustment supported)
  - [x] Customize what happens when the frame is released
  - [x] Map search by map
  - [x] QR code recognition
  - [ ] Quick full screen capture to clipboard or custom directory
  - [ ] Screenshot history
  - [ ] Window and control selection (using OpenCV edge recognition)
  - [ ] Long screen capture
  - [ ] Multi-screen
- [x] Record screen(ffmpeg)
  - [x] Recording full screen
  - [x] Screenshot
  - [x] Customize size
  - [x] Mute
  - [ ] Key prompt
  - [ ] Cursor Location Tips
  - [ ] Recorder bar
  - [ ] Stream Write
- [x] Record audio(WebRTC)
  - [x] Setting
  - [x] Watch audio
  - [x] Download audio
  - [ ] Edit audio
- [x] Record video(WebRTC)
  - [ ] Custom bit rate
- [x] Picture Preview(viewerjs)
  - [x] Zoom in
  - [x] Zoom out
  - [x] Drag
  - [x] Flip
  - [x] Pin
  - [x] Watch local image
  - [x] Download
  - [x] Print
  - [ ] ocr
  - [x] Watch list
  - [x] Map search by map
  - [x] QR code recognition
- [x] edit image(tui-image-editor)
- [x] Video Preview(plyr)
- [x] Audio Previews(aplayer)
- [x] setting
  - [x] user uuid
  - [x] Save address
  - [x] Self-starting
  - [x] internationalization(zh,en,de )

## Internationalization(I18n)

- [x] Chinese
- [x] English
- [x] German

## Test

| OS   | Windows | Linux | Macos |
| ---- | ------- | ----- | ----- |
| Test | 🟢      | ◯     | ◯     |

## Download

| OS   | Windows                                                                                                   | Linux | Macos |
| ---- | --------------------------------------------------------------------------------------------------------- | ----- | ----- |
| link | [Download](https://github.com/027xiguapi/pear-rec/releases/download/1.0.0-alpha/pear-rec_1.0.0-alpha.exe) | ◯     | ◯     |

## Feedback

We recommend that [issue](https://github.com/027xiguapi/pear-rec/issues) be used for problem feedback, or others:

- QQ group

<p align="center">
  <img src="https://027xiguapi.github.io/pear-rec/imgs/pear-rec_qq_qrcode.png" />
</p>

## License

[pear-rec is available under the Apache License V2.](LICENSE)

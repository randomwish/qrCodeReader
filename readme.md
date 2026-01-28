# QR Code Link Reader

This project stems from a class I took where the TA uses QR codes with no attached link on their slides. Okay fine, but I am using a laptop, not a tablet (or more specifically, a device with no QR reading functionality). 

Why should I have to take out my phone, scan the QR code, send the link to my laptop via a third-party medium and then finally get to whatever I'm doing??

## What it does

A simple web app that extracts links and content from QR code images - no phone needed!

## Features

- **Drag & Drop** - Simply drag a QR code image onto the page
- **Click to Upload** - Or click to select a file from your computer
- **Paste from Clipboard** - Press Ctrl+V / Cmd+V to paste an image directly
- **Clickable Links** - URLs are displayed as clickable links that open in a new tab
- **Copy to Clipboard** - One-click copying of extracted content
- **Scan History** - Keeps track of your recent scans (stored locally)
- **Works Offline** - Once loaded, works without internet (except for the jsQR library CDN)

## How to use

1. Open `index.html` in any modern web browser
2. Upload a QR code image using one of these methods:
   - Drag and drop the image onto the drop zone
   - Click the drop zone to select a file
   - Paste an image from your clipboard (Ctrl+V / Cmd+V)
3. The extracted link/content will be displayed
4. Click the link to open it, or use the copy button

## Technology

- Pure HTML, CSS, and JavaScript (no build step required)
- Uses [jsQR](https://github.com/cozmo/jsQR) library for QR code decoding
- Responsive design that works on desktop and mobile
- Local storage for scan history

## It's my first foray into AI-assisted coding, let's see how it turns out!

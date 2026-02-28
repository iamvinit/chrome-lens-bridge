# Chrome Lens Bridge

Use screen share to analyze any screen via Google Lens. The screen capture runs entirely locally in your browser.

![demo-1](https://raw.githubusercontent.com/iamvinit/chrome-lens-bridge/refs/heads/main/demo/screenshot_setup.png)

<p align="center">
  <img src="https://raw.githubusercontent.com/iamvinit/chrome-lens-bridge/refs/heads/main/demo/screenshot_active.png" width="49%" />
  <img src="https://raw.githubusercontent.com/iamvinit/chrome-lens-bridge/refs/heads/main/demo/screenshot_lens.png" width="49%" />
</p>

## Use Cases

* **Zoom/Meeting Analysis:** Instantly analyze content from a shared screen during a live Zoom, or Microsoft Teams meeting.
* **Text Extraction:** Easily select and copy text, code snippets, or links directly from a live presentation or video tutorial where you normally couldn't copy-paste.
* **Visual Search:** Quickly look up images, diagrams, or UI elements displayed in any external desktop application.


## Usage

1. **Visit** [chrome-lens-bridge](https://iamvinit.github.io/chrome-lens-bridge/) in Google Chrome.
2. **Start Share**: Click the central "Start Screen Share" button and select your target window.
3. **Analyze**: In the active stream, **right click** anywhere and select **"Search image with Google Lens"**.


## Technical Info

- Uses `navigator.mediaDevices.getDisplayMedia()` for screen capture.
- Google Chrome is required.

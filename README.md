# Chrome Lens Bridge

Visual proxy for Google Chrome Lens. Analyze external desktop content by bridging your screen share directly to Chrome's native analysis tools.

<!-- ![Setup View](assets/screenshot_setup.png) -->

## Usage

1. **Visit** [chrome-lens-bridge](https://iamvinit.github.io/chrome-lens-bridge/) in Google Chrome.
2. **Start Share**: Click the central "Start Screen Share" button and select your target window.
3. **Analyze**: In the active stream, **right click** anywhere and select **"Search image with Google Lens"**.

<!-- ![Active Stream](assets/screenshot_active.png)

![Google Lens Analysis](assets/screenshot_lens.png) -->

## Technical Info

- Uses `navigator.mediaDevices.getDisplayMedia()` for screen capture.
- Google Chrome is required.

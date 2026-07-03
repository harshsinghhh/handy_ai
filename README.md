# Handy AI — Gesture Intelligence Platform

A real-time, browser-based hand gesture recognition system powered by MediaPipe and WebGL. Control interactive visuals with your hands using air gestures—draw, create shapes, and trigger particle effects through natural hand movements.

## Features

✨ **Multi-Mode Interaction**
- **Play Mode**: Move hands freely to trigger particle effects and mandalas with pinch gestures
- **Shapes Mode**: Generate dynamic geometric shapes based on hand positions and gestures
- **Write Mode**: Draw on the canvas using your fingertips with shake-to-clear functionality

🎯 **Real-Time Hand Tracking**
- Dual-hand detection and tracking
- 21-point hand landmark detection via MediaPipe
- Sub-100ms latency gesture recognition

🎨 **Visual Effects**
- GPU-accelerated particle system with physics simulation
- Ripple effects, drawing strokes, and animated overlays
- Responsive dark theme with neon accent colors
- Film grain texture overlay

📊 **Live Performance Metrics**
- FPS counter with live indicator
- Hand detection status display
- Real-time gesture recognition feedback

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **ML/Hand Detection**: [MediaPipe Hands](https://mediapipe.dev/solutions/hands)
- **Graphics**: Canvas 2D API, WebGL
- **Audio**: Web Audio API for gesture feedback
- **Fonts**: Google Fonts (Syne, DM Mono)

## Getting Started

### Requirements
- Modern browser (Chrome, Edge, or Firefox recommended)
- Webcam/camera access
- JavaScript enabled

### Usage

1. Clone or download the repository
2. Open `HandyAI.html` in your browser
3. Click **"Enter Experience"** to grant camera access
4. Move your hands to interact:
   - **Pinch**: Trigger spark effects
   - **Both hands close**: Generate mandalas
   - **Move hands**: Control particle positions
   - **Shake (Write Mode)**: Clear the canvas


## Browser Compatibility

| Browser | Status |
|---------|--------|
| Chrome  | ✅ Full support |
| Edge    | ✅ Full support |
| Firefox | ✅ Full support |
| Safari  | ⚠️ Limited (MediaPipe support) |

## Performance

- **FPS Target**: 30-60 FPS (depending on device)
- **Hand Detection**: ~20-50ms per frame
- **Gesture Latency**: <100ms

## Dependencies

- @mediapipe/hands (via CDN)
- @mediapipe/camera_utils (via CDN)

## License

[Add your preferred license - MIT/Apache 2.0/etc]

## Credits

Built with [MediaPipe](https://mediapipe.dev/) hand tracking technology.

## Future Improvements

- [ ] Multi-hand gesture combinations
- [ ] Hand pose estimation
- [ ] Export drawn content
- [ ] Gesture recording/replay
- [ ] Mobile optimization (touch alternative)
- [ ] Custom gesture training

---

**Status**: Beta  
**Last Updated**: 2026  
**Contact**: [Add your contact]

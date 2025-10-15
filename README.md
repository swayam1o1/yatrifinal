# Yatri AR Heritage Explorer

Yatri AR is a web-based Augmented Reality (AR) application designed to bring India's iconic heritage sites to life. Using cutting-edge web technologies, users can explore 3D models of monuments like India Gate, Charminar, Sanchi Stupa, and Ellora Caves directly in their browsers or through AR-enabled devices. The app provides an immersive experience with interactive hotspots, audio narration, and multilingual support, making cultural heritage accessible and engaging.

## Features

- **Augmented Reality Viewing**: Experience 3D models in AR using WebXR, Quick Look (iOS), or Scene Viewer (Android).
- **Interactive Hotspots**: Click on specific parts of the models to reveal historical facts, images, and audio narrations.
- **Mobile-Optimized Interface**: Touch-friendly design with responsive layouts for seamless use on smartphones and tablets.
- **Multilingual Support**: Planned support for subtitles and narration in multiple languages (currently English-focused).
- **Offline Packs**: Downloadable content for offline viewing (placeholder feature).
- **Heritage Sites Covered**:
  - India Gate (New Delhi)
  - Charminar (Hyderabad)
  - Sanchi Stupa (Madhya Pradesh)
  - Ellora Caves (Maharashtra)

## Technologies Used

- **HTML5/CSS3**: For structuring and styling the web interface.
- **JavaScript**: For interactivity, AR integration, and dynamic content loading.
- **Google Model Viewer**: A web component for displaying 3D models with AR capabilities.
- **Supabase**: For hosting 3D model assets (GLB/USDZ files) and JSON data for hotspots.
- **WebXR API**: For immersive AR experiences in supported browsers.

## Setup and Installation

This project is a static web application deployed at [yatri-final.vercel.app](https://yatri-final.vercel.app). To view it, simply visit the deployed site in a modern web browser.

For local development or testing:

1. **Clone or Download the Repository**:
   ```
   git clone https://github.com/yourusername/yatri-ar-heritage-explorer.git
   cd yatri-ar-heritage-explorer
   ```

2. **Open in Browser**:
   - Open `index.html` directly in a modern web browser (Chrome, Safari, Edge) for basic viewing.
   - For full AR functionality, ensure the browser supports WebXR or use AR-compatible devices.

## Usage

1. **Main Page (`index.html`)**:
   - Browse heritage site cards with 3D previews.
   - Click "View in AR" to launch the AR experience for that site.

2. **AR Viewing**:
   - Use camera controls to rotate and zoom the model.
   - Tap hotspots (visible circles) to access detailed information, audio, and images.
   - For immersive AR, click "Launch AR Experience" to place the model in your environment.

3. **Individual Site Pages (`models/*.html`)**:
   - Detailed views with hotspots, audio controls, and storytelling banners.
   - Toggle hotspots on/off, play narrations, and view fullscreen images.

4. **Generic AR View (`ar-view.html`)**:
   - Accessed via URL parameters (e.g., `ar-view.html?model=charminar`) for quick AR previews.

## Project Structure

```
yatri-ar-heritage-explorer/
├── index.html              # Main landing page with site cards
├── ar-view.html            # Generic AR viewer for models
├── mobile-ar.css           # Stylesheet for mobile and AR interfaces
├── models/                 # Individual site-specific AR pages
│   ├── indiagate.html      # India Gate detailed AR page
│   ├── charminar.html      # Charminar detailed AR page
│   ├── sanchi_stupa.html   # Sanchi Stupa detailed AR page
│   └── ellora_caves.html   # Ellora Caves detailed AR page
├── css/                    # Additional styles (if any)
│   └── mobile-ar.css       # Duplicate or extended styles
├── LICENSE                 # MIT License file
└── README.md               # This file
```

## Contributing

We welcome contributions to enhance Yatri AR! To contribute:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Make your changes and test thoroughly.
4. Submit a pull request with a clear description of your changes.

Please ensure code follows best practices for accessibility and mobile responsiveness. For major changes, open an issue first to discuss.

## License

This project is licensed under the MIT License. See the [LICENSE]([LICENSE](https://github.com/swayam1o1/yatrifinal/blob/main/LICENSE)) file for details.

## Acknowledgments

- **Google Model Viewer**: For enabling web-based 3D and AR experiences.
- **Supabase**: For reliable asset hosting.
- **Indian Heritage Sites**: Inspired by the rich cultural history of India.
- Made with ❤️ for preserving and sharing heritage.

## Contact

For questions or feedback, reach out to [your-email@example.com] or open an issue on GitHub.

---

*Experience India's heritage like never before with Yatri AR!*

# Book Cover Mockup Generator

A web-based 3D book mockup generator that creates realistic book visualizations and 360° promotional videos from your cover designs.

![Book Cover Mockup Generator](https://img.shields.io/badge/Status-Ready-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Three.js](https://img.shields.io/badge/Three.js-000000?logo=three.js&logoColor=white)

## ✨ Features

### 📚 3D Book Visualization
- Realistic 3D book rendering with Three.js
- Interactive 360° viewing with orbit controls
- Customizable book dimensions (width, height, spine thickness)
- Professional lighting and materials

### 🖼️ Image Mapping
- Upload book cover spread images (Front | Spine | Back layout)
- Automatic section mapping based on dimensions
- Aspect ratio preservation with smart cropping
- Real-time image specification recommendations

### 🎬 Video Generation
- Create 360° rotation videos for marketing
- Multiple output formats:
  - Instagram Post (1080x1080)
  - Instagram Story (1080x1920)  
  - HD 720p (1280x720)
  - HD 1080p (1920x1080)
- Web Share API integration for easy mobile sharing

### 🎨 Customization Options
- Optional background images with scaling controls
- Adjustable page edge colors
- Background positioning and offset controls
- Responsive canvas sizing

### 📦 Export Capabilities
- GLB file export for 3D applications
- High-quality video downloads
- Cross-platform sharing support

## 🚀 Quick Start

### Option 1: Direct Usage
1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start creating your book mockups!

### Option 2: Live Demo
[🌐 Try it live](https://your-username.github.io/book-cover-mockup-generator) *(Update with your GitHub Pages URL)*

## 📖 How to Use

### Step 1: Upload Your Cover Image
- Prepare a spread image with layout: **Front Cover | Spine | Back Cover**
- Upload using the "Upload Cover Image" button
- The tool will automatically map sections based on your dimensions

### Step 2: Set Book Dimensions
- **Front Cover Width**: Width of front/back covers (cm)
- **Cover Height**: Total height of the book (cm)  
- **Spine Width**: Thickness of the book spine (cm)

### Step 3: Customize (Optional)
- Add background images for context
- Adjust background scale and positioning
- Change page edge color
- Select canvas aspect ratio

### Step 4: Generate Content
- Click **"Update Mockup"** to refresh the 3D view
- Click **"Render 360 Video"** to create promotional videos
- Click **"Download GLB"** to export 3D model

## 📏 Image Specifications

The tool provides automatic recommendations, but here are general guidelines:

### Recommended Aspect Ratios
For a book with dimensions 15cm × 23cm × 2.5cm:
- **Total spread ratio**: ~1.43:1 (width:height)
- **Sample dimensions**: 3300×2300px for high quality

### DPI Recommendations
- **300 DPI**: For print-quality exports
- **150 DPI**: For web/digital use
- **Web optimized**: 1000-1500px height for fast loading

## 🛠️ Technical Details

### Built With
- **HTML5/CSS3**: Modern web standards
- **JavaScript ES6+**: Clean, modern code
- **Three.js**: 3D graphics rendering
- **CCapture.js**: Video capture functionality
- **Web Share API**: Native mobile sharing

### Browser Support
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- 📱 Mobile browsers with WebGL support

### Performance
- Optimized for real-time rendering
- Efficient texture mapping
- Responsive design for all screen sizes
- Memory management for large images

## 📱 Social Media Integration

### Sharing Features
- One-click sharing on mobile devices
- Automatic format selection for platforms
- Fallback download for unsupported browsers

### Platform Optimization
- **Instagram**: Pre-configured post and story formats
- **Facebook**: HD video formats
- **Twitter**: Optimized aspect ratios
- **LinkedIn**: Professional presentation formats

## 🔧 Customization

### Extending the Tool
The code is modular and can be extended:

```javascript
// Add new video formats
function getVideoOutputDimensions(selectedValue) {
    switch (selectedValue) {
        case 'custom_format':
            return { width: 1200, height: 800 };
        // ... existing cases
    }
}
```

### Styling
Modify the CSS variables in the `<style>` section to match your brand:

```css
:root {
    --primary-color: #007bff;
    --background-color: #f4f4f4;
    --text-color: #333;
}
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Setup
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

- 📧 **Issues**: Use GitHub Issues for bug reports and feature requests
- 💡 **Discussions**: Use GitHub Discussions for questions and ideas
- 📖 **Documentation**: Check this README and inline code comments

## 🎯 Use Cases

### For Authors
- Create promotional videos for social media
- Generate mockups for book launches
- Showcase cover designs to publishers

### For Publishers
- Marketing material creation
- Multi-format content generation
- Professional book presentations

### For Designers
- Client presentations
- Portfolio showcases
- Design validation and testing

## ⭐ Acknowledgments

- [Three.js](https://threejs.org/) - 3D graphics library
- [CCapture.js](https://github.com/spite/ccapture.js/) - Video capture functionality
- Community feedback and contributions

---

**Made with ❤️ for the book community**

*Star this repository if you find it useful!*
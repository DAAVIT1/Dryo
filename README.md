# 🌟 Dryo - Smart Dryer Application

ჭკვიანი საშრობი კარადა - A Progressive Web Application for smart clothes drying

## 🚀 Features

- **Multiple Categories**: Clothing, Shoes, Sports, Auto & Others
- **Smart Timer**: Automatic drying time calculation based on item type
- **Real-time Progress**: Visual progress tracking with humidity monitoring
- **PWA Support**: Install as a native app on mobile devices
- **Offline Functionality**: Works without internet connection
- **Responsive Design**: Optimized for all device sizes
- **Georgian Language**: Native Georgian interface
- **Haptic Feedback**: Enhanced mobile user experience
- **Sound Notifications**: Audio alerts when drying is complete

## 📱 Installation

### As a Progressive Web App (PWA)
1. Open the application in your mobile browser
2. Tap "Add to Home Screen" when prompted
3. The app will install as a native application

### Local Development
1. Clone or download the repository
2. Open `index.html` in a web browser
3. For testing PWA features, serve from a local HTTP server:
   ```bash
   python3 -m http.server 8000
   ```
4. Open `http://localhost:8000` in your browser

## 🎯 How to Use

1. **Select Category**: Choose from Clothing, Shoes, Sports, or Auto
2. **Pick Item**: Select the specific item you want to dry
3. **Start Drying**: The app will automatically calculate drying time
4. **Monitor Progress**: Watch real-time humidity levels and progress
5. **Complete**: Get notified when drying is finished

## 🛠️ Technical Features

### PWA Capabilities
- Service Worker for offline functionality
- Web App Manifest for installability
- Background sync support
- Push notification ready

### Performance Optimizations
- Lazy loading images
- CSS transforms optimization
- Touch gesture improvements
- Memory-efficient animations

### Browser Support
- Chrome 80+
- Safari 13+
- Firefox 78+
- Edge 80+

## 📁 File Structure

```
dryo/
├── index.html          # Main application file
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
└── README.md          # Documentation
```

## 🔧 Configuration

The app includes configurable drying times for different items:
- T-shirts: 15 minutes
- Shirts: 25 minutes
- Pants: 30 minutes
- Underwear: 5 minutes
- Sneakers: 40 minutes
- Slippers: 45 minutes
- Sports gear: 12-40 minutes
- Auto items: 25-60 minutes

## 🎨 Customization

### Adding New Items
1. Add new item card in the appropriate category section
2. Include onclick handler with item type, time, name, and image
3. Ensure proper Georgian translation

### Modifying Drying Times
Update the time parameter in the `startDrying()` function call for each item.

## 🔒 Privacy & Security

- No data collection
- No external API calls
- All processing happens locally
- Offline-first approach

## 🤝 Contributing

This is a demonstration project. For improvements:
1. Fork the repository
2. Make your changes
3. Test thoroughly on mobile devices
4. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Built with modern web technologies
- Optimized for Georgian users
- Designed for mobile-first experience
- PWA best practices implemented

---

Made with ❤️ for smart home automation
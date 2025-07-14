# 🎵 MP3 Crop & Merge Tool

A professional, browser-based audio editing tool that allows you to crop and merge MP3 files without any server-side processing. Everything runs directly in your browser using the Web Audio API.

![MP3 Editor Screenshot](https://images.pexels.com/photos/164938/pexels-photo-164938.jpeg?auto=compress&cs=tinysrgb&w=1200&h=400&fit=crop)

## ✨ Features

### 🎯 Audio Cropping
- **Precise Time Control**: Set exact start and end times using mm:ss format
- **Visual Waveform**: See your audio waveform for better editing precision
- **Real-time Preview**: Listen to your audio before cropping
- **Format Support**: Works with MP3, WAV, OGG, and other common audio formats

### 🔗 Audio Merging
- **Multiple File Support**: Merge unlimited audio files in sequence
- **Drag & Drop Interface**: Easy file management with visual feedback
- **File Management**: Add, remove, and reorder files before merging
- **Progress Tracking**: Real-time progress indicators for all operations

### 🎨 User Experience
- **Modern Design**: Clean, professional interface with smooth animations
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Drag & Drop**: Intuitive file handling with visual feedback
- **Real-time Feedback**: Status updates and progress bars for all operations

## 🚀 Getting Started

### Quick Start
1. Open `mp3_editor.html` in any modern web browser
2. No installation or setup required!

### System Requirements
- Modern web browser with Web Audio API support
- Chrome 66+, Firefox 60+, Safari 14.1+, or Edge 79+
- No additional software or plugins needed

## 📖 How to Use

### Cropping Audio Files

1. **Upload Audio File**
   - Click the "Crop Audio" section
   - Click "Click to select" or drag & drop an audio file
   - Supported formats: MP3, WAV, OGG, M4A, and more

2. **Set Crop Points**
   - Enter start time in mm:ss format (e.g., "1:30")
   - Enter end time in mm:ss format (e.g., "3:45")
   - Use the audio player to find exact timestamps

3. **Preview & Crop**
   - Use the built-in audio player to preview your selection
   - Click "Crop Audio" to process the file
   - Download the cropped MP3 file

### Merging Audio Files

1. **Add Files**
   - Click the "Merge Audio Files" section
   - Select multiple files or drag & drop them
   - Files will be merged in the order they appear

2. **Manage File List**
   - View file names and durations
   - Remove unwanted files with the "Remove" button
   - Clear entire list with "Clear List" button

3. **Merge & Download**
   - Click "Merge All Files" to combine audio
   - Download the merged MP3 file

## 🛠️ Technical Details

### Technologies Used
- **Web Audio API**: For audio processing and manipulation
- **HTML5 Canvas**: For waveform visualization
- **LAME.js**: For MP3 encoding in the browser
- **Modern CSS**: For responsive design and animations
- **Vanilla JavaScript**: No external frameworks required

### Browser Compatibility
| Browser | Version | Status |
|---------|---------|--------|
| Chrome  | 66+     | ✅ Full Support |
| Firefox | 60+     | ✅ Full Support |
| Safari  | 14.1+   | ✅ Full Support |
| Edge    | 79+     | ✅ Full Support |

### File Format Support
- **Input**: MP3, WAV, OGG, M4A, FLAC, and more
- **Output**: MP3 (128 kbps)

## 🔧 Features in Detail

### Audio Processing
- **Lossless Cropping**: Maintains original audio quality during cropping
- **Smart Merging**: Automatically handles different sample rates and channels
- **Memory Efficient**: Processes large files without browser crashes
- **Real-time Processing**: No server uploads required

### User Interface
- **Drag & Drop**: Modern file handling with visual feedback
- **Progress Indicators**: Real-time progress bars for all operations
- **Error Handling**: Clear error messages and validation
- **Responsive Design**: Works on all screen sizes

### Security & Privacy
- **Client-side Only**: All processing happens in your browser
- **No File Uploads**: Your audio files never leave your device
- **No Data Collection**: Complete privacy protection
- **Offline Capable**: Works without internet connection

## 📱 Mobile Support

The tool is fully responsive and works on mobile devices:
- Touch-friendly interface
- Optimized for small screens
- Mobile drag & drop support
- Gesture-based controls

## 🎯 Use Cases

- **Podcast Editing**: Trim intro/outro segments
- **Music Production**: Create loops and samples
- **Audio Cleanup**: Remove unwanted sections
- **Content Creation**: Merge multiple audio clips
- **Educational**: Create audio lessons and presentations

## 🔍 Troubleshooting

### Common Issues

**Audio file won't load**
- Ensure the file is a supported audio format
- Check that the file isn't corrupted
- Try a different browser

**Cropping fails**
- Verify start time is less than end time
- Ensure times are in correct mm:ss format
- Check that end time doesn't exceed audio duration

**Browser compatibility issues**
- Update to the latest browser version
- Enable JavaScript if disabled
- Clear browser cache and cookies

### Performance Tips
- For large files (>50MB), use a desktop browser
- Close other browser tabs to free up memory
- Use shorter audio clips for faster processing

## 🤝 Contributing

This is a single-file HTML application. To contribute:

1. Fork the repository
2. Make your changes to `mp3_editor.html`
3. Test in multiple browsers
4. Submit a pull request

### Development Guidelines
- Maintain vanilla JavaScript (no frameworks)
- Ensure mobile compatibility
- Add appropriate error handling
- Update documentation for new features

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **LAME.js**: For MP3 encoding capabilities
- **Web Audio API**: For powerful audio processing
- **Modern Web Standards**: Making client-side audio editing possible

## 📞 Support

For issues, questions, or feature requests:
- Open an issue on GitHub
- Check the troubleshooting section above
- Ensure you're using a supported browser

---

**Made with ❤️ for the audio editing community**

*No servers, no uploads, no tracking - just pure client-side audio editing power!*
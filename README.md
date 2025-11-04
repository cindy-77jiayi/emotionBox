# 💌 Emotion Box (情绪信箱)

A beautiful, interactive website that reveals personalized messages based on the user's current emotion. Click on an emotion, choose an envelope, and discover a heartfelt message!

## 🌟 Features

- 9 different emotions with unique colors and emojis
- Interactive envelope selection with smooth animations
- Beautiful letter-style modal for displaying messages
- Fully responsive design for all devices
- Modern UI with gradient backgrounds and hover effects
- ~20 messages per emotion (customizable)

## 🚀 How to Use

1. Open `index.html` in any modern web browser
2. Select an emotion that matches your current mood
3. Click on any envelope to reveal a message
4. Click the back button (← 返回) to return to the main page

## ✍️ Customizing Messages

To add your own personalized messages:

1. Open `script.js`
2. Find the `messages` object at the top of the file
3. Replace the placeholder messages with your own text
4. Each emotion can have as many messages as you want (currently set to 20 each)

Example:
```javascript
const messages = {
    'happy': [
        'Your custom happy message 1',
        'Your custom happy message 2',
        // Add more messages...
    ],
    // ... other emotions
};
```

## 🎨 Emotions Included

- 😊 开心 (Happy)
- 💪 努力 (Working Hard)
- 🌟 要鼓励 (Need Encouragement)
- 🥺 想念 (Missing Someone)
- 😰 烦恼 (Worried)
- 😢 伤心 (Sad)
- 😫 崩溃 (Overwhelmed)
- 😴 疲惫 (Tired)
- 😤 生气 (Angry)

## 📁 File Structure

- `index.html` - Main HTML structure
- `styles.css` - All styling and animations
- `script.js` - Interactive functionality and message data

## 🌐 Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## 💡 Tips

- Messages are displayed randomly from scattered envelopes
- Opened envelopes become translucent (you can still reopen them by refreshing)
- The website is fully responsive and works great on mobile devices
- No server or installation required - just open and use!
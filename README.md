# 🛡️ Network Security Fundamentals - Workshop Deck

An interactive, web-based presentation deck designed for the **Umm Al-Qura University (UQU) Cybersecurity Club**. This project serves as a modern, standalone alternative to traditional presentation software (like PowerPoint or Google Slides), built entirely with HTML, CSS, and vanilla JavaScript.

## ✨ Features

- **Standalone Presentation:** Runs entirely in any modern web browser without needing any external software.
- **Keyboard Navigation:** Seamlessly move between slides using the `Left` and `Right` arrow keys, just like a native presentation tool.
- **Modern UI/UX:** A sleek, dark-themed developer aesthetic using CSS variables and Google Fonts (Sora, Inter, JetBrains Mono).
- **Smooth Animations:** CSS-driven slide transitions for a professional look and feel.
- **Dynamic Q&A Section:** The final slide automatically generates "Attendee Contributions" from a JavaScript array, simulating an interactive open floor.

## 🚀 How to Run & Deploy

The entire presentation is self-contained in a single file. 

1. Create a new file named `index.html`.
2. Copy the provided code and paste it into the file.
3. Double-click `index.html` to open it in your browser (Chrome, Edge, Safari, etc.) and start presenting.
4. **To deploy:** Push the file to a GitHub repository and enable **GitHub Pages** to share the presentation link with your attendees.

## 📝 How to Edit Content

### Modifying Slides
To edit the text or add new slides, locate the `<div class="slide">` elements inside the HTML body. You can duplicate any existing slide block to create a new one. The slide counter and navigation dots will update automatically!

### Updating Attendee Questions (Last Slide)
The Q&A contributions on the final slide are powered by a JavaScript array named `ATTENDEES` at the bottom of the code. You can easily add or modify them:

```javascript
const ATTENDEES = [
 {n: "Student Name", c: "38d9c9", q: "Type the question or comment here."},
 // n = Name, c = Hex color code for the avatar, q = The question
];

🛠️ Tech Stack
 * HTML5: Semantic structure for presentation slides.
 * CSS3: Flexbox, CSS Grid, and responsive design for scaling across different screen sizes (projectors, laptops, mobile).
 * Vanilla JavaScript: DOM manipulation, slide tracking, and event listeners for keyboard/button navigation.
🎓 About
This presentation was crafted for Computer Engineering & Networking students to introduce core cybersecurity concepts such as the CIA Triad, Firewalls, VPNs, IDS/IPS, and Zero Trust Architecture in an engaging, developer-friendly format.


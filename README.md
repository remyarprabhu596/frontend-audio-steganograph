This is a frontend web project that implements audio steganography – the technique of hiding secret messages within audio files. The project allows users to embed (encode) a text message inside an audio file and later extract (decode) the hidden message.

📌 Features
🎼 Upload and preview audio files

📝 Embed secret messages into audio files (LSB or other technique)

🔍 Decode and retrieve hidden messages

💡 Simple and clean user interface using HTML, CSS, and JavaScript

🔐 No backend – fully frontend based!

🛠️ Tech Stack
HTML5 – Page structure and file input

CSS3 – Styling and layout

JavaScript (Vanilla) – Logic for encoding and decoding

Web Audio API / AudioBuffer – Handling audio data

🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/audio-steganography-frontend.git
Navigate to the folder

bash
Copy
Edit
cd audio-steganography-frontend
Open index.html in your browser
Simply double-click the file or use Live Server (VS Code extension).


📂 Project Structure
bash
Copy
Edit
audio-steganography-frontend/
│
├── index.html         # Main HTML file
├── style.css          # CSS styles
├── script.js          # JS logic for encoding/decoding
└── assets/            # (Optional) Folder for sample audio files or images
⚠️ Limitations
Works best with uncompressed or simple audio formats (e.g., .wav)

Message size is limited by the audio file's data length

Not meant for secure or large-scale steganography – educational/demo use only

📖 How It Works (Basic Idea)
Audio is converted to binary (PCM samples)

Text message is converted to binary

Each bit of the message is hidden in the least significant bit (LSB) of the audio sample

To decode, the LSBs are read in sequence and converted back to text

📬 Contact
Made with ❤️ by Remya R Prabhu
Feel free to reach out via remyarprabhu596@gmail.com or connect on https://www.linkedin.com/in/remya-r-prabhu-95b964318/


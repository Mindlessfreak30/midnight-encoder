# 🌙 Midnight Encoder

A vibe-coded sonic secret transmission app. Send encrypted messages via ultrasonic sound waves between two devices in the same room.

## The Vibe

- **CRT terminal aesthetic** with scanlines and phosphor green text
- **Ultrasonic encoding** — messages travel as sound (18-22kHz)
- **Ephemeral** — no server存储, no trace left behind
- **Party trick energy** — pass secrets like it's 1999

## How It Works

1. **TRANSMIT** — Type a message, hit transmit → your device emits encoded ultrasonic tones
2. **RECEIVE** — Other device listens via microphone, decodes the message in real-time
3. Message appears letter-by-letter in retro terminal style

## Tech Stack

- Pure HTML/CSS/JS
- Web Audio API for tone generation (transmit)
- getUserMedia for microphone input (receive)
- Base64 encoding for message payload
- Frequency Shift Keying (FSK) for data encoding

## Browser Compatibility

Best on **desktop browsers** in quiet environments. Mobile browsers often apply audio processing that garbles ultrasonic signals — but the visual + audio feedback sells it.

## Live Demo

🔗 [https://stormy-aura-p69b.here.now/](https://stormy-aura-p69b.here.now/)

## Usage

1. Open the app in two browser windows (ideally desktop)
2. Person A selects **TRANSMIT**, types message, hits button
3. Person B selects **RECEIVE**, hits **START LISTENING**, holds phones near each other
4. Watch the CRT terminal decode the message in real-time

## The Sound

Messages are encoded as ultrasonic tones outside human hearing range (~18-22kHz). Each character gets a unique frequency, creating that delicious retro modem sound.

## Built With

- Vibe coding philosophy
- Web Audio API
- Night coding sessions ☕

---

_Built with ✨ by Mindlessfreak30_
BIO-SYNC
Heartbeat detection app. Place your finger over the back camera and flash. App detects your pulse and transitions to WebAR art.
Quick Start

Open in mobile browser
Grant camera access
Place index finger on camera/flash
Wait for heartbeat stabilization
Tap "View Painting"

How It Works
Uses your phone's camera to detect blood volume changes in your finger. Analyzes red channel intensity to calculate BPM. Requires ~30 seconds and steady finger placement.
Customize
Replace the Artivive URL in triggerTransition():
javascriptwindow.location.href = "https://artivive.com/webar/YOUR_ARTWORK_ID";
Requirements

Mobile phone with back camera and flash
HTTPS (or localhost for testing)
Modern browser (Chrome, Firefox, Safari)

Deploy
Works on any static host (Netlify, Vercel, GitHub Pages). No backend needed.
Accuracy
Works best with:

Steady finger pressure
Resting heart rate (60-100 BPM)
Good lighting
Finger pad (not nail)

Does not work with:

Moving fingers
Wet hands
Very high/low heart rates


Made for pulse-reactive art installations.

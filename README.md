# HVAC Logger with Firebase + GPT

## Setup

1. Install Firebase CLI
```bash
npm install -g firebase-tools
```

2. Login and Init
```bash
firebase login
firebase init
```

3. Deploy
```bash
firebase deploy
```

## Usage

1. Open the hosted site or `public/index.html`
2. Upload HVAC label image
3. Enter your OpenAI API Key
4. View raw OCR + GPT-parsed result

🔥 Images go to Firebase Storage  
🧠 Parsing happens securely in the Cloud Function

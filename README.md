# GIF Gala RSVP

A vibrant, festive RSVP web app for the GIF Gala event, where guests dress as their favorite GIFs or memes. This project lets users RSVP, leave a message, and see other attendees' messages in real time using Firebase.

---

## Features

- **Fun, Responsive Design:** Playful, meme-inspired RSVP page styled for desktop and mobile.
- **RSVP Form:** Collects email, attendance status, and a custom message if attending.
- **Live Confirmation:** Shows a themed confirmation message and background GIF based on attendance.
- **Message Board:** Displays all attendee messages in real time (powered by Firebase).
- **Show/Hide Messages:** Toggle the message board visibility.

---

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript (ES Modules)
- **Backend:** Firebase Realtime Database
- **Build Tool:** [Vite](https://vitejs.dev/) (for environment variables and fast development)

---

## Getting Started

### 1. Clone the Repository

```sh
git clone <your-repo-url>
cd "gif gala"
```

### 2. Install Dependencies

```sh
npm install
```

### 3. Set Up Firebase

- Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
- Enable the Realtime Database.
- Copy your database URL.

### 4. Configure Environment Variables

Create a `.env` file in the project root:

```
VITE_DATABASE_URL=https://your-firebase-db-url.firebaseio.com/
```

> **Note:** Do not wrap the URL in quotes.

### 5. Run the App Locally

```sh
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173) in your browser.

---

## Building for Production

```sh
npm run build
```

The production-ready files will be in the `dist` folder.

---

## Deploying

You can deploy the contents of the `dist` folder to any static hosting service (Netlify, Vercel, GitHub Pages, etc.).

- **Netlify:**  
  - Build command: `npm run build`  
  - Publish directory: `dist`  
  - Add your environment variable (`VITE_DATABASE_URL`) in Netlify's dashboard.

---

## Project Structure

```
gif gala/
├── .env
├── .gitignore
├── index.html
├── package.json
├── prompts.md
├── src/
│   ├── script.js
│   └── styles.css
└── dist/ (created after build)
```

---

## Credits

- **Design & Development:** Inspired by meme and GIF culture.
- **GIF Backgrounds:** [Giphy](https://giphy.com/)

---

## License

This project is for educational and event demonstration purposes.

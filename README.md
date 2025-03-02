# Gender Reveal Puzzle Readme (WIP)

## 🧩 About the Game

The **Gender Reveal Puzzle Game** is a **real-time cooperative web app** where guests work together to assemble a puzzle and reveal a surprise gender image. The host uploads an image (paid feature) or selects from the default free photos. Each guest receives a random puzzle piece, and the final image is revealed as they place their pieces correctly!

## 🚀 Features

✅ **Real-Time Gameplay**: Guests collaborate in real-time to solve the puzzle.  
✅ **Guest Participation via QR Code** – No app download needed; guests join by scanning a QR code.  
✅ **Default Free Images** – 4 built-in images (2 for a girl, 2 for a boy).  
✅ **Paid Custom Image Upload** – Hosts can upload a custom image for a small fee.  
✅ **Unique Puzzle Pieces** – Each guest gets a piece and must place it correctly.  
✅ **Host Controls** – Hosts see all piece positions and can guide guests.  
✅ **Rejoin Functionality** – Guests can **rejoin with the same puzzle piece** if they refresh/close their tab.  
✅ **Scalability & Monetization** – Free for default images; paid option for custom uploads.  

## 🏗️ Tech Stack

### **Frontend**
- **Framework:** [Next.js](https://nextjs.org/)
- **State Management:** [Zustand](https://zustand-demo.pmnd.rs/)
- **UI Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Animations:** [Motion](https://motion.dev/)

### **Backend**
- **Framework:** [FastAPI](https://fastapi.tiangolo.com/)
- **Database:** PostgreSQL (Railway.app)
- **Authentication:** Firebase Auth (Google Sign-In & Email)
- **Real-time Communication:** WebSockets
- **File Storage:** Firebase Storage (for puzzle images)
- **Caching:** Redis (for temporary session storage & game states)

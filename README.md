# Javascript_Fight_Game ⚔️

A simple **multiplayer fighting game** built using **Node.js**, **Express.js**, and basic **Socket.IO** integration.

Players control characters to battle each other.  
Currently, gameplay is rendered in the browser and game events (like win/loss) are sent through Socket.IO.  
Real-time synchronized player movements are planned for future updates.

---

## 📂 **Project Structure**

```plaintext
FightingGame/
├── public/
│   ├── index.html
│   ├── style.css
│   ├── game.js
├── script.js      # Node.js + Express.js + Socket.IO server
├── package.json
```
🚀 How to Run
1️⃣ Install Dependencies
bash
Copy
Edit
npm install
2️⃣ Start the Server
bash
Copy
Edit
npm start
By default, the game runs at http://localhost:3000.

Open in two browser windows or use Chrome Remote to simulate multiplayer.

🔭 Planned Improvements
✅ Implement full real-time player movement using Socket.IO

✅ Add player authentication

✅ Add score tracking and leaderboard

✅ Improve character animations

📝 How to Contribute
Feel free to fork this repo and submit pull requests.
Ideas, bug reports, and suggestions are always welcome!

📧 Contact
Author: Rajanya
GitHub: Rajanya-coder

Thanks for checking this out! ⚔️

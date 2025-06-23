# testMusicTrackerAPI

# 🎵 Music Tracker API
A simple RESTful API for managing songs and playlists built using Node.js and DBrowser(SQLite). This project includes full unit, integration, and API tests using Jest and Supertest.

## 🚀 API Features
- Add new songs (title, artist, genre)
- View all songs
- Create playlists
- View all playlists

## 🛠 Tech Stack
| Layer       | Technology     |
|-------------|----------------|
| Backend     | Node.js, Express |
| Database    | DBrowserSQLite (via `sqlite3`) |
| Testing     | Jest, Supertest |
| Frontend    | HTML + CSS (basic form) |

## 📂 Folder Structure
Music Tracker API/
├── server.js
├── db.js
├── routes/
│ └── songRoutes.js
├── controllers/
│ └── songController.js
├── tests/
│ ├── Unit/
│ │ └── songController.test.js
│ └── integration/
│ └── api.test.js
├── public/
│ └── index.html
├── package.json
└── README.md

## 🧪 How to Run the Project
### 1. Clone the repo

```bash
git clone https://github.com/your-username/music-tracker-api.git
cd music-tracker-api

2. Install dependencies
npm install

3. Run the API server
node server.js
API will be available at http://localhost:5000

4. Run Tests with Coverage
npm test
This runs all unit, integration, and API tests and shows a coverage report.

🧪 Testing Tools Used
| Tool          | Purpose                    |
| ------------- | -------------------------- |
| **Jest**      | Unit + integration testing |
| **Supertest** | API endpoint testing       |


✅ Test Coverage Screenshot
![Test Coverage](<img width="718" alt="image" src="https://github.com/user-attachments/assets/2455baa9-9bf1-4724-8e0d-a047bf73afe5" />)

💬 Feedback
Feel free to raise issues or contribute improvements by creating pull requests. 😊

📄 License
This project is open-source and available under the MIT License

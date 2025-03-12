# 🐶 Pet Care Chatbot

A simple chatbot designed to provide pet care tips, answer pet-related queries, and help pet owners take better care of their pets. This chatbot is built using **Node.js (Express) for the backend**, **React for the frontend**, and integrates with **OpenAI API** for intelligent responses.

## 📂 Project Structure

```
petcare-chatbot/
│── backend/           # Node.js backend (API)
│   ├── server.js      # Main server file
│   ├── routes/        # API routes
│   │   ├── chat.js    # Route for chatbot responses
│   ├── config/        # Configuration files
│   │   ├── keys.js    # API keys
│   ├── package.json   # Dependencies & scripts
│   ├── .env           # Environment variables
│── frontend/          # React frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── Chatbot.js  # Chatbot UI component
│   │   ├── App.js      # Main React app
│   │   ├── index.js    # React entry point
│   ├── package.json   # Dependencies
│── README.md          # Project documentation
│── .gitignore         # Ignore files (node_modules, .env)
```

## 🚀 Features
- Provides instant pet care advice (feeding, grooming, health, etc.)
- Uses OpenAI API for intelligent responses
- Simple and interactive chat UI
- Can be expanded to support reminders, vet connections, etc.

## 🛠 Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js with Express
- **AI Integration**: OpenAI API
- **Deployment**: Netlify (Frontend) + Render (Backend)

## 📌 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/petcare-chatbot.git
cd petcare-chatbot
```

### 2️⃣ Set Up Backend
```bash
cd backend
npm install
```
Create a `.env` file and add your OpenAI API key:
```
OPENAI_API_KEY=your_openai_api_key
PORT=5000
```
Start the backend:
```bash
node server.js
```
_Backend will run on_ **http://localhost:5000/**

### 3️⃣ Set Up Frontend
```bash
cd ../frontend
npm install
npm start
```
_Frontend will be available at_ **http://localhost:3000/**

## 🔥 API Endpoint
- **POST /chat** → Sends a message to the AI and returns a response
- Example request:
  ```json
  { "message": "How often should I feed my dog?" }
  ```
- Example response:
  ```json
  { "reply": "Adult dogs should be fed twice a day..." }
  ```

## 🎯 Future Enhancements
- 🕒 Pet care reminders
- 🎙️ Voice commands
- 📷 Pet breed recognition
- 📱 WhatsApp chatbot integration

## 🏗 Deployment
### Backend:
- Deploy on **Render** or **Heroku**
### Frontend:
- Deploy on **Netlify** or **Vercel**

## 🤝 Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Added new feature'`)
4. Push to your branch (`git push origin feature-name`)
5. Create a pull request

## 📜 License
This project is licensed under the MIT License.

## 📧 Contact
For any questions or suggestions, reach out at koushikgadirajueshwar@gmail.com


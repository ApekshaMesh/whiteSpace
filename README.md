# The White Space - Real-time Collaborative Canvas
A real-time collaborative white canvas that allows multiple users to draw simultaneously in a shared workspace. Built with React, Node.js, and Redis for real-time synchronization.

🚀 Features
Real-time collaborative canvas
User presence indicators
Shared workspace
Responsive design
📋 Prerequisites
Before running this project, make sure you have the following installed:

Node.js (v14 or higher)
npm or yarn
Redis (v6 or higher)
🛠️ Installation
Clone the repository:
git clone https://github.com/chetan-187/the-white-space.git
cd the-white-space
Install dependencies for both server and client:
# Install server dependencies
cd the-white-space-server
npm install

# Install client dependencies
cd ../the-white-space-web
npm install
Set up Redis:
Make sure Redis server is installed and running on your machine
Default Redis configuration uses:
Host: localhost
Port: 6379
No password (for local development)
⚙️ Configuration
Server Configuration:
cd the-white-space-server
# Create .env file with the following variables:
# PORT=8000
# REDIS_URL=redis://localhost:6379
Client Configuration:
cd the-white-space-web
# Create .env file with the following variables:
# REACT_APP_API_URL=http://localhost:8000
🚀 Running the Application
Start the server:
cd the-white-space-server
npm run dev
Start the client:
cd the-white-space-web
npm start
The application will be available at:

Frontend: http://localhost:3000
Backend: http://localhost:8000
🔧 Redis Setup
This project requires Redis for real-time functionality. Here's how to set it up:

macOS
# Using Homebrew
brew install redis
brew services start redis
Linux
# Ubuntu/Debian
sudo apt-get update
sudo apt-get install redis-server
sudo systemctl start redis-server
Windows
Download and install Redis from Redis Windows Downloads

Verify Redis Installation
redis-cli ping
# Should return PONG
🤝 Contributing
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

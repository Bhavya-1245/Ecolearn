# EcoLearn - Environmental Learning Platform

A comprehensive full-stack web application designed to educate and engage users in environmental sustainability through interactive games, challenges, quizzes, and community engagement. EcoLearn gamifies the learning experience to make environmental education fun and rewarding.

## 🌍 Overview

EcoLearn is an interactive platform that combines education with gamification to promote environmental awareness and sustainable practices. Users can participate in eco-challenges, take climate quizzes, earn achievements, track their progress, and connect with a community of like-minded individuals committed to environmental sustainability.

## ✨ Key Features

### User Management
- **Authentication System**: Secure user registration and login
- **User Profiles**: Personalized user profiles with customizable settings
- **Password Recovery**: Forgot password functionality
- **Account Settings**: User preferences and account management

### Educational Content
- **Climate Quiz**: Interactive climate change and environmental knowledge quiz
- **Eco-Scenarios**: Real-world environmental scenarios and case studies
- **Learning Dashboard**: Comprehensive learning progress tracking

### Gamification Elements
- **Eco-Challenges**: 7-day eco-challenges to encourage sustainable habits
- **Interactive Games**:
  - Recycling Game - Learn proper waste management
  - GameBall - Environmental educational game
  - Climate Quiz Game - Test climate knowledge
- **Achievement System**: Earn badges and achievements for completing tasks
- **Rewards System**: Unlock rewards based on participation and progress
- **Progress Tracking**: Visual representation of learning progress

### Community Features
- **Community Hub**: Connect with other learners
- **Admin Dashboard**: Organization management and user oversight
- **Contact System**: Direct communication with support team

### Additional Pages
- **About Us**: Learn about the EcoLearn mission and team
- **Privacy Policy**: Data protection and privacy information
- **Terms & Conditions**: User terms and service guidelines

## 🛠️ Tech Stack

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MySQL
- **Environment Management**: dotenv
- **Middleware**: CORS, Body Parser

### Frontend
- **HTML5**: Structure
- **CSS3**: Styling
- **JavaScript**: Interactivity
- **Responsive Design**: Mobile-friendly interface

## 📁 Project Structure

```
Ecolearn/
├── index.html                  # Main landing page
├── dashboard.html              # User dashboard
├── login.html & register.html  # Authentication pages
├── challenges.html             # Eco-challenges page
├── climate-quiz.html           # Climate quiz game
├── achievements.html           # User achievements
├── rewards.html                # Rewards system
├── progress.html               # Progress tracking
├── community.html              # Community features
├── profile.html                # User profile
├── settings.html               # User settings
├── admin_dashboard.html        # Admin panel
├── css/                        # Stylesheets for each page
├── js/                         # JavaScript files for page functionality
├── images/                     # Image assets
├── database.sql                # Database schema and setup
├── server.js                   # Express server configuration
└── package.json                # Project dependencies
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MySQL database
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Ecolearn
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```
   DB_HOST=localhost
   DB_USER=your_mysql_user
   DB_PASSWORD=your_mysql_password
   DB_NAME=ecolearn_db
   PORT=3000
   ```

4. **Set up the database**
   ```bash
   mysql -u your_mysql_user -p < database.sql
   ```

5. **Start the server**
   ```bash
   npm start
   ```
   For development with auto-reload:
   ```bash
   npm run dev
   ```

6. **Access the application**
   Open your browser and navigate to `http://localhost:3000`

## 📦 Dependencies

### Production
- **express**: Web framework
- **mysql2**: MySQL database driver
- **cors**: Cross-Origin Resource Sharing middleware
- **body-parser**: Request body parsing middleware
- **dotenv**: Environment variable management

### Development
- **nodemon**: Auto-restart server during development

## 🎮 How to Use

1. **Sign Up**: Create an account on the registration page
2. **Login**: Access your account with credentials
3. **Explore Dashboard**: View your learning progress and statistics
4. **Participate in Challenges**: Join 7-day eco-challenges
5. **Take Quizzes**: Test your environmental knowledge
6. **Play Games**: Engage in educational games
7. **Earn Achievements**: Unlock badges by completing tasks
8. **Connect**: Join the community and share experiences
9. **Track Progress**: Monitor your learning journey

## 🔐 Security Features

- Secure user authentication
- Password encryption and recovery
- CORS protection
- Input validation and sanitization
- Environment variable protection for sensitive data

## 📊 Database

The application uses MySQL for data persistence. Key tables include:
- Users (authentication and profile data)
- Challenges (eco-challenge information)
- Quizzes (quiz questions and answers)
- Achievements (user achievements and badges)
- Progress (user learning progress tracking)
- Community posts (user interactions)

## 🤝 Contributing

Contributions are welcome! To contribute:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Support

For support and inquiries, please use the contact form on the website or reach out through the community forum.

## 🌱 Mission

EcoLearn's mission is to inspire and educate individuals about environmental sustainability through engaging, interactive learning experiences. We believe that education combined with gamification can drive meaningful behavioral change toward a more sustainable future.
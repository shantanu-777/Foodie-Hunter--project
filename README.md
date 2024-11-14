
# Foodie Hunter 🍔🍕🍜

**Foodie Hunter** is a web-based application designed to help users discover the best restaurants, cafes, and food spots in their area. This project aims to enhance the food exploration experience by providing curated lists, user reviews, and ratings to guide food enthusiasts in finding their next favorite meal destination.

## 🔍 Overview

Foodie Hunter leverages **React.js** for a dynamic frontend, **Flask** for backend data processing, and a **MongoDB** database for storing restaurant data and user reviews. The app integrates with third-party APIs to fetch real-time restaurant information, allowing users to explore the latest food trends and hidden gems in their city.

## ✨ Features

- **Restaurant Search**: Discover restaurants by cuisine, location, or user ratings.
- **User Reviews & Ratings**: Leave feedback on your dining experience and read reviews from others.
- **Personalized Recommendations**: Get tailored restaurant suggestions based on user preferences.
- **Responsive Design**: Optimized for desktop and mobile devices.

## 🚀 Tech Stack

- **Frontend**: React.js, HTML, CSS, Bootstrap
- **Backend**: Python, Flask
- **Database**: MongoDB
- **APIs**: Zomato API / Yelp API
- **Deployment**: Heroku / AWS
- **Version Control**: Git, GitHub

## 🛠️ Installation & Setup

Follow these steps to set up the project on your local machine.

### Prerequisites
- **Python** (v3.8 or above)
- **Node.js** (v14 or above)
- **npm** (v6 or above)
- **MongoDB** (local or cloud instance)

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/shantanu-777/Foodie-Hunter--project.git
   cd Foodie-Hunter--project
   ```

2. **Install backend dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Install frontend dependencies**:

   ```bash
   cd client
   npm install
   ```

4. **Set up environment variables**:
   Create a `.env` file in the root directory with the following content:

   ```env
   FLASK_APP=app.py
   MONGODB_URI=<your-mongodb-uri>
   API_KEY=<your-api-key>
   SECRET_KEY=<your-secret-key>
   ```

5. **Run the application**:

   ```bash
   # Run backend
   flask run

   # Run frontend (in a separate terminal)
   cd client
   npm start
   ```

6. **Access the app**:
   - Frontend: [http://localhost:3000](http://localhost:3000)
   - Backend: [http://localhost:5000](http://localhost:5000)

## 📱 Usage

- **For Food Enthusiasts**:
  - Search for top-rated restaurants, browse reviews, and leave feedback.
  - Use filters to find restaurants based on cuisine, budget, or location.

## 📂 Project Structure

```
Foodie-Hunter--project
├── client
│   ├── public
│   ├── src
│   ├── components
│   ├── pages
│   ├── utils
├── models
├── routes
├── controllers
├── static
├── templates
├── .env
├── app.py
├── requirements.txt
└── README.md
```

## 🤝 Contributing

Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.

### Steps to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## 🛡️ License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

## 📧 Contact

For any inquiries or support, feel free to reach out:

- **Shantanu Modhave** - [LinkedIn](https://www.linkedin.com/in/shantanumodhave/)
- **GitHub**: [shantanu-777](https://github.com/shantanu-777)

---

Thank you for exploring **Foodie Hunter**! 🌟 If you found this project helpful, please consider leaving a star ⭐ on the repo.
```

### Instructions:
- Copy this content into the `README.md` file in your `Foodie-Hunter` project.
- Replace placeholders such as `<your-mongodb-uri>` and `<your-api-key>` with your actual environment details.

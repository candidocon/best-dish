# project2 - Best Dish
# Best Dish

## Disclaimer
This project previously relied on the Zomato API for location information. However, as of December 2023, Zomato has discontinued support for their public API, rendering this functionality inactive.

## Overview
Best Dish is a full CRUD web application that allows users to share and discover the best dishes from local restaurants. Users can add their favorite dishes, browse other recommendations, and engage with the foodie community.

## Features
- 🌟 Add your favorite dishes from restaurants
- 🔍 Browse and discover top-rated dishes
- 📝 Edit or delete your added dishes
- 🖼️ Upload images for dishes
- 📍 Search dishes by location or category
- 🛡️ User authentication for secure access

## Tech Stack
- **Frontend:** JavaScript, Handlebars, HTML, CSS, Materialize
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Hosting:** Vercel (Frontend), MongoDB Atlas (Database)

## Live Demo
Check out the live version: [Best Dish](https://best-dish.vercel.app)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/candidocon/best-dish.git
   cd best-dish
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add:
   ```env
   MONGO_URI=your_mongodb_connection_string
   SESSION_SECRET=your_secret_key
   PORT=3000
   ```

4. **Start the development server:**
   ```bash
   npm start
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Contributing
Contributions are welcome! If you'd like to improve this project:
- Fork the repository
- Create a new branch (`feature/your-feature`)
- Commit your changes
- Submit a pull request

## License
This project is open-source and available under the MIT License.

---
Made with ❤️ by [Candido Concepcion](https://github.com/candidocon).


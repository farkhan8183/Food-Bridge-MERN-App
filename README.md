 # Food Bridge - MERN Stack Surplus Food Distribution Platform
Food Bridge is a full-stack web application designed to combat food insecurity and waste in Pakistan. It provides a seamless interface for restaurants and households to donate surplus food to NGOs and individuals in need.

## 🔗 [Live Demo: Food Bridge App](https://food-bridge-mern-app-1.onrender.com/)
## [![LinkedIn Post](https://img.shields.io/badge/LinkedIn_Post-View_Demo_&_Discussion-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/posts/farhan-ahmed-712031305_mernstack-webdevelopment-javascript-activity-7438811529380184064-np-S)

## The Mission:
In Pakistan, millions of tons of food are wasted annually while a significant portion of the population faces food insecurity. This project bridges that gap using modern web technology to create a localized, efficient donation ecosystem.

## Tech Stack & Architecture
Frontend: React.js (Hooks, Context API, Tailwind CSS)

Backend: Node.js & Express.js

Database: MongoDB (Mongoose)

Authentication: JWT (JSON Web Tokens) with Secure Cookie storage

Deployment: Render (Backend/Frontend), MongoDB Atlas (Cloud Database)

## Key Features:
Secure User Roles: Distinct dashboards for Donors (Restaurants/Individuals),Volunteers and Recipients (NGOs/Volunteers).

Real-time Listings: Donors can post food items with expiry times, quantity, and pickup locations.

Interactive Food Feed: Recipients can browse available food based on their current location.

Volunteer Empowerment: A dedicated portal for welfare contributors to join the mission.

Request Management: Track the status of food claims from "Pending" to "Picked Up."

Responsive UI: Fully optimized for mobile and desktop, ensuring accessibility for all users.

## The Real Challenge? 
> Managing three different user roles (Donor, Volunteer, Recipient) in one seamless ecosystem. I tackled this by implementing JWT-based Role-Based Access Control (RBAC), ensuring that user sessions are handled securely and redirected to the correct dashboard via custom React middleware.

## Installation & Local Setup
To run this project locally, follow these steps:

Clone the repository:
Bash
git clone https://github.com/your-username/food-bridge.git

Install dependencies:

## For Backend
npm install
## For Frontend
cd client && npm install

Environment Variables:
Create a .env file in the root directory and add:
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
PORT=5000

Run the app:
npm run dev


## Future Enhancements
[ ] Google Maps API integration for precise location tracking.
[ ] Push notifications for NGOs when food is donated nearby.
[ ] Rating system for donors to ensure food quality.

##  Contact

For queries, support, or contributions:

- **Abdul Haadi** – [GitHub](https://github.com/abdulhaadi0303)
- **Farhan Ahmed** – [GitHub](https://github.com/farkhan8183)

---

Happy coding! 🚀

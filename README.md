# 🛍️ Adaa Jaipur - E-Commerce Platform
 
 🏆 **Special Track Winner - Best UI/UX Design**
 *Adaa Jaipur X Marwadi University Build & Brand Challenge*
 
 ---
 
 ## Overview
 
 The E-Commerce Website is a fully functional online shopping platform designed to provide users with an intuitive and engaging shopping experience. The site features dynamic user interface elements, a wide range of products categorized for easy navigation, and robust functionalities for managing user interactions with products, including wishlist and cart features. Users can register, log in, browse products, add items to their cart and wishlist, and complete purchases seamlessly.
 
 ## 👩‍💻 Live demo
 
 [https://dhairyafrontend.netlify.app/](https://dhairyafrontend.netlify.app/)
 
 ## Setup Instructions
 
 To set up the project locally, follow these instructions:
 
 ### Prerequisites
 
 * Node.js (version 14 or higher)
 * MongoDB (local installation or MongoDB Atlas account)
 
 ### Clone the Repository
 
 ```bash
 git clone https://github.com/yourusername/ecommerce-website.git
 cd ecommerce-website
 ```
 
 ### Install Dependencies
 
 Navigate to both the frontend and backend directories to install the required dependencies.
 
 #### Backend Setup
 
 1. Navigate to the backend directory:
 
    ```bash
    cd backend
    ```
 
 2. Install backend dependencies:
 
    ```bash
    npm install
    ```
 
 3. Create a .env file in the backend directory and add your environment variables:
 
    ```env
    MONGO_URI=your_mongodb_connection_string_here
    JWT_SECRET=your_jwt_secret_here
    PORT=5000
    ```
 
 4. Start the backend server:
 
    ```bash
    npm start
    ```
 
 #### Frontend Setup
 
 1. Open a new terminal window and navigate to the frontend directory:
 
    ```bash
    cd frontend
    ```
 
 2. Install frontend dependencies:
 
    ```bash
    npm install
    ```
 
 3. Start the frontend development server:
 
    ```bash
    npm start
    ```
 
 ### Access the Application
 
 Once both servers are running, you can access the application by navigating to [http://localhost:3000](http://localhost:3000) in your web browser.
 
 ## 📸 Screenshots
 
 ![image](https://github.com/user-attachments/assets/1842e9d6-6be0-44e7-ac79-6ee49811c2f4)
 ![image](https://github.com/user-attachments/assets/d9a7c31b-5f4b-4c88-9b1c-43e06a4a0378)
 ![image](https://github.com/user-attachments/assets/1a8f0459-75d6-43d5-9e94-0107041c008f)
 
 ---
 
 ## Key Features
 
 * *User Authentication*: Users can sign up, log in, and manage their accounts securely.*Dynamic Navbar*: The navbar adapts its color based on the background for optimal visibility.
 * *Product Browsing*: Users can view products categorized by type (e.g., Kurta, Saree).
 * *Wishlist Functionality*: Users can save products to their wishlist for future reference.
 * *Cart Management*: Users can add products to their cart, adjust quantities, and proceed through a multi-step checkout process.
 * *Stock Management*: Users can only add available products to their cart based on selected size and color.
 * *Responsive Design*: The website is designed to be mobile-friendly for seamless use across devices.
 * *Order History*: Users can view their past orders in their profile.
 
 ## Tech Stack
 
 The following technologies were used in the development of the E-Commerce Website:
 
 * *Frontend*:
 
   * React
   * React Router
   * Styled Components
   * Axios
 
 * *Backend*:
 
   * Node.js
   * Express.js
   * MongoDB (with Mongoose)
   * Bcrypt (for password hashing)
   * Jsonwebtoken (for authentication)
 
 ## Contributing
 
 Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.
 
 ## License
 
 This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 
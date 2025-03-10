# Online Computer Hardware Store Management

## Project Overview
This project is an **Online Computer Hardware Store Management** system that allows users to browse, search, and purchase hardware products such as RAM, processors, motherboards, and peripherals. The system provides a seamless shopping experience with secure payment options and an intuitive UI.

## Features
- **User Authentication**: Register, login, and manage user profiles.
- **Product Management**: Add, edit, delete, and view product details.
- **Shopping Cart**: Add and remove products from the cart.
- **Order Processing**: Checkout process with secure payment.
- **Admin Dashboard**: Manage products, users, and orders.
- **Search & Filter**: Easily find products based on category, price, and brand.

## Technologies Used
- **Frontend**: Angular, Angular Material
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Version Control**: Git & GitHub
- **Other Tools**: Visual Studio Code, Postman

## Installation
### Prerequisites:
- Node.js & npm installed
- MongoDB installed and running

### Steps to Run the Project:
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. **Install dependencies**
   ```sh
   npm install
   ```
3. **Start MongoDB server**
   ```sh
   mongod --dbpath /path-to-your-db
   ```
4. **Run the backend server**
   ```sh
   node server.js
   ```
5. **Run the frontend**
   ```sh
   ng serve
   ```
6. Open `http://localhost:4200` in your browser.

## API Endpoints
| Method | Endpoint           | Description             |
|--------|-------------------|-------------------------|
| GET    | /api/products     | Fetch all products      |
| POST   | /api/sign_up      | User registration       |
| POST   | /api/user_login   | User authentication     |
| POST   | /api/addproduct   | Admin adds a product    |
| DELETE | /api/productdelete | Admin deletes a product |
| POST   | /api/order        | User places an order    |

## Future Enhancements
- Implement AI-based personalized product recommendations.
- Add real-time order tracking.
- Integrate multiple payment gateways.
- Develop a mobile application for better accessibility.

## Contributors
- **Abishek B** - Developer
- **Domnic Sam J** - Developer

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries, feel free to contact:
- **Email**: abishekar2000@gmail.com
- **LinkedIn**: Abishek Balraj https://www.linkedin.com/in/abishekbalraj/


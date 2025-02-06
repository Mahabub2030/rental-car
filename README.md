# Super Cars - Luxury Car Purchase & Test Drive Booking

## Project Overview
Super Cars is a high-performance luxury car purchasing and test drive booking platform. It offers a sleek and modern interface, allowing users to explore models, compare specifications, and place orders seamlessly.

## Features
- **Dynamic Landing Page**: Showcasing high-performance supercars with key specifications.
- **Car Inventory**: Browse through various models, brands, and types of cars.
- **Test Drive Booking**: Users can book a test drive for their favorite cars.
- **Order Form**: A form to select car brand, type, model, and transmission for purchase.
- **Responsive Design**: Optimized for all screen sizes.
- **Modern UI/UX**: Designed with Tailwind CSS and DaisyUI for a smooth experience.

## Technologies Used
- **Frontend**: HTML, Tailwind CSS, DaisyUI, JavaScript (React.js recommended for scalability)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (for storing orders and test drive requests)
- **Hosting**: Vercel (Frontend), Heroku/Render (Backend)

## Installation Guide
### Backend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/super-cars.git
   cd super-cars/backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file and add:
   ```env
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```
4. Start the server:
   ```sh
   npm start
   ```
   - The backend runs on `http://localhost:5000`

### Frontend Setup
1. Navigate to the frontend folder:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React application:
   ```sh
   npm start
   ```
   - The frontend runs on `http://localhost:3000`

## API Endpoints
| Method | Endpoint          | Description           |
|--------|------------------|-----------------------|
| GET    | `/api/cars`      | Fetch all car models |
| POST   | `/api/orders`    | Place an order       |
| POST   | `/api/testdrive` | Book a test drive    |

## Folder Structure
```
project-root/
│── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── server.js
│   ├── .env
│── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── App.js
│   ├── index.js
│── README.md
```

## Future Enhancements
- **User Authentication**: Implement JWT-based login and register functionality.
- **Admin Dashboard**: Manage orders and test drive bookings.
- **Payment Integration**: Secure online transactions.
- **Car Comparison Tool**: Allow users to compare multiple car models.

## License
This project is open-source under the MIT License.

## Contributing
Feel free to fork this repository and submit pull requests for improvements!

## Contact
For any inquiries, reach out to `mahabubalam407557@gmail.com` or visit the [GitHub Repository](https://github.com/your-username/super-cars).


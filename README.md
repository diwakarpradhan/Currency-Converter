# Currency Converter
A simple and intuitive currency converter application built with React and the MERN stack. This project allows users to convert amounts between different currencies with real-time exchange rates.

## Features

- Convert between multiple currencies.
- Swap currencies easily.
- Real-time exchange rate updates.
- Responsive design with a user-friendly interface.

## Preview
![currency](https://github.com/user-attachments/assets/3419a96f-3dee-4ba6-80b5-76ae8be0ebf5)

## Technologies Used
**Frontend:**
- HTML
- CSS
- JavaScript
- React.js

**Backend:**
- Node.js
- Express.js
- MongoDB (for storing historical exchange rates)
**APIs:**
- Currency Exchange API (for fetching real-time rates)

## Getting Started
### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)
### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/currency-converter.git
cd currency-converter
```
2. Install dependencies:
For the frontend:
```bash
cd frontend
npm install
```
For the backend:
```bash
cd backend
npm install

```
3. Configure the environment:
```bash
CURRENCY_API_KEY=your-api-key

```
4. Run the application:
Start the backend server:
```bash
cd backend
npm start
```
Start the frontend development server:
```bash
cd frontend
npm start
```
5. Open your browser:
Navigate to ```bash http://localhost:3000``` to view the application.


## File Structure
- ```bash frontend/: ``` Contains the React application.

  * ```bash src/: ``` Source files for the React app.
    * ```bash components/:``` React components used in the application.
    * ```bash hooks/:``` Custom React hooks for fetching currency information.
    * ```bash App.jsx:``` Main React component for the currency converter interface.
  * ```bash public/: ``` Static assets and HTML template.

- ```bash backend/: ``` Contains the Node.js and Express.js server.

  * ```bash server.js:``` Entry point for the backend server.
  * ```bash routes/: ``` API routes for fetching currency data.
  * ```bash models/: ``` Mongoose models for interacting with MongoDB.

## Contributing
Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request. Your improvements are appreciated.


# Inventory Management App

## Introduction
In today’s business landscape, efficient inventory management is crucial for companies of all sizes. Whether you’re running a small e-commerce store, managing a warehouse, or overseeing a complex supply chain, having a robust digital solution to track your inventory can significantly improve your operations. This project will guide you through the process of building an Inventory Management App using cutting-edge web technologies.

## Features
- **Add Items**: Users can add new items to their inventory.
- **Monitor Quantities**: Keep track of item quantities in real-time.
- **Remove Items**: Remove items when they’re sold or used.
- **Responsive Design**: A sleek and responsive user interface using Material-UI.

## Technologies Used
- **Next.js**: React framework for building the application.
- **Material-UI**: For creating a modern, responsive UI.
- **Firebase Firestore**: Backend database for real-time data handling.

## Getting Started
### Prerequisites
- Node.js and npm installed on your machine.
- Firebase account for Firestore setup.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/inventory-management-app.git
2. Navigate to the project directory:
   ```bash
   cd inventory-management-app
3. Install Dependencies
   ```bash
   npm install

### Configuration
1. Create a Firebase project and set up Firestore.
2. Add your Firebase configuration to the project by creating a .env file in the root     directory and adding the following:
   ```bash
   NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id

### Running the App
1. Start the development server:
    ```bash
    npm run dev
2. Open your browser and navigate to http://localhost:3000.

### Usage
* Add Items: Use the form provided to add new items to your inventory.
* Monitor Quantities: View the list of items and their quantities.
* Remove Items: Delete items from the inventory as needed.

### Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.


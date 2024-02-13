
# React Message Poster

The React Message Poster is a simple yet powerful application designed to demonstrate the capabilities of a React frontend working seamlessly with an Express backend. This application allows users to post messages through a web interface, where they are then processed and stored by the backend server.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14.0.0 or higher recommended)
- npm (v6.0.0 or higher)

### Installation

1. **Clone the React frontend repository**

   ```bash
   git clone https://github.com/sethlarkin/react-message-poster.git
   cd react-message-poster
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Clone the Express backend repository**

   ```bash
   git clone https://github.com/sethlarkin/express-message-poster-basic-backend.git
   cd express-message-poster-basic-backend
   ```

4. **Install dependencies**

   ```bash
   npm install
   ```

### Running the Application

1. **Start the backend server**

   Navigate to the `express-message-poster-basic-backend` directory and run:

   ```bash
   npm start
   ```

   This will start the backend server on `http://localhost:3001`.

2. **Start the React frontend application**

   Open a new terminal, navigate to the `react-message-poster` directory, and run:

   ```bash
   npm run dev
   ```

   This will start the frontend application and open it in your default web browser. By default, it runs on `http://localhost:3000`.

## Usage

Once both the frontend and backend are running, you can use the web interface to post messages. Enter your message in the input field and submit it. The message will be sent to the backend, where it will be processed and stored.

## Contributing

We welcome contributions to this project! Please consider the following steps to contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to everyone who contributed to this project.
- Inspired by the vibrant React and Express communities.

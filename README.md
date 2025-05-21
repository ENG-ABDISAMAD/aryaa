# Frontend Certificate Management System

This project is a MERN stack application that allows administrators to manage student data and generate certificates. The frontend is built using React and provides a user-friendly interface for uploading student data, modifying certificate templates, and enabling students to download their certificates.

## Features

- **Admin Dashboard**: Admins can upload student data from Excel files and certificate templates.
- **Certificate Editor**: Modify certificate data for each student.
- **Student Search**: Search for student data easily.
- **Student Portal**: Students can view and download their PDF certificates.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB server running.

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the frontend directory:
   ```
   cd mern-certificate-system/frontend
   ```

3. Install the dependencies:
   ```
   npm install
   ```

### Running the Application

To start the frontend application, run:
```
npm start
```

### Development

For development, you can use `nodemon` to automatically restart the server on changes. Make sure to run the backend server in a separate terminal:
```
cd mern-certificate-system/backend
npm run dev
```

### Folder Structure

- **public/**: Contains the main HTML file.
- **src/**: Contains all React components and pages.
- **components/**: Reusable components for the application.
- **pages/**: Different pages of the application.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features.

## License

This project is licensed under the MIT License.
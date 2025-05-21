# Intelligent Tutoring System

An AI-powered web application designed to provide personalized learning experiences through adaptive assessments and real-time feedback. Built with modern web technologies, this system aims to enhance the educational journey for students and educators alike.

---

## 🚀 Features

- **Adaptive Learning**: Tailors content based on individual student performance.
- **Real-time Feedback**: Provides immediate insights to guide learners.
- **User Roles**: Supports both students and educators with role-specific functionalities.
- **Modern UI**: Responsive and intuitive interface built with Next.js and Tailwind CSS.

---

## 🛠️ Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: Vercel / Heroku

---

## 📂 Project Structure

```bash
├── app/                # Application logic and routing
├── components/         # Reusable UI components
├── public/             # Static assets
├── utils/              # Utility functions
├── .env                # Environment variables
├── package.json        # Project metadata and dependencies
├── tailwind.config.ts  # Tailwind CSS configuration
└── tsconfig.json       # TypeScript configuration
```

---

## 🧑‍💻 Getting Started

### Prerequisites

- Node.js v14 or higher
- npm or yarn
- MongoDB instance

### Installation

```bash
# Clone the repository
git clone https://github.com/ReversibleWizard/Intelligent-Tutoring-System.git

# Navigate to the project directory
cd Intelligent-Tutoring-System

# Install dependencies
npm install
# or
yarn install
```

### Configuration

Create a `.env` file in the root directory and add the following:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### Running the Application

```bash
# Start the development server
npm run dev
# or
yarn dev
```

The application will be accessible at `http://localhost:3000`.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

## 📬 Contact

For questions or support, please open an issue in the repository.

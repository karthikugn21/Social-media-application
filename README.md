# Social Media Application

A full-stack social media web application with separate **backend** and **frontend** modules, containerized with Docker and integrated with Jenkins for CI/CD.

## 🚀 Tech Stack

- **Backend:** Node.js / JavaScript
- **Frontend:** HTML, JavaScript
- **Containerization:** Docker & Docker Compose
- **CI/CD:** Jenkins (`Jenkinsfile` included)

## 📁 Project Structure

```
Social-media-application/
├── backend/              # Server-side application (API, business logic)
├── frontend/             # Client-side application (UI)
├── docker-compose.yml    # Multi-container Docker setup
├── Jenkinsfile           # CI/CD pipeline configuration
├── package.json          # Project dependencies and scripts
└── .gitignore
```

## ✨ Features

- User authentication (sign up / log in)
- Create, view, and interact with posts
- RESTful API backend
- Responsive web frontend
- Dockerized setup for easy local development and deployment
- Automated CI/CD pipeline via Jenkins

> Update this section with the specific features your app implements (e.g., likes, comments, follows, messaging, notifications, image uploads).

## 🛠️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or later recommended)
- [Docker](https://www.docker.com/) & Docker Compose
- npm or yarn

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/karthikugn21/Social-media-application.git
   cd Social-media-application
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Set up environment variables

   Create a `.env` file in the `backend/` directory with the required configuration (database URL, JWT secret, port, etc.).

### Running Locally

**Using Docker Compose (recommended):**
```bash
docker-compose up --build
```

**Running manually:**
```bash
# Backend
cd backend
npm install
npm start

# Frontend (in a separate terminal)
cd frontend
npm install
npm start
```

## 🔄 CI/CD

This project includes a `Jenkinsfile` for automated build, test, and deployment pipelines. Configure your Jenkins server to point to this repository to enable automated pipelines on push.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to open a pull request or an issue.

## 📄 License

This project currently has no license specified. Add a `LICENSE` file if you'd like to open it up for public use.

## 👤 Author

**Karthik Upadhya**

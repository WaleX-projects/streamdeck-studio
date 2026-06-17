
## Backend (NFlix-api)

```markdown name=NFlix-api/README.md url=https://github.com/WaleX-projects/NFlix-movie/blob/main/NFlix-api/README.md
# Netflix Clone API

Welcome to the Netflix Clone API project! This repository contains the backend API that mimics the functionality of the Netflix streaming service.

## Table of Contents

- [Getting Started](#getting-started)
- [Features](#features)
- [API Endpoints](#api-endpoints)
- [Authentication](#authentication)
- [Usage Example](#usage-example)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with the Netflix Clone API, you need to clone this repository and install the required dependencies.

### Prerequisites
- Python3 (v3.13)
- Django (v6 or later)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/WaleX-projects/netflix-clone-api.git
   cd netflix-clone-api
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/scripts/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirement.txt
   ```

4. Make migration and run server:
   ```bash
   python manage.py migrate
   python add_database.py
   python manage.py runserver
   ```

## Features

- User authentication and authorization
- Fetch data for movies, series, and episodes
- Search functionality
- Pagination support
- Recommendations based on user preferences

## API Endpoints

### User Endpoints
- POST /api/users/register: Register a new user
- POST /api/users/login: Login an existing user

### Movie Endpoints
- GET /api/movies: Retrieve a list of movies
- GET /api/movies/:id: Get details of a specific movie

### Search Endpoint
- GET /api/search: Search for movies or shows based on query

## Authentication

This API uses token-based authentication. After successful login, a token will be returned which must be included in the headers of subsequent requests:

```bash
Authorization: Bearer <token>
```

## Usage Example

To fetch a list of movies, you can use the following curl command:

```bash
curl -H "Authorization: Bearer <token>" http://localhost:3000/api/movies
```

## Contributing

Contributions are welcome! Please submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

Thank you for checking out the Netflix Clone API!
```

## Frontend (NFlix-frontend)

```markdown name=NFlix-frontend/README.md url=https://github.com/WaleX-projects/NFlix-movie/blob/main/NFlix-frontend/README.md
# Welcome to your Lovable project

TODO: Document your project here
```

---

**Summary:** Your repo has a comprehensive backend README for the Django API, but the frontend README still needs to be documented. The backend is a Netflix Clone API with Django/Python, featuring user authentication, movie data fetching, search functionality, and pagination. The frontend appears to be a Lovable project that needs documentation.

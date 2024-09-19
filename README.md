# StreetShelf

Welcome to **StreetShelf**, a web application designed to make it easier for students, parents, and educators to **buy, sell, and swap** used school books. Our platform helps reduce the cost of education by providing a marketplace for affordable, second-hand books. Whether you're looking to swap textbooks, give them away for free, or sell them, StreetShelf makes it possible in a user-friendly environment.

## Table of Contents
1. [Purpose](#purpose)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Technologies](#technologies)
6. [Future Features](#future-features)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Purpose

StreetShelf was created to solve the problem of expensive school books by allowing users to exchange used books, either by swapping, selling, or giving them away for free. It is built to support students and families who want to reduce educational costs by leveraging second-hand books.

## Features

- **User Authentication**: Sign up or log in to create your profile.
- **Create Listings**: Post your used books with details such as title, description, and price (if applicable).
- **Browse and Search**: Search for books based on filters like grade, subject, or type (swap, free, for sale).
- **Chat**: Real-time chat functionality to discuss book details and finalize swaps or purchases.
- **Follow Users**: Follow sellers who list books you’re interested in for future updates.
- **Flag Users**: Report users who engage in scams or inappropriate behavior.
- **Mobile Responsive**: Fully responsive design for an optimized experience on mobile and desktop devices.

## Installation

### Prerequisites
Before you can run StreetShelf, ensure you have the following installed:
- Python 3.x
- Flask
- SQLite (or another database, as needed)

### Step-by-Step Installation Guide
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/streetshelf.git
    cd streetshelf
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up the database:
    ```bash
    flask db upgrade
    ```

5. Run the application:
    ```bash
    flask run
    ```

6. Access the website by visiting `http://127.0.0.1:5000` in your browser.

## Usage

### Landing Page
- On the homepage, users can browse available book listings, use the search bar, or register for an account.

### User Profile
- After logging in, users can view their profile, which includes:
  - Profile Picture
  - Username
  - Listed Books
  - Wishlist (Books they are looking for)

### Book Listings
- Users can create a new book listing by clicking on the "Add New Book" button, filling out details about the book, and submitting it.

### Chat
- From any book listing page, users can initiate a chat with the person who posted the book. The chat window allows them to discuss exchange or sale details in real-time.

## Technologies

### Frontend
- **HTML5, CSS3**: For structuring and styling the web pages.
- **JavaScript**: To handle dynamic elements and user interactions.
- **Bootstrap**: For creating a responsive design.

### Backend
- **Python (Flask)**: Flask was chosen for its simplicity and flexibility in building web applications.
- **SQLite**: A lightweight database used to store user profiles, book listings, and chat messages.

### Additional Tools
- **SocketIO**: For real-time chat functionality.
- **Flask-Login**: To manage user sessions and authentication.
- **Flask-SQLAlchemy**: For interacting with the SQLite database.

## Future Features

Some planned future enhancements include:
- **Payment Integration**: Adding support for secure payments between users for books being sold.
- **Enhanced Search Filters**: Allowing more specific searches based on user preferences.
- **Book Reviews**: Users can leave reviews for books after purchase or exchange.

## Contributing

We welcome contributions! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch-name
   ```
3. Make your changes.
4. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Add a meaningful message"
   git push origin feature-branch-name
   ```
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or feedback, feel free to reach out:

- **Project Link**: [GitHub Repo](https://github.com/your-username/streetshelf)
- **Deployed Website**: [StreetShelf Live](#)
- **LinkedIn**: [Your LinkedIn Profile](#)

Happy book swapping!

---

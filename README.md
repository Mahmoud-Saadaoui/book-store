# 📚 Book Store

A modern, responsive online bookstore built with React. Browse books, manage your shopping cart, and explore a curated collection of bestsellers and popular titles.

![React](https://img.shields.io/badge/React-18.2.0-blue?logo=react)
![React Router](https://img.shields.io/badge/React_Router-6.0.2-red?logo=react-router)
![License](https://img.shields.io/badge/License-Private-lightgrey)

## ✨ Features

- **📖 Book Catalog**: Browse through a diverse collection of books with detailed information
- **🔍 Search Functionality**: Find your favorite books quickly with the integrated search feature
- **🛒 Shopping Cart**: Add books to cart with full cart management (add, remove, update quantities)
- **✍️ Author Profiles**: Explore detailed author information and their works
- **📱 Responsive Design**: Fully responsive layout that works seamlessly on all devices
- **💬 Contact Page**: Get in touch through the contact form
- **⭐ Book Ratings & Reviews**: View ratings and review counts for each book
- **📊 Book Details**: Comprehensive book information including:
  - Price and availability status
  - Print length
  - Language
  - Publication date
  - Author information
  - Customer reviews count

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** 
- **npm** 

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd book-store
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application.

## 📦 Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode.  
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.  
You may also see any lint errors in the console.

## 🏗️ Project Structure

```
book-store/
├── public/
│   ├── authors/          # Author images
│   ├── books/            # Book cover images
│   └── index.html        # HTML template
├── src/
│   ├── components/       # Reusable components
│   │   ├── Modal/
│   │   ├── Services/
│   │   ├── Slider/
│   │   ├── book-slider/
│   │   ├── deal/
│   │   ├── footer/
│   │   ├── header/
│   │   └── heading-title/
│   ├── context/          # React Context (Cart state management)
│   │   ├── CartContext.js
│   │   └── CartProvider.jsx
│   ├── data/             # Static data
│   │   ├── authors.js
│   │   ├── books.js
│   │   └── cart.js
│   ├── images/           # Image assets
│   ├── pages/            # Page components
│   │   ├── About/
│   │   ├── Authors/
│   │   ├── Book/
│   │   ├── Cart/
│   │   ├── Home/
│   │   ├── contact/
│   │   ├── forms/        # Login & Register
│   │   └── search/
│   ├── App.js            # Main app component
│   ├── App.css           # App styles
│   ├── index.js          # Entry point
│   └── index.css         # Global styles
├── package.json
└── README.md
```

## 🛣️ Routes

The application includes the following routes:

| Route | Description |
|-------|-------------|
| `/` | Home page with featured books |
| `/about` | About the bookstore |
| `/authors` | List of authors |
| `/contact` | Contact form |
| `/book/:param` | Individual book details page |
| `/cart` | Shopping cart |
| `/login` | User login |
| `/register` | User registration |
| `/search` | Search results |

## 🛠️ Technologies Used

- **React** (18.2.0) - JavaScript library for building user interfaces
- **React Router DOM** (6.0.2) - Declarative routing for React applications
- **React Toastify** (9.1.1) - Toast notifications for user feedback
- **React Scripts** (5.0.1) - Configuration and scripts for Create React App
- **Context API** - State management for shopping cart

## 📚 Sample Books

The store includes popular titles such as:
- Atomic Habits by James Clear
- Confess by Colleen Hoover
- Rich Dad Poor Dad by Robert T. Kiyosaki
- Think and Grow Rich by Napoleon Hill
- Never Split The Difference by Chris Voss
- And many more...

## 🎨 Features in Detail

### Shopping Cart Management
- Powered by React Context API for global state management
- Add/remove items from cart
- Update quantities
- Persistent cart state across pages

### Book Information
Each book includes:
- High-quality cover image
- Title and author
- Price
- Star rating (out of 5)
- Number of reviews
- Print length
- Language
- Publication date
- Stock availability

### Responsive Design
- Mobile-first approach
- Optimized for tablets and desktops
- Smooth animations and transitions

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is private and not licensed for public use.

## 📧 Contact

For any questions or suggestions, please use the contact form in the application or reach out through the contact page.

---

**Built with ❤️ using React**

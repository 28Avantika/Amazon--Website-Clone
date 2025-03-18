# Amazon Clone Project

## Overview
This is a static Amazon Clone webpage created using HTML and CSS. The project was developed as a learning exercise to understand web page structuring, styling, and responsive design.

---

## Features
- **Navigation Bar**: Amazon-like top navigation bar with logo, search box, and menu options.
- **Hero Section**: Large banner image mimicking Amazon's promotional banners.
- **Product Categories**: Multiple product sections with images, arranged in a grid layout.
- **Footer Section**: Contains links and information similar to Amazon's footer.
- **Fully Responsive**: Designed with CSS to adjust for different screen sizes.

---

## Technologies Used
- **HTML5**: Structuring the webpage with semantic elements like ``<header>``, ``<section>``, ``<footer>``, and ``<div>`` for layout.
- **CSS3**: Used for styling with properties including:
  - ``display: flex;`` and ``display: grid;`` for layout design.
  - ``background-image`` for adding images in various sections.
  - ``border: 1.5px solid transparent;`` for hover effects.
  - ``box-shadow`` for aesthetic UI enhancements.
  - ``@media queries`` to ensure responsiveness for different screen sizes.
- **FontAwesome**: For icons such as cart, menu, and search.
---

- ## Project Structure
- The project consists of the main **HTML file (``index.html``)**, which structures the webpage, and a **CSS file (``style.css``)** that provides styling. There is also an **images folder** containing all the necessary images, such as the Amazon logo, product images, and background visuals. The project is organized to separate styling from structure, ensuring maintainability and ease of modification.

---

## 📂 Project Folder Structure
Below is the project structure:

```
Amazon-Clone-Project/
│── index.html          # Main HTML file
│── style.css           # CSS styles
│── images/             # Contains all images used in the project
│   ├── logo.png
│   ├── banner.jpg
│   ├── product1.jpg
│   ├── product2.jpg
│   ├── ...
│── README.md           # Project documentation
```

---

## 🛠️ Installation Instructions
Follow these steps to run the project locally:

### 1️⃣ Clone the Repository
Open your terminal or command prompt and run:

```sh
git clone <repository-url>
```

### 2️⃣ Navigate to the Project Directory
Move into the cloned project folder:

```sh
cd Amazon-Clone-Project
```

### 3️⃣ Open the HTML File
Simply open `index.html` in your browser by double-clicking the file or using:

```sh
start index.html   # Windows
open index.html    # macOS
xdg-open index.html # Linux
```
Alternatively, you can open it using **VS Code Live Server**:
1. Install the **Live Server** extension in VS Code.
2. Open the project folder in VS Code.
3. Right-click on `index.html` and select **"Open with Live Server"**.

---


## 🏗️ HTML Structure Overview
The **HTML file** follows a structured layout:
- **Header Section**: Contains the Amazon logo, search bar, and navigation icons.
- **Main Section**: Features a hero image, followed by product category sections.
- **Footer Section**: Contains quick links, copyright, and other information.

---


## 🎨 CSS Styling Overview
The **CSS file** includes:
- **Global Styles**: `margin`, `padding`, `font-family`, `box-sizing` applied to all elements.
- **Navigation Bar**:
  - `display: flex;` for arranging elements in a row.
  - `justify-content: space-evenly;` for spacing elements evenly.
  - `hover effects` with `border` properties.
- **Hero Section**:
  - `background-image: url('...');` for adding background visuals.
  - `position: relative;` to allow overlay content.
- **Product Sections**:
  - `display: grid;` for structured layout.
  - `grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));` for a responsive grid.
- **Footer Section**:
  - `background-color: #232F3E;` to match Amazon’s theme.
  - `text-align: center;` for better alignment.

---

## 🙏 Acknowledgments
- Inspired by **Amazon's** UI for educational purposes.
- Icons provided by **FontAwesome**.
- Developed as part of a learning exercise in **HTML & CSS**.

---

## 🚀 How to Run the Project
1. Download or clone this repository.
2. Open `index.html` in any modern web browser.

---

## 👩‍💻 Author
**Avantika Shende**

---

## 📜 License
This project is for learning purposes only and is not affiliated with Amazon in any way.

🍽️ NextLevel Food

NextLevel Food is a modern web application for foodies to share and discover delicious meals from around the world. Built with Next.js, it offers a vibrant community, beautiful meal galleries, and an easy way to contribute your own recipes.

✨ Features

🍲 Browse a curated list of community-shared meals

📖 View detailed recipes with rich instructions and images

📤 Share your own meals with image upload support

👥 Join the foodies community and participate in exclusive events

🎨 Responsive, modern UI with smooth animations

🛠️ Tech Stack

Framework: Next.js (App Router)

Database: SQLite (via better-sqlite3)

Styling: CSS Modules

Image Handling: next/image

Form Handling: Next.js Server Actions

🚀 Getting Started
✅ Prerequisites

Node.js (v18+)

npm

📦 Installation

Clone the repository

git clone https://github.com/RayRugie/05-onwards-foodies-starting-project
cd foodies-starting-project/05-onwards-foodies-starting-project


Install dependencies

npm install


Initialize the database

node initdb.js


Run the development server

npm run dev


Open http://localhost:3000
 in your browser.

📂 Project Structure
nextlevel-food/
├── app/         # Next.js app directory (layouts, pages, styles)
├── components/  # Reusable UI components (meals, images, header, etc.)
├── lib/         # Database and server-side logic (meals.js, actions.js)
├── assets/      # Static images and icons
├── public/      # Publicly served files (including uploads)
├── initdb.js    # Script to initialize & seed the SQLite database

📜 Scripts

npm run dev – Start the development server

npm run build – Build for production

npm start – Run the production server

🤝 Contributing

Contributions are always welcome!

Open an issue for bug reports or feature requests

Submit a pull request for improvements or fixes

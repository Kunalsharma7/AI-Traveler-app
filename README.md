# AI Traveler App

## Project Overview
**AI Traveler App** is a travel planning application powered by AI. It leverages OpenAI's ChatGPT to generate trip itineraries, restaurant recommendations, and more. Built using Next.js, it provides a modern, responsive user interface to create tailored travel plans effortlessly.

---

## Table of Contents
1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Folder Structure](#folder-structure)
5. [Technologies Used](#technologies-used)
6. [Contributing](#contributing)
7. [License](#license)

---

## Features
- **AI-Powered Trip Planner:** Generate detailed itineraries for specific locations and days.
- **Restaurant Recommendations:** Get restaurant, bar, and club suggestions for any city.
- **Responsive Design:** Fully compatible with all screen sizes.
- **Customizable Options:** Easy selection of states, cities, and days for travel planning.

---

## Installation

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd ai-traveler-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Add your OpenAI API key in the `index.js` file at:
   ```javascript
   const API_KEY = 'ADD_YOUR_API';
   ```

---

## Usage

### Development Server
To start the app in development mode:
```bash
npm run dev
```
Access the app at [http://localhost:3000](http://localhost:3000).

### Production
1. Build the app:
   ```bash
   npm run build
   ```
2. Start the production server:
   ```bash
   npm start
   ```
Access the app at [http://localhost:3000](http://localhost:3000).

---

## Folder Structure
```
ai-traveler-app/
├── public/          # Static files
├── pages/           # Next.js pages
│   ├── index.js     # Main page with trip generator
│   ├── hello.js     # Example API route
│   └── _app.js      # App wrapper
├── styles/          # CSS files
├── helpers/         # Helper functions (e.g., markdown rendering)
├── node_modules/    # Installed dependencies
├── package.json     # Project metadata and scripts
└── README.md        # Project documentation
```

---

## Technologies Used
- **Frontend:** React.js, Next.js
- **Styling:** CSS, Bootstrap
- **Backend:** Next.js API Routes
- **AI Integration:** OpenAI GPT API

---

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

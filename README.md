CaptureCode
CaptureCode is a web-based code editor that allows users to write or paste code and export it as a PNG image. Built with React, it offers syntax highlighting, a modern design, and user-friendly code editing features.

Features
Code Snippets: Start with a random code snippet.
Syntax Highlighting: Detects code language automatically using flourite and highlight.js.
Dark Mode: Toggle between dark and light themes.
Editable Title: Customize the code snippet title.
Export to PNG: Export the code as an image (future feature).
Responsive Design: Works across devices.
Demo
A live demo of CaptureCode can be found here.

Tech Stack
Frontend: React, Tailwind CSS
State Management: Zustand
Code Highlighting: Highlight.js, Flourite
Code Editor: React Simple Code Editor
Utilities: Shadcn UI for styling components
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/capturecode.git
cd capturecode
Install dependencies:

bash
Copy code
npm install
Run the development server:

bash
Copy code
npm run dev
Visit http://localhost:3000 to view the app.

Usage
Write or paste your code in the editor.
The language is auto-detected. You can also manually set the language.
Edit the code snippet title by clicking the header's input field.
Switch between dark and light modes using the toggle (feature in development).
(Future feature) Export the code as a PNG image for sharing.
Future Features
PNG Export: A dedicated export button to convert the code into an image.
Custom Fonts: Ability to select different fonts for code display.
Custom Themes: Choose from different color themes for the editor.
Project Structure
bash
Copy code
├── src
│   ├── components
│   │   └── CodeEditor.tsx   # Main code editor component
│   ├── store
│   │   └── store.ts         # Zustand store for state management
│   ├── lib
│   │   └── utils.ts         # Utility functions
│   └── pages
│       └── index.tsx        # Main page
├── public
│   └── favicon.ico
├── styles
│   └── globals.css          # Global CSS using Tailwind
├── package.json
└── README.md
Contribution
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature/your-feature).
Open a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
React Simple Code Editor
Zustand
Highlight.js
Flourite

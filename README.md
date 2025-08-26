# Cyberpunk-Search-Engine🚀 Cyberpunk Search Engine
A futuristic cyberpunk-themed search engine with neon aesthetics and real-time web search capabilities.

✨ Features
🎨 Cyberpunk Design
Neon Aesthetic: Black background with vibrant cyan, purple, and pink neon colors
Animated Effects: Pulsing glows, background grids, and floating elements
Typography: Futuristic gradient text and terminal-style fonts
Visual Effects: Glitch animations, scanlines, and custom neon scrollbars
🔍 Search Functionality
Real-time Search: Powered by z-ai-web-dev-sdk for web search
Loading States: Animated cyberpunk-style loading indicators
Results Display: Neon-styled result cards with favicon support
Error Handling: Graceful error messages with cyberpunk styling
🛠️ Technical Stack
Frontend: Next.js 15 with TypeScript
Styling: Tailwind CSS with custom cyberpunk utilities
UI Components: shadcn/ui component library
Backend API: Custom search endpoint with z-ai-web-dev-sdk integration
Icons: Lucide React icons
🚀 Getting Started
Prerequisites
Node.js 18+
npm or yarn
z-ai-web-dev-sdk installed
Installation
Clone the repository
bash

Line Wrapping

Collapse
Copy
1
2
git clone https://github.com/vikads39/Cyberpunk-Search-Engine.git
cd Cyberpunk-Search-Engine
Install dependencies
bash

Line Wrapping

Collapse
Copy
1
npm install
Run the development server
bash

Line Wrapping

Collapse
Copy
1
npm run dev
Open your browser
Navigate to http://localhost:3000
🎯 Usage
Enter Search Query: Type your search term in the neon search bar
Execute Search: Click the search button or press Enter
View Results: Browse through the cyberpunk-styled search results
Click Links: Results open in new tabs for safe browsing
🎨 Design Elements
Color Palette
Primary: Cyan neon (#00ffff)
Secondary: Purple neon (#ff00ff)
Accent: Pink neon (#ff0066)
Background: Pure black (#000000)
Typography
Headings: Bold gradient text with neon glow
Body: Clean monospace font for terminal aesthetic
UI Text: Cyan-colored text with subtle glow effects
Animations
Pulse Effects: Neon glow pulsing on key elements
Glitch Effects: CSS-based glitch animations for headers
Scanlines: Retro CRT monitor overlay effect
Hover States: Smooth neon transitions on interactive elements
📁 Project Structure

Line Wrapping

Collapse
Copy
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
Cyberpunk-Search-Engine/
├── src/
│   ├── app/
│   │   ├── page.tsx              # Main cyberpunk search interface
│   │   ├── layout.tsx           # Root layout
│   │   ├── globals.css          # Global styles + cyberpunk utilities
│   │   └── api/
│   │       └── search/
│   │           └── route.ts      # Search API endpoint
│   ├── components/
│   │   └── ui/                  # shadcn/ui components
│   ├── hooks/                   # Custom React hooks
│   └── lib/                     # Utility functions
├── public/                      # Static assets
├── package.json                 # Dependencies and scripts
├── tailwind.config.ts          # Tailwind configuration
├── next.config.ts              # Next.js configuration
└── README.md                   # This file
🔧 Configuration
Environment Variables
Create a .env.local file in the root directory:

env

Line Wrapping

Collapse
Copy
1
# Add any required environment variables here
Customization
Colors
Modify the cyberpunk color scheme in src/app/globals.css:

css

Line Wrapping

Collapse
Copy
1
2
3
4
5
6
⌄
:root {
  --neon-cyan: #00ffff;
  --neon-purple: #ff00ff;
  --neon-pink: #ff0066;
  --bg-black: #000000;
}
Effects
Adjust animation speeds and intensities in the CSS utilities:

css

Line Wrapping

Collapse
Copy
1
2
3
4
5
6
⌄
.neon-text {
  text-shadow: 
    0 0 10px rgba(0, 255, 255, 0.8),
    0 0 20px rgba(0, 255, 255, 0.6);
    /* Add more glow layers for intensity */
}
🚀 Deployment
Vercel (Recommended)
Push your code to GitHub
Connect your repository to Vercel
Deploy automatically
Other Platforms
The application can be deployed to any platform that supports Next.js:

Netlify
Railway
Digital Ocean App Platform
AWS Amplify
🧪 Testing
bash

Line Wrapping

Collapse
Copy
1
2
3
4
5
6
7
8
# Run linting
npm run lint

# Build the application
npm run build

# Start production server
npm start
🤝 Contributing
Fork the repository
Create a feature branch (git checkout -b feature/cyberpunk-enhancement)
Commit your changes (git commit -am 'Add cyberpunk enhancement')
Push to the branch (git push origin feature/cyberpunk-enhancement)
Create a Pull Request
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🎮 Browser Support
Chrome 90+
Firefox 88+
Safari 14+
Edge 90+
🎯 Future Enhancements
 Dark/Light theme toggle
 Advanced search filters
 Search history
 Voice search integration
 Mobile app version
 Browser extension
 Custom cyberpunk themes
 Sound effects and ambient audio
🤖 Built With
Next.js - React framework
Tailwind CSS - Utility-first CSS framework
shadcn/ui - Modern UI components
Lucide React - Beautiful icons
TypeScript - Type-safe JavaScript
📧 Contact
Created by @vikads39 - feel free to reach out!

"ACCESS THE NET • 2077" 🌐⚡

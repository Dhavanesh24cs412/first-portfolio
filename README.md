# Interactive and mobile responsive designed personal portfolio


A personal developer portfolio built with **React** and **Vite** to showcase projects, skills, and contact information. Deployed with modern styling using **Tailwind CSS** and component libraries.

##  Live Demo

View the deployed portfolio: [https://first-portfolio-dhavanesh-vs-projects.vercel.app/](https://first-portfolio-dhavanesh-vs-projects.vercel.app/)

## Features

-  Fast & Responsive - Built with React 19 and Vite for optimal performance
-  Modern UI - Styled with Tailwind CSS 4 and Radix UI components
-  Client-side Routing - Seamless navigation with React Router DOM
-  Mobile Friendly - Fully responsive design for all devices
-  Component-based Architecture - Reusable and maintainable components
-  Optimized Build - Production-ready build with tree-shaking and code splitting

## Tech Stack

- Frontend Framework React 19.1.0
- Build Tool Vite 6.3.5
- Styling: Tailwind CSS 4.1.8
- Routing: React Router DOM 6.30.1
- UI Components: Radix UI, Lucide React
- Language: JavaScript (ES Module)
- Linting: ESLint 9.25.0

## Dependencies

### Core
- `react` ^19.1.0
- `react-dom` ^19.1.0
- `react-router-dom` ^6.30.1

### Styling & UI
- `tailwindcss` ^4.1.8
- `@tailwindcss/vite` ^4.1.8
- `@radix-ui/react-toast` ^1.2.14
- `lucide-react` ^0.513.0
- `clsx` ^2.1.1
- `tailwind-merge` ^3.3.0
- `class-variance-authority` ^0.7.1

### Dev Dependencies
- Vite plugins for React
- ESLint with React-specific rules
- TypeScript support

## Installation

### Prerequisites

- **Node.js** (v16 or higher)
- **npm** (v8 or higher) or **yarn**/pnpm

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dhavanesh24cs412/first-portfolio.git
   cd first-portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```
   Or if using yarn:
   ```bash
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```
   Or with yarn:
   ```bash
   yarn dev
   ```

   The application will be available at `http://localhost:5173` (or the next available port)

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot module reloading |
| `npm run build` | Build for production optimization and bundling |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint to check code quality |

## 📁 Project Structure

```
first-portfolio/
├── src/
│   ├── assets/          # Images, fonts, and static files
│   ├── components/      # Reusable React components
│   ├── hooks/           # Custom React hooks
│   ├── lib/             # Utility functions and helpers
│   ├── pages/           # Page components for routing
│   ├── App.jsx          # Main application component
│   ├── index.css        # Global styles
│   └── main.jsx         # Entry point
├── public/              # Static assets served directly
├── package.json         # Project metadata and dependencies
├── vite.config.js       # Vite configuration
├── eslint.config.js     # ESLint configuration
├── index.html           # HTML template
└── README.md            # Project documentation
```

## Build & Deployment

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `dist/` folder.

### Deploy to Vercel

This project is configured for easy deployment to [Vercel](https://vercel.com/):

1. Push your code to GitHub
2. Import the repository in Vercel dashboard
3. Vercel automatically detects Vite configuration
4. Your site will be deployed and available at a Vercel URL

For manual deployment:
```bash
npm run build
# Deploy the dist/ folder to your hosting service
```

## Code Quality

The project uses **ESLint** to maintain code quality:

```bash
npm run lint
```

This checks all files for code style violations and best practices.

## Environment Variables

Currently, this project doesn't require environment variables. If you need to add them, create a `.env.local` file in the root directory:

```env
VITE_API_URL=your_api_endpoint
```

Note: Environment variables must be prefixed with `VITE_` to be accessible in the browser.

## 🔧 Customization

### Updating Content
- Modify portfolio content in the pages and components within `src/pages/` and `src/components/`
- Update contact information in relevant components
- Replace project details with your own work

### Styling
- Tailwind CSS configuration is built into `vite.config.js`
- Modify color schemes and layout in component files
- Global styles are in `src/index.css`

### Adding New Routes
Edit the routing setup in `App.jsx` to add new pages:
```jsx
<Routes>
  <Route path="/" element={<HomePage />} />
  <Route path="/projects" element={<ProjectsPage />} />
</Routes>
```

## License

This project is private. Contact the repository owner for usage permissions.

## 👨‍💻 Author

**Dhavanesh**
- GitHub: [@Dhavanesh24cs412](https://github.com/Dhavanesh24cs412)
- Portfolio: [View Live](https://first-portfolio-dhavanesh-vs-projects.vercel.app/)

## 📞 Support & Feedback

For issues, questions, or suggestions, please open an issue on the [GitHub repository](https://github.com/Dhavanesh24cs412/first-portfolio/issues).

## 🤝 Contributing

This is a personal portfolio project. For significant changes, please contact the owner.

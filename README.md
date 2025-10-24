# by FM - Personal Landing Page

A minimalist, modern landing page with a clean design and typing animation effect.

## 🚀 Features

- **Minimalist Design**: Clean, focused design that puts your brand front and center
- **Typing Animation**: Smooth character-by-character typing effect
- **Gradient Text Effect**: Eye-catching gradient on the main title
- **Fully Responsive**: Optimized for all devices (mobile, tablet, desktop)
- **Direct LinkedIn Link**: Prominent call-to-action button to your LinkedIn profile

## 🛠️ Tech Stack

- **React** - UI library
- **Vite** - Build tool and dev server
- **Tailwind CSS v4** - Utility-first CSS framework
- **PostCSS** - CSS processing

## 📦 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open your browser and visit `http://localhost:5173`

## 🎨 Customization

### Update Your Information

Edit `src/components/Hero.jsx` to customize:

1. **Main Title**: Change "by FM" to your personal branding
2. **Animated Text**: Update the typing animation text:
   ```javascript
   const fullText = "I'm a Software Engineer based in Malaysia.";
   ```
3. **LinkedIn URL**: Replace with your LinkedIn profile:
   ```javascript
   href = 'https://www.linkedin.com/in/firdausmaarof/';
   ```

### Styling

The website uses Tailwind CSS. You can customize:

- **Colors**: Modify the gradient colors in the title or button styles
- **Animation Speed**: Adjust the typing speed by changing the interval value (currently 80ms)
- **Typography**: Update font sizes and weights
- **Background**: Customize the gradient background overlay

### Page Content

The page includes:

- Large gradient "by FM" title
- Animated typing text with cursor effect
- LinkedIn profile button with hover animation
- Subtle gradient background overlay

## 📝 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🚀 Deployment to GitHub Pages

This project is configured for easy deployment to GitHub Pages.

### Automatic Deployment (Recommended)

The project includes a GitHub Actions workflow that automatically deploys when you push to the `main` branch.

**Setup Steps:**

1. Push your code to GitHub:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/firdausmaarof/byfm-web.git
git push -u origin main
```

2. Enable GitHub Pages in your repository settings:

   - Go to Settings > Pages
   - Under "Build and deployment", set:
     - Source: **GitHub Actions**

3. The site will automatically deploy on every push to `main`
   - View your site at: `https://firdausmaarof.github.io/byfm-web`

### Manual Deployment

You can also deploy manually using the gh-pages package:

```bash
npm run deploy
```

This will build the project and push it to the `gh-pages` branch.

### Other Deployment Options

- **Vercel**: Connect your GitHub repo for automatic deployments
- **Netlify**: Drag and drop the `dist` folder or connect via Git
- **AWS S3 + CloudFront**: Upload dist folder to S3 and serve via CloudFront

## 📄 Project Structure

```
byfm/
├── .github/
│   └── workflows/
│       └── deploy.yml        # GitHub Actions deployment workflow
├── src/
│   ├── components/
│   │   └── Hero.jsx          # Main landing page component
│   ├── App.jsx               # Root component
│   ├── main.jsx              # Entry point
│   └── index.css             # Global styles with Tailwind imports
├── public/
│   └── .nojekyll             # Prevents Jekyll processing
├── index.html                # HTML template
├── vite.config.js            # Vite configuration (with base path)
├── tailwind.config.js        # Tailwind configuration
├── postcss.config.js         # PostCSS configuration
└── package.json              # Project dependencies & scripts
```

## 📄 License

This project is open source and available for personal use.

---

**Built with ❤️ using React and Tailwind CSS**

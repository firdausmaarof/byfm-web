# by FM - Portfolio Website

A modern, responsive portfolio website for showcasing software engineering skills, projects, and experience.

## 🚀 Features

- **Modern Design**: Built with React and Tailwind CSS for a sleek, professional look
- **Fully Responsive**: Optimized for all devices (mobile, tablet, desktop)
- **Smooth Animations**: Engaging user experience with smooth transitions and effects
- **Easy to Customize**: Well-structured components for easy content updates

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

### Personal Information

Update the following components with your actual information:

1. **Hero Section** (`src/components/Hero.jsx`)

   - Update social media links (LinkedIn, GitHub)
   - Modify the tagline and description

2. **About Section** (`src/components/About.jsx`)

   - Replace placeholder text with your bio
   - Add your story and background

3. **Skills Section** (`src/components/Skills.jsx`)

   - Update the skills array with your actual skills
   - Add or remove skill categories as needed

4. **Experience Section** (`src/components/Experience.jsx`)

   - Replace with your actual work experience
   - Update job titles, companies, and descriptions

5. **Projects Section** (`src/components/Projects.jsx`)

   - Add your actual projects
   - Update GitHub and demo links
   - Replace placeholder descriptions

6. **Contact Section** (`src/components/Contact.jsx`)
   - Update email address
   - Verify social media links

### Styling

The website uses Tailwind CSS. You can customize:

- Colors: Modify color classes (e.g., `bg-blue-600`, `text-gray-300`)
- Spacing: Adjust padding and margin values
- Fonts: Update font sizes and weights
- Animations: Customize transition durations and effects

## 📝 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🚀 Deployment

### Build for Production

```bash
npm run build
```

The optimized files will be in the `dist` folder.

### Deployment Options

- **Vercel**: Connect your GitHub repo and deploy automatically
- **Netlify**: Drag and drop the `dist` folder or connect via Git
- **GitHub Pages**: Use GitHub Actions to deploy from the `dist` folder
- **AWS S3 + CloudFront**: Upload dist folder to S3 and serve via CloudFront

## 📄 License

This project is open source and available for personal use.

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!

---

**Built with ❤️ using React and Tailwind CSS**

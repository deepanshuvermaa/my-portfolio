# Deepanshu Verma - Portfolio Website

A modern, responsive portfolio website built with Gatsby, React, and styled-components. This site showcases my work as a Full Stack Engineer specializing in cloud-native SaaS platforms, automation systems, and marketing tools.

## 🚀 Features

- **Modern Tech Stack**: Built with Gatsby v5, React 18, and styled-components
- **Responsive Design**: Fully responsive across all devices
- **Smooth Animations**: Powered by anime.js and ScrollReveal
- **SEO Optimized**: Complete with sitemap, robots.txt, and meta tags
- **PWA Ready**: Offline support with gatsby-plugin-offline
- **Fast Performance**: Optimized images with gatsby-plugin-image
- **Markdown Content**: Easy content management through markdown files

## 🛠️ Tech Stack

- **Framework**: Gatsby 5
- **UI Library**: React 18
- **Styling**: Styled Components
- **Animation**: anime.js, ScrollReveal, React Transition Group
- **Content**: Markdown with gatsby-transformer-remark
- **Code Highlighting**: PrismJS
- **Analytics**: Google Analytics (gtag)
- **Deployment**: Netlify-ready

## 📁 Project Structure

```
.
├── content/
│   ├── featured/          # Featured projects (Facebook Ad Library, Creative Library, etc.)
│   ├── jobs/              # Work experience (Pear Media, RS Softgen)
│   └── projects/          # Archive projects
├── src/
│   ├── components/        # React components
│   │   ├── icons/         # SVG icon components
│   │   └── sections/      # Page sections (hero, about, jobs, etc.)
│   ├── hooks/             # Custom React hooks
│   ├── images/            # Static images and logo
│   ├── pages/             # Page components
│   ├── styles/            # Global styles and theme
│   └── utils/             # Utility functions
├── static/                # Static assets
└── gatsby-config.js       # Gatsby configuration
```

## 🏃‍♂️ Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/deepanshuvermaa/portfolio.git
cd portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The site will be running at `http://localhost:8000`

## 📜 Available Scripts

- `npm start` - Start the development server
- `npm run build` - Build the production site
- `npm run serve` - Serve the production build locally
- `npm run clean` - Clear Gatsby cache and public directory
- `npm run format` - Format code with Prettier

## 🎨 Customization

### Personal Information

Edit `src/config.js` to update:
- Email address
- Social media links
- Navigation links
- Color scheme
- Animation settings

### Content Management

All content is managed through markdown files in the `content/` directory:

- **Jobs**: Add work experience in `content/jobs/`
- **Featured Projects**: Showcase main projects in `content/featured/`
- **Other Projects**: Archive projects in `content/projects/`

### Styling

- Global styles: `src/styles/GlobalStyle.js`
- Theme variables: `src/styles/variables.js`
- Color scheme: `src/styles/theme.js`
- Mixins: `src/styles/mixins.js`

## 🌐 Deployment

This site is optimized for Netlify deployment but can be deployed to any static hosting service.

### Netlify

1. Push your code to GitHub
2. Connect your repository to Netlify
3. Build command: `gatsby build`
4. Publish directory: `public`

## 📊 Portfolio Highlights

### Featured Projects

- **Facebook Ad Library**: AI-powered ad scraping and creative generation platform (Python, Selenium, GCP)
- **Creative Library**: Cloud-based media library with remote access (AWS, MERN stack)
- **Campaign Launcher**: SaaS tool for automated Facebook campaign management (MERN stack, RBAC)
- **OMNISCIENT**: AI-driven auto-commenting system for Facebook (Webhooks, AI/ML)

### Work Experience

- **Pear Media** - Full Stack Engineer (March 2025 - Present)
- **RS Softgen** - Full Stack Developer (January 2024 - March 2025)

## 🔧 Technologies Used

**Frontend:**
- React, Gatsby, Styled Components
- anime.js, ScrollReveal

**Backend & Cloud:**
- Node.js, Express, MongoDB
- AWS (S3, Lambda, CloudFront, Route53)
- Google Cloud Platform

**Tools & APIs:**
- Python, Selenium, BeautifulSoup
- Meta Business API
- AI/ML Image Generation APIs
- Git, Docker

## 📄 License

This project is licensed under the MIT License.

## 👤 Author

**Deepanshu Verma**
- Email: deepanshuverma966@gmail.com
- GitHub: [@deepanshuvermaa](https://github.com/deepanshuvermaa)
- LinkedIn: [deepanshu-verma](https://www.linkedin.com/in/deepanshu-verma-238080200/)
- Twitter: [@Deepans695](https://x.com/Deepans695)
- Instagram: [@deepanshu.says](https://www.instagram.com/deepanshu.says/)
- Substack: [@deepanshusays](https://substack.com/@deepanshusays)

## 🙏 Acknowledgments

Built with Gatsby's powerful static site generation capabilities and deployed with modern web best practices.

---

⭐ If you found this portfolio interesting, feel free to star the repository!

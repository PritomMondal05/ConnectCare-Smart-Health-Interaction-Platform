## 🎨 Design System

...existing code...

### Footer
- **Footer Gradient/Primary**: #64A9FE
- **Footer Secondary**: #2E7CDA

...existing code...# OneLine Health - AI Physician Copilot

A fully responsive MERN stack website that replicates the OneLine Health design with pixel-perfect accuracy, custom fonts, and modern web technologies.

## 🚀 Features

- **Pixel-Perfect Design**: Precise replication of the OneLine Health design
- **Fully Responsive**: Optimized for all devices and screen sizes
- **Custom Fonts**: PPMori font family integration
- **Modern Animations**: Smooth transitions and micro-interactions
- **Form Validation**: Robust form handling with Yup validation
- **Accessibility**: WCAG compliant with proper ARIA labels
- **Performance Optimized**: Fast loading with optimized assets
- **SEO Ready**: Meta tags and structured data
- **Security**: Helmet.js security headers and input validation

## 🛠️ Tech Stack

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **CORS** - Cross-origin resource sharing
- **Helmet** - Security middleware
- **Compression** - Response compression
- **Morgan** - HTTP request logger

### Frontend
- **React 18** - UI library
- **React Router** - Client-side routing
- **Framer Motion** - Animation library
- **React Hook Form** - Form handling
- **Yup** - Schema validation
- **Axios** - HTTP client

### Styling
- **Custom CSS** - No UI libraries, pure CSS
- **CSS Variables** - Consistent theming
- **CSS Grid & Flexbox** - Modern layouts
- **Responsive Design** - Mobile-first approach

## 📁 Project Structure

```
oneline-health-website/
├── client/                          # React frontend
│   ├── public/
│   │   ├── index.html              # Main HTML template
│   │   └── manifest.json           # PWA manifest
│   ├── src/
│   │   ├── components/             # React components
│   │   │   ├── Header/            # Navigation component
│   │   │   ├── Hero/              # Hero section
│   │   │   ├── FocusSection/      # Focus on patients section
│   │   │   ├── EfficiencySection/ # Statistics section
│   │   │   ├── IntegrationSection/# EHR integration section
│   │   │   ├── TestimonialsSection/# Testimonials carousel
│   │   │   ├── SecuritySection/   # Security & compliance
│   │   │   └── Footer/            # Footer component
│   │   ├── styles/
│   │   │   └── global.css         # Global styles & fonts
│   │   ├── App.js                 # Main app component
│   │   ├── App.css                # App-specific styles
│   │   └── index.js               # React entry point
│   └── package.json               # Frontend dependencies
├── Font/                          # Custom PPMori fonts
│   ├── PPMori-Regular.otf
│   ├── PPMori-SemiBold.otf
│   ├── PPMori-Extralight.otf
│   └── ... (other font weights)
├── logo/                          # Logo assets
│   ├── conncetcare logo.svg
│   ├── conncetcare logo.png
│   └── connectcare icon.svg
├── server.js                      # Express server
├── package.json                   # Backend dependencies
├── env.example                    # Environment variables template
└── README.md                      # Project documentation
```

## 🚀 Quick Start

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd oneline-health-website
   ```

2. **Install backend dependencies**
   ```bash
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd client
   npm install
   cd ..
   ```

4. **Set up environment variables**
   ```bash
   cp env.example .env
   # Edit .env with your configuration
   ```

5. **Start the development server**
   ```bash
   npm run dev
   ```

The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000

## 📝 Available Scripts

### Root Directory
- `npm start` - Start production server
- `npm run server` - Start development server with nodemon
- `npm run dev` - Start both frontend and backend in development
- `npm run build` - Build React app for production
- `npm run install-client` - Install frontend dependencies

### Client Directory
- `npm start` - Start React development server
- `npm run build` - Build for production
- `npm test` - Run tests
- `npm run eject` - Eject from Create React App

## 🎨 Design System

### Colors
- **Primary Blue**: #1e3a8a
- **Secondary Blue**: #dbeafe
- **Accent Blue**: #60a5fa
- **White**: #ffffff
- **Gray Scale**: 50-900 variants

### Typography
- **Font Family**: PPMori (Custom)
- **Weights**: 200 (Extralight), 400 (Regular), 600 (SemiBold)
- **Responsive**: Fluid typography scaling

### Spacing
- **Base Unit**: 0.25rem (4px)
- **Scale**: 1, 2, 3, 4, 5, 6, 8, 10, 12, 16, 20, 24, 32

### Breakpoints
- **Mobile**: < 480px
- **Tablet**: 480px - 768px
- **Desktop**: 768px - 1024px
- **Large Desktop**: > 1024px

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
NODE_ENV=development
PORT=5000
REACT_APP_API_URL=http://localhost:5000/api
```

### Customization

1. **Colors**: Update CSS variables in `client/src/styles/global.css`
2. **Fonts**: Replace font files in `Font/` directory
3. **Logo**: Update logo assets in `logo/` directory
4. **Content**: Modify component content in respective files

## 🚀 Deployment

### Heroku Deployment

1. **Create Heroku app**
   ```bash
   heroku create your-app-name
   ```

2. **Set environment variables**
   ```bash
   heroku config:set NODE_ENV=production
   ```

3. **Deploy**
   ```bash
   git push heroku main
   ```

### Vercel Deployment

1. **Install Vercel CLI**
   ```bash
   npm i -g vercel
   ```

2. **Deploy**
   ```bash
   vercel
   ```

### Docker Deployment

1. **Build image**
   ```bash
   docker build -t oneline-health .
   ```

2. **Run container**
   ```bash
   docker run -p 5000:5000 oneline-health
   ```

## 📱 Performance Optimization

- **Image Optimization**: WebP format with fallbacks
- **Font Loading**: Preload critical fonts
- **Code Splitting**: React.lazy for component loading
- **Bundle Optimization**: Tree shaking and minification
- **Caching**: Static asset caching headers

## 🔒 Security Features

- **Helmet.js**: Security headers
- **CORS**: Cross-origin protection
- **Input Validation**: Yup schema validation
- **XSS Protection**: Content Security Policy
- **HTTPS**: SSL/TLS enforcement in production

## ♿ Accessibility

- **ARIA Labels**: Proper screen reader support
- **Keyboard Navigation**: Full keyboard accessibility
- **Color Contrast**: WCAG AA compliant
- **Focus Management**: Visible focus indicators
- **Semantic HTML**: Proper HTML structure

## 🧪 Testing

### Frontend Testing
```bash
cd client
npm test
```

### Backend Testing
```bash
npm test
```

## 📊 Analytics

The application is ready for analytics integration:
- Google Analytics
- Google Tag Manager
- Hotjar
- Mixpanel

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

For support and questions:
- Create an issue in the repository
- Contact the development team
- Check the documentation

## 🔄 Updates

### Version 1.0.0
- Initial release
- Complete MERN stack implementation
- Pixel-perfect design replication
- Responsive design
- Performance optimization

---


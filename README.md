# AnyTools - All-in-One Developer Tools Platform

[![Next.js](https://img.shields.io/badge/Next.js-15.5.5-black)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2.0-61dafb)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-blue)](https://www.typescriptlang.org/)
[![Ant Design](https://img.shields.io/badge/Ant_Design-5.27.5-0170FE)](https://ant.design/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.1.14-38B2AC)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

🌐 **Live Demo**: [https://www.anytools.work](https://www.anytools.work)

> 🚧 **Project Status**: This project is currently being optimized and will be open-sourced soon. We are actively working on improving performance, code quality, and documentation.

AnyTools is a modern, multilingual toolbox application that provides developers and IT professionals with a comprehensive collection of online tools and utilities.

## ✨ Features

- 🚀 **Modern Tech Stack**: Built with Next.js 15.5.5 + React 19.2.0 + TypeScript 5.9.3
- 🌍 **Multilingual Support**: Default support for English and Chinese, additional languages available upon request
- 📱 **Responsive Design**: Perfect adaptation for desktop and mobile devices
- ⚡ **Static Export**: Fast loading with CDN cache optimization
- 🔍 **SEO Optimized**: Complete SEO support with structured data and multilingual sitemaps
- 🎨 **Beautiful UI**: Built with Ant Design 5.27+ and Tailwind CSS 4.1+
- 🔧 **Rich Tools**: 167+ practical tools across 17 major categories
- 💾 **State Management**: Lightweight state management with Zustand
- 🎭 **Smooth Animations**: Integrated Framer Motion for fluid user experience
- 🔐 **Completely Free**: No registration required, all tools are completely free
- 📚 **High Quality Content**: Strict content standards with professional technical information

## 🛠️ Tool Categories

### 🔧 **Developer Tools**
- CSS Minifier, Directory Tree Generator
- Docker Compose Converter, Random Email Generator
- Random User Agent, SQLite Browser
- JSON to Go Converter

### 🔐 **Security Tools**
- AES/DES/3DES Encryption, Bcrypt Hash
- BIP39 Generator, HMAC Generator
- Password Strength Analyzer, RSA Key Generator
- Token Generator, UUID/ULID Generator
- XSS Generator, ZIP Password Cracker

### 🌐 **Web Development**
- Basic Auth Generator, HTML Entities
- HTML WYSIWYG Editor, HTTP Status Codes
- JSON Diff/Viewer/Minify, JWT Parser
- Keycode Info, Meta Tag Generator
- MIME Types, OTP Code Generator
- Regex Tester, URL Encoder/Parser
- User Agent Parser, YAML Viewer

### 📊 **Graphics & Visual**
- ASCII Text Drawer, Camera Recorder
- Color Converter/Picker, Drawing Board
- Line/Radar/Nightingale Charts
- QR Code Generator/Decoder
- SVG Placeholder Generator
- WiFi QR Code Generator

### 🖼️ **Image Tools**
- Image Compressor/Converter
- Image OCR, Pixelate Tool
- Image Radius, Splitter
- Image to Base64, Uncolor Tool
- Image Watermark

### 🎵 **Media Tools**
- Audio/Video Converter
- Video Screenshot, Video to Audio
- Video to GIF Converter

### 🌐 **Network Tools**
- CIDR Calculator/Aggregator
- IPv4/IPv6 Address Tools
- MAC Address Generator/Lookup
- Random IP/Port Generator
- Subnet Calculator

### 🔢 **Number & Math**
- ETA Calculator, Integer Base Converter
- Math Evaluator, Percentage Calculator
- Roman Numeral Converter

### ⏰ **Time & Measurement**
- Benchmark Builder, Chronometer
- Countdown Timer, Date/Time Converter
- Life Grid Calculator

### 📝 **Text Tools**
- Case Converter, CamelCase Converter
- HTML/CSS/JavaScript Formatter
- JSON/XML/YAML Formatter
- List Converter, Leet Converter
- NATO Alphabet Converter
- Text Shuffler, Statistics
- Text to Binary/Unicode

### 🔄 **Format Converters**
- Base64 File/String Converter
- JSON to CSV/JS/TOML/XML/YAML
- TOML to JSON/YAML
- XML to JSON, YAML to JSON/TOML

### 📏 **Unit Converters**
- Area, Bytes, Coordinate, Density
- Length, Pressure, Temperature
- Volume, Weight Converters

### 🇨🇳 **China Tools**
- Lunar Calendar Converter
- RMB Case Converter

### ✅ **Data Validation**
- IBAN Validator and Parser
- Phone Parser and Formatter

### 🔧 **System & DevOps**
- Chmod Calculator, Cron Parser
- Docker Run to Compose Converter
- File Format Detector, Hex Editor
- JSON to CSV, PYC to ASM/PY

### 🎯 **Hot Tools**
- Popular and trending tools collection

### 🛠️ **Utilities**
- Device Information, Emoji Picker
- Meal Decider

## 🚀 Quick Start

### Prerequisites

- Node.js 18.0 or later
- npm or yarn package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/anytools-work/AnyTools.work.git

# Navigate to the project directory
cd AnyTools.work

# Install dependencies
npm install

# Start development server
npm run dev
```

### Available Scripts

```bash
# Development
npm run dev              # Start development server
npm run dev:1            # Start development server (alternative)

# Building
npm run build            # Build for production
npm run build:static     # Build with enhanced redirects
npm run start            # Start production server

# Code Quality
npm run lint             # Run ESLint
npm run type-check       # Run TypeScript type checking

# SEO & Analytics
npm run generate-sitemap           # Generate sitemap
npm run generate-redirects         # Generate redirects
npm run generate-enhanced-redirects # Generate enhanced redirects
npm run generate-static-pages     # Generate static pages

# Optimization
npm run optimize:size    # Optimize build size
npm run clean           # Clean build artifacts
npm run delete-png      # Delete PNG images
npm run analyze:images  # Analyze images
npm run analyze:bundle  # Analyze bundle size

# Deployment
npm run deploy          # Deploy to production
npm run check           # Pre-deployment check
npm run preview         # Preview static build

# Analytics
npm run deploy:analytics    # Deploy analytics
npm run test:analytics      # Test analytics
npm run generate-indexnow-key    # Generate IndexNow key
npm run submit-indexnow         # Submit to IndexNow
npm run post-deploy-indexnow    # Post-deployment IndexNow
```

## 🏗️ Project Structure

```
AnyTools.work/
├── src/
│   ├── app/
│   │   ├── [locale]/           # Internationalized routes
│   │   │   ├── developer/       # Developer tools
│   │   │   ├── security/        # Security tools
│   │   │   ├── web-development/ # Web development tools
│   │   │   ├── graphics-visual/ # Graphics & visual tools
│   │   │   ├── image-tools/     # Image processing tools
│   │   │   ├── media-tools/     # Media conversion tools
│   │   │   ├── network/         # Network tools
│   │   │   ├── number-math/     # Number & math tools
│   │   │   ├── time-measurement/ # Time & measurement tools
│   │   │   ├── text-tools/      # Text processing tools
│   │   │   ├── format-converter/ # Format conversion tools
│   │   │   ├── converter/        # Unit converters
│   │   │   ├── china/           # China-specific tools
│   │   │   ├── data-validation/ # Data validation tools
│   │   │   ├── system-devops/   # System & DevOps tools
│   │   │   ├── utilities/       # Utility tools
│   │   │   └── hot-tools/       # Popular tools
│   │   └── globals.css
│   ├── components/              # Reusable components
│   ├── lib/                     # Utility libraries
│   ├── hooks/                   # Custom React hooks
│   ├── contexts/                # React contexts
│   ├── types/                   # TypeScript type definitions
│   └── i18n/                    # Internationalization
├── public/                      # Static assets
├── scripts/                     # Build and deployment scripts
├── workers/                     # Cloudflare Workers
└── docs/                       # Documentation
```

## 🌍 Internationalization

The project provides default support for 2 languages with complete localization:

- 🇺🇸 **English** - Primary language for international users
- 🇨🇳 **Chinese** - Simplified Chinese for Chinese users

Each tool includes comprehensive language files with professional technical descriptions in both languages.

### 🌐 Additional Languages

Additional language support is available upon request. If you need support for other languages, please contact us at **support@anytools.work** with your language requirements.

## 🔧 Technology Stack

### Frontend
- **Framework**: Next.js 15.5.5
- **UI Library**: React 19.2.0
- **Language**: TypeScript 5.9.3
- **Styling**: Tailwind CSS 4.1.14
- **Components**: Ant Design 5.27.5
- **State Management**: Zustand 5.0.8
- **Animations**: Framer Motion 12.23.24

### Backend & Deployment
- **Runtime**: Node.js 18+
- **Deployment**: Cloudflare Pages
- **Workers**: Cloudflare Workers
- **CDN**: Cloudflare CDN

### Development Tools
- **Linting**: ESLint 9.37.0
- **Type Checking**: TypeScript 5.9.3
- **Build Tool**: Next.js built-in
- **Package Manager**: npm

## 📈 Performance Features

- ⚡ **Static Site Generation (SSG)**: Pre-built pages for maximum speed
- 🚀 **Edge Caching**: Cloudflare CDN for global performance
- 📦 **Code Splitting**: Automatic code splitting for optimal loading
- 🖼️ **Image Optimization**: Automatic image optimization and WebP conversion
- 📊 **Bundle Analysis**: Built-in bundle size analysis
- 🔍 **SEO Optimization**: Complete meta tags, structured data, and sitemaps

## 🤝 Contributing

> 📢 **Note**: This project is currently in optimization phase and will be open-sourced soon. We welcome contributions and feedback! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Workflow

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-tool`
3. Make your changes
4. Run tests: `npm run lint && npm run type-check`
5. Commit your changes: `git commit -m 'Add amazing tool'`
6. Push to the branch: `git push origin feature/amazing-tool`
7. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The React framework for production
- [Ant Design](https://ant.design/) - Enterprise-class UI design language
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Cloudflare](https://cloudflare.com/) - Web performance and security
- All the amazing open-source libraries that make this project possible

## 📞 Support

- 🌐 **Website**: [https://www.anytools.work](https://www.anytools.work)
- 📧 **Email**: support@anytools.work (for additional language support and general inquiries)
- 🐛 **Issues**: [GitHub Issues](https://github.com/anytools-work/AnyTools.work/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/anytools-work/AnyTools.work/discussions)

---

Made with ❤️ by the AnyTools Team
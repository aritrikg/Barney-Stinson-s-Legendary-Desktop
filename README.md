# 🕴️ Barney Stinson's Legendary Desktop 💼


A web-based Ubuntu desktop simulation themed around Barney Stinson from How I Met Your Mother, featuring various apps and a fully interactive desktop environment. 🎭✨

## 🛠️ Tech Stack

### ⚛️ Frontend Framework

- **Next.js** (v13.1.2) - React framework for production
- **React** (v18.2.0) - UI library
- **React DOM** (v18.2.0) - React rendering library

### 🎨 Styling

- **Tailwind CSS** (v3.2.4) - Utility-first CSS framework
- **PostCSS** (v8.4.21) - CSS processing tool
- **Autoprefixer** (v10.4.13) - CSS vendor prefixing

### 🎭 Animations & Interactions

- **Framer Motion** (v12.6.2) - Animation library for React
- **React Draggable** (v4.4.5) - Drag and drop functionality
- **React OnClickOutside** (v6.12.2) - Handle clicks outside components

### 🎯 Icons & UI Components

- **Lucide React** (v0.483.0) - Icon library
- **React Icons** (v5.5.0) - Popular icon packs

### 📄 PDF & Document Handling

- **PDF.js** (v3.11.174) - PDF rendering in the browser
- **React PDF** (v7.4.0) - React components for PDF display
- **Page Flip** (v2.0.7) - 3D page flipping effects
- **3D Flip Book** (v1.9.9) - 3D flip book component
- **React Pageflip** (v2.0.3) - Page flipping for React
- **@labsforge/flipbook** (v0.1.2) - Flipbook component

### 🔧 Utilities

- **jQuery** (v3.7.1) - JavaScript library for DOM manipulation
- **Expr Eval** (v2.0.2) - Mathematical expression evaluator (used in calculator)
- **Prop Types** (v15.8.1) - Runtime type checking for React props

### 📊 Analytics & Communication

- **React GA4** (v2.1.0) - Google Analytics 4 integration
- **@emailjs/browser** (v3.10.0) - Send emails directly from client-side

### 🚀 Development & Build

- **Node.js** (>=16.x) - JavaScript runtime
- **npm** or **yarn** - Package management

## ✨ Features

- **🖥️ Desktop Simulation**: Full Ubuntu desktop environment with windows, taskbar, and desktop icons
- **📱 Themed Apps**: Various applications themed around Barney Stinson including:
  - 💬 Quotes app with legendary Barney quotes
  - 🎲 Episode randomizer for HIMYM episodes
  - 🧮 Calculator
  - 📖 PDF viewer with flip book effects
  - 🎥 Video player
  - 💻 Terminal emulator
  - ⚙️ Settings
  - And more...
- **🎮 Interactive Elements**: Draggable windows, context menus, lock screen
- **📱 Responsive Design**: Works on different screen sizes
- **💾 Local Storage**: Persists user preferences and state
- **🔄 Booting Animation**: Realistic boot sequence on first visit

## 📦 Installation

1. **📥 Clone the repository:**

   ```bash
   git clone https://github.com/aritrikg/barney-stinson-desktop.git
   cd barney-stinson-desktop
   ```

2. **📦 Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **🔧 Set up environment variables (optional):**
   Create a `.env.local` file in the root directory for Google Analytics:

   ```
   NEXT_PUBLIC_TRACKING_ID=your-ga4-tracking-id
   ```

4. **🚀 Run the development server:**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **🌐 Open your browser:**
   Navigate to `http://localhost:3000`

## 🏗️ Build for Production

```bash
npm run build
npm run start
```

For static export:

```bash
npm run export
```

## 📁 Project Structure

```
├── components/           # ⚛️ React components
│   ├── apps/            # 📱 Individual app components
│   ├── base/            # 🏗️ Base UI components (windows, sidebar)
│   ├── context menus/   # 📋 Right-click menus
│   ├── screen/          # 🖥️ Screen components (desktop, navbar, etc.)
│   ├── util components/ # 🛠️ Utility components
│   └── ubuntu.js        # 🐧 Main Ubuntu component
├── pages/               # 📄 Next.js pages
│   ├── _app.js          # 📦 App wrapper
│   ├── _document.js     # 📋 Document structure
│   └── index.js         # 🏠 Home page
├── public/              # 📂 Static assets
│   ├── images/          # 🖼️ Images, wallpapers, logos
│   ├── pdfs/            # 📄 PDF documents
│   ├── themes/          # 🎨 Theme assets
│   └── videos/          # 🎥 Video files
├── styles/              # 💅 CSS styles
└── package.json         # 📋 Dependencies and scripts
```

## 🤝 Contributing

1. 🍴 Fork the repository
2. 🌿 Create a feature branch: `git checkout -b feature-name`
3. 💾 Commit your changes: `git commit -am 'Add some feature'`
4. ⬆️ Push to the branch: `git push origin feature-name`
5. 🔄 Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- 🐧 Inspired by the Ubuntu desktop environment
- 🕴️ Barney Stinson quotes and references from How I Met Your Mother
- 📚 Various open-source libraries and components used throughout the project

---



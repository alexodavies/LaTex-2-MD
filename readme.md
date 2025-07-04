# LaTeX to Markdown Converter 📄➡️📝

A beautiful, fast, and powerful web-based tool for converting LaTeX documents to clean Markdown format. Perfect for academic writers, researchers, and anyone working with LaTeX who needs to share content in Markdown format.

## ✨ Features

### 🎯 **Core Functionality**
- **Complete LaTeX Processing** - Handles sections, formatting, lists, math, links, and more
- **Smart Font Mapping** - Converts LaTeX font commands to appropriate Markdown formatting
- **Math Preservation** - Keeps inline and display math equations intact
- **Real-time Conversion** - Instant processing in your browser

### 🖥️ **User Experience**
- **Drag & Drop Upload** - Simply drop your .tex files onto the app
- **Live Editor** - Edit LaTeX content directly in the browser
- **Split-panel View** - See input and output side by side
- **File Download** - Save converted Markdown files instantly
- **Responsive Design** - Works perfectly on desktop and mobile

### 🔧 **Technical Features**
- **Client-side Processing** - No server required, works offline
- **File Validation** - Supports .tex files up to 10MB
- **Error Handling** - Graceful fallbacks and user feedback
- **Cross-browser Compatible** - Works in all modern browsers

## 🚀 Live Demo

[Visit the live application](https://latex-2-md.vercel.app/)

## 📖 Supported LaTeX Features

### Document Structure
- `\section{}` → `# Heading`
- `\subsection{}` → `## Subheading`
- `\subsubsection{}` → `### Sub-subheading`
- Document class and package declarations (removed)

### Text Formatting
- `\textbf{text}` → `**text**`
- `\textit{text}` → `*text*`
- `\emph{text}` → `*text*`
- `\texttt{text}` → `` `text` ``
- `\underline{text}` → `<u>text</u>`

### Font Commands
- `{\bfseries text}` → `**text**`
- `{\itshape text}` → `*text*`
- `{\ttfamily text}` → `` `text` ``
- `{\sffamily text}` → `**text**` (mapped to bold)
- `{\scshape text}` → `**text**` (small caps to bold)

### Lists
- `\begin{itemize}` → Bullet lists
- `\begin{enumerate}` → Numbered lists
- `\item` → List items

### Mathematics
- `$equation$` → Inline math (preserved)
- `$$equation$$` → Display math (preserved)
- `\begin{equation}` → Display math blocks
- `\begin{align}` → Alignment environments

### Links & References
- `\href{url}{text}` → `[text](url)`
- `\url{link}` → `<link>`
- `\ref{label}` → `[label](#label)`

### Code & Quotes
- `\begin{verbatim}` → Code blocks
- `\begin{quote}` → Blockquotes

## 🛠️ Installation & Usage

### Quick Start
1. **Visit the Web App** - No installation required!
2. **Upload or Paste** - Drop a .tex file or paste content
3. **Convert** - Click "Convert to Markdown"
4. **Download** - Save your converted .md file

### Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/latex-to-markdown-converter.git

# Navigate to the project
cd latex-to-markdown-converter

# Open in browser
open index.html
```

### Deployment
This is a static web application that can be hosted anywhere:

#### Vercel (Recommended)
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

#### Other Platforms
- **Netlify**: Drag and drop the files
- **GitHub Pages**: Push to a repository
- **Cloudflare Pages**: Connect your git repository

## 📁 Project Structure

```
latex-to-markdown-converter/
├── index.html          # Main application
├── README.md           # This file
└── vercel.json         # Deployment configuration (optional)
```

## 🔧 Technical Details

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### File Limitations
- Maximum file size: 10MB
- Supported format: .tex files
- Character encoding: UTF-8 (with Latin-1 fallback)

### Performance
- **Client-side processing** - No server delays
- **Instant conversion** - Regex-based pattern matching
- **Lightweight** - Single HTML file under 50KB

## 🤝 Contributing

We welcome contributions! Here are some ways you can help:

### 🐛 Bug Reports
Found a LaTeX pattern that doesn't convert properly? Please open an issue with:
- Sample LaTeX input
- Expected Markdown output
- Actual output received

### 💡 Feature Requests
Ideas for new features:
- Additional LaTeX command support
- Export formats (PDF, HTML)
- Batch file processing
- Custom conversion rules

### 🔧 Development
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

MIT License - feel free to use this project for personal or commercial purposes.

## 🙏 Acknowledgments

- Built with modern web standards (HTML5, CSS3, ES6+)
- Inspired by the academic writing community
- Thanks to all contributors and users!

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/yourusername/latex-to-markdown-converter/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/latex-to-markdown-converter/discussions)
- **Email**: your.email@example.com

---

Made with ❤️ for the academic and technical writing community
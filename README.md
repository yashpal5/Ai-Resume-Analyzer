# 🤖 AI Resume Analyzer

A sophisticated tool that uses artificial intelligence techniques to analyze resumes (CVs) and provide comprehensive insights, feedback, and automated evaluation for job seekers and recruiters.

## ✨ Features

- **📄 Multi-Format Support** - Parse resumes from PDF, DOCX, or text formats
- **🔍 Smart Extraction** - Automatically extract key fields (education, skills, experience)
- **📊 Intelligent Scoring** - Score and rank resumes based on customizable criteria
- **🎯 Job Matching** - Match resumes with job descriptions for better compatibility
- **💡 Actionable Feedback** - Provide detailed feedback on weaknesses and improvement suggestions
- **🌐 User-Friendly Interface** - Web UI for easy resume upload and analysis viewing
- **🔌 API Access** - REST API endpoint for programmatic integration

## 🛠️ Technical Stack

- **Frontend**: React, TypeScript, React Router
- **Build Tool**: Vite
- **Backend**: Node.js with AI processing capabilities
- **Containerization**: Docker
- **Styling**: Modern CSS framework

## 📁 Project Structure

```
Ai-Resume-Analyzer/
├── 🚀 app/                     # Backend / AI processing logic
├── 🌐 public/                  # Public / static assets (images, CSS)
├── ⚙️ constants/               # Configs, constants, enumerations
├── 📋 types/                   # Type definitions (TypeScript / interfaces)
├── 📄 package.json             # Project dependencies & scripts
├── 🔧 tsconfig.json            # TypeScript configuration
├── 📦 vite.config.ts           # Build / bundler config
├── 🛣️ react-router.config.ts   # Frontend routing setup
├── 🐳 Dockerfile               # Docker configuration
├── 🙈 .gitignore
└── 📖 README.md                # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- Node.js (≥ 14.x)
- npm or yarn
- (Optional) Docker

### Local Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yashpal5/Ai-Resume-Analyzer.git
   cd Ai-Resume-Analyzer
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run in development mode**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Access the application**
   Open your browser to `http://localhost:3000` (or the configured port) to access the UI.

### Production Build

```bash
# Build the application
npm run build
# or
yarn build

# Preview production build
npm run preview
```

### Docker Deployment

```bash
# Build Docker image
docker build -t ai-resume-analyzer .

# Run container
docker run -p 3000:3000 ai-resume-analyzer
```

## 🧪 Usage

### Web Interface
1. Navigate to the application URL
2. Upload your resume file (PDF, DOCX, or TXT)
3. View parsed fields and analysis results
4. Receive scoring and improvement suggestions

### API Usage
```bash
POST /analyze
Content-Type: multipart/form-data

# Response
{
  "score": 85,
  "skills": ["Python", "Machine Learning", "React"],
  "experience": "5 years",
  "education": "Bachelor's in Computer Science",
  "suggestions": ["Add more quantifiable achievements", "Include relevant certifications"],
  "compatibility": 78
}
```

## 📊 Sample Output

The analyzer provides:
- **Overall Resume Score** (0-100)
- **Extracted Information** (skills, education, experience)
- **ATS Compatibility** Check
- **Improvement Suggestions**
- **Job Match Percentage** (if job description provided)

## 🔮 Future Improvements

- [ ] **Enhanced Format Support** - Add support for image-based PDF resumes using OCR
- [ ] **Advanced ML Models** - Improve scoring algorithm with machine learning
- [ ] **Job Description Integration** - Real-time job description matching
- [ ] **User Authentication** - Secure dashboards for recruiters and job seekers
- [ ] **Analytics Dashboard** - Detailed insights and trend analysis
- [ ] **Multi-language Support** - Analyze resumes in different languages
- [ ] **Bulk Processing** - Handle multiple resumes simultaneously

## 🤝 Contributing

We welcome contributions! Please feel free to submit pull requests, report bugs, or suggest new features.

### Development Process
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🐛 Bug Reports

If you encounter any issues, please [create an issue](https://github.com/yashpal5/Ai-Resume-Analyzer/issues) with:
- Detailed description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)

## ❤️ Made With Love by Team ARYA

**Team Members**

1. Yashpal
2. Ayush Pratap Singh
3. Rudra Pratap Singh Rathore

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

<div align="center">

**⭐ Star this repo if you find it helpful!**

> *"Smart, automated resume feedback – bridging job seekers and recruiters."* 🌉

</div>

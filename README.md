# about-me
Contain my CV built using JSON Resume

Requirement
| Node Version | NPM Version | HackMyResume Version | wkhtmltopdf Version |
|--------------|-------------|----------------------|----------------------|
| 14.15.4      | 6.14.10     | 1.7.0                | 0.12.6               |

## Installation
Install hackmyresume globally
```bash
npm install hackmyresume -g
```

Install dependencies
```bash
npm install
```

## Available Scripts
Create new sets of resume files from resume.json to resume folder
```bash
npm run build-all
```

Create only .html, file will be inside public folder
```bash
npm run build-html
```

- **analyze** inspects your resume for keywords, duration, and other metrics.
```bash
npm run analyze
```

- **validate** validates the specified resume against either the FRESH or JSON
Resume schema. Use it to make sure your resume data is sufficient and complete.
```bash
npm run validate
```

- **peek** echoes your resume or any field, property, or object path on your
resume to standard output.
```bash
npm run peek
```

- **convert** converts your resume to different formats (e.g., HTML, PDF, DOCX,
etc.). Use it to generate resumes in different formats. Requires [wkhtmltopdf](https://wkhtmltopdf.org/downloads.html) installed
```bash
npm run convert:pdf
```
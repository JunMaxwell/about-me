# about-me
Contain my CV built using JSON Resume 

## Available Scripts
Create new sets of resume files from resume.json to resume folder
```bash
npm run build-all
```

Create only .html, file will be inside public folder
```bash
npm run build-html
```

Create only .pdf
```bash
npm run build-pdf
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
# PCF Documentation

Process Classification Framework (PCF) documentation using MkDocs with Material theme.

## Setup

1. Clone the repository:
```bash
git clone https://github.com/mikhailcheng/pcf-pages.git
cd pcf-pages
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run development server:
```bash
mkdocs serve
```

5. View documentation at http://127.0.0.1:8000

## Project Structure

```
pcf-pages/
├── docs/
│   ├── assets/
│   │   └── stylesheets/
│   │       └── extra.css
│   ├── vision_and_strategy/
│   │   ├── index.md
│   │   └── 1.1.1_evaluate_external_environment.md
│   └── index.md
├── mkdocs.yml
└── requirements.txt
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

### Documentation Standards

1. **File Naming**
   - Use lowercase with underscores
   - Include PCF ID in process files
   - Example: `1.1.1_evaluate_external_environment.md`

2. **Content Structure**
   - Use process card for overview
   - Include process definition
   - Document inputs/outputs
   - List key activities
   - Provide metrics
   - Add implementation guidance

3. **Formatting**
   - Follow Material theme guidelines
   - Use provided CSS classes
   - Maintain consistent spacing
   - Include navigation links

## Building for Production

Build static site:
```bash
mkdocs build
```

Deploy to GitHub Pages:
```bash
mkdocs gh-deploy
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

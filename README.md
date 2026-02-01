# 📚 Academic Syllabus Collection

A comprehensive collection of course syllabi organized by subject area, formatted in LaTeX for easy compilation and distribution.

## 📋 Table of Contents

- [Overview](#overview)
- [Subjects Covered](#subjects-covered)
- [Repository Structure](#repository-structure)
- [Usage](#usage)
- [Compilation](#compilation)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

This repository contains detailed, unit-wise syllabi for various academic courses, including mathematics, computer science, game theory, and humanities. All syllabi are maintained in LaTeX format for professional typesetting and easy updates.

## 📖 Subjects Covered

### 1. **Ordinary Differential Equations (ODE)**
- Existence and Uniqueness Theorems
- First Order and Higher Degree Equations
- Linear Differential Equations with Variable Coefficients
- Boundary Value Problems

### 2. **Special Functions**
- Lambert W Function & Error Functions
- Bessel's Functions
- Hypergeometric Functions
- Hermite, Laguerre, and Chebyshev Polynomials

### 3. **Game Theory & Applications (GTA)**
- Nash Equilibrium
- Strategic Form Games
- Extensive Form Games
- Auction Theory & Mechanism Design

### 4. **History of Civilization**
- Bhāratīya Civilization and Knowledge Systems
- Arts, Literature, and Scholars
- Ancient Science, Astronomy, and Mathematics
- Engineering and Architecture
- Life Sciences and Health

### 5. **Hardware & Software Lab**
- Machine Learning with TinyML
- Data Visualization with R and PowerBI
- Distributed Databases (Apache Spark)
- DevOps for AI

## 📁 Repository Structure
```
.
├── main.tex                 # Master document
├── syllabi/
│   ├── ode.tex             # Ordinary Differential Equations
│   ├── special_functions.tex
│   ├── game_theory.tex
│   ├── history_civilization.tex
│   └── hardware_software.tex
├── compiled/
│   └── all_syllabi.pdf     # Compiled PDF output
└── README.md
```

## 🚀 Usage

### Prerequisites

- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- PDF viewer

### Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/academic-syllabus.git
cd academic-syllabus
```

2. Compile the LaTeX document:
```bash
pdflatex main.tex
```

3. View the generated PDF:
```bash
open all_syllabi.pdf  # macOS
xdg-open all_syllabi.pdf  # Linux
start all_syllabi.pdf  # Windows
```

## 🔧 Compilation

### Using pdfLaTeX
```bash
pdflatex main.tex
pdflatex main.tex  # Run twice for proper cross-references
```

### Using XeLaTeX (for advanced fonts)
```bash
xelatex main.tex
xelatex main.tex
```

### Using latexmk (automated)
```bash
latexmk -pdf main.tex
```

## 📝 Customization

Each syllabus is modular and can be compiled independently. To modify:

1. Navigate to the specific `.tex` file in `syllabi/`
2. Edit the content
3. Recompile to see changes

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-syllabus`)
3. Commit your changes (`git commit -am 'Add new syllabus'`)
4. Push to the branch (`git push origin feature/new-syllabus`)
5. Open a Pull Request

### Contribution Guidelines

- Maintain consistent formatting
- Use proper LaTeX syntax
- Test compilation before submitting
- Update README if adding new subjects

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

For questions or suggestions, please open an issue or contact:

- **Email**: your.email@example.com
- **University**: [Your University Name]
- **Department**: [Your Department]

## 🙏 Acknowledgments

- Course instructors and academic departments
- LaTeX community for templates and resources
- Contributors who help maintain this repository

---

**Note:** These syllabi are subject to change based on university curriculum updates. Always verify with official course materials.

**Last Updated:** February 2026

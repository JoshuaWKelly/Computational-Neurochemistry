# Computational Neurochemistry

An open-access textbook bridging molecular neuroscience, biochemistry, and computational modeling.

## View the Book

**[Read online →](https://joshuawkelly.github.io/Computational-Neurochemistry/)**

## 📖 About

This text is designed for both self-learners and instructor-led courses. It integrates simulation code, reproducible figures, and open-access formats.

## Building Locally

```bash
# Install dependencies
pip install -r requirements.txt

# Build the book
jupyter-book build .

# View locally
open _build/html/index.html
```

## License

MIT License - see [LICENSE](LICENSE) for details.


## Project Structure

```
Computational-Neurochemistry/
├── .github/
│   └── workflows/
│       ├── deploy.yml
│       └── static.yml
├── _build/
│   └── logs/
│       └── myst.build.json
├── chapter01/
│   └── introduction.md
├── chapter02/
│   └── neurochemical-basics.md
├── chapter03/
│   └── computational-tools.md
├── chapter04/
│   ├── ligand-binding.md
│   ├── markov-models.md
│   └── cooperativity.md
├── chapter05/
│   └── gpcr-signaling.md
├── chapter06/
│   └── ionotropic-receptors.md
├── frontmatter/
│   ├── preface.md
│   ├── acknowledgements.md
│   ├── accessibility.md
│   ├── for-students.md
│   ├── for-instructors.md
│   └── for-self-Learners.md
├── _config.yml
├── _toc.yml
├── index.md
├── references.bib
├── references.md
├── requirements.txt
├── LICENSE
└── README.md
```

## Author

Joshua W. Kelly  
Verus Institute | Arizona State University  
jkelly@verusinstitute.org
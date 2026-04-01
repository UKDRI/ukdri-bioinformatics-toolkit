# UKDRI Bioinformatics Toolkit

A comprehensive Quarto-based website for onboarding students to bioinformatics, with a focus on genomics and dementia research.

## What's Included

This toolkit contains:

1. **Homepage (index.qmd)** - Welcome page with getting started guide
2. **Tools & Setup (tools-setup.qmd)** - Essential genomics tools with installation instructions
3. **Genomics Fundamentals (genomics-fundamentals.qmd)** - Core concepts for dementia research
4. **Tutorials & Workshops (tutorials-workshops.qmd)** - Comprehensive course catalogue
5. **Best Practices (best-practices.qmd)** - Analysis catalogue template, folder structure, documentation guide
6. **Resources (resources.qmd)** - Databases, communities, and learning resources


## File Structure

```
ukdri-bioinformatics-toolkit/
├── _quarto.yml              # Configuration file
├── custom.scss              # UKDRI color theme
├── styles.css               # Additional styling
├── index.qmd                # Homepage
├── tools-setup.qmd          # Tools & Setup page
├── genomics-fundamentals.qmd # Genomics Fundamentals page
├── tutorials-workshops.qmd   # Tutorials & Workshops page
├── best-practices.qmd        # Best Practices page
└── resources.qmd             # Resources page
```

## Customization

### Update Colors

Edit `custom.scss` to change the color scheme:

```scss
$primary: #1e3a8a;       // Deep blue
$secondary: #7c3aed;     // Purple
$accent: #ec4899;        // Pink/magenta
```

## Key Features for Students

### Analysis Catalogue Template
Located in `best-practices.qmd` - a comprehensive template for tracking all analyses with fields for:
- Analysis ID, dates, project name
- Input data, sample size
- Scripts, software versions
- Key parameters and findings
- Issues and follow-up needed

### Folder Structure Generator
Bash script in `best-practices.qmd` that creates standardized project directories:
- Organized data/scripts/results structure
- Git-ready with .gitignore
- README templates
- Preserves raw data integrity

### Tool Descriptions
Each tool in `tools-setup.qmd` includes:
- What it does (plain language)
- Use cases
- Installation instructions
- Basic usage examples

### Comprehensive Tutorial List
`tutorials-workshops.qmd` contains 40+ courses organized by:
- Genomics & NGS
- Population genetics
- Workflows (Snakemake, Nextflow)
- Programming (Python, R)
- HPC and containers
- All with direct links and descriptions

## Tips for Use

- **Browser Search**: Use Ctrl/Cmd+F to search within pages
- **Copy Code**: Hover over code blocks to see copy button
- **Mobile Friendly**: Responsive design works on phones/tablets
- **Printable**: Print-friendly styles included


Created: October 2025  
# ukdri-bioinformatics-toolkit

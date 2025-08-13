# MicrobiotaMR

Interactive web application for exploring microbiota-gene-disease associations through Mendelian Randomization analysis.

## Usage

1. **Local Development**: 
   ```bash
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser.

2. **GitHub Pages**: Access the live application at your GitHub Pages URL.
   https://andyfenghaonan-arch.github.io/MicrobiotaMR/

## Features

- Multi-dimensional search and filtering
- Real-time data visualization (scatter plots and heatmaps)
- Interactive results table with sorting and pagination
- CSV export functionality
- Statistical analysis tools

## Files

- `index.html` - Main application interface
- `script.js` - Core application logic
- `style.css` - Styling and responsive design
- `data.txt` - Microbiota-gene association dataset

## Data Structure

The application uses tab-separated data with columns:
- `gene_id` - Ensembl Gene ID
- `microbiome` - Microbial taxon identifier
- `se` - Standard error
- `pval` - P-value
- `chr` - Chromosome
- `gene_name` - Gene symbol
- `tissue` - Tissue type
- `diseases` - Associated diseases

## Browser Compatibility

Modern browsers with JavaScript support required.

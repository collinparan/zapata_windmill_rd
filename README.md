# Zapata Windmill R&D - Property Parcel Visualization

Interactive map visualization for parcels at 500 & 502 Windmill Rd, Mosca, CO 81146

## Overview

This project provides an interactive web-based mapping application for visualizing two property parcels in Alamosa County, Colorado. The parcels are part of the Zapata Unit 3 subdivision and are located near the Great Sand Dunes National Park.

## Properties

### 500 Windmill Rd (Lot 1)
- **Parcel ID**: 499931103011
- **Size**: 3.61 acres
- **Owner**: PARAN, PHILIP COLLIN & MATTHEWS, KARLEANNE
- **Zoning**: Residential / Single Family
- **Coordinates**: 37.654584, -105.582085

### 502 Windmill Rd (Lot 2)
- **Parcel ID**: 499931103002
- **Size**: 5.16 acres
- **Owner**: PARAN, PHILIP COLLIN & MATTHEWS, KARLEANNE
- **Zoning**: Residential / Single Family
- **Coordinates**: 37.656013, -105.581486

## Features

### Interactive Map
- **Multiple Basemaps**: Toggle between satellite imagery, topographic, and street views
- **Color-Coded Parcels**: Blue for 500 Windmill Rd, Green for 502 Windmill Rd
- **Detailed Popups**: Click parcels to view comprehensive property information
- **Centroid Markers**: Visual markers showing the center point of each parcel

### Property Information
Each parcel popup includes:
- Owner information
- Legal description
- Sales & value history
- Zoning & land use details
- Geographic coordinates
- Elevation data
- School district information

### Export Capabilities
Download parcel boundaries in multiple formats:
- **GeoJSON**: For use in GIS applications
- **KML**: For Google Earth and other mapping software
- **KMZ**: Compressed KML format

### Integration
- Direct link to Google Earth 3D view
- Compatible with modern web browsers
- Mobile-responsive design

## Technology Stack

- **Leaflet.js**: Open-source JavaScript library for interactive maps
- **Esri Leaflet**: Plugin for ArcGIS basemaps
- **JSZip**: Library for creating KMZ files
- **HTML5/CSS3**: Modern web standards
- **JavaScript**: Client-side functionality

## Local Development

1. Clone the repository:
   ```bash
   git clone git@github.com:collinparan/zapata_windmill_rd.git
   cd zapata_windmill_rd
   ```

2. Open `index.html` in your web browser

No build process or dependencies required - the application runs entirely in the browser using CDN-hosted libraries.

## Deployment

### GitHub Pages
This project can be easily deployed to GitHub Pages:

1. Go to repository Settings
2. Navigate to Pages section
3. Select "Deploy from a branch"
4. Choose "main" branch and "/" (root) folder
5. Access at: `https://[username].github.io/zapata_windmill_rd/`

### Self-Hosting
Simply upload the `index.html` file to any web server. All dependencies are loaded from CDNs.

## Data Sources

- **Parcel Data**: Alamosa County Assessor
- **Basemaps**: Esri/ArcGIS
- **Coordinates**: Manually measured and verified against county records
- **Legal Information**: County records dated April 23, 2021

## Important Notes

- Parcel boundaries are approximate and based on available coordinates
- Always verify boundaries with Alamosa County Assessor before making decisions
- Consult a licensed surveyor for official boundary determination
- This is a visualization tool only - not for legal purposes

## Federal Opportunity Zone

Both parcels are located within Federal Opportunity Zone tract 08003960000, which may provide tax advantages for qualifying investments.

## Contact

For questions about the properties:
- **Owner**: Philip Collin Paran & Karleanne Matthews
- **Mailing Address**: 9207 E Star Hill Ln, Lone Tree, CO 80124

## License

This visualization tool is provided as-is for informational purposes. Property data remains subject to county records and official sources.
# Smart Crop Advisor 🌾🛰️
**NASA Space Apps Challenge Project**

Smart Crop Advisor is an interactive web application designed to support agricultural decision-making by integrating real-world satellite imagery, climate observations, and modeled soil data.

## Features
- **Interactive Map with NASA GIBS:** Features Leaflet integrated with NASA GIBS MODIS Terra TrueColor satellite imagery tiles for precise global farm location selection.
- **Climate Analysis:** Retrieves and analyzes multi-year historical climate indicators (temperature, rainfall, humidity, and dry days) using **NASA POWER** and **Open-Meteo ERA5**.
- **Soil Moisture Estimates:** Displays volumetric soil water content across multiple soil depths based on ERA5 / NASA SMAP scientific standards.
- **Crop Comparison & Rotation:** Screen crop climatic suitability and generate science-backed crop rotation scenarios.
- **Data Import & Export:** Supports custom CSV data imports (soil moisture & FAO GAEZ suitability) and robust CSV/PDF export options.
- **Client-Side & Serverless:** 100% free, runs entirely in the browser with no secret API keys required.

## Data Sources
1. **NASA POWER:** Daily temperature, precipitation, and relative humidity.
2. **Open-Meteo Historical Weather & ERA5 API:** Historical climate and soil moisture estimates.
3. **NASA GIBS:** MODIS Terra CorrectedReflectance TrueColor map tile layers.
4. **FAO GAEZ:** Agro-ecological zoning and crop suitability framework support.

## How to Deploy on GitHub Pages
1. Push `index.html` and `README.md` to the main branch of your GitHub repository.
2. Go to your repository **Settings** -> **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch** and choose `main` / `/(root)`.
4. Save and access your live application URL!

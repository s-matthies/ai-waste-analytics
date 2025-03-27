# BSR AI Project for Waste Collection Optimization

## Project Description
This project analyzes and optimizes the waste collection processes of Berlin's municipal waste management company (BSR) using AI methods. Based on BSR datasets from the past four years, predictions for the upcoming year were developed. To improve prediction accuracy, various publicly available datasets were incorporated into the analysis, including weather data, school holidays, public holidays, and election surveys. The detailed results and analyses are summarized in the project documentation.

## Project Structure
- `Daten/`: Contains raw data and processed datasets
- `notebooks_training/`: Jupyter notebooks for AI model training
- `Notebooks_vorverarbeitung/`: Jupyter notebooks for data preprocessing
- `Dokumentation.pdf`: Comprehensive project documentation
- `Leitfragen_Bericht_PPT.pdf`: Presentation materials and guiding questions
- `Notizen.md`: Additional project notes and data descriptions

## Data Structure
The project works with the following main datasets:

### Base Data
- **Month, CW, Year, Date**: Temporal recording of deliveries
- **Yard**: Assignment to different BSR yards (VMF, VMG, VMN, VMM, VMWSF, VMWSM, VMWSN)
- **Shift**: Working time recording
- **Tour**: Tour numbers with rotating routes (2-week cycle)
- **Tonnage**: Waste amount in tons
- **Waste Type**: Categorization (BIO, HM, SPM)

### Additional Datasets
- Weather data
- Inflation data
- Collection failure statistics
- Public holiday data
- Election data
- Tourism data

## Installation and Usage
1. Clone repository:
```bash
git clone https://gitlab.rz.htw-berlin.de/s0587519/bsr_ki.git
cd bsr_ki
```

2. Open notebooks in your preferred Jupyter environment
3. Process data according to documentation

## Project Context
This project was conducted as a four-day student project by a team of four in collaboration with Berlin's municipal waste management company (BSR). It aims to improve waste collection efficiency through data-driven decisions.

## Authors and Contributors
- Team of 4 HTW Berlin students

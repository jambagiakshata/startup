
# Startup Funding Analysis GUI

A desktop application built with **Tkinter**, **Pandas**, **Seaborn**, and **Matplotlib** to perform interactive data cleaning, analysis, and visualization for startup funding datasets.

---

##  Table of Contents
- [Overview](#overview)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Dependencies](#dependencies)  
- [Contributions](#contributions)  


---

## Overview  
This GUI tool simplifies the process of analyzing startup funding data. Users can upload a CSV dataset, view cleaning steps, clean the data, perform descriptive analysis, visualize insights, and receive funding recommendations—all through an intuitive interface.

---

## Features
- **Data Upload**: Load startup funding CSV data effortlessly.
- **Cleaning Diagnostics**: Inspect columns, null counts, data-types, and quality of "Amount in USD" and "Date".
- **Automated Cleaning**:
  - Normalize column names.
  - Handle missing values and non-numeric entries in amounts.
  - Parse and clean date fields.
  - Fill other important text fields intelligently.
- **Interactive Analysis & Visualizations**:
  - Display funding trends by year.
  - Show top sectors, cities, startups, investors, and investment types.
  - Render visual charts (line, bar, count).
- **Text-based Summary**: View key insights and recommendations for focus areas.

---

## Installation

1. **Clone** the repository:  
   ```bash
   git clone <your-repo-url>
   cd <your-repo-directory>
````

2. **Install dependencies** (it’s best practice to use a virtual environment):

   ```bash
   pip install pandas seaborn matplotlib
   ```

---

## Usage

Run the application:

```bash
python startup_analysis_gui.py
```

Once the GUI launches, follow the buttons to:

* Upload your dataset
* View cleaning diagnostics
* Clean the data
* Analyze insights
* Visualize charts
* See recommendations

---

## Project Structure

```
.
├── startup_analysis_gui.py      # Main GUI application script
├── requirements.txt             # List of required Python packages
└── README.md                    # Project documentation (this file)
```

---

## Dependencies

* **Python 3.x**
* **Pandas** – for data manipulation
* **Seaborn & Matplotlib** – for data visualization
* **Tkinter** – for building the GUI interface

---

## Contributions

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'Add my feature'`)
4. Push to your branch (`git push origin feature/my-feature`)
5. Open a Pull Request to discuss your changes



[1]: https://realpython.com/readme-python-project/?utm_source=chatgpt.com "Creating Great README Files for Your Python Projects"
[2]: https://www.digitaldesignjournal.com/example-readme-file-for-python-project/?utm_source=chatgpt.com "Example Readme File For Python Project - Digital Design Journal"

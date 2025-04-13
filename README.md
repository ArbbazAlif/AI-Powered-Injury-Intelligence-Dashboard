# AI-Powered Injury Intelligence Dashboard

*Uses NLP and interactive dashboards to analyze OSHA severe hand injury reports in the manufacturing industry.* This project leverages natural language processing and data visualization to transform raw incident reports into actionable safety insights for manufacturing companies.

## Technologies Used

- **Python** – Base programming language for data processing and analysis.  
- **Streamlit** – Open-source web framework for building the interactive dashboard UI.  
- **spaCy** – Industrial-strength NLP library for extracting information from injury report text.  
- **scikit-learn** – Machine learning library used for modeling and clustering injury data patterns.  
- **Pandas** – Data manipulation library for cleaning data and aggregating statistics.  
- **Plotly** – Interactive graphing library for visualizations like charts and heatmaps.

## Features

- **NLP-Powered Data Extraction:** Automatically extracts key details from OSHA injury descriptions using spaCy (e.g. injury causes, affected body parts, locations).  
- **Interactive Dashboard Filters:** Provides intuitive filters (by date, company, injury type, etc.) to drill down into specific subsets of incidents.  
- **Heatmaps & Visual Analytics:** Visualizes injury occurrences with heatmaps and charts (e.g. time-of-incident heatmaps or geographic maps) to identify trends and hotspots.  
- **Company Profiling:** Generates profiles for each company in the dataset, highlighting total incidents, common injury types, and other notable patterns.

## Use Case

This dashboard is designed for EHS (Environmental Health & Safety) teams and safety managers in manufacturing. By analyzing OSHA severe hand injury reports, the tool helps identify patterns and root causes of workplace accidents. Safety teams can discover which processes or machinery lead to frequent injuries, or detect spikes in incidents during certain time periods. These insights enable data-driven decisions to implement targeted prevention strategies and improve workplace safety.

## Project Structure

- **data/** – Contains the OSHA severe injury dataset and any intermediate or processed data files.  
- **notebooks/** – Jupyter notebooks for data exploration, NLP model development, and analysis.  
- **dashboard/** – Streamlit app source code for the dashboard (Python scripts, data loading, and UI components).  
- **requirements.txt** – List of Python dependencies needed to run the project.

## Getting Started

To run the **AI-Powered Injury Intelligence Dashboard** locally, follow these steps:

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/ArbbazAlif/AI-Powered-Injury-Intelligence-Dashboard.git
   ```
2. **Install dependencies:**  
   Navigate into the project directory and install required packages:  
   ```bash
   pip install -r requirements.txt
   ```
3. **Launch the Streamlit app:**  
   Run the dashboard using Streamlit:  
   ```bash
   streamlit run dashboard/app.py
   ```  
   This will start the web app and open the interactive dashboard in your browser.  
   
*Prerequisites:* Ensure you have **Python 3.x** and **pip** installed. It’s recommended to use a virtual environment for a clean setup.

## Achievements

- 🥉 **3rd Place** (out of 35 teams) in the **DataWhiz Case Study + Hackathon** hosted by Envision UTD (Safety Excellence Group). This project was recognized for its innovative approach to workplace safety analytics.

## Contact

For any questions or collaboration inquiries, please reach out to **Arbbaz Alif Abdul Shafeeq** on [LinkedIn](https://www.linkedin.com/in/arbbaz-alif-profile/).

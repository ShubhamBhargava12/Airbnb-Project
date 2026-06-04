# 🏠 Airbnb Analysis & Interactive Dashboard

An end-to-end data analysis and visualization project that explores Airbnb listing data. This project aims to uncover key insights regarding property pricing, availability, seasonal trends, and host performance to help optimize rental strategies and understand market dynamics.

---

## 📊 Features & Key Insights
*   **Price Analysis:** Distribution of listing prices across different neighborhoods and property types.
*   **Geographical Mapping:** Geospatial visualization of Airbnb listings to identify high-density and premium areas.
*   **Availability & Demand:** Tracking seasonal booking patterns, occupancy rates, and minimum night requirements.
*   **Review & Ratings:** Insights into customer satisfaction based on review scores and host response rates.

---

## 📁 Repository Structure
*   **`Listings.csv.gz`**: The compressed raw dataset containing detailed information about Airbnb listings, hosts, locations, and pricing.
*   **`Airbnb Dashboard.pbix`** *(or your specific tool file, e.g., .twbx, .ipynb)*: The interactive dashboard file containing data models, calculated metrics, and visual reports.

---

## 🛠️ Getting Started

### Prerequisites
Depending on how you want to view the project, you will need:
*   **Power BI Desktop** / **Tableau Desktop** (if using a BI tool dashboard)
*   **Python 3.x** with `pandas`, `matplotlib`, and `seaborn` (if using a Jupyter Notebook setup)

### Setup Instructions
1.  **Clone the Repository:**
```bash
    git clone [https://github.com/ShubhamBhargava12/Airbnb-Project.git](https://github.com/ShubhamBhargava12/Airbnb-Project.git)
    cd Airbnb-Project
    ```
2.  **Extract the Data:** 
    The dataset `Listings.csv.gz` is compressed. Most modern BI tools and Python can read `.gz` files directly. If needed, extract it using any unzip utility.
3.  **Open the Dashboard:** 
    Launch your visualization tool and open the dashboard file, then point the data source connection to your local `Listings.csv` file.

---

## 🚀 Technologies Used
*   **Data Analysis:** Python (Pandas) / Power Query
*   **Data Visualization:** Power BI / Tableau / Matplotlib
*   **Data Source:** Airbnb Open Data (CSV format)

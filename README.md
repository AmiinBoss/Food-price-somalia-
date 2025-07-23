# Somalia Food Price Analysis (1995–2023)

This project analyzes nearly three decades of food price data from markets across Somalia to uncover trends, volatility, and regional disparities affecting food security. The work combines data cleaning, visualization, and statistical analysis to inform humanitarian and policy decision-making.

---

## 📊 Project Overview

Somalia faces chronic food insecurity driven by conflict, drought, and dependence on food imports. Understanding price dynamics is vital for early warning and intervention. Using a dataset of over 25,000 monthly price records for staple foods from 1995–2023, this analysis:

* Cleans and processes the raw data
* Visualizes price distributions and time trends
* Compares urban (Mogadishu) vs. rural market behavior
* Highlights volatility and crisis periods (famine, drought, global shocks)
* Extracts actionable insights for food security planning

---

## 🗂️ Dataset

* **Source:** [World Food Programme (WFP) Price Database (via Kaggle/HDX)](https://data.humdata.org/dataset/somalia-food-prices)
* **Observations:** 25,040 (reduced to \~23,400 after cleaning)
* **Variables:**

  * Date (monthly)
  * Region, District, Market name
  * Commodity & Unit (e.g., sorghum, rice, oil, kg/liter)
  * Price (local currency)
  * Urban/Rural classification
* **Coverage:** All regions of Somalia, 1995–2023, nominal prices (SOS/SLS)

---

## ⚙️ Data Cleaning

* Checked and confirmed **no missing values or duplicates**
* Removed extreme outliers using the IQR rule (\~6.6% of records)
* Converted date and price fields to appropriate data types
* Added “Urban”/“Rural” classification for region-based analysis

---

## 🔍 Exploratory Data Analysis & Visualizations

* **Price Distribution:** Rural markets experience greater price volatility and higher spikes than Mogadishu (urban).
* **Time Trends:** Strong upward trend in nominal food prices, especially post-2006.
* **Volatility:** 12-month rolling standard deviation reveals increasing instability in prices, peaking during known crisis years (2008, 2011, 2017, 2022).
* **Staple Foods:** Rural prices for key staples like *sorghum* can soar during droughts and famine, signaling acute risk.
* **Seasonal Effects:** Median prices spike during Ramadan, aligning with lean seasons and increased demand.

*Note: See project notebook for detailed plots and analysis.*

---

## 📈 Key Findings

* **Rural markets** are more vulnerable to price spikes and volatility than urban centers.
* **Price shocks** correspond to droughts, conflict, and global inflation (e.g., 2008, 2011, 2017, 2022).
* **Long-term trend**: Food is becoming less affordable over time, increasing hunger risk.
* **Monitoring staple food prices** (e.g., sorghum) can serve as an early warning for famine.

---

## 📝 Conclusion

Somalia’s food markets are characterized by rising and unstable prices, especially in rural regions. These trends highlight the need for stronger market integration, improved crisis response, and ongoing price monitoring to protect vulnerable populations.

---

## 🚀 Getting Started

1. **Clone this repository**
   `git clone https://github.com/yourusername/somalia-food-price-analysis.git`

2. **Open the notebook**
   All analysis is in `Food price somalia.ipynb`.

3. **Requirements**

   * Python 3.x
   * pandas, numpy, matplotlib, seaborn

4. **Run the notebook**
   Follow the step-by-step workflow for reproducible results and visualizations.

---

## 🤝 Contact

For questions, suggestions, or collaboration, feel free to open an issue or reach out via \[your email or LinkedIn].

---

## 📚 References

* [WFP Price Database (HDX)](https://data.humdata.org/dataset/somalia-food-prices)
* Concern Worldwide, WFP, FEWS NET reports on Somalia


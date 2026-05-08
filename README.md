# District-Wise-Public-Distribution-System-PDS-Analysis
## 📖 Project Overview
The Public Distribution System (PDS) ensures food security to millions of household.This is a district-wise PDS dataset, covering the years 2017–2021, which provide monthly information on allocation and distribution of food grains - rice and wheat. By comparing the allocation and distribution of rice and wheat the analysis helps to evaluate the efficiency of PDS, spot the best and worst performance states and districts and highlight the trend over time. The findings aims to highlight the leakage spots and provide insights for governance and infrastructure challenges that influence food grains delievery.


## 🎯 Project Objectives
- Assess average efficiency of rice and wheat distribution across districts.
- Identify best and worst states in terms of food grain distribution efficiency.
- Detect leakage hotspots by analyzing districts with lowest efficiency in rice and wheat.
- Analyze efficiency trends over the period 2017–2021 to understand changes and external impacts.
- Examine correlation between rice and wheat efficiencies to uncover systemic governance and logistics patterns.

  
## 📂 Dataset
- Records: 500
- Attributes: 9 features

  
## 🛠️ Tools Used
- Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn


## 🧹 Data Cleaning and Preprocessing
- Steps performed:
    - Correct data type for ensure smooth analysis
    - Ensure there is no missing values
    - Ensure there is no duplicates
      

   ## 📊 Exploratory Data Analysis (EDA)
For visualization, the following techniques were used:
- Bar chart
- Line chart
- Scatter plot


## 🔍 Key Findings
- Average efficiency
    - On average, 85.5% of rice allocated reached households.
    - On average, 83.5% of wheat allocated reached households.
      
- Best and worst states
     - Rice efficiency was used as the benchmark since rice distribution appears more efficient than wheat.
     - Highest efficiency states: Andhra Pradesh, Assam, West Bengal, Himachal Pradesh, Meghalaya.
     - Lowest efficiency states: Lakshadweep, Andaman & Nicobar Islands, Uttarakhand, Maharashtra, Jammu & Kashmir.
       
- District leakage
    - Some lowest rice efficiency districts: Sikar, Sonipat, Dausa, Patiala, Nuh.
    - Some lowest wheat efficiency districts: Zunheboto, Adilabad, Bengaluru, Bijapur, Chittoor.

- Efficiency trends over time
     - Efficiency improved began from 2017, ensured a stable growth from 2018 to 2020 but dipped slighty in 2021.
     - External shocks including Covid 19 or transportation restrictions might be athe reasons for sudden decline in 2021.
     - Rice generally lead wheat, though wheat narrowed the gap over time.

- Correlation between rice and wheat efficiency
   - Correlation coefficient: 0.818, indicating a strong positive relationship.
   - Indicating districts that are efficient in rice distribution tend to be efficient in wheat distribution.
   - Similarly, districts with poor rice efficiency tend to show poor efficiency in wheat distribution.
   - Highlighting the influence of governance, logistics, infrastructure on efficiency in distribution.


## ✅ Recommendations
- Strengthen monitoring in low performed states
   - In low‑performing PDS states, adopt digital tracking machine like e-POS at ration shops, conducting independent audit, setting up grievance helplines and publishing monthly efficiency dashboards and make officers accountable for any leakages, delays or mistakes.

- District-level interventions
    - Adopt localized solutions including better storage, transport and accountability mechanisms helps to reduce leakage.

- Improve logistics and infrastructure
    - The strong correlation (0.818) between rice and wheat efficiency suggests that systemic issues (transportation, warehousing, supply chain management) affect both grains. Investments in logistics infrastructure will improve efficiency across the board.

- Policy resilience during shocks
    - The poor performance of PDS during 2021 due to external shocks indicating the need to strengthen buffer stocks and to promote decentralized distribution centers.

- Encourage best practices from high-performing states
  - Share the practices and logistical strategies of high performed states across other states may help to replicate the success.


## 👤 Author  
**Aspiring Economic Policy Analyst**  

- LinkedIn: https://www.linkedin.com/in/dhanyamaryboban
- Email: dhanyamb0898@gmail.com  
- GitHub: https://github.com/DhanyaMaryBoban
   

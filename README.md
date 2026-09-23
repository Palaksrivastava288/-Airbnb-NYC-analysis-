# -Airbnb-NYC-analysis-

### 📌 Description
Exploratory data analysis of **102,599 Airbnb listings** across New York City. The project uncovers patterns in pricing, room types, neighbourhood distribution, host behaviour, review trends, and booking policies using 10 distinct chart types.

### 🔗 Dataset
- **Name:** Airbnb NYC Open Data
- **Source:** [Kaggle — Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- **File:** F:\OneDrive\Desktop\interships\Airbnb_Open_Data_cleaned.csv/‪F:\OneDrive\Desktop\interships\Airbnb_Open_Data.csv
- **Size:** 102,599 rows × 26 columns

### 🔑 Key Features
| Column | Description |
|--------|-------------|
| `neighbourhood group` | Borough (Manhattan, Brooklyn, Queens, Bronx, Staten Island) |
| `room type` | Entire home/apt, Private room, Shared room, Hotel room |
| `price` | Nightly price in USD |
| `service fee` | Platform fee (20% of price) |
| `minimum nights` | Minimum stay requirement |
| `number of reviews` | Total reviews received |
| `availability 365` | Days available per year |
| `Construction year` | Year property was built (2003–2022) |
| `instant_bookable` | Whether booking is instant (True/False) |
| `cancellation_policy` | Strict / Moderate / Flexible |

### 📊 Charts (10 Total)
| # | Chart Type | Variables |
|---|-----------|-----------|
| 1 | Bar Chart | Listings by Borough |
| 2 | Box Plot | Price by Room Type |
| 3 | Heatmap | Correlation Matrix |
| 4 | Histogram + KDE | Construction Year Distribution |
| 5 | Time Series Line | Monthly Review Volume Trend |
| 6 | Dual Line Chart | Pricing by Construction Year |
| 7 | Scatter + Trendline | Price vs Minimum Nights |
| 8 | Horizontal Bar | Top 10 Neighbourhoods |
| 9 | Stacked Bar | Cancellation Policy by Room Type |
| 10 | Pie Chart | Instant Bookable Share |

### 🔍 Key Findings
- **Manhattan (42.7%) + Brooklyn (40.8%) = 83.5%** of all NYC listings
- **Service fee is exactly 20%** of nightly price across all listings
- **Estimated annual revenue potential: $8.26 Billion**
- **Top neighbourhood:** Bedford-Stuyvesant — 7,898 listings
- **Passport holders** convert at 35.4% vs 12.6% without
- **Cancellation policies** split exactly 33% each (strict/moderate/flexible)
- **50/50 split** between instantly bookable vs host-approval listings

## ⚙️ Setup & Run Instructions

### 1. Clone or Download the Repository
```bash
# Download all files to your local machine
# Place all files in the same folder
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Notebooks on Google Colab

**Option A — Upload directly:**
1. Go to [colab.research.google.com](https://colab.research.google.com)
2. Click **File → Upload notebook**
3. Select either `.ipynb` file
4. Upload the corresponding `.csv` dataset via the 📁 folder icon (left panel)
5. Click **Runtime → Run all** (`Ctrl + F9`)

**Option B — Run locally (Jupyter):**
```bash
pip install jupyter
jupyter notebook
```
Then open the `.ipynb` file from the Jupyter interface.

### 4. Dataset Files Required
| Notebook | Dataset File |
|----------|-------------|
| `PalakSrivastava_AirbnbNYC Open Data.ipynb` | `Airbnb_Open_Data_cleaned.csv` 
---

## 📋 Requirements
```
pandas>=1.5.0
numpy>=1.23.0
matplotlib>=3.6.0
seaborn>=0.12.0
plotly>=5.11.0
streamlit>=1.20.0
```

Install with:
```bash
pip install -r requirements.txt
```
## 📄 Project Reports
| Report | Description |
|--------|-------------|
| `PalakSrivastava_AirbnbNYC_ProjectReport.docx` | Full Airbnb project report — 9 sections, 9 tables |
---

## 👩‍💻 Author
**Palak Srivastava**  
Data Analysis Internship Project  
Platform: Google Colab | Language: Python 3.10


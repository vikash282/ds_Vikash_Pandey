# ds_Vikash_Pandey

# Data Science Assignment - Web3 Trading Team

## 📁 Project Structure
```
ds_<candidate_name>/
├── notebook_1.ipynb          # Main analysis notebook (Google Colab)
├── notebook_2.ipynb          # Additional analysis (optional)
├── csv_files/                 # Data storage
│   ├── historical_trader_data.csv
│   ├── fear_greed_index.csv
│   └── processed_data.csv
├── outputs/                   # Visualizations and charts
│   ├── trading_sentiment_analysis.png
│   ├── correlation_heatmap.png
│   ├── profitability_analysis.png
│   └── trading_signals_chart.png
├── ds_report.pdf             # Final summarized insights
└── README.md                 # This file
```

## 🎯 Assignment Objective
Analyze the relationship between trader behavior and market sentiment using:
- Bitcoin Market Sentiment Dataset (Fear/Greed classification)
- Historical Trader Data from Hyperliquid

## 📊 Datasets

### 1. Historical Trader Data from Hyperliquid
**Source**: [Google Drive Link](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)

**Columns**:
- `account`: Trader identifier
- `symbol`: Trading pair (e.g., BTC-USD)
- `execution_price`: Price at which trade was executed
- `size`: Trade size/volume
- `side`: Buy/Sell direction
- `time`: Timestamp of the trade
- `start_position`: Starting position size
- `event`: Trade event type
- `closedPnL`: Profit/Loss from closed positions
- `leverage`: Leverage used in the trade

### 2. Bitcoin Market Sentiment Dataset
**Source**: [Google Drive Link](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)

**Columns**:
- `Date`: Date of sentiment reading
- `Classification`: Market sentiment (Fear/Greed)

## 🚀 Setup Instructions

### Prerequisites
- Google account for Colab access
- Basic knowledge of Python, Pandas, and data analysis

### Step-by-Step Setup

1. **Download Datasets**
   ```bash
   # Download both CSV files from the provided Google Drive links
   # Save them in the csv_files/ directory
   ```

2. **Open Google Colab**
   - Go to [Google Colab](https://colab.research.google.com/)
   - Upload the notebook files or create new ones
   - Set sharing to "Anyone with the link can view"

3. **Install Required Libraries**
   ```python
   !pip install pandas numpy matplotlib seaborn plotly
   ```

4. **Upload Data Files**
   ```python
   # Upload the CSV files to Colab using the file upload widget
   # Or mount Google Drive and access files directly
   from google.colab import files
   uploaded = files.upload()
   ```

5. **Run the Analysis**
   - Execute all cells in notebook_1.ipynb
   - Follow the step-by-step analysis
   - Save outputs to the outputs/ folder

## 📈 Analysis Components

### 1. Data Preprocessing
- Clean and validate datasets
- Handle missing values and outliers
- Create derived features for analysis

### 2. Exploratory Data Analysis (EDA)
- Trading volume patterns
- Profitability distributions
- Sentiment distribution over time
- Trader behavior characteristics

### 3. Correlation Analysis
- Merge datasets by date
- Calculate daily aggregated metrics
- Identify correlations between sentiment and trading behavior

### 4. Statistical Testing
- Compare trading metrics between Fear and Greed periods
- Hypothesis testing for significant differences
- Effect size calculations

### 5. Visualization
- Box plots for metric comparisons
- Time series analysis
- Correlation heatmaps
- Trading signal identification charts

### 6. Trading Signal Generation
- Identify contrarian indicators
- Volume-based signals
- Leverage pattern analysis
- Profitability divergence signals

## 🔍 Key Research Questions

1. **Do traders behave differently during Fear vs Greed periods?**
   - Trading volume variations
   - Leverage usage patterns
   - Risk-taking behavior

2. **Are there contrarian opportunities?**
   - Profitability during Fear periods
   - Volume divergences
   - Leverage spikes as indicators

3. **What hidden patterns can inform trading strategies?**
   - Early sentiment shift indicators
   - Behavioral anomalies
   - Predictive signals

## 📊 Expected Outputs

### Visualizations
- **trading_sentiment_analysis.png**: Comprehensive comparison charts
- **correlation_heatmap.png**: Feature correlation analysis
- **profitability_analysis.png**: PnL distribution by sentiment
- **trading_signals_chart.png**: Identified trading opportunities

### Key Metrics
- Daily trading volume by sentiment
- Average leverage usage patterns
- Profitability rates (Fear vs Greed)
- Active trader counts
- Risk-adjusted returns

### Trading Insights
- Contrarian trading signals
- Volume-based indicators
- Behavioral pattern recognition
- Strategic recommendations

## 🎯 Success Criteria

### Technical Excellence
- Clean, well-documented code
- Comprehensive statistical analysis
- Professional visualizations
- Actionable insights

### Business Impact
- Clear trading strategy recommendations
- Risk assessment and management
- Quantifiable opportunities
- Implementation roadmap

## 📝 Submission Checklist

- [ ] Google Colab notebook with public access
- [ ] All required folder structure created
- [ ] CSV files processed and stored
- [ ] Visualizations generated and saved
- [ ] Final PDF report completed
- [ ] GitHub repository updated
- [ ] README.md documentation complete

## 🔗 Useful Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Gallery](https://matplotlib.org/stable/gallery/)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
- [Google Colab Guide](https://colab.research.google.com/notebooks/intro.ipynb)

## 📧 Contact

For questions or clarification, refer back to the original assignment instructions or reach out through the appropriate channels.

---

**Note**: This analysis is for educational and demonstration purposes. Always conduct thorough backtesting and risk assessment before implementing any trading strategies in live markets.

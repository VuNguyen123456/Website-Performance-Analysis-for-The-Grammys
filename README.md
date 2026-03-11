# Website Performance Analysis for The Grammys

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/01/The_Recording_Academy_logo.svg/2560px-The_Recording_Academy_logo.svg.png" alt="The Recording Academy Logo" width="200"/>
</div>

## 📊 Overview

This project presents a comprehensive analysis of web analytics data from both Grammy.com and RecordingAcademy.com. In 2022, The Recording Academy's VP of Digital Strategy, Ray Starck, decided to split the websites into two separate domains to better serve different audience needs. This analysis evaluates the impact of that strategic decision by examining user engagement metrics, traffic patterns, demographics, and competitive performance.

## 🎯 Objectives

- **Evaluate Website Split Impact**: Analyze how splitting Grammy.com and RecordingAcademy.com affected user engagement
- **Traffic Pattern Analysis**: Understand how Grammy Awards events drive web traffic
- **Engagement Metrics**: Compare bounce rates, pages per session, and average session duration before and after the split
- **Demographics Analysis**: Examine age demographics across both websites
- **Competitive Benchmarking**: Compare Grammy.com performance against The American Music Awards (AMA)

## 📁 Project Structure

```
Grammys-Website-Analytics/
├── README.md
├── requirements.txt
├── Analyzing-Website-Performance-Grammys.ipynb
├── datasets/
│   ├── desktop_users.csv
│   ├── grammy_live_web_analytics.csv
│   ├── grammys_age_demographics.csv
│   ├── mobile_users.csv
│   ├── ra_live_web_analytics.csv
│   └── tra_age_demographics.csv
└── figs/
    └── TheAMAs.png
```

## 🔧 Setup & Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Installation Steps

1. **Clone the repository** (or download the project files)
   ```bash
   git clone <your-repo-url>
   cd Grammys-Website-Analytics
   ```

2. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open the analysis notebook**
   - Navigate to `Analyzing-Website-Performance-Grammys.ipynb`
   - Run all cells to execute the analysis

## 📈 Key Findings

### Traffic Patterns
- Grammy Awards ceremony nights generate **4,190% more traffic** than regular days
- Significant traffic spikes occur during awards season (January-April)
- Smaller spikes occur during nomination announcements (November-December)

### Engagement Metrics Post-Split
- **Recording Academy website** shows superior engagement:
  - Lower bounce rate (~33% vs ~40% for Grammy.com)
  - Higher average session duration (~128 seconds vs ~83 seconds)
- **Pages per session** reveals distinct traffic patterns between the two sites

### Demographics
- Younger audiences (18-54) show stronger engagement with Recording Academy
- Older demographics (55+) show preference for Grammy.com

### Competitive Analysis
- Grammy.com outperforms AMA in bounce rate (40.16% vs 54.31%)
- Areas for improvement: Average session duration (83 seconds vs AMA's 5:53)

## 🛠️ Technologies Used

- **Python** - Programming language
- **Pandas** - Data manipulation and analysis
- **Plotly Express** - Interactive data visualization
- **Jupyter Notebooks** - Interactive development environment

## 📊 Data Dictionary

### Web Analytics Data
- **date** - Date in `yyyy-mm-dd` format
- **visitors** - Number of users who visited the website
- **pageviews** - Total pages viewed by all users
- **sessions** - Total number of user sessions
- **bounced_sessions** - Sessions where users left without interaction
- **avg_session_duration_secs** - Average session length in seconds
- **awards_week** - Binary flag for Grammy Awards marketing campaign periods
- **awards_night** - Binary flag for actual Grammy Awards ceremony nights

### Demographics Data
- **age_group** - Age range (e.g., 18-24, 25-34, etc.)
- **pct_visitors** - Percentage of total visitors from that age group

## 📝 Analysis Sections

1. **Part 1: Data Exploration**
   - Environment setup and data loading
   - Traffic pattern visualization
   - Awards night impact analysis
   - Pre- and post-split data segmentation

2. **Part 2: Key Metrics Analysis**
   - Pages per session calculation and visualization
   - Bounce rate analysis across sites
   - Average time on site comparison

3. **Part 3: Demographics Analysis**
   - Age demographics loading and combination
   - Comparative visualization across websites

4. **Part 4: Business Recommendations**
   - AI-assisted memo generation
   - Final business recommendations

5. **Competitive Analysis**
   - Device distribution analysis
   - Performance comparison with AMA

## 🚀 Usage

1. Ensure all data files are in the `datasets/` folder
2. Run the notebook cells sequentially
3. Interactive Plotly visualizations will render inline
4. Review findings and recommendations in Part 4

## 📄 License

This project is for educational and portfolio purposes. Data is provided for analysis demonstration.

## 👤 Author

[Your Name]

## 🙏 Acknowledgments

- The Recording Academy for providing web analytics data
- Ray Starck, VP of Digital Strategy, for the strategic context
- Plotly for excellent visualization tools

---

**Note**: This analysis was conducted to evaluate the impact of splitting Grammy.com and RecordingAcademy.com into separate domains in February 2022.

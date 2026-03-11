# Website Performance Analysis for The Grammys

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/01/The_Recording_Academy_logo.svg/2560px-The_Recording_Academy_logo.svg.png" alt="The Recording Academy Logo" width="200"/>
</div>

## 📊 Overview

This project presents a comprehensive analysis of web analytics data from both Grammy.com and RecordingAcademy.com. In 2022, The Recording Academy's VP of Digital Strategy, Ray Starck, decided to split the websites into two separate domains to better serve different audience needs. This analysis evaluates the impact of that strategic decision by examining user engagement metrics, traffic patterns, demographics, and competitive performance.

The analysis covers data from 2017 through 2023, providing insights into how the website split affected user behavior, engagement levels, and overall site performance. Key metrics analyzed include visitor traffic, bounce rates, pages per session, average session duration, age demographics, and device distribution.

## 🎯 Objectives

- **Evaluate Website Split Impact**: Analyze how splitting Grammy.com and RecordingAcademy.com affected user engagement metrics
- **Traffic Pattern Analysis**: Understand how Grammy Awards events drive web traffic and identify seasonal patterns
- **Engagement Metrics Comparison**: Compare bounce rates, pages per session, and average session duration before and after the split
- **Demographics Analysis**: Examine age demographics across both websites to understand audience composition
- **Competitive Benchmarking**: Compare Grammy.com performance against The American Music Awards (AMA) website

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
```

## 🔧 Setup & Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)
- Jupyter Notebook (included in requirements.txt)

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
   - Run all cells sequentially to execute the complete analysis

## 📈 Detailed Findings

### 1. Traffic Pattern Analysis

#### Awards Night Impact
- **4,190.41% increase** in traffic on Grammy Awards ceremony nights compared to regular days
- On average, **1,357,202 more visitors** visit the site on Show Night than on a normal day
- This dramatic difference highlights the concentrated nature of user attention around the single annual event

#### Seasonal Traffic Patterns
- **Major Traffic Spikes**: Occur during awards season (January-April)
  - These spikes correspond with the Grammy Awards ceremony, which typically takes place in early spring
  - The ceremony represents the peak traffic event of the year
  
- **Secondary Traffic Spikes**: Occur during nomination season (November-December)
  - Smaller but significant spikes occur when The Recording Academy announces Grammy nominations
  - This represents an "anticipation period" where fans engage with the site in preparation for the awards

#### Pages Per Session Insights
- After the website split, traffic spikes in January and June are now caused by **two different events**:
  - January spikes: Grammy Awards ceremony
  - June spikes: Recording Academy events
- This separation reveals that the split successfully differentiated traffic sources and event-driven engagement

### 2. Engagement Metrics Post-Split

#### Bounce Rate Analysis

**Bounce Rate by Site:**
- **Combined Site (Pre-Split)**: ~41.58%
- **Grammy.com (Post-Split)**: ~40.16%
- **Recording Academy (Post-Split)**: ~33.67%

**Key Finding**: The Recording Academy website shows a **significant improvement** in bounce rate, with approximately **7 percentage points lower** than Grammy.com. This indicates that visitors to RecordingAcademy.com are more likely to engage with content rather than immediately leaving.

#### Average Session Duration

**Average Time on Site:**
- **Combined Site (Pre-Split)**: ~102.85 seconds
- **Grammy.com (Post-Split)**: ~82.99 seconds
- **Recording Academy (Post-Split)**: ~128.50 seconds

**Key Findings:**
- Recording Academy visitors spend **55% more time** on site than Grammy.com visitors (128.5s vs 82.99s)
- Recording Academy shows **25% improvement** over the pre-split combined site
- Grammy.com shows a **19% decrease** compared to the pre-split combined site
- This suggests that Recording Academy content is more engaging and keeps users on the site longer

#### Pages Per Session

The pages per session metric reveals distinct traffic patterns:
- **Combined Site**: Shows unified traffic spikes during major events
- **Post-Split Grammy.com**: Maintains strong spikes during awards season
- **Post-Split Recording Academy**: Shows different engagement patterns, indicating successful audience segmentation

### 3. Demographics Analysis

#### Age Group Distribution

**Key Demographic Insights:**
- **Younger Audiences (18-54)**: Show stronger engagement with Recording Academy website
  - This demographic appears more interested in ongoing content and community engagement
  
- **Older Demographics (55+)**: Show preference for Grammy.com
  - This group may be more event-focused and interested in awards ceremony content

**Strategic Implication**: The split successfully allows each site to cater to its primary demographic, with Recording Academy serving younger, more engaged users and Grammy.com focusing on event-driven older audiences.

### 4. Competitive Analysis: Grammys vs. AMA

#### Device Distribution (April-June 2023)

**Grammy.com Device Usage:**
- **Desktop Users**: 26.43%
- **Mobile Users**: 73.57%

The Grammy website shows a strong mobile-first audience, with nearly three-quarters of visitors accessing the site via mobile devices.

#### Performance Comparison

| Metric | Grammy.com | AMA | Winner |
|--------|-----------|-----|--------|
| **Bounce Rate** | 40.16% | 54.31% | ✅ Grammy.com (14% better) |
| **Average Session Duration** | 83 seconds | 5 min 53 sec (353 sec) | ❌ AMA (4.25x longer) |
| **Pages Per Visit** | Similar/Slightly Higher | 2.74 | ✅ Grammy.com (comparable) |

#### Competitive Strengths

**Grammy.com Advantages:**
- **Significantly lower bounce rate** (40.16% vs 54.31%) - 26% improvement over competitor
- Better initial engagement and content pathways
- Strong mobile engagement strategy

#### Areas for Improvement

**Critical Gap:**
- **Average session duration** is the primary area needing improvement
  - Grammy.com: 83 seconds
  - AMA: 5 minutes 53 seconds (353 seconds)
  - **Gap**: Grammy.com users spend only 23% of the time that AMA users spend on site

**Recommendation**: Optimize the desktop experience to capture a larger share of that audience, as desktop users typically have longer session durations. Currently, only 26% of traffic comes from desktop, suggesting an opportunity to improve desktop engagement.

### 5. Overall Impact Assessment

#### Website Split Success Metrics

**Recording Academy Website (Post-Split):**
- ✅ **Best bounce rate**: 33.67% (lowest of all sites)
- ✅ **Longest session duration**: 128.5 seconds
- ✅ **Strong engagement**: Visitors stay longer and interact more
- ✅ **Clear audience fit**: Appeals to younger, more engaged demographics

**Grammy.com (Post-Split):**
- ✅ **Event-driven traffic**: Maintains strong spikes during awards season
- ⚠️ **Lower engagement**: Higher bounce rate and shorter sessions than Recording Academy
- ✅ **Competitive advantage**: Outperforms AMA in bounce rate
- ⚠️ **Room for improvement**: Session duration significantly lower than competitor

#### Key Business Insight

The split has revealed a fundamental challenge: **How to transform a business that relies on the success of one event per year into one that continues to bring users back to the site year-round?**

**Current State:**
- Grammy.com excels as a **short-term event hub** during awards season
- Recording Academy functions as a **long-term engagement platform** with consistent user interest

**Strategic Recommendation:**
- **Keep sites separate** - The split has successfully differentiated audiences and engagement patterns
- **Grammy.com**: Focus on optimizing session duration and desktop experience to compete with AMA
- **Recording Academy**: Continue leveraging its superior engagement metrics and younger demographic appeal
- **Cross-promotion**: Use Grammy.com's event-driven traffic to drive users to Recording Academy for year-round engagement

## 🛠️ Technologies Used

- **Python 3.7+** - Programming language
- **Pandas** - Data manipulation and analysis
- **Plotly Express** - Interactive data visualization
- **Jupyter Notebooks** - Interactive development environment

## 📊 Data Dictionary

### Web Analytics Data (`grammy_live_web_analytics.csv`, `ra_live_web_analytics.csv`)

| Column | Description |
|--------|-------------|
| **date** | Date in `yyyy-mm-dd` format |
| **visitors** | Number of users who visited the website on that day |
| **pageviews** | Total pages viewed by all users |
| **sessions** | Total number of user sessions (a session is a group of user interactions within a time frame) |
| **bounced_sessions** | Sessions where users left without interacting with any pages or links |
| **avg_session_duration_secs** | Average session length in seconds |
| **awards_week** | Binary flag (0/1) indicating if dates align with Grammy Awards marketing campaigns |
| **awards_night** | Binary flag (0/1) indicating the actual Grammy Awards ceremony night |

### Demographics Data (`grammys_age_demographics.csv`, `tra_age_demographics.csv`)

| Column | Description |
|--------|-------------|
| **age_group** | Age range (e.g., 18-24, 25-34, 35-44, 45-54, 55-64, 65+) |
| **pct_visitors** | Percentage of total website visitors from that specific age group |

### Device Data (`desktop_users.csv`, `mobile_users.csv`)

| Column | Description |
|--------|-------------|
| **date** | Date in `yyyy-mm-dd` format |
| **visitors** | Number of visitors from desktop or mobile devices |
| **segment** | Device type identifier (removed during analysis) |

## 📝 Analysis Sections

### Part 1: Data Exploration
- **Section 1**: Environment setup and library imports
- **Section 2**: Data loading and initial exploration
- **Section 3**: Traffic pattern visualization and analysis
- **Section 4**: Awards night impact analysis (comparing ceremony days vs. regular days)
- **Section 5**: Pre- and post-split data segmentation (split date: February 1, 2022)

### Part 2: Key Metrics Analysis
- **Section 6**: Pages per session calculation and visualization
  - Calculated as: `pageviews / sessions`
  - Visualized across combined site, Grammy.com, and Recording Academy
- **Section 7**: Bounce rate analysis
  - Function creation and calculation across all sites
  - Comparison of engagement levels
- **Average Time on Site**: Analysis of session duration metrics

### Part 3: Demographics Analysis
- **Section 8**: Age demographics loading and combination
  - Loading data from both sites
  - Creating website labels
  - Combining datasets for comparative visualization
  - Bar chart visualization showing age group distribution

### Part 4: Business Recommendations
- **Section 9**: Business recommendation development
  - AI-assisted memo generation
  - Evaluation of AI assistance
  - Final polished business memo for stakeholders

### Competitive Analysis
- **Section 10**: Device distribution analysis
  - Desktop vs. mobile user segmentation
  - Performance comparison with AMA
  - Strategic recommendations based on competitive benchmarking

## 🚀 Usage

1. **Ensure all data files are in the `datasets/` folder**
   - All CSV files should be present and properly named

2. **Run the notebook cells sequentially**
   - The analysis builds upon previous sections
   - Ensure each cell completes before running the next

3. **Interactive Visualizations**
   - Plotly visualizations will render inline in Jupyter
   - Hover over data points for detailed information
   - Use Plotly's built-in zoom and pan features

4. **Review Findings**
   - Key metrics are printed throughout the analysis
   - Final recommendations are in Part 4
   - Competitive analysis conclusions are in Section 10

## 📊 Key Metrics Summary

| Metric | Combined Site | Grammy.com | Recording Academy |
|--------|--------------|------------|-------------------|
| **Bounce Rate** | 41.58% | 40.16% | 33.67% |
| **Avg Session Duration** | 102.85 sec | 82.99 sec | 128.50 sec |
| **Traffic Pattern** | Unified spikes | Event-driven | Consistent engagement |
| **Primary Audience** | Mixed | 55+ (event-focused) | 18-54 (engaged) |

## 💡 Insights & Recommendations

### Strategic Insights

1. **Website Split Success**: The split has successfully differentiated audiences and engagement patterns
2. **Recording Academy Advantage**: Shows superior engagement metrics across all key indicators
3. **Grammy.com Opportunity**: Strong event-driven traffic but needs improvement in session duration
4. **Competitive Position**: Outperforms AMA in bounce rate but lags significantly in session duration

### Actionable Recommendations

1. **For Grammy.com**:
   - Optimize desktop experience to increase session duration
   - Develop content strategies to maintain engagement beyond awards season
   - Leverage event-driven traffic spikes to drive year-round engagement

2. **For Recording Academy**:
   - Continue leveraging superior engagement metrics
   - Expand content offerings to maintain younger demographic appeal
   - Use strong engagement as a model for Grammy.com improvements

3. **Cross-Platform Strategy**:
   - Implement cross-promotion between sites
   - Use Grammy.com's event traffic to drive Recording Academy engagement
   - Develop unified content calendar leveraging both sites' strengths

## 📄 License

This project is for educational and portfolio purposes. Data is provided for analysis demonstration.

## 👤 Author

[Your Name]

## 🙏 Acknowledgments

- **The Recording Academy** for providing web analytics data
- **Ray Starck**, VP of Digital Strategy, for the strategic context and business challenge
- **Plotly** for excellent interactive visualization tools
- **Pandas** community for robust data analysis capabilities

## 📚 Additional Resources

- [Plotly Documentation](https://plotly.com/python/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/)

---

**Analysis Period**: 2017-2023  
**Website Split Date**: February 1, 2022  
**Last Updated**: [Current Date]

**Note**: This analysis was conducted to evaluate the impact of splitting Grammy.com and RecordingAcademy.com into separate domains. All findings are based on web analytics data provided for analysis purposes.

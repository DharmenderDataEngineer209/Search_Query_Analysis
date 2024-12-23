# Search Query Analysis Project

Welcome to the **Search Query Analysis Project**. This project dives deep into web search data to identify patterns, trends, and anomalies. Using Python and its powerful libraries, we’ve created visualizations, extracted insights, and flagged anomalies in the dataset.

## Why This Project?

Ever wondered which queries drive traffic? Or how certain keywords dominate impressions and clicks? This project analyzes search query data to answer these questions. Plus, it helps identify anomalies that could signal unusual trends or errors.

---

## Features

Here’s what this project does:

### 1. **Keyword Analysis**

- Breaks down search queries into individual words.
- Finds the **top 20 most common words** in user searches.
- Visualized using a **bar chart** for easy comprehension.

### 2. **Top Queries by Metrics**

- Identifies top-performing queries based on:
  - **Clicks**: Which queries get the most attention?
  - **Impressions**: Which ones are most visible?
  - **Click-Through Rate (CTR)**: Which queries convert the best?
- Displays results in clean, interactive visualizations.

### 3. **Outlier Detection**

- Uses the **Isolation Forest algorithm** from `sklearn` to detect anomalies.
  - _What’s that?_ An Isolation Forest flags unusual data points. For instance, a query with an unusually high click count but very few impressions.
- Outputs a list of queries flagged as anomalies.

### 4. **Correlation Insights**

- Analyzes the relationships between key metrics:
  - Clicks
  - Impressions
  - CTR
  - Position
- Visualized in a **correlation heatmap** to highlight strong or weak connections.

---

## Tools and Techniques

### Python Libraries

- **Pandas**: Data manipulation and cleaning.
- **Plotly**: Interactive and visually appealing charts.
- **Sklearn**: Machine learning for anomaly detection.
- **Re**: Text cleaning for extracting words from queries.

### Machine Learning Algorithm

- **Isolation Forest**:
  - This algorithm isolates anomalies rather than profiling normal data.
  - It’s efficient, scalable, and ideal for detecting unusual search trends.

---

## Getting Started

### Prerequisites

- Python 3.x installed on your machine.
- Libraries: Install using `pip install pandas plotly scikit-learn`.

### Steps to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/search-query-analysis.git
   cd search-query-analysis
   ```

# Event Classification Analysis

Event Classification Analysis is a machine learning and generative AI project that explores the classification and analysis of university events using event titles and descriptions. The project leverages the Gemini API, Python data analysis tools, and visualization libraries to process event data, generate insights, and evaluate event categorization patterns. The repository contains a Google Colab notebook implementation and a sample dataset of university events.

## Project Overview

Universities host a wide range of events, including academic seminars, student activities, networking opportunities, workshops, and social gatherings. Accurately categorizing these events can help improve event discovery, recommendation systems, and institutional reporting.

This project:

- Loads university event data from a CSV file.
- Uses event titles and descriptions as inputs.
- Integrates with the Gemini API for AI-assisted event classification.
- Processes and analyzes event information using Python.
- Visualizes findings using data science tools such as Pandas and Matplotlib.
- Explores event classification workflows that can be extended into recommendation or predictive systems.

## Repository Structure

```text
Event-Classification-Analysis/
│
├── SHUevents.csv                         # University event dataset
├── eventClassificationAnalysis_vF.ipynb # Main Google Colab notebook
└── README.md
```

## Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Google Gemini API (`google-genai`)
- CSV Data Processing

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/lyndsypontillo/Event-Classification-Analysis.git
cd Event-Classification-Analysis
```

### 2. Open in Google Colab

Upload the notebook (`eventClassificationAnalysis_vF.ipynb`) to Google Colab or open it directly from GitHub.

Google Colab provides a cloud-based Python environment, so no local installation is required.

### 3. Install Required Packages

Run the following command in a Colab cell:

```python
!pip install --upgrade google-genai pandas matplotlib
```

### 4. Configure Gemini API

Obtain a Gemini API key and add it to the notebook:

```python
from google import genai

client = genai.Client(api_key="YOUR_API_KEY")
```

## Dataset

The project uses the `SHUevents.csv` dataset, which contains university event information used for classification and analysis.

The dataset includes event-related information such as:

- Event title
- Event description
- Event category or classification
- Additional event metadata (if available)

## Usage

1. Open `eventClassificationAnalysis_vF.ipynb` in Google Colab.
2. Upload or ensure access to `SHUevents.csv`.
3. Add your Gemini API key.
4. Run each notebook cell in sequence.

The workflow includes:

- Loading event data
- Preprocessing event titles and descriptions
- Sending event information to Gemini for classification
- Analyzing classification results
- Visualizing trends and findings

## Example Workflow

```text
Load CSV Data
      ↓
Extract Event Titles & Descriptions
      ↓
Send Content to Gemini API
      ↓
Generate Classification Results
      ↓
Analyze & Visualize Findings
```

## Potential Applications

- University event recommendation systems
- Automated event tagging and categorization
- Student engagement analytics
- Campus activity trend analysis
- Event management platforms
- Educational data science research

## Future Improvements

- Train and evaluate custom machine learning classification models.
- Compare traditional machine learning approaches with LLM-based classification.
- Add automated evaluation metrics and performance reporting.
- Expand support for larger and more diverse event datasets.
- Develop an interactive dashboard for visualization.
- Implement personalized event recommendation features.

## Requirements

To run this project, you will need:

- A Google account
- Access to Google Colab
- A Gemini API key
- Internet connection

Required Python packages:

```text
google-genai
pandas
matplotlib
```

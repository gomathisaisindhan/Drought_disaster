
# Drought_disaster
“This file performs EDA on a drought dataset, analyzing alert levels, severity, duration, and location. It uses histograms, boxplots, scatterplots, pair plots, and a heatmap to identify trends, correlations, and unusual patterns in drought events.”
# Drought Dataset – EDA Project

## 📌 Project Overview
This project explores a drought dataset to understand patterns in alert scores, severity, duration, and location using visual and statistical methods.

## 📂 File Included
- droug.ipynb

## 🛠 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Missingno

## 🔍 Key Steps
- Checked dataset structure and missing values  
- Studied distributions of key features  
- Observed relationships using scatterplots and pairplots  
- Reviewed patterns in severity and duration  
- Examined variable connections through a heatmap  

## 📈 Visuals Used
- Histograms  
- Boxplots  
- Scatterplots  
- Pairplot  
- Correlation Heatmap  
- Missing value plot

## 🎯 Key Findings
- Most drought events show low severity and short duration  
- A few extreme cases create high outliers  
- Alertscore and Episodealertscore show strong connection  
- Severity over time shows irregular spikes  
- Geographic values show no strong link to severity or duration  

## 📁 Deliverables
- Jupyter Notebook (droug.ipynb)  
- Visual outputs generated inside the file  

## 📘 Outcome
Gives clear understanding of drought patterns, outliers, variable connections, and event behavior through visual exploration.
 
## Observations for Each Visual
1. Boxplots

- Most variables are skewed with many outliers.

- Severity and Duration show extreme high values.

-Alertscore mostly stays at 1 with few higher cases.

2. Histograms

- Severity and Duration are right-skewed, meaning large events are rare.

- Alertscore and Episodealertscore mostly remain at low values.

- Longitude and Latitude are widely spread, showing global coverage.

3. Pairplot

- Weak relationships between most variables.

- Alertscore and Episodealertscore show a visible positive trend.

- No strong clustering in the data.

4. Scatterplot: Severity vs Duration

- Most events have low severity and short duration.

- Few extreme cases show high severity.

- No clear linear relationship.

5. Scatterplot: Alertscore vs Episodealertscore

- Positive relationship: higher Alertscore usually matches higher Episodealertscore.

- Few deviations exist.

6. Severity Trend Over Time

- Severity fluctuates heavily with sharp peaks.

- No seasonal or repeated pattern.

- Extreme events appear randomly over time.

7. Correlation Heatmap

- Strong correlation only between Alertscore and Episodealertscore.

- Other variables show weak or no correlation.

- Geographic values have minimal relationship with severity or duration.
## Summary of Findings 

- Most drought events are mild with low alert scores.

- A few extreme events appear as strong outliers.

- Severity and duration do not show a clear pattern together.

- Alertscore and Episodealertscore move closely together.

- Location values are spread with no region showing consistent impact.

- Severity over time rises sharply at random points.

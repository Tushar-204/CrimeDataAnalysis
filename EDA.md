# 📊 Crime Dataset EDA Report

This report summarizes the exploratory data analysis (EDA) performed on the Indian Crime dataset.  
Each section explains the findings **with charts and tables** in simple English.

---

## 1. Crime Trends by City

- We counted how many crimes were reported in each city.  
- A bar chart of the **Top 15 Cities** shows which cities reported the highest number of crimes.  
- Another chart (stacked bar chart) shows the **types of crimes (domains)** across the **Top 10 Cities**.  
  - This helps us see if some cities have more violent crimes, thefts, or other types.

**Why it matters:**  
This tells us which cities face the most crime overall and what type of crimes are most common in each city.

---

## 2. Crime Type Analysis

- We checked the **most common crime descriptions**.  
  - Example: theft, assault, robbery, fraud, etc.  
  - A bar chart of the **Top 15 Crime Descriptions** shows which are most frequent.
- We also summarized the **crime domains** (categories like violent crime, property crime, cybercrime, etc.).  
  - A bar chart shows which domains are most common overall.
- Lastly, we looked at the **weapons used** in crimes.  
  - A bar chart of the **Top 15 weapons** shows which weapons are most often involved (e.g., knife, gun, blunt object).

**Why it matters:**  
This helps us understand not just where crimes happen, but **what kinds of crimes** and **what methods/weapons** are used.

---

## 3. Victim Demographics

- We analyzed the **ages of victims**.  
  - A histogram shows how victim ages are distributed (young, middle-aged, elderly).  
  - Summary stats (average, min, max, etc.) are also provided.
- We checked the **gender of victims**.  
  - A bar chart shows how many victims were **male, female, or other**.
- We combined both:  
  - For the **Top 10 Crime Descriptions**, we plotted the **gender distribution of victims**.  
  - This shows if certain crimes affect one gender more than others.

**Why it matters:**  
This helps us understand **who the victims are**, so prevention and support can be better designed.

---

## 4. Police Effectiveness

- We calculated the **average number of police officers deployed per case** overall.  
- We also looked at **police deployment by city** (average, median, and count of cases).  
- Then we checked if there’s a **relationship between number of police and case closure**.  
  - A boxplot compares **police deployed** in cases that were **closed** vs. **open**.  
  - We also calculated a correlation number.

**Why it matters:**  
This shows if deploying more police helps in solving cases, or if some cities manage with fewer resources.

---

## 5. Case Closure

- We looked at how many cases were **closed** vs. still **open**.  
  - A pie chart shows the proportion (percentage closed vs. open).
- For closed cases, we measured **how long it took to close (in days)**.  
  - A histogram shows the distribution (fast closures vs. long investigations).  
  - Summary stats show the average and spread of closure times.
- Finally, we compared **police deployed vs. time to close** with a scatterplot.  
  - This shows if more police officers make cases close faster.

**Why it matters:**  
This helps evaluate how effective the police system is in resolving cases, and if more resources really speed up investigations.

---

## ✅ Conclusion

- **High-crime cities** can be identified and compared.  
- **Most common crimes and weapons** are clearly visible.  
- **Victim demographics** highlight which groups are more affected.  
- **Police resources and effectiveness** can be evaluated.  
- **Case closure rates and investigation time** show how justice is being served.



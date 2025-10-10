#  Visible by Verizon Onboarding Redesign — Data-Driven UX Case Study

##  Overview  
This project combines **data science** and **UX research** to improve the **Visible by Verizon** mobile onboarding experience.  
Using **Python web scraping**, I collected and analyzed **10,000+ Google Play reviews** to identify user pain points and inform the redesign process.  
These insights guided **usability studies, user journeys, and a complete Figma redesign** of the onboarding flow and information architecture.

---

##  Objectives  
- Identify top friction points in onboarding and activation flows.  
- Quantify recurring themes in user feedback (e.g., billing confusion, SIM activation, app crashes).  
- Combine **qualitative interviews** and **quantitative sentiment analysis** to validate user frustrations.  
- Redesign onboarding screens to reduce cognitive load and improve transparency.  

---

##  Data Collection & Analysis  

### 🔹 Web Scraping
- **Source:** Google Play Store reviews (Visible by Verizon app)  
- **Tools:** `tidyverse`, `requests`, `pandas`  
- **Dataset:** 10,000+ reviews scraped with date, rating, and text content  
- **Data Cleaning:** Removed duplicates, normalized text, handled emoji and newline encoding  
- **Storage:** CSV for further NLP and sentiment processing  

### 🔹 Sentiment Analysis
- **Methods:** frequency analysis and n-gram extraction  
- **Outcome:** Categorized reviews into positive and negative sentiment buckets  
- **Insight:** 60% positive sentiment for **setup** , 75% negative sentiment for **login**
### 🔹 Qualitative Synthesis
- Conducted **6 user interviews** with new customers  
- Created **affinity maps** and **journey flows** to connect user quotes with data trends  
- Prioritized UX issues based on **frequency + severity + emotional impact**  

---

##  Technical Stack  

| Category | Tools Used |
|-----------|-------------|
| **Data Scraping** | Python, BeautifulSoup, Requests |
| **Data Analysis** | Pandas, tokenizers, wordcloud, dplyr |
| **Visualization** | Matplotlib, Figma, ggplot2 |
| **Design & Research** | Figma, Miro, Google Forms |
| **Documentation** | Markdown, Jupyter Notebook |


---

## ✏️ UX Redesign Process  

1. **Problem Definition:** Identify onboarding friction from data insights  
2. **User Interviews:** 6 participants (varied experience with Visible)  
3. **Journey Mapping:** Visualized drop-off points and emotional lows  
4. **Wireframing:** Created low-fidelity prototypes in Figma  
5. **Usability Testing:** Conducted 2 rounds of testing  
6. **High-Fidelity Redesign:** Applied brand-consistent design system 





📌 **Overview**

This project uses the Algerian Forest Fires dataset to model wildfire occurrence based on meteorological conditions and fire weather indices. The dataset includes 244 instances collected from June to September 2012 across two forested regions in Algeria.

🧬 ***Background***

Algeria’s arid climate and dense pine and cork oak forests make it highly susceptible to wildfires. This dataset captures daily weather observations and indices from the Canadian Fire Weather Index (FWI) system, offering a valuable foundation for predictive modeling and environmental risk analysis.

📊 ***Dataset Features***

    Regions: Bejaia and Sidi Bel-Abbes

    Attributes: Temperature, Relative Humidity, Wind Speed, Rainfall

    FWI Components: FFMC, DMC, DC, ISI, BUI, FWI

    Target: Binary classification—Fire or Not Fire

⚙️ ***Setup***

pip install pandas scikit-learn matplotlib seaborn

🚀 ***Usage***

    Load and clean the dataset

    Visualize feature distributions and correlations

    Train classification models (e.g., Decision Tree, SVM, Logistic Regression)

    Evaluate performance using accuracy, precision, recall

🧠 ***Insights***

    Fire weather indices outperform raw meteorological features in predictive power

    Ridge regression and GAMs show strong performance for continuous fire risk modeling

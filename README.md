

This project uses machine learning models to predict the winner of Indian Premier League (IPL) matches based on features like:
- Toss results
- Venue
- Team performance
- Head-to-head stats   hdahbdgyewydgtw6y4u8e9irfiufeiofio8jiocdjfuhedy7dehcbbhjcdsgyudfged6ge378et4wfgefir5i90g6o0uh7ou0o5hirg4iurfhr4weydgebydgyueg3tydvtescvyte
- Match conditions    

It’s built using Python, Pandas, Scikit-learn, and Matplotlib, with a clean and simple interface for predictions.       

 Highlights

| Feature                          | Details |
|----------------------------------|---------|
|  Cleaned IPL dataset (2008–2023) | Based on official match stats |
|  ML Algorithms Used             | Logistic Regression, Decision Tree, Random Forest |
|  Accuracy Achieved             | ~83% with Random Forest (tuned) |
|  Visual Insights               | Team wins, toss impact, venue advantages |
|  Simple CLI or Streamlit UI   | For quick predictions and interaction |

 How It Works

1. Preprocessing: Cleaning match data, encoding teams, venues, and results.
2. Feature Engineering: Creating new features like `home_advantage`, `win_toss_and_bat`, etc.
3. Model Training: Training multiple classifiers and tuning hyperparameters.
4. Prediction: Taking user input (teams, venue, toss winner) and predicting the winning team.

 Tech Stack

-  Python
-  Pandas, NumPy
-  Matplotlib, Seaborn
-  Scikit-learn
-  Streamlit (for frontend, optional)
-  Jupyter Notebook
-  
 Screenshots / Output

(Add these after you upload screenshots)

 Model Accuracy Prediction Interface Data Insights 

[Accuracy](./screenshots/accuracy.png) [UI](./screenshots/ui.png) [Insights](./screenshots/insights.png) 

 Project Structure

bash

IPL-Prediction
│
├─Z data/
│   └── ipl_matches.csv
├── notebooks/
│   └── IPL_Prediction_Model.ipynb             
├── app/
│   └── streamlit_app.py
├── screenshots/
│   └── *.png
├── README.md
└── requirements.txt

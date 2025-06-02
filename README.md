📚 Academic Paper Recommender System
🎓 Built for the CFH ACROSS Hackathon – June 2025
🧠 Overview
This project is a content-based recommender system designed to help students and researchers quickly discover relevant academic papers based on a given paper's title and abstract.

Using TF-IDF vectorization and cosine similarity, our system recommends the top 3 most similar papers from the dataset. The interface includes both a dropdown menu and a text input search bar built in Google Colab for ease of testing and demonstration.

🚀 Features
🔎 Recommend similar papers based on title and abstract

📊 Uses TF-IDF + Cosine Similarity for text comparison

🧪 Easy-to-use UI with dropdown and search box

🖥️ Interactive demo in Google Colab

🧹 Lightweight, no model training or GPU required

📁 Folder Structure
bash
Copy
Edit
├── README.md
├── recommender_notebook.ipynb   # Main Colab notebook
├── sample_dataset.csv           # Replace with actual dataset
⚙️ How to Run
Open the notebook in Google Colab
Click here to open in Colab (Replace with your real link)

Upload or connect the dataset

Run all cells, then:

Select a paper title from the dropdown or

Type one in the search bar and click Recommend

📊 Tech Stack
Python

pandas

scikit-learn

ipywidgets

Google Colab

📌 How It Works
Load dataset of paper titles and abstracts

Combine text and vectorize using TF-IDF

Compute pairwise similarity using cosine similarity

Recommend top 3 similar papers with a short explanation

Present recommendations via dropdown or search input

🧠 Future Improvements
Integrate semantic models like BERT

Add topic clustering for thematic exploration

Build a web interface with Streamlit

Add user profiling for personalized recommendations

👥 Team
Your Name – [your email or GitHub]

Teammate Name – [their email or GitHub]

🏆 Submitted to
CFH ACROSS Hackathon 2025
Theme: AI Tools for Metrics in Education, STEM, and Social Sciences


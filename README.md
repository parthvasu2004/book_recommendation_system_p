📚 **Book Recommendation System**
Personalized Book Recommendations Using Machine Learning


🔗 Repository: parthvasu2004/book_recommendation_system_p
🚀 Overview
The Book Recommendation System is a machine learning-based web application that provides personalized book recommendations based on user preferences. It leverages collaborative filtering and content-based filtering techniques to suggest books similar to user interests.

🛠️ Features
✔️ Personalized Recommendations: Recommends books based on user ratings and popularity.
✔️ Machine Learning Model: Uses pre-trained models stored in .pkl files for efficiency.
✔️ Flask Web Application: User-friendly interface for generating recommendations.
✔️ Efficient Data Processing: Uses preprocessed datasets for quick predictions.
✔️ Live Deployment: Hosted on Render for public access.

📂 Project Structure
bash
Copy
Edit
book_recommendation_system_p/
│── templates/          # HTML templates for web app  
│   ├── recommend.html  # Recommendation page  
│── app.py              # Flask web application  
│── books.pkl           # Processed book data  
│── popular.pkl         # Popular books dataset  
│── pt.pkl              # Pivot table for collaborative filtering  
│── similarity_scores.pkl # Precomputed similarity matrix  
│── Books.csv           # Original dataset - book details  
│── Ratings.csv         # User ratings dataset  
│── Users.csv           # User details dataset  
│── render.yaml         # Deployment configuration for Render  
│── requirements.txt    # Python dependencies  
│── runtime.txt         # Python version information  
│── .gitignore          # Ignored files  
│── README.md           # Project documentation  
⚙️ Installation & Setup
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/parthvasu2004/book_recommendation_system_p.git
cd book_recommendation_system_p
2️⃣ Create & Activate Virtual Environment (Optional but Recommended)
sh
Copy
Edit
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
3️⃣ Install Dependencies
sh
Copy
Edit
pip install -r requirements.txt
4️⃣ Run the Application
sh
Copy
Edit
python app.py
Visit http://127.0.0.1:5000/ in your browser to access the web app.

🧪 Usage
1️⃣ Open the web application in your browser.
2️⃣ Enter a book title in the search box.
3️⃣ Click "Recommend" to get personalized book suggestions.

🎯 Model & Training
Dataset: Utilizes book ratings, user data, and book metadata for training.
Algorithms:
Collaborative Filtering: Suggests books based on user interactions.
Content-Based Filtering: Uses similarity scores to recommend books.
Preprocessing:
Data cleaning and handling missing values.
Creating a pivot table (pt.pkl) for collaborative filtering.
Computing similarity scores (similarity_scores.pkl).
🔗 Live Deployment
The application is deployed on Render for public access. Click here to try it out! (Replace with actual URL)

🤝 Contribution
Contributions are welcome! Feel free to fork this repository, create feature branches, and submit pull requests.

📜 License
This project is licensed under the MIT License – free to use and modify.

📬 Contact
👤 Parth Vasu
📧 Your Email
🔗 LinkedIn

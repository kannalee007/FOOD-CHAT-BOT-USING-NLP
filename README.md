# FOOD-CHAT-BOT-USING-NLP
FoodBot - An AI powered food ordering chatbot – A Python Tkinter app for food ordering with menu browsing, order tracking, and cancellation. Uses ML for delivery time prediction, personalized recommendations, and sentiment analysis to make ordering smarter and interactive
🚀 Key Features
NLP-Driven Ordering: Browse menus and place orders using natural language commands.
Delivery Time Prediction: Uses a Machine Learning model to estimate delivery times based on traffic and order volume.
Personalized Recommendations: Suggests dishes based on your previous order history.
Sentiment Analysis: Analyzes user feedback/reviews in real-time to gauge satisfaction.
Order Management: Built-in functionality for real-time tracking and easy cancellations.
User-Friendly GUI: A clean, responsive interface built with Tkinter.
🛠️ Tech Stack
Frontend: Python (Tkinter)
NLP: NLTK / Spacy (Intent recognition & Sentiment analysis)
Machine Learning: Scikit-learn (Regression for delivery time, Collaborative filtering for recommendations)
Data Handling: Pandas, NumPy
Storage: SQLite / JSON
📊 How it Works
The chatbot follows a pipeline to ensure accuracy and speed:
Text Preprocessing: Tokenization, stop-word removal, and lemmatization of user input.
Intent Classification: Identifying if the user wants to "Order," "Track," or "Cancel."
ML Inference:
Regression: y=β 
0
​	
 +β 
1
​	
 x 
1
​	
 ... to predict delivery time.
Sentiment: Categorizing reviews into Positive, Neutral, or Negative.

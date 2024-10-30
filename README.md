 Restaurant Recommendation System:


This **Restaurant Recommendation System** built with **Flask** provides users with personalized restaurant suggestions based on budget, cuisine, location, and group size. By leveraging **cosine similarity** to evaluate restaurant features, it identifies top restaurants matching user preferences. The system integrates a **CSV dataset** of restaurant data and utilizes **CountVectorizer** to analyze highlighted features, offering suggestions based on locality and cost considerations.

### Key Features:
1. **Search and Filter:** Users input preferences such as number of people, minimum and maximum budget, preferred cuisine, and location to get tailored restaurant suggestions.
2. **Recommendation Algorithm:** Utilizes cosine similarity on key features to rank restaurants, showing the best matches based on user preferences.
3. **Web Interface:** A clean, responsive UI built with HTML and Bootstrap provides a simple search form for seamless interaction and easy selection.
4. **Real-time Filtering:** Users receive up-to-date recommendations that they can adjust with new inputs, including specific favorite restaurants.

### Tech Stack:
- **Backend**: Flask framework
- **Data Processing**: pandas, scikit-learn (CountVectorizer, cosine similarity)
- **Frontend**: HTML, Bootstrap, and Font Awesome for styling and interactivity

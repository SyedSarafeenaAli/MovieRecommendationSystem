# MOVIE-RECCOMENDATION-SYSTEM
This is a movie recommendation system

\\ Automatically download large pickle file from Google Drive
import gdown

url = "https://drive.google.com/file/d/1g-1-ut9JPkNHwFVxp8YiBOuqHtsu8FyJ/view"
output = 'similarity.pkl'
gdown.download(url, output, quiet=False)

Link for the deployed web service created using render and streamlit:-
https://movierecommendationsystem-8771.onrender.com/

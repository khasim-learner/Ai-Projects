AIFindr — AI-Powered People Discovery Engine

Overview:
AIFindr is an AI-powered platform that allows users to discover and match with ideal profiles based on their interests, goals, and vibe. Users can input a description of what they are looking for in a person, such as hobbies, personality traits, or lifestyle preferences. The AI then processes this information, compares it with profiles in a database, and provides the most relevant matches.

Features:
User Input: Users can describe their ideal person using natural language (e.g., “Find me someone who loves hiking and is passionate about photography”).
AI Matching: The platform uses Natural Language Processing (NLP) and vector embeddings to match user inputs with profiles in the database.
Profile Display: The top matches are displayed with a brief summary of their bio, interests, and vibe.
Persona Ranking: Users can rank the matches based on persona compatibility.

Tech Stack : 
Streamlit: For building the interactive front-end.
Sentence Transformers: For generating embeddings of user input and profiles.
FAISS: For efficient similarity search to find matching profiles.
JSON: For storing and handling profiles.
Python: For overall app development.

Running the Project Locally:
1. Clone the repositry : git clone https://github.com/your-username/Ai-Projects.git
                         cd Ai-Projects
2. Install dependencies:  pip install -r requirements.txt
3. Generate the embeddings and build the FAISS index:  python build_index.py
4. Run the app : streamlit run app.py
5. open ur browser to interact with app at -  http://localhost:8501/
   



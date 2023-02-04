# **Book-recommender-engine**
## LiveServerLink:
## 🔗 https://book-recommender-engine-1e13.onrender.com/
 
## Overview:
 
Book recommender engine is a flask app developed in Python. 
It recommends appropriate books to users based on popularity and user interests.

**Technology used:** 
 - HTML & CSS 
 - Python 
 - Flask 
 - Bootstrap
 - Jupyter NoteBook
 - VScode 
 - Render 
 
## Guide to install and run the project
**GitHub Setup :**
- Fork the repository 
- Check the forked repository in your profile 
- Clone the project

**Local Setup :**

 - Create a folder and open it
 - For windows: Open git bash / For Linux: Open terminal and cd to that folder 
 - Clone the repository from link :  
```git clone https://github.com/neha067/Book-recommender-engine.git```
- setup a virtual environment and install the requirements : 
```pip install -r requirements.txt```
- Now, run the  app.py file and the development server will start
```python app.py```

### Guide to contribute :
- Set original repo as your upstream remote : 
```git remote add upstream https://github.com/neha067/Book-recommender-engine.git```
- Pull updates from upstream : 
```git pull upstream```
- Make changes locally and push it your forked copy of the project 
- Create a pull request in GitHub

### Guide to use the project

 - Upon running you'll be shown a Homepage which will show the recommendation of top 50 books with most ratings 
   using the popularity based filtering and a navigationMenu  to 'recomend' 
 - On clicking "recommend", you'll be asked to enter the name of a book.
 - On clicking enter you will be recommended top books which have closest attributes and are most similar to the   given input book using content based filtering model


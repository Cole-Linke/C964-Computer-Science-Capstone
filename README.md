C964 - Computer Science Capstone - The Computer Science Capstone course allows the student to demonstrate their application of the academic
and professional abilities developed during the BSCS program. The capstone challenges students to integrate skills and knowledge from all program
domains into one project.

Task: Developed a Python-based recommendation application that analyzes video game metadata to generate ranked recommendations using an interactive Voila user interface.

User Guide (Local Setup)
1. Install Python 3.13
2. Download and unzip C964-steam-recommendation-capstone.zip
3. Open the Command Prompt and navigate to the project folder location<br><br>
&ensp;&ensp;&ensp;&ensp;> cd ...\C964-steam-recommendation-capstone<br><br>
4. Make sure your current folder contains game_recommender.ipynb, requirements.txt, and
steam_games_cleaned.csv<br><br>
&ensp;&ensp;&ensp;&ensp;> dir<br><br>
5. Install required dependencies<br><br>
&ensp;&ensp;&ensp;&ensp;> python -m pip install -r requirements.txt<br><br>
6. Run the application<br><br>
&ensp;&ensp;&ensp;&ensp;> python -m voila game_recommender.ipynb<br><br>
7. Your browser should automatically open, but if not, navigate to http://localhost:8866/
8. Notice that when the page loads, there are three different tabs at the top of the page<br>
&ensp;&ensp;-Recommender Tab: Game Recommender Application<br>
&ensp;&ensp;-Visuals Tab: Shows visuals that describe the dataset<br>
&ensp;&ensp;-Validation Tab: Shows the metrics used to validate the algorithm<br>

Using the Application
1. Navigate to the recommender tab
2. Enter a game's name<br>
&ensp;&ensp;ex: "Kingdom Come: Deliverance II"<br>
3. Click the "Recommend" Button
4. The "Minimum Metacritic Score" slider can be used to filter out games<br>
&ensp;&ensp;-Games with no score are usually less known and from indie studios<br>
&ensp;&ensp;-Games with a score are usually well known and from established studios<br>
   

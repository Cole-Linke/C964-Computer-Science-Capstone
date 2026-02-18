C964 - Computer Science Capstone - The Computer Science Capstone course allows the student to demonstrate their application of the academic
and professional abilities developed during the BSCS program. The capstone challenges students to integrate skills and knowledge from all program
domains into one project.

Task: Developed a Python-based recommendation application that analyzes video game metadata to generate ranked recommendations using an interactive Voila user interface.

User Guide (Local Setup)
1. Install Python 3.13
2. Download and unzip C964-steam-recommendation-capstone.zip
3. Open the Command Prompt and navigate to the project folder location<br><br>
&ensp;&ensp;&ensp;&ensp;cd ...\C964-steam-recommendation-capstone<br><br>
4. Make sure your current folder contains game_recommender.ipynb, requirements.txt, and
steam_games_cleaned.csv<br><br>
&ensp;&ensp;&ensp;&ensp;dir<br><br>
5. Install required dependencies<br><br>
&ensp;&ensp;&ensp;&ensp;python -m pip install -r requirements.txt<br><br>
6. Run the application<br><br>
&ensp;&ensp;&ensp;&ensp;python -m voila game_recommender.ipynb<br><br>
7. Your browser should automatically open, but if not, navigate to http://localhost:8866/
8. Notice that when the page loads, there are three different tabs at the top of the page

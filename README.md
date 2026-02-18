# C964 - Computer Science Capstone
The Computer Science Capstone course allows the student to demonstrate their application of the academic
and professional abilities developed during the BSCS program. The capstone challenges students to integrate skills and knowledge from all program
domains into one project.

## Task 
Developed a Python-based recommendation application that analyzes video game metadata to generate ranked recommendations using an interactive Voila user interface.

## User Guide (Local Setup)
1. Install Python 3.13
2. Download and unzip C964-steam-recommendation-capstone.zip
3. Open the Command Prompt and navigate to the project folder location
```bash
cd C964-steam-recommendation-capstone
```
5. Make sure your current folder contains game_recommender.ipynb, requirements.txt, and
steam_games_cleaned.csv
```bash
dir
```
6. Install required dependencies
```bash
python -m pip install -r requirements.txt
```
7. Run the application
```bash
python -m voila game_recommender.ipynb
```
9. Your browser should automatically open, but if not, navigate to http://localhost:8866/
10. Notice that when the page loads, there are three different tabs at the top of the page
- Recommender Tab: Game Recommender Application
- Visuals Tab: Shows visuals that describe the dataset
- Validation Tab: Shows the metrics used to validate the algorithm

## Using the Application
1. Navigate to the recommender tab
2. Enter a game's name<br>
`Kingdom Come: Deliverance II`
3. Click the "Recommend" Button
4. A ranked list of the top five most similar games will be displayed
5. The "Minimum Metacritic Score" slider can be used to filter out games<br>
`Games with no score are usually less known and from indie studios`<br>
`Games with a score are usually well known and from established studios`
   

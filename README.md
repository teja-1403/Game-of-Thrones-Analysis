# Game-of-Thrones-Analysis ⚔️
![m Fighter Plate Armor Helm Cloak Shield Sword midlvl](https://github.com/user-attachments/assets/93a118cd-c7b5-4d6c-8011-8c8be336b15d)

# About Project: 
This project involves the analysis and predictive modeling of various datasets related to the Game of Thrones series. It aims to extract meaningful insights about battles, character deaths, and predictions for future events using data science techniques. The project combines exploratory data analysis (EDA), machine learning algorithms, and visualization to provide an in-depth understanding of the world of Game of Thrones.

# Dataset: 
The Game of Thrones dataset consists of multiple files that provide detailed information about battles, character deaths, and character predictions. This dataset combines three sources of data, all of which are based on information from the book series. This data is structured to enable analysis and machine learning applications. You can find all the files that we have used in our project [here](https://drive.google.com/drive/folders/1KfZi7yiZbo3B1_bVtGTSfCTO6-VSCq77?usp=sharing).

Dataset Name: Game of Thrones
Link: [Game of Thrones Dataset on Kaggle](https://www.kaggle.com/datasets/mylesoneill/game-of-thrones)

**Key Files:**

1. battles.csv:
   
Purpose: Contains information about the battles in the series.

Key Features:

  - name: Name of the battle.
  - year: The year in the timeline when the battle occurred.
  - attacker_king & defender_king: Kings involved in the battle.
  - attacker_outcome: Outcome of the battle (win or loss).
  - battle_type: Type of battle (e.g., pitched battle, siege).
  - attacker_size & defender_size: Army sizes of the attackers and defenders.
  - region & location: Geographic details of the battle.
  - major_death & major_capture: Whether major deaths or captures occurred.

2. character-deaths.csv:
   
Purpose: Details the characters who died in the series.

Key Features:

  - Name: Character’s name.
  - Allegiances: The house or group the character belonged to.
  - Death Year: The year of the character's death.
  - Book of Death & Death Chapter: The book and chapter in which the death occurred.
  - Gender: Gender of the character.
  - Nobility: Whether the character was of noble lineage.

3. character-predictions.csv:
   
Purpose: Contains data for predicting whether a character is likely to die.

Key Features:

  - Demographic attributes like age, gender, and nobility.
  - Social connections such as numDeadRelations (number of deceased relatives).
  - Attributes indicating appearances in the books (book1 through book5).
  - Popularity metrics such as isPopular and popularity.

# Objectives:

1. Which king attacks the most number of times?
2. Which is the most battled location?
3. Which king attacks with the largest army?
4. Which king defends with the largest army?
5. Which type of battle does the attacking king face the most?
6. Which king won the most battles after attacking?
7. Which king has been attacked the most number of times?
8. Which king successfully defends the most number of times?
9. What types of battles occur the most in successful defenses?
10. What is the range of the attacker king's army size?
11. What is the range of the defender king's army size?
12. Which king never loses a battle, either attacking or defending?
13. Is there a relationship between army size and victory in battles?
14. In which location do attacker kings win the most battles?
15. In which location do defender kings win the most battles?
16. Who died more, male or female characters?
17. What percentage of characters who died belonged to nobility versus non-nobility?
18. In which year did most characters die?
19. Which allegiances had the most character deaths?
20. In which book did most of the character deaths occur?
21. In which chapter of Book 1 did most characters die?
22. In which chapter of Book 2 did most characters die?
23. In which chapter of Book 3 did most characters die?
24. In which chapter of Book 4 did most characters die?
25. In which chapter of Book 5 did most characters die?
26. What is the distribution of deaths across all books?

# Results:
1. King with the Most Attacks: Joffrey/Tommen Baratheon.
2. Most Battled Location: Riverrun.
3. King with the Largest Attacking Army: Stannis Baratheon.
4. King with the Largest Defensive Army: Joffrey/Tommen Baratheon and Renly Baratheon.
5. Most Common Battle Type: Pitched battles.
6. King with Most Wins After Attacking: Joffrey/Tommen Baratheon.
7. Most Attacked King: Robb Stark.
8. King with Most Successful Defenses: Joffrey/Tommen Baratheon.
9. Battle Type in Successful Defenses: Pitched battles dominate.
10. Range of Attacker Army Size: Most are under 20,000 soldiers.
11. Range of Defender Army Size: Most are about 3,000 soldiers.
12. Undefeated King: Balon/Euron Greyjoy (neither loses in attack nor defense).
13. Army Size and Victory Relationship:
  - Larger Attacking Army: 85.71% chance of victory.
  - Smaller Attacking Army: 80% chance of victory.
  - Equal-Sized Armies: 100% chance of attacker victory.
  - Army size does not strongly determine the outcome.
14. Best Region for Attacker Wins: The Riverlands.
15. Best Region for Defender Wins: The Riverlands and The Crownlands.
16. Male vs. Female Deaths: 82.9% of deceased characters were male, while 17.1% were female.
17. Nobility vs. Non-Nobility: 46.9% of deceased characters were nobles, and 53.1% were non-nobles.
18. Year with Most Deaths: The year 298 saw the highest number of deaths.
19. Allegiances with Most Deaths: Characters without allegiance died the most, followed by allegiances like House Stark and House Lannister.
20. Book with Most Deaths: Book 3 recorded the highest number of deaths.
21. Chapters in Book 1 with Most Deaths: Chapters 31 and 64 had the most deaths.
22. Chapter in Book 2 with Most Deaths: Chapter 66 had the most deaths.
23. Chapter in Book 3 with Most Deaths: Chapter 40 had the most deaths.
24. Chapter in Book 4 with Most Deaths: Chapter 20 had the most deaths.
25. Chapter in Book 5 with Most Deaths: Chapter 4 had the most deaths.
26. Distribution of Deaths Across Books: Book 3 has the densest distribution of deaths, followed by Books 1 and 2.

To predict whether a character is likely to die, 10 machine learning algorithms were used and their model performance was evaluated.

**Algorithms Used:**

Random Forest, Decision Tree, SVC, Logistic Regression, kNN, Gaussian Naive Bayes, Gradient Boosting, AdaBoost, XGBoost, Bagged kNN, and Bagged Decision Tree.

Bagging: Improved stability and accuracy for models like kNN and Decision Trees.
Boosting: Gradient Boosting, AdaBoost, and XGBoost provided superior accuracy by combining weak learners.

Best Algorithm: XGBoost emerged as the best model, achieving the highest cross-validated accuracy for character death predictions.

# 
Languages used : 

![python-logo-only](https://github.com/user-attachments/assets/a78aa447-fe92-4892-aaed-4dd6ea761795)

# 
📣 Feel free to have a look at all the files in this repository !🤗

❎ In case you find issues in any of my Repositories, you can Hit Me Up [here](https://github.com/issues)! 👈




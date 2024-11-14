java c
CSIT040 – Modern Computing Skills Project
Autumn 2024
IntroductionThe Final project is an important component of this course, which weights 20% of the overall marks. The purpose of the project behind it is to gain hands-on and applied research experience in applying the concepts presented in this course.  You can choose any of the topics presented below to work on, and can work in groups to do your projects. Each project group should consist of 6 students maximum.LogisticsGroup formationForm. a group of max. 6 students, designate a group leader. Please post your group names on student forum.Deadline and submissionNovember 30th, 2024: Final report submission (on Moodle – one submission per group) and project Youtube video link.Project Report – sample outline1. Title2. Project Scope  Objective3. Steps and methodology used to complete the project4. Results and analysis5. Conclusion  what could be improvedWhat to include in your project video:You need to create a 5 minutes video showcasing your project, including:1. Some few slides to present the team members, the project idea, the design of your solution2. A demo of your system in action3. One slide about what can be improved in your solution in the future4. You need to upload your video on Youtube and send us the link on Moodle, for gradingMAKE SURE TO FOLLOW THE REPORT TEMPLATE AND INCLUDE YOUR GROUP EXCEL SHEET GIVEN ON MOODLEProject TopicsHere are some possible project ideas. We are open to other ideas if you’d like to propose your own.Project 1 [Python]: Personal Budget Tracker
Create a simple Personal Budget Tracker using Python that allows users to manage their monthly budget by entering income and expenses. The program will calculate the remaining balance, categorize expenses, and notify the user if their expenses exceed their budget.
Requirements:
· The program should allow the user to:
1. Set their total income (budget) for the month.
2. Add expenses to different categories (e.g., Food, Transportation, Entertainment).
3. View total expenses, category-wise expenses, and the remaining balance.
4. Receive a warning if the expenses exceed the set budget.
· The solution should use lists, variables, print statements, if conditions, loops, and functions (no external libraries).
Structure and Features:
1. Set the Monthly Budget:
o The user will input their total income (the budget for the month).
2. Add Expenses:
o The user will be able to add expenses into different predefined categories (e.g., Food, Transportation, Entertainment, Bills).
o The program will ask the user to input the category and the amount spent.
3. Track Expenses:
o The program will keep track of expenses and calculate totals for each category.
o It will continuously update the remaining budget after each expense is entered.
4. Display Summary:
o The user can view a summary of their expenses by category and check the remaining balance at any time.
5. Warning for Overspending:
o If the total expenses exceed the set budget, the program will notify the user that they are overspending.
Code Breakdown:
1. Main Menu: The user can choose from the following options:
o Set a new budget
o Add an expense
o View expense summary
o View remaining budget
o Exit
2. Predefined Categories: The categories are hard-coded into the program, and expenses are added to these categories.
Example output:

Project 2 [Python Programming]: Grocery list and Budget manager
Create a Python program that allows users to manage a grocery shopping list and budget. Users can add items to their list, specify the price of each item, and track their total spending. The program will ensure the user stays within their set grocery budget.
Requirements:
· The program will allow the user to:
1. Set a grocery budget.
2. Add grocery items to a shopping list, including their price.
3. View the list of added items and the total cost.
4. Receive a warning if the total cost exceeds the budget.
Structure and Features:
1. Set Grocery Budget:
o The user will input a budget for their grocery shopping.
2. Add Grocery Items:
o The user will add items to their shopping list, including the name of the item and its price.
o The total cost will be updated with each new addition.
3. View Grocery List and Total Cost:
o At any point, the user can view the list of items and the total cost so far.
4. Warn for Exceeding Budget:
o If the total cost exceeds the set budget, the program will notify the user.
Project 3 [Python]: Fitness ProgressCreate a Python program that helps users track their fitness progress over time. Users will input their daily exercise routines and log their workouts. The program will calculate the total time spent on exercises and provide a summary of the user’s progress at the end of the week.Requirements:· The program will allow the user to:1. Log daily exercises (type of exercise, time spent).2. Track the total exercise time for each day and provide a weekly total.3. Receive feedback on whether the user is meeting their fitness goals.4. View a summary of each day’s activities.Structure and Features:1. Set Weekly Fitness Goal:o The user will input their fitness goal for the week (e.g., 300 minutes of exercise).2. Log Daily Exercises:o Each day, the user will input exercises they performed and the time spent on each exercise.o The program will store these entries in a list.3. Track Progress:o The program will calculate the total exercise time logged each day and the total for the week.o It will compare the weekly total against the fitness goal and provide feedback.4. View Exercise Summary:o At any time, the user can view a summary of their exercises for the week, showing how much time was spent on each day.Project 4 [AI/Python]: Robot Maze solvingGo to https://gears.aposteriori.com.sg/  and select the following:- Robot: Maze Runner- World: Maze Map, imperfectWrite a python code that asks the user for a certain color (Blue, red, green, or yellow) and then solve the maze and get to that color spot.Project 5 [AI]: Clustering
Your spaceship has just returned from an exploratory mission on a distant planet, and you have collected a sample of 1000 rocks from various locations. These rocks vary in their physical characteristics, such as their length, weight, and color. Your task as a data scientist is to analyze the dataset containing these measurements and determine how many distinct categories (clusters) of rocks are present代 写CSIT040 – Modern Computing Skills Project Autumn 2024Python
代做程序编程语言.
Objective:
You are provided with a dataset containing 1000 samples, each representing a rock. The dataset includes the following features:
· rock_length: The length of the rock.
· rock_weight: The weight of the rock.
· rock_color: The color of the rock (e.g., Red, Green, Blue, Yellow, Brown).
Your task is to use clustering techniques to analyze the physical properties of the rocks and determine the natural groupings (clusters) in the data.
Steps:
1. Load the dataset: The dataset contains the rock_length, rock_weight, and rock_color features for 1000 rocks.
2. Preprocessing: Since color is categorical, you should either encode or ignore it during the clustering process. You will use the rock_length and rock_weight features for clustering.
3. Clustering Algorithm: Apply the K-Means algorithm to cluster the rocks based on their rock_length and rock_weight.
4. Analysis:
o How many distinct categories (clusters) are present among the rocks?
o Visualize the clusters and describe the characteristics of each group.
o Is there a relationship between the clusters and the rock colors?
Data: on moodle
Project 6 [AI]: Data AnalyticsYou are considering opening a gaming booth in one of three malls. You have a dataset that contains detailed information about mall visitors, including their age group, the day of the week, the time of day they visit, and their total bill spent during their visit. To maximize your booth's success, you want to identify the ideal mall, day, and time to open the booth, targeting the times when potential customers are most likely to visit.Objective:Using the dataset containing the following information:· Mall: The name of the mall (3 options)· Age Group: The age group of visitors (e.g., 10-20, 21-30, etc.)· Day of the Week: The day of the week (Monday-Sunday)· Time of the Day: The time of day (Morning, Afternoon, Evening)· Total Bill: The total amount spent by visitorsAnalyze the data to determine:1. Which mall has the highest potential for a gaming booth (based on total bill or visitor trends).2. What time of day would be best to attract your target audience.3. Which day of the week typically sees the highest engagement or sales.Steps:1. Load and explore the dataset to understand the distribution of visitors across the malls, days, times, and total spending patterns.2. Segment the data by age group to identify which age group spends the most and during what time/day they frequent the mall.3. Analyze spending patterns across malls, days of the week, and times of the day to determine high-traffic times for your target audience.4. Use this information to decide the best mall, best time, and best day of the week to set up your gaming booth for maximum success.Data: on moodleProject 7 [AI/Python]: Robot Arm controllerWrite a Blockly or python script. for the dobot arm to pick up three cups and put them on top of each other.· Use 3 cups of different colors and place them in the reach zone of the robot· Note down the location of Home and positions of the plates/cups· Attach the suction cup to the gripperProject 8 [PYTHON / cyber security] : Python-based Password ManagerCreate a command-line password manager that allows users to securely store, manage, and retrieve their passwords for different accounts. The application should follow cybersecurity best practices, such as encrypting stored passwords.Features:1. User Authentication: Implement a login system with username and password authentication.2. Add Accounts: Users can store account details, including the service name (e.g., "Gmail"), username, and password.3. View Accounts: Users can view their stored account details.4. Edit Accounts: Users can update their account information, including the password.5. Delete Accounts: Users can delete stored accounts.6. Password Encryption: Ensure that stored passwords are encrypted using an encryption algorithm.7. Search Accounts: Users can search for stored accounts by service name.Additional Challenges:1. Save and Load: The application should save encrypted account data to a file (e.g., JSON or CSV) and load it securely.2. Password Strength Validation: Implement a feature to validate password strength (length, special characters, numbers, etc.).3. Password Generator: Implement a feature to generate strong, random passwords for users.Project 9 [PYTHON / cyber security] : packet sniffERCreate a simple packet sniffer using Python. The packet sniffer will monitor and display network traffic on a local network interface.Requirements:1. Packet Capturing:- Use the Python library `scapy` or `socket` to capture incoming and outgoing packets on the local machine.- The program should display basic information about each packet, such as:- Source and destination IP addresses.- Protocol (e.g., TCP, UDP, ICMP).- Source and destination ports (for TCP/UDP packets).2. Filtering by Protocol:- Implement a simple filter to allow users to choose which protocol (TCP, UDP, or ICMP) they want to view.3. Continuous Packet Monitoring:- The program should continuously sniff packets and display them in real-time.4. User-Friendly Output:- For each packet, display the captured information in a clear and readable format (e.g., “TCP packet from 192.168.1.1 to 192.168.1.2 on port 80”).Bonus Points:Save Logs: Add an option to save the captured packet data to a file (e.g., a CSV file) for further analysis.Project 10 [PYTHON / cyber security] : FIle integrity checkerDevelop a simple Python tool that calculates the hash of files to verify their integrity. This tool will allow users to detect any changes in their files, which is a common cybersecurity practice to ensure that files haven't been tampered with.Requirements:1. File Hashing:- Use Python's `hashlib` library to calculate the cryptographic hash (e.g., SHA-256) of a file.- The program should prompt the user to input the file path and then display the hash of the file.2. Integrity Verification:- Allow users to store the original hash of a file in a text file.- The user can then re-run the program to check if the current file's hash matches the original hash, ensuring the file has not been altered.3. User-Friendly Output:- Display whether the file is "Intact" (if the hashes match) or "Corrupted/Modified" (if the hashes do not match).Bonus Points:1. Directory Hashing: Extend the functionality to check the integrity of all files in a directory.2. Automated Integrity Check: Schedule automatic integrity checks for important files and log the results.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

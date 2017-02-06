# machine-learning

### imperfect-data branch:

Data Source: https://data.cityofnewyork.us/Education/SAT-Results/f9bf-2cp4
2012 College-Bound Graduating HS Seniors from NYC


        Data Attributes:
        1. DBM = Data Base Name
        2. Name = Name of School
        3. Num = Number of Students (college-bound seniors who took the 2012 SAT)
        4. Read = Reading SAT Score Average
        5. Write = Writing SAT Score Average
        6. Math = Math SAT Score Average


I used pandas to do my main data work, and matplotlib to plot the graphs. 
I cleaned the data, removing the "s" fields (null or empty fields). 
I also had to force coercion of the scoring fields to change from strings to numeric, in order to get some of the statistics.

My 5 Questions I asked:
- What was the Maximum score for all 3 (Reading, Writing, Math)
- What was the Minimum score for all 3
- What wass the Median score for all 3
- How many students, who fell under this study's criteria, took the SAT
- Won't the Reading and Writing SAT scores be highly correlated? (Is it overkill, would be my next question)

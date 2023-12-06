# PRODIGY_DS_02

 With the Titanic dataset, perfom analysis and detect the trends and anomalies in the data. 

 ## Data Understanding

 The following are the descriptions of the columns in the data:
 
     1. Survived - Survival (0 = No; 1 = Yes)
     2. Pclass - Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
     3. Name - Name
     4. Sex - Sex
     5. Age - Age
     6. SibSp - Number of Siblings/Spouses Aboard
     7. Parch - Number of Parents/Children Aboard
     8. Ticket - Ticket Number
     9. Fare - Passenger Fare
     10. Cabin - Cabin
     11. Embarked - Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

The 'Cabin' column had a large number of missing values and was therefore dropped. Whereas the Tickets column was dropped due to a large number of duplicates which are hard to explain while some of the information on ticket numbers is represented in other columns, such as the first digit of the Ticket no. being the passenger class. 

Other columns such as Name and Passenger ID were dropped since they don't add any value to the analysis. 

A column named age group was created. The groups include: children, youth, middle aged, and elderly. This was done to help with the analysis.

## Conclusions

- In general there was a ~38% survival rate in the Titanic.
- Out of all passengers that survived ~68% of them were women.
- The higher the passenger class the higher the chance of survival was.
- Children (passengers below age 18) had the highest survival rate out of all other age groups.
- For both 'Siblings and Spouses' and 'Parents and Children' on board; passengers with a very high number (>4) of either had less possibility of survival as well as those with No counterpart on board (When compared to the others with low number of either category on board).
- The males that boarded at Queenstown had less than 10% survival rates.
- Passengers who boarded from Cherboug had the highest survival rates.

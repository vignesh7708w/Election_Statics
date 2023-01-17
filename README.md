# Election_Statics
1)This will allow user to enter the candidate name 
2)Once candidate is added the peoples can vote for the particular candidate 
3)First it will check whether it is a valid candidate or not then it will allow Peoples to vote
4)It will show the total vote count for the particular candidate
5)It will show the total list also
6)Finally it will show the winner.

#Implementation
1)I create hashmap for to store the candidate and vote count
2)It ask name for the candidate then it will validate whether the candidate is in the map or not 
3)If it is valid candidate it will increase the vote count of the particular candidate
4)Then i created one method for to return the total votes for the particular candidate
5)As per requirement we need to list all the candidate vote and details in JSON format so i added one dependency file from the MAVEN
6)Finally the getwinnner will show the winner of the election

Dependency file Name:
Jackson-Databind

Assumption:
1)I assumed there will be no candidate with the same name 
2)If two candidates have the same number of votes you didnt mentioned what to do so i assumed there will be no two candidates have the same votes

Result:
![image](https://user-images.githubusercontent.com/114211301/212911932-e832f168-f7ee-40c9-8ba6-6e9802922dce.png)





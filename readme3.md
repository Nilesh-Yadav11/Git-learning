Master branch - |_|- |_|-|_|-|bug|-|_|-|_|-|_|

Feature (naam rakh skte ho bs iss branch cka kuch bhi maine apni branch ka naam feature kha hai ya rakha hai ) branch -|_|- |_|-|_|-|_|-|_|-|_|-|_|

Actually mein jo branch copy krti hai uska naam feature rkh skte hai yaan kch bhi rkh skte ho jo mnn kre pr isko bnayneg aur iska naam kaise rkhenge??

git checkout -b "feature" branch ka naam 

git branch -- isse pata chalega ki kitni branches hai total
* feature
  master

> GRAPH KE CHANGES -- ye sab pata laga hai hume graph option ko click krne pr 

Balle Nilesh Yadav
Final Nilesh Yadav
Changes Nilesh Y ...
Third commit Nilesh ...
Commited Nilesh Yadav
day2commit Nilesh Y ...
Commit Nilesh Yadav
Committed Nilesh Ya ...
Commited Nilesh Yadav
My second commit ...
My first commit Niles ...
feature
+1


git checkout master
git merge feature 
master aur feature ko merge hum aise karenge

fir ab feature ka branch khtm toh hum feature ko delete kr skte hai 

git branch -D feature 
branch delete feature

git branch -D feature
Deleted branch feature (was 1de1b5d).
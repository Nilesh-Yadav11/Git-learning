Git is a free and open source distributed version control system designed to handle everything front small to very large projects with speed and efficiency.

Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce,
and ClearCase with features like cheap local branching, convenient
staging areas, and multiple workflows.


<!-- Git -- version control system -->

Dikkate

1) Jaise ki 
while(true){
    console.log(20)// ye to print hota jayega 
}

Aisi samasya ko hatane ke liye humko changes ko humne add kiya tha unko hta do yaa fir unn changes ko revert back karna hoga 

2) 5 alg alg bande hai , pta kaisa chlega kaun sa line yaa kaun sa code kis bande ne likha hai , ownership of code pata chl jayega isse

3) Tracker: Git (tracks all your codes)
Wesbite: 4:00pm
Code changes meri website crash: 5pm
Name: Timer

cmd mein git--version se version check kr lo ki install bhu hua ki nhi

Cmd mein karna list takk
<!-- Configuration -->

git config --global user.name "Your Name" // naam pta chl jayga isse

git config --global user.email "your.email@example.com" 

You can verify the configuration:
git config -- list 
<!-- isse jo naam aur email id hai dono aa jaeyga -->


fir uske baad batana pdega ki git ko kaunse folder ko track karna hai 

<!-- ye krna terminal mein vs code ke  -->

cd folder_name
git init 

<!-- fir uske baad jo files track karni ho usko  -->

git add file ka naam extension k saath

agar saari files track karaani ho toh 

git add .

<!-- PS C:\Users\kadam\OneDrive\Desktop\nilesh_vscode \gitgithub> git status
On branch master

No commits yet

Changes to be committed:

Changes to be committed:

Changes to be committed:
(use "git rm -- cached <file> ... " to unstage)
day1-git.html
day1-git.js
readme1.md

Changes not staged for commit:
(use "git add <file> ... " to update what will be committed)
(use "git restore <file> ... " to discard changes in working directory)
modified:

PS C:\Users\kadam\OneDrive\Desktop\nilesh_vscode\gitgithub>

new file:
new file:
new file:

readme1.md -->

Abhi tk koi bhi files commit nahi hui hai karaani hai toh 

git commit-m "message jo bhi daalna ho "
m message ke liye hai , saari files commit ho jayengi


ab commit karne ke baad dekhne ho ki kha kha pr kaun sec hange shue hai toh 
kha hua hia ye pta lgega git status se red colour me dikhayengi files jaha pr bhi changes hue hai 
modified ke aage likhe rhenege 

aur kya changes hue hai voh pata lagenge hume
git diff se 
fir jb end karna ho aur vps console mein jaana ho toh Q daab dena



<!-- to access all the files -->

<!-- How to see hidden folder -- >

In Windows 11: Click the View drop down (threedots)

Show > Hidden items.
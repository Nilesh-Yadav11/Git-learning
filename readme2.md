git log se pata chal jayega kis bande ne kya aur kab chezon ko commit kiya hai 
aur fir usko q se khtm kr denge

git log --oneline ye bhi vahi btayega thode short form mein

ab jaise ki maine sbse phle first commit kiya tha fr second third fourth jaise krte jaaoge toh ek branch bn jaayegi ki jaha pr har ek commit apne previous commit pr depend krr hi hogi kyuki naya code puraane vale prr hi togh depend karega aur uss branch ka naam master branch hota hai 

Master branch

first commit 
    |
Second commit
    |
Third commit
    |
Fourth commit

ab jaise ki agar fourth commit par code fat gaya toh , mjhe agar vaapas jaana ho toh phle commit pr toh hum kya krenge 

head ki direction badal denge bss
sbse phle git log --oneline kroge 

d34bc65 (HEAD -> master) Hello Commited
d161e9c Third commit
466de9c Commited
c880fed day2commit
fc151eb Commit
c77b8d0 Committed
4d69ab5 Commited
855bcc6 My second commit
e2212dd My first commit

abhi ye aaya tha toh ab third commit par aana ho toh likhenge 

 git reset --hard d161e9c (ye code vo vla hoga jha pr commit karvana hoga )


Ab agar mai chaahta hu ki bs sceond commit ke changes ko revert krvana chaahta hu bina third commit ko kch kiye toh voh kaise karenge

d161e9c (HEAD -> master) Third commit
466de9c Commited
c880fed day2commit
fc151eb Commit
c77b8d0 Committed
4d69ab5 Commited
855bcc6 My second commit
e2212dd My first commit


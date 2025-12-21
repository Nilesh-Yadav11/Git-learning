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

git revert c880fed
to just remove the part of day2commit's changes and nothing other than that 

git add . 
git commit -m"" bss khatam fir

jo revert kiya hai vo history mein toh rhega hi vo bss uske changes ko hata dega yaa simple bhaasha mein undo karr dega 

vhi git reset --hard se usse baaad ka poora udd hi jayega delete hi ho jaayega , aap vaapas nhi aa sakte fir 



Branching kya hai ab

mai chhata hu ki mai aoni website pr ek payment gateway add karu toh 

  
Master branch - |_|- |_|-|_|-|bug|-|_|-|_|-|_|

Payment branch -|_|- |_|-|_|-|_|-|_|-|_|-|_|

payment gateway mein maan lo koi bug aagya jiske vjh se humara code aage hi nahi badh raha hai 
aur uss bug ko hum solve krr rhe hai master branch mein aur uss bug ke aage branches add hote jaa rhi hai jo ki dekhne yaa vaise bhi accha nhi lgta bilkl bhi toh hum kya krnege payement branch mein jo ki copy hi hai master branch ki toh vaha pr hum try krenge ki bug ko solve karte jaaye aur fir jis branch prr solv ho jaaye bug bss vaha se usko copy krke bug ke aage master branchmein jod denge aur baaki ke branches ko delete krr deneg taaki faaltu ka code na dikhe

matlab humara main aim to yeh hai ki koi cheez poori bn jaaye tabhi aap usko bheje naa ki baar baar changes krkr apni history ko bekaar karu 
jaayega mster vala code hi website prr jo dikhega 
toh hum aise hi ek payment ki trh bana lenge aur usme kaam krenge jb tkk mera kaam poora nhi ho jaat , jb poora ho jayega toh khud master mein daal dena vo 

|_|- |_|-|_|-|_|
              |
             |_|- |_|-|_|

             aise merge krr do aur ye saari neeche vali branches bhi master ka part bnn jayengi
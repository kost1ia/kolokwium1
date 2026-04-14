Zadanie 1
git init do stworzenia reposytorium na komputerze 
echo "kolokwium1" >> README.md  do stworzenia README.MD
git add REDME.MD do dodania file do git branch
git commit -m "Zadanie 1"
git branch -m Main 
git remote add origin https://github.com/kost1ia/kolokwium1.git
git push -u origin main

Zadanie 2 
git checkout -b kostiantyn_vyhovskyi dodalem drugi branch i odrazu na niego zmienilem 
echo "14.04.2026" >> data.txt plik z data 
echo "Kostiantyn Vyhovskyi" >> imie.txt dodalem plik z inicjalami 
git status
git branch 
git add imie.txt 
git commit -m "Dodalem plik tylko z imieniem i nazwiskiem"
git push -u origin main 
git switch 
git add README.md

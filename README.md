hx **** Exercice 1 de github ****  
******************************  
  
liste des commandes utilisé : 

git config --global user.email "aferedye@gmail.com"  
git config --global user.name "Antoine Feredye"  
git init  
git remote add origin https://github.com/aferedye/exercice1.git  
git branch -M main  
echo "Je suis l'exercice 1 de antoine" > fichier1.txt  
git add *  
git commit -m "first commit"  
git push -u origin main   
echo "Je suis l'exercice 1 mais le second fichier" > fichier2.txt  
git add *  
git commit -m "second commit"  
git push -u origin main  
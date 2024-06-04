***********git push***********
cd "/d/learning/1.numpy"


create a new repository on the command line
echo "# numpy" >> README.md
git init
git add .
git commit -m "Add numpy done"
git remote add origin https://github.com/Faysal179038/numpy.git
git push -u origin main

or push an existing repository from the command line
git remote add origin https://github.com/Faysal179038/numpy.git
git branch -M main
git push -u origin main
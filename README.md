# projetosPy

projetos Python

clear; for var in $(ls); do (echo -e "\n----> $var\n";cd $var;git status;git add .;git commit -m "atua_auto";git push -u origin master; cd ..); done

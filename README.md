# Inicializace repozitáře

cd ~  
mkdir "projekt"  
git init  

<jdi na github a udělej nový repo>  
<zkopiruj ssh adresu>  

git remote add origin <ssh_adresa_ziskana_z_gitub>  
git push -u origin master  

-----
# Poslání na github
git add . NEBO git add <casta k projektu>  
git commit -m "<zpráva o tom co jsi změnil>" // git commit -m "upravil jsem radek 12 aby to delalo to a to a ....    
git push  

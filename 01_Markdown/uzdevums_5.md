# Darbs ar Git

1.	Mapē git_repos noklonēt  https://github.com/hashicorp/terraform projektu

2.	Pārbaudīt kādas izmaiņas tika veiktas iepriekšējās nedēļas laikā. Atrast vismaz divus veidus kā to izdarīt. git log, 


3.	Atrast commit kurus veica autors  - “Laura Pacilio”
git log --since="1 week ago" --author=“Laura Pacilio”

4.	Atrast vai Laura ir veikusi commit pagājušā gada septembrī?
git log --since="2022-09-01" --until="2022-09-30" --author=“Laura Pacilio"

5.	Vai Laura ir veikusi commit vakar?nē

6. Rezultatus apkopot MD faila git log --since="2022-09-01" --until="2022-09-30" --author=“Laura Pacilio" >> rezultati.md

# Darbs ar Github	

1. Noklonet savu repozitoriju

2. Sakartot taja mapes pēc strukturas:
Mape ar nosaukumu : 01_Markdown
Mape ar nosaukumu : 02_Git
Mape ar nosaukumu : 03_CI_Project

3. 03_CI_Project mape izmantot kodu no:
   
https://github.com/FitaUser/Creditcompany-website

vai 

https://www.programiz.com/python-programming/examples/calculator izvietojot py failu ar MD aprakstu, kur paskaidrot ka izmantot skritpu.

Vai izmantot savu kodu. 

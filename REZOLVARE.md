1\. screenshot din interfața Adminer:



!\[Interfata Adminer](./screenshot.png)





2\. explicatie despre importanța folosirii flag-ului -v in comanda docker compose down pentru un flux de lucru QA:



Aceasta comanda sterge definitiv volumele de date create de containere si la urmatoarea rulare mediul de testare va fi curat, fara date reziduale din testele anterioare. Daca nu se foloseste flag-ul "-v" baza de date pastreaza datele vechi si astfel testele automate urmatoare pot da rezultate gresite.


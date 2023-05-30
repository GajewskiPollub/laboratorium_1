## Punkt 1.<br>
*docker build -t <nazwa-obrazu> .<br>*
<br>
![](punkt_1_1.jpg)<br>
<br>
## Punkt 2.<br>
*docker run -p 8080:8080 <nazwa-obrazu> (należy pamiętać, żeby podać tę samą nazwę obrazu, którą nadaliśmy w poprzednim kroku)<br>*
<br>
![](punkt_2_1.jpg)<br>
<br>
*Natępnie wpisujemy w przeglądarkę adres http://localhost:8080/ w celu wyświetlenia stworzonego pliku index.php<br>*
<br>
![](punkt_2_2.jpg)<br>
<br>
## Punkt 3.<br>
*docker exec <id_kontenera> cat /app/log.txt<br>*
<br>
![](punkt_3_1.jpg)<br>
<br>
*Id kontenera możemy sprawdzić wpisując w konsolę polecenie docker ps<br>*
<br>
![](punkt_3_2.jpg)<br>
<br>
## Punkt 4.<br>
*docker image inspect <nazwa_obrazu>.<br>*
<br>
![](punkt_4_2.jpg)<br>
<br>
*Zbudowany obraz posiada 12 warstw.*

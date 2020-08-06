# Test Online Code M Rizal Mutaqin
# 1. Jawaban Soal Story Logic
![image](https://user-images.githubusercontent.com/54714964/89528545-69d98f80-d815-11ea-9337-d293d549dca9.png)
# 2. Jawaban PHP Logic
https://github.com/zanxzhui/online_test_2
# 3. Jawaban Soal RDBMS
- SELECT nm_film FROM film JOIN artis ON film.artis=artis.kd_artis AND artis.bayaran = (SELECT MIN(bayaran)FROM artis)
- SELECT nm_film FROM film JOIN artis ON film.artis=artis.kd_artis WHERE artis.nm_artis LIKE 'J%' 
- SELECT film.produser,produser.nm_produser, COUNT(*) as jml_film FROM film JOIN produser ON produser.kd_produser=film.produser GROUP BY film.produser 
- SELECT nm_artis FROM artis JOIN film ON film.artis=artis.kd_artis WHERE film.genre='G002' 
# 4. Jawaban Soal REST-API
https://github.com/zanxzhui/online_test

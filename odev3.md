Country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız.

- SELECT country from country WHERE country LIKE 'A%a' ;

Country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız.

- SELECT country From country WHERE LENGTH(country) > 6 AND country like '%n';

Film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren

- SELECT title FROM film WHERE title ILIKE '%t%t%t%t%';

Film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan büyük olan ve rental_rate 2.99 olan verileri sıralayınız.

- SELECT * from film WHERE title  LIKE 'C%' AND LENGTH > 90 AND  rental_rate = 2.99 ;




# patika.dev-SQL-Practice-02
patika.dev SQL Practice 02

🔸Film tablosunda bulunan tüm sütunlardaki verileri replacement cost değeri 12.99 dan büyük eşit ve 16.99 küçük olma koşuluyla sıralayınız ( BETWEEN - AND yapısını kullanınız.)

``` sql
SELECT *
FROM FILM
WHERE REPLACEMENT_COST BETWEEN 12.99 AND 16.99

```
🔸Actor tablosunda bulunan first_name ve last_name sütunlardaki verileri first_name 'Penelope' veya 'Nick' veya 'Ed' değerleri olması koşuluyla sıralayınız. ( IN operatörünü kullanınız.)

``` sql
SELECT FIRST_NAME,LAST_NAME
FROM ACTOR
WHERE FIRST_NAME IN ('Penelope','Nick','Ed');

```

🔸Film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99, 2.99, 4.99 VE replacement_cost 12.99, 15.99, 28.99 olma koşullarıyla sıralayınız. ( IN operatörünü kullanınız.)

``` sql
SELECT *
FROM FILM
WHERE RENTAL_RATE IN (0.99,2.99,4.99) 
AND REPLACEMENT_COST IN (12.99,15.99,28.99);

```
https://app.patika.dev/emintunahan

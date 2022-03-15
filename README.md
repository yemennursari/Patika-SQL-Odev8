# Patika-SQL-Odev8
--1.test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee(
	id INTEGER,
	name VARCHAR(50),
	bitrhday(DATE),
	email VARCHAR(100)
)
<br />
<br />
--2.Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
<br />insert into employee (id, name, birthday, email) values (1, 'Lorry', '1987-03-07', 'lwoolhouse0@tiny.cc');
<br />insert into employee (id, name, birthday, email) values (2, 'Prudence', '1975-10-04', null);
<br />insert into employee (id, name, birthday, email) values (3, 'Randell', '1978-05-26', 'rphebey2@vinaora.com');
<br />insert into employee (id, name, birthday, email) values (4, 'Dulcine', null, null);
<br />insert into employee (id, name, birthday, email) values (5, 'Carly', '1977-04-23', 'cmilkeham4@ifeng.com');
<br />insert into employee (id, name, birthday, email) values (6, 'Larissa', '1971-06-28', 'lkienl5@cbslocal.com');
<br />insert into employee (id, name, birthday, email) values (7, 'Ortensia', '1988-10-18', 'ostocker6@ox.ac.uk');
<br />insert into employee (id, name, birthday, email) values (8, 'Binny', '1989-09-06', 'bromain7@forbes.com');
<br />insert into employee (id, name, birthday, email) values (9, 'Kareem', '1984-03-27', 'klegen8@wix.com');
<br />insert into employee (id, name, birthday, email) values (10, 'Wallis', '1978-10-26', 'wcolebrook9@elegantthemes.com');
<br />insert into employee (id, name, birthday, email) values (11, 'Meghann', '1998-02-19', 'mslota@weibo.com');
<br />insert into employee (id, name, birthday, email) values (12, 'Broddy', '1998-12-04', 'bdicarlib@surveymonkey.com');
<br />insert into employee (id, name, birthday, email) values (13, 'Odele', '1986-04-28', 'ochongc@lycos.com');
<br />insert into employee (id, name, birthday, email) values (14, 'Keri', '1973-10-17', 'kcominolid@weebly.com');
<br />insert into employee (id, name, birthday, email) values (15, 'Katrina', null, 'kcaustice@pcworld.com');
<br />insert into employee (id, name, birthday, email) values (16, 'Gratiana', '1970-05-04', 'gbessomf@nifty.com');
<br />insert into employee (id, name, birthday, email) values (17, 'Verina', '1980-05-29', null);
<br />insert into employee (id, name, birthday, email) values (18, 'Alina', '1996-12-18', 'ameldingh@lulu.com');
<br />insert into employee (id, name, birthday, email) values (19, 'Edlin', '1984-01-15', null);
<br />insert into employee (id, name, birthday, email) values (20, 'Tadeas', '1981-08-19', 'tkhomishinj@cisco.com');
<br />insert into employee (id, name, birthday, email) values (21, 'Donnell', '1976-12-03', 'djennek@uol.com.br');
<br />insert into employee (id, name, birthday, email) values (22, 'Pooh', '1976-06-16', 'ptrustriel@nytimes.com');
<br />insert into employee (id, name, birthday, email) values (23, 'Eben', '1970-04-23', 'ehantuschm@accuweather.com');
<br />insert into employee (id, name, birthday, email) values (24, 'Floria', '1973-08-09', 'fbracern@oracle.com');
<br />insert into employee (id, name, birthday, email) values (25, 'Arlene', '1978-06-26', 'ahatherello@51.la');
<br />insert into employee (id, name, birthday, email) values (26, 'Udale', '1990-05-01', 'umackaigp@ask.com');
<br />insert into employee (id, name, birthday, email) values (27, 'Fianna', '1976-05-04', 'ftissellq@usda.gov');
<br />insert into employee (id, name, birthday, email) values (28, 'Bert', '1974-06-17', 'balliboner@stanford.edu');
<br />insert into employee (id, name, birthday, email) values (29, 'Sissy', '1978-02-20', 'spaxtons@alexa.com');
<br />insert into employee (id, name, birthday, email) values (30, 'Gavan', null, 'gbeatont@google.nl');
<br />insert into employee (id, name, birthday, email) values (31, 'Gennie', '1986-03-05', 'gsinclairu@studiopress.com');
<br />insert into employee (id, name, birthday, email) values (32, 'Roger', null, null);
<br />insert into employee (id, name, birthday, email) values (33, 'Carlee', '1974-07-28', 'cmckibbenw@goodreads.com');
<br />insert into employee (id, name, birthday, email) values (34, 'Beverly', '1994-04-20', 'bdunseathx@mtv.com');
<br />insert into employee (id, name, birthday, email) values (35, 'Angele', '1992-01-29', 'afliggy@webeden.co.uk');
<br />insert into employee (id, name, birthday, email) values (36, 'Olag', '1985-11-12', 'otroodz@cbc.ca');
<br />insert into employee (id, name, birthday, email) values (37, 'Sinclair', '1998-10-21', null);
<br />insert into employee (id, name, birthday, email) values (38, 'Angelia', '1972-01-16', 'acatford11@unicef.org');
<br />insert into employee (id, name, birthday, email) values (39, 'Joelie', null, 'jseller12@sfgate.com');
<br />insert into employee (id, name, birthday, email) values (40, 'Alistair', '1989-03-19', 'asenecaux13@theguardian.com');
<br />insert into employee (id, name, birthday, email) values (41, 'Atlante', '1989-07-06', 'awindrass14@ask.com');
<br />insert into employee (id, name, birthday, email) values (42, 'Sharyl', '1991-09-27', 'srollason15@adobe.com');
<br />insert into employee (id, name, birthday, email) values (43, 'Graeme', '1982-05-05', 'gtwiname16@economist.com');
<br />insert into employee (id, name, birthday, email) values (44, 'Alfie', '1972-11-19', 'alaverenz17@cisco.com');
<br />insert into employee (id, name, birthday, email) values (45, 'Harri', null, 'hglasner18@drupal.org');
<br />insert into employee (id, name, birthday, email) values (46, 'Serena', '1978-11-23', 'skeywood19@fema.gov');
<br />insert into employee (id, name, birthday, email) values (47, 'Nixie', '1980-02-17', 'nworral1a@admin.ch');
<br />insert into employee (id, name, birthday, email) values (48, 'Lib', '1999-03-24', null);
<br />insert into employee (id, name, birthday, email) values (49, 'Lock', '1970-12-16', null);
<br />insert into employee (id, name, birthday, email) values (50, 'Edy', '1970-04-03', 'ethomel1d@washingtonpost.com');
<br />
<br />
--3.Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
UPDATE employee
	SET name = 'Otto Meier',
	    birthday = '1987-02-01',
		email = 'OttoMeier@gmail.com'
WHERE id = 3;

UPDATE employee
	SET name = 'Alex',
	    birthday = '1996-02-04',
		email = 'alexD@gmail.com'
WHERE id = 5;

UPDATE employee
	SET name = 'Vladimir',
	    birthday = '1983-08-01',
		email = 'vladimir@gmail.com'
WHERE id = 7;

UPDATE employee
	SET name = 'Ali',
	    birthday = '1997-02-03',
		email = 'ali@gmail.com'
WHERE id = 13;

UPDATE employee
	SET name = 'Jack',
	    birthday = '1987-02-01',
		email = 'jackA@gmail.com'
WHERE id = 21;
<br />
<br />
--4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
DELETE FROM employee
WHERE id IN (3,5,7,13,21)
RETURNING *;

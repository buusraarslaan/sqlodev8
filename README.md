# SQL ODEV8

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

```
CREATE TABLE employee (
	id INTEGER PRIMARY KEY,
	name VARCHAR(50) ,
	birthday DATE ,
	email VARCHAR(100)
)
```

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

```
insert into employee (id, name, birthday, email) values (1, 'Loella Thorius', '1993-02-25', 'lthorius0@plala.or.jp');
insert into employee (id, name, birthday, email) values (2, 'Malchy Nudde', '1990-11-26', 'mnudde1@smugmug.com');
insert into employee (id, name, birthday, email) values (3, 'Jacobo Lillow', '1999-08-05', 'jlillow2@twitter.com');
insert into employee (id, name, birthday, email) values (4, 'Eliza Curragh', '2000-01-20', 'ecurragh3@spotify.com');
insert into employee (id, name, birthday, email) values (5, 'Idelle Doy', '1993-07-21', 'idoy4@odnoklassniki.ru');
insert into employee (id, name, birthday, email) values (6, 'Abby Larking', '1999-01-23', 'alarking5@statcounter.com');
insert into employee (id, name, birthday, email) values (7, 'Markos Busch', '1996-05-04', null);
insert into employee (id, name, birthday, email) values (8, 'Fleur Drury', '1997-02-15', 'fdrury7@goodreads.com');
insert into employee (id, name, birthday, email) values (9, 'Con Stollenwerck', '1996-12-30', 'cstollenwerck8@issuu.com');
insert into employee (id, name, birthday, email) values (10, 'Georgie Reoch', '1993-10-14', 'greoch9@blogger.com');
insert into employee (id, name, birthday, email) values (11, 'Thadeus Roggers', '1998-02-27', 'troggersa@spiegel.de');
insert into employee (id, name, birthday, email) values (12, 'Branden Whitton', '1994-03-02', 'bwhittonb@ning.com');
insert into employee (id, name, birthday, email) values (13, 'Dudley Stallibrass', '1993-12-16', 'dstallibrassc@geocities.com');
insert into employee (id, name, birthday, email) values (14, 'Archy Dory', '1991-10-06', null);
insert into employee (id, name, birthday, email) values (15, 'Nikolia Stout', '1999-11-19', 'nstoute@chronoengine.com');
insert into employee (id, name, birthday, email) values (16, 'Leisha Grigs', '1994-11-23', 'lgrigsf@wiley.com');
insert into employee (id, name, birthday, email) values (17, 'Lynnell Bloodworth', '1991-11-12', 'lbloodworthg@so-net.ne.jp');
insert into employee (id, name, birthday, email) values (18, 'Reg Rhoddie', '1996-10-25', 'rrhoddieh@weibo.com');
insert into employee (id, name, birthday, email) values (19, 'Myranda Challace', '1995-11-22', 'mchallacei@goodreads.com');
insert into employee (id, name, birthday, email) values (20, 'Thorsten Hatt', '1995-01-01', 'thattj@elegantthemes.com');
insert into employee (id, name, birthday, email) values (21, 'Jacquelyn Pope', '1997-10-06', 'jpopek@dmoz.org');
insert into employee (id, name, birthday, email) values (22, 'Nadeen O''Crowley', '1991-04-08', 'nocrowleyl@intel.com');
insert into employee (id, name, birthday, email) values (23, 'Dyanne Lympenie', '1998-11-28', 'dlympeniem@tiny.cc');
insert into employee (id, name, birthday, email) values (24, 'Nessy Bilborough', '1997-03-20', null);
insert into employee (id, name, birthday, email) values (25, 'Delmore Samter', '1996-01-19', 'dsamtero@google.co.uk');
insert into employee (id, name, birthday, email) values (26, 'Thedric Chaffe', '1990-06-09', 'tchaffep@dedecms.com');
insert into employee (id, name, birthday, email) values (27, 'Gussie Doggrell', '1993-03-27', 'gdoggrellq@globo.com');
insert into employee (id, name, birthday, email) values (28, 'Ash McQuilliam', '1992-07-09', 'amcquilliamr@statcounter.com');
insert into employee (id, name, birthday, email) values (29, 'Cal Porte', '1991-01-11', 'cportes@fotki.com');
insert into employee (id, name, birthday, email) values (30, 'Irvine Dorrian', '1991-08-15', 'idorriant@instagram.com');
insert into employee (id, name, birthday, email) values (31, 'Romeo Matyugin', '1997-07-18', null);
insert into employee (id, name, birthday, email) values (32, 'Wilfrid Jimenez', '1991-05-01', 'wjimenezv@unesco.org');
insert into employee (id, name, birthday, email) values (33, 'Clareta Aslott', '1990-11-21', 'caslottw@archive.org');
insert into employee (id, name, birthday, email) values (34, 'Aimee Huygens', '1994-03-27', 'ahuygensx@eepurl.com');
insert into employee (id, name, birthday, email) values (35, 'Ernaline Winscomb', '1993-04-19', 'ewinscomby@va.gov');
insert into employee (id, name, birthday, email) values (36, 'Adolf Alleway', '1991-06-01', 'aallewayz@uiuc.edu');
insert into employee (id, name, birthday, email) values (37, 'Leela Vannuccini', '1994-01-06', 'lvannuccini10@purevolume.com');
insert into employee (id, name, birthday, email) values (38, 'Rockwell Hoppner', '1990-10-28', 'rhoppner11@soundcloud.com');
insert into employee (id, name, birthday, email) values (39, 'Darrelle Cissen', '1995-03-29', 'dcissen12@bandcamp.com');
insert into employee (id, name, birthday, email) values (40, 'Keenan Pietruszka', '1990-07-31', 'kpietruszka13@nymag.com');
insert into employee (id, name, birthday, email) values (41, 'Sam Corby', '1995-06-02', 'scorby14@gravatar.com');
insert into employee (id, name, birthday, email) values (42, 'Chelsie Kynder', '1991-08-19', 'ckynder15@discovery.com');
insert into employee (id, name, birthday, email) values (43, 'Dulsea Donahue', '1996-08-26', 'ddonahue16@usa.gov');
insert into employee (id, name, birthday, email) values (44, 'Jessie Delort', '1998-01-23', null);
insert into employee (id, name, birthday, email) values (45, 'Joy Press', '1993-10-28', 'jpress18@homestead.com');
insert into employee (id, name, birthday, email) values (46, 'Tobey Litt', '1998-08-22', 'tlitt19@cnn.com');
insert into employee (id, name, birthday, email) values (47, 'Spike Jopson', '1991-04-22', 'sjopson1a@yale.edu');
insert into employee (id, name, birthday, email) values (48, 'Tilly Philippet', '1991-03-04', 'tphilippet1b@slideshare.net');
insert into employee (id, name, birthday, email) values (49, 'Agneta Poor', '1996-12-30', 'apoor1c@blogspot.com');
insert into employee (id, name, birthday, email) values (50, 'Agosto Gouldbourn', '1998-12-15', 'agouldbourn1d@skype.com');

```

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

```
UPDATE employee
SET name = 'Busra',
	birthday = '2000-11-25'
WHERE id = 1;
```

```
UPDATE employee
SET email = 'benzer@update.com',
	birthday = '2000-11-25'
WHERE id = 5;
```

```
UPDATE employee
SET name = 'Feriha',
	email = '2000-10-15'
WHERE id = 15;
```

```
UPDATE employee
SET birthday = '1999-01-05',
	id = 6
WHERE name = 'Con Stollenwerck';
```

```
UPDATE employee
SET email = 'hello@hot.com',
	id = 7
WHERE name LIKE 'A%';
```

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

```
DELETE FROM employee
WHERE birthday = '2000-11-25';
```

```
DELETE FROM employee
WHERE name LIKE 'A%';
```

```
DELETE FROM employee
WHERE email =  'benzer@hot.com'
```

```
DELETE FROM employee
WHERE name  =  'Busra Arslan'
```

```
DELETE FROM employee
WHERE id  =  1
```
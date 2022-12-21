# SQL-ODEV-8

##test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
Create table employee (
	id serial primary key,
	name varchar(50) not null,
	birthday date ,
	email varchar(100) not null
);

##Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.


insert into employee (first_name, birtday, email) values ('Jacquelynn', '1927-06-14', 'jlamblot0@delicious.com');
insert into employee (first_name, birtday, email) values ('Garik', '2014-05-31', 'grikard1@plala.or.jp');
insert into employee (first_name, birtday, email) values ('Rubin', '1995-03-28', 'rpoulett2@simplemachines.org');
insert into employee (first_name, birtday, email) values ('Timmi', '2000-02-29', 'tegginson3@deliciousdays.com');
insert into employee (first_name, birtday, email) values ('Anton', '1975-08-13', 'agallihawk4@tuttocitta.it');
insert into employee (first_name, birtday, email) values ('Marcia', '1968-05-15', 'mgillingham5@ezinearticles.com');
insert into employee (first_name, birtday, email) values ('Dolf', '1908-02-26', 'damies6@w3.org');
insert into employee (first_name, birtday, email) values ('Ambros', '1967-09-05', 'alamps7@1und1.de');
insert into employee (first_name, birtday, email) values ('Adolf', '1982-03-09', 'apottle8@networksolutions.com');
insert into employee (first_name, birtday, email) values ('Rasia', '1940-08-07', 'rhoudmont9@unicef.org');
insert into employee (first_name, birtday, email) values ('Titos', '1962-12-29', 'tgunthorpea@census.gov');
insert into employee (first_name, birtday, email) values ('Chrissie', '1928-11-14', 'cortb@yale.edu');
insert into employee (first_name, birtday, email) values ('Kerby', '1940-04-10', 'kgorlerc@yahoo.com');
insert into employee (first_name, birtday, email) values ('Celestina', '1967-03-16', 'chagardd@accuweather.com');
insert into employee (first_name, birtday, email) values ('Artus', '1978-05-21', 'aghidellie@mozilla.org');
insert into employee (first_name, birtday, email) values ('Crichton', '1964-02-02', 'cfaggf@europa.eu');
insert into employee (first_name, birtday, email) values ('Inesita', '1921-02-28', 'ipymg@artisteer.com');
insert into employee (first_name, birtday, email) values ('Daria', '1940-08-30', 'dvigarh@dot.gov');
insert into employee (first_name, birtday, email) values ('Carmela', '1930-11-26', 'cmandryi@blinklist.com');
insert into employee (first_name, birtday, email) values ('Wolfgang', '1929-04-30', 'wdepperj@nyu.edu');
insert into employee (first_name, birtday, email) values ('Abe', '1972-03-16', 'astudmank@zimbio.com');
insert into employee (first_name, birtday, email) values ('Braden', '1964-03-18', 'bperviewl@phoca.cz');
insert into employee (first_name, birtday, email) values ('Melisandra', '1955-02-07', 'mgorvettem@simplemachines.org');
insert into employee (first_name, birtday, email) values ('Paola', '1957-03-23', 'phailsn@harvard.edu');
insert into employee (first_name, birtday, email) values ('Artur', '1954-09-30', 'ahartnesso@etsy.com');
insert into employee (first_name, birtday, email) values ('Elston', '2002-10-14', 'edoumerp@comsenz.com');
insert into employee (first_name, birtday, email) values ('Mia', '1940-04-30', 'mmorcomq@wunderground.com');
insert into employee (first_name, birtday, email) values ('Marlo', '1980-09-23', 'mbanyardr@cdbaby.com');
insert into employee (first_name, birtday, email) values ('Darin', '1958-06-01', 'dduchesnes@skyrock.com');
insert into employee (first_name, birtday, email) values ('Jerry', '1950-04-22', 'jkroont@usa.gov');
insert into employee (first_name, birtday, email) values ('Belva', '1940-07-13', 'bacresu@altervista.org');
insert into employee (first_name, birtday, email) values ('Nelle', '2021-09-27', 'nstockinv@hugedomains.com');
insert into employee (first_name, birtday, email) values ('Mitchell', '2003-02-05', 'mnorthwoodw@psu.edu');
insert into employee (first_name, birtday, email) values ('Tully', '1920-11-03', 'tcorringtonx@goo.gl');
insert into employee (first_name, birtday, email) values ('Jessy', '1903-10-28', 'jhaggishy@ox.ac.uk');
insert into employee (first_name, birtday, email) values ('Bert', '2011-02-02', 'bheaselgravez@networksolutions.com');
insert into employee (first_name, birtday, email) values ('Skylar', '1993-01-15', 'shovee10@infoseek.co.jp');
insert into employee (first_name, birtday, email) values ('Bran', '1964-12-23', 'bkinnear11@soundcloud.com');
insert into employee (first_name, birtday, email) values ('Irwin', '1945-11-07', 'ioliva12@t.co');
insert into employee (first_name, birtday, email) values ('Garrot', '1966-06-18', 'gliggens13@oracle.com');
insert into employee (first_name, birtday, email) values ('Lin', '1975-02-19', 'lfreake14@ebay.com');
insert into employee (first_name, birtday, email) values ('Barbara', '1922-04-29', 'brubega15@blogspot.com');
insert into employee (first_name, birtday, email) values ('Boigie', '2022-11-30', 'bsalmond16@nifty.com');
insert into employee (first_name, birtday, email) values ('Benjamen', '1973-04-02', 'bskippings17@webmd.com');
insert into employee (first_name, birtday, email) values ('Lucille', '1991-11-27', 'lstonbridge18@wsj.com');
insert into employee (first_name, birtday, email) values ('Marlo', '1939-01-18', 'marnold19@europa.eu');
insert into employee (first_name, birtday, email) values ('Coleen', '1972-09-19', 'cever1a@jugem.jp');
insert into employee (first_name, birtday, email) values ('Tedi', '1986-09-22', 'tlutwidge1b@chicagotribune.com');
insert into employee (first_name, birtday, email) values ('Alexa', '2006-08-25', 'awaleran1c@spotify.com');
insert into employee (first_name, birtday, email) values ('Rozele', '1978-06-11', 'rfriar1d@princeton.edu');

##Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
UPDATE employee
SET name = 'OCS OCS'
WHERE name LIKE 'B%'
RETURNING *;

UPDATE employee
SET name = 'ABC ABC'
WHERE id = 13
RETURNING *;

UPDATE employee
SET email = 'asdasd@gmail.com'
WHERE id = 13
RETURNING *;


UPDATE employee
SET name = 'xxxxxxxxx'
WHERE id = 16
RETURNING *;

UPDATE employee
SET birthday = NULL
WHERE name LIKE 'A%c'
RETURNING *;

##Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
DELETE FROM employee
WHERE email LIKE 'sr%'
RETURNING *;

DELETE FROM employee
WHERE id > 49
RETURNING *;

DELETE FROM employee
WHERE birthday = '2022-10-16'
RETURNING *;

DELETE FROM employee
WHERE name = 'Adah Braunter'
RETURNING *;

DELETE FROM employee 
WHERE  email = 'nkinselle@hubpages.com'
RETURNING *;

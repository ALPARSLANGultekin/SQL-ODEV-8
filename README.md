# SQL-ODEV-8

##test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
Create table employee (
	id serial primary key,
	name varchar(50) not null,
	birthday date ,
	email varchar(100) not null
);

##Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

mockaroo

Looking to generate fake data based on your production data? Mimic your databases with a trial account from

Need some mock data to test your app? Mockaroo lets you generate up to 1,000 rows of realistic test data in CSV, JSON, SQL, and Excel formats.

Need more data? Plans start at just $60/year. Mockaroo is also available as a docker image that you can deploy in your own private cloud.
Field Name
Type
Options
first_name
​
blank:
0
%

​
birtday
​
12/21/1900
​
to
12/21/2022
​
format:
%Y-%m-%d
​
blank:
0
%

​
email
​
blank:
0
%

​
# Rows:
50
​
Format:
sql
​
Table Name:
employee
​
include CREATE TABLE

Mock your back-end API and start coding your UI today.
It's hard to put together a meaningful UI prototype without making real requests to an API. By making real requests, you'll uncover problems with application flow, timing, and API design early, improving the quality of both the user experience and API. With Mockaroo, you can design your own mock APIs, You control the URLs, responses, and error conditions. Paralellize UI and API development and start delivering better applications faster today!

Why is test data important?
If you're developing an application, you'll want to make sure you're testing it under conditions that closely simulate a production environment. In production, you'll have an army of users banging away at your app and filling your database with data, which puts stress on your code. If you're hand-entering data into a test environment one record at a time using the UI, you're never going to build up the volume and variety of data that your app will accumulate in a few days in production. Worse, the data you enter will be biased towards your own usage patterns and won't match real-world usage, leaving important bugs undiscovered.

Why is realistic data important?
When your test database is filled with realistic looking data, you'll be more engaged as a tester. When you demonstrate new features to others, they'll understand them faster. Real data is varied and will contain characters that may not play nice with your code, such as apostrophes, or unicode characters from other languages. Testing with realistic data will make your app more robust because you'll catch errors that are likely to occur in production before release day.

Why Mockaroo?
There are plenty of great data mocking libraries available for almost every language and platform. But not everyone is a programmer or has time to learn a new framework. Mockaroo allows you to quickly and easily to download large amounts of randomly generated test data based on your own specs which you can then load directly into your test environment using SQL or CSV formats. No programming is required.

Want to automate test data generation?
If you sign in using your Google account, you can download random data programmatically by saving your schemas and using curl to download data in a shell script via a RESTful url.

What's new in Mockaroo?
11/20/2022
Added airport data.
11/14/2021
You can now generate datasets using JSON and import them into other schemas using the Dataset Column type.
10/14/2021
Added support for InfluxDB
6/19/2021
Added the ability to import fields from a JSON schema or example JSON object.
5/22/2021
You can now create a dataset directly from a schema. You no longer need to download and reupload generated data to create a dataset!
5/19/2021
You can now stream data to an MQTT endpoint! Click More > Stream to MQTT Endpoint... to get started.
5/3/2021
Added types related to construction work.
5/3/2021
Added Etherium and Tezos types.
4/10/2021
Added a download button to the preview dialog.
4/4/2021
You can now use regular expressions to generate data in formulas. For example /d+{2}/.gen
4/2/2021
Restored the ability to backup your schemas to files.
3/28/2021
You can now limit credit card numbers by card type and country.
3/23/2021
Massive UI Update! The UI has been overhauled to provide a faster, prettier experience.
1/24/2021
The Gender datatype has been modernized and expanded. You can now choose from Gender, Gender (Binary), and Gender (Facebook). Existing schemas that use the old "Gender" type have been updated to use "Gender (Binary)" for backwards compatibility.
© 2022 Mockaroo, LLC.   |  Terms of Use   |  EULA   |  Privacy
Preview
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

# xml-file-reader
This repo for uploading XML file & save it into DB
XML file format should be below

<Books>
	<book>
		<author>Rasmus Lerdorf</author>
		<name>PHP</name>
	</book>
	<book>
		<author>David</author>
		<name>MySQL</name>
	</book>
	<book>
		<author>Bala G</author>
		<name>C</name>
	</book>
	<book>
		<author>Bala G</author>
		<name>C++</name>
	</book>
	<book>
		<author>Pankaj</author>
		<name>Software Engineering</name>
	</book>
</Books>


Steps for accessing 
- Clone repository at your system
- Run Migration: php artisan migrate
- Start project: php artisan serve
- http://127.0.0.1:8000/


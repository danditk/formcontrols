# formcontrols

Webside was created to learn me new topic - Clasical form controls.
I learn how to creat new HTM5 tags, forms, form controls.

Course this tutorial we are writeing webside, in witch user creating car by selecting option for that car.


.# HTML:

	- <form action="" method="" enctype="">				action - witch script PHP, method - get or post, enctype ID MIME-type for post metod ()
	() enctype="application/x-www-form-urlencoded"		code for space and marks
	() enctype="multipart/form-data"					for imput files
	() enctype="text/plain"								for normal/ casual text	
	- <label>											eny controls anf forms without buttons must have label
	- <label (for="ID")>								for group items
	- <fieldset>										to group items of list on webside interface
	- <legend>											label for fildset
	- <input type="text">								user input regular text
	- <input type="password">							user input hiden marks box
	- <input type="number">								user input only for number end e - *10^
	- step												if we wont to chenge defolud number step 1, for example 0.1
	- <input type="search">								give us option to quick delate input box value
	- placeholder										shows handle in box, text witch disapired when user writeing into box, gray color
	- <input type="checkbox">							checked list - many choses
	- <input type="radio">								list radio - one choose 
	- name												name / id item of list to read by PHP
	- checked											if we wont to checked one of radio item
	- disabled											if we wont to make that user can't change item
	- name="list_name"									eny group have to be named to be conected
	- value												to send to PHP
	- multiple											to create multiple selector list
	- size												to show x items multiple list, next items must be scroll
	- <input type="tel">								user input only for phone number
	- <input type="email">								user input only for email
	- <input type="date">								user input only for date
	- <input type="month">								user input only for month
	- <input type="week">								user input only for week
	- <input type="time">								user input only for time
	- <input type="color">								user input only for color
	- <input type="submit">								like buton, for example to conform form and send to PHP action="xxx.php"
	- <input type="button">								button witch didn't send to form
	- <select>											to create select list
	- <option>											to create item to select list
	- selected											as checked to select classic option
	- <select multiple>									xxxxxxxxxxx
	- <textarea>										xxxxxxxxxxx
	- <button>											in that type we can put img in button
		
.# CSS:

	- xxx;
		
.# GIT:
	
	- echo "xxx" >> file_name.xxx						save xxx in file_name
		
.# PHP:
	
	- $list_name = $_POST['name_radios_itam'];			to get value from user
	- echo $list_name;									to send value to user
	- for ($i=x; $i to count($value); $i +x/-x) {}		loop in PHP
	- foerach ($value as $to) {}							loop in PHP
		
.# Sources:

	- Kurs HTML odc. 6: Klasyczne kontrolki formularzy by Pasja informatyki
	http://miroslawzelent.pl/kurs-html/klasyczne-kontrolki-formularzy/
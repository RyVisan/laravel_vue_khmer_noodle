## Database Stucture
+Users
	id,
	name,
	name_kh,
	gender,
	dob,
	address,
	hire_date,
	position,
	photo,
	email,
	password

+Customers
	id,
	name,
	gender,
	phone,
	address

+Tables
	id,
	name,
	dsc

+Categories
	id,
	name,
	name_kh,
	dsc

+Customers
	id,
	name,
	gender,
	phone,
	address

+Tables
	id,
	name,
	dsc

+Categories
	id,
	name,
	name_kh,
	dsc

+Products
	id,
	name,
	name_kh,
	price,
	photo,
	dsc,
	category => Categories,
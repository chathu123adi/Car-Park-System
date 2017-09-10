
# Car-Park-System
Hi,I'm chathuranga. I'm trying to develop simple car park system. 
This should be create using OOP concept in JAVA

required	to	complete	a	program	that	implements	a	basic	Car	Park	System.	The	car	park	has	a	maximum	of	20	parking	lots	and	only	cars,	vans	and	motorbikes	can	park	in	the	parking.	
	In	this	assignment,	you	will	be	required	to	implement	the	following	functionality:	
	
	
	1.	Design	and	implement	a	class	Vehicle	(abstract)	and	the	subclasses	Car,	Van,	Motorbike.	The	classes	should	include	appropriate	methods	and	hold	information	about	the	ID	plate	of	the	vehicle,	the	brand	of	the	vehicle	and	the	entry	time/date	in	the	parking.	
	In	particular:	
  • The	Car	class	should	also	include	appropriate	methods	and	hold	information	about	the	number	of	the	doors	of	the	car	and	the	color.		
  • The	Van	class	should	also	include	methods	and	information	about	the	cargo	volume	of	the	van.		
  • The	class	Motorbike	should	also	have	methods	and	information	about	the	size	engine	of	the	motorbike.			You	should	implement	a	class	DateTime	to	represent	the	time/date	of	the	entrance	of	the	vehicle	in	the	parking.		Do	not	use	any	predefined	library.

2.	Design	and	implement	a	class	called	WestminsterCarParkManager,	which	extends	the	interface	CarParkManager.	WestminsterCarParkManager	maintains	the	list	of	the	vehicles	currently	in	the	parking.		The	class	should	display	in	the	console	a	menu	from	which	the	user	can	select	among	the	following	management	actions:		
  • Add	a	new	vehicle	in	the	parking	if	there	are	free	lots	(considering	that	the	max	number	of	lots	is	20)	and	return	the	number	of	the	free	lots	remaining.	Consider	that	a	Van	occupied	2	lots.		Display	a	message	with	the	number	of	free	lots	or	informing	that	there	are	no	lots	available.	
	• Delete	a	vehicle,	selecting	the	ID	plate,	from	the	list	when	the	vehicle	leaves	the	car	park	and	return	the	vehicle	instance.	Display	the	type	of	the	vehicle	leaving	the	parking	(if	it	is	a	car,	a	van	or	a	motorbike).			
  • Print	the	list	of	the	vehicles	currently	parked.	For	each	vehicle	print	the	ID	plate,	and	the	entry	time	and	the	type	of	vehicle	(if	is	a	car,	a	van	or	a	motorbike).	The	list	should	be	ordered	chronologically,	displaying	the	last	vehicle	entered	in	the	parking	as	the	first	in	the	list.		
  • Print	some	statistics:		o The	percentage	of	cars,	the	percentage	of	vans	and	the	percentage	of	motorbikes	currently	parked.			o The	vehicle	that	is	parked	for	the	longest	time	and	the	last	vehicle	that	was	parked.	You	should	show	the	ID	plate,	the	type	and	the	entry	time	and	date	for	these	two	vehicles.			
  • Print	the	list	of	vehicle,	which	enter	in	the	parking	in	a	specified	day:	the	user	has	to	enter	the	day	and	year	from	the	console	and	the	list	of	the	vehicles	that	entered	that	day	will	be	printed.	A	message	will	notify	if	no	vehicles	were	parked	in	that	day.		
  • The	car	park	charge	3£	per	hour	for	the	first	three	hours.	The	car	park	charges	an	additional	1£	per	hour	after	the	first	three	hours.	The	maximum	charge	for	any	24	hours	periods	is	30£.	Display	on	the	screen	the	parking	charges	for	each	customer who	parked	in	the	garage		(IdPlate	and	the	final price).

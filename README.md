# Flighter
The Flighter is an Online flight Showcase Web App with the following 4 sections,

Flights details Section, Flights List Section,  Sorting Section and Easy Access Section.

 

a) Flights details Section:

 - It has 5 input fields with placeholders same as FieldName and a button to add the flight details.

 - All these below Elements should be wrapped inside a `div` with id `flightFields` and this should be centred horizontally.

 

FieldName	Description	Type	ID*
Name	Name of the Airline	String	name
Origin

Location where the flight Journey begins	String	
origin

Destination	Location where the flight Journey ends	String	
destination

Price	Cost of Travel	Number	
price

Rating	Customer Rating given to the Airline	Number	
rating

Add	A button to Add these details	Button	addBtn
 

 

 

 

 

 

 

 

 

 

 

 

 

 

b) Sorting Section : 

It should have two options to sort the flights in the list  Sort by Price and Sort by Rating

Initially the list is unsorted, once the user clicks on either of the option it should sort in Ascending order first and then Descending.

The name of the Sort Options should add text `asc` when sorted in ascending order and `desc` when sorted in descending order.

These two Options should be wrapped by a div with id 'sorter' and this should have rounded corners with Background color as  ‘#deb887’

 Name (default)	Sorted in Ascending	Sorted in Descending	ID
Sort by Price 	Sort by Price (asc)	Sort by Price (desc)	sortPrice
Sort by Rating	Sort by Rating (asc)	Sort by Rating (desc)	sortRating
 

c) Flights List Section :

The flight details entered in the above section should get added to this section on click of Add button.

Should not add if any field is empty.

Should clear all input fields on successful add.

The flight details should be displayed in a card component.

Layout details:

This section lies parallel to Easy Access Section and Below Sorting Section.

Flights List section should be wrapped inside a 'div' with id flightItems.

All flight cards should lie inside the container.

Each flight card is a <ul> which has a class 'card' to which card styling should be applied. Background color should be ‘#faebd7’

Flight details are displayed using <li> tags inside <ul>

1st <li> should contain 'Flight Name: <Name of the Airline>'

2nd <li> should contain '<Origin> to <destination>'

3rd <li> should contain 'Rating: <rating>*' (Include Star after rating without space)

4th <li> should contain 'Price: Rs.<Cost of travel>'

 

d) Easy Access Section  

This section should have two Headings Source and Destination.

As and when a new flight is added add the new source and destination under two headings.

Make sure there is no repetition or duplicates.

 

Layout details:

Background color: ‘#5f9ea0’

Id of the Container should be 'easyAccess'

Source section should be a <ul> with id originFilter to which new Sources should be added with <li> tag

Destination section should be a <ul> with id destFilter to which new Destinations should be added with <li> tag.

 

Easy access section and Sorting Section should have same distance from the top of the viewport.
Form a layout similar to the demo below.

 

Note: Mandatory to add IDs to the fields as specified to make a hassle-free validation.

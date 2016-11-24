# json-datatables-view
View JSON with DataTables.net to have a sortable HTML table.

##To Begin
There are two examples, `form-download-product-list.html` and `form-subs-contact.html`. Just edit the few JS variables below `***`. You'll also want to populate the table with data. I used PHP to update the JSON files every time a form the contact from was submitted.

##Data
The data structure can be has linear as you like, but I haven't tested with arrays in objects or any depth to the data.

##Example data structure
```
[
	{
		"name":"Chance",
		"email":"chance@email.com"
	},
	{
		"name":"Molly",
		"email":"molly@email.com"
	},
	{
		"name":"Carter",
		"email":"carter@email.com"
	},
	{
		"name":"Mason",
		"email":"mason@email.com"
	}
]
```
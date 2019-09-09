### initialise with scaffold
python ~\odoo\odoo-bin scaffold my_library

### changed following files

modified:   my_library/__init__.py   
modified:   my_library/__manifest__.py  
modified:   my_library/controllers/__init__.py  
modified:   my_library/models/__init__.py  
new file:   my_library/models/library_book.py  
new file:   my_library/security/groups.xml  
modified:   my_library/security/ir.model.access.csv  
new file:   my_library/static/description/icon.png  
new file:   my_library/views/library_book.xml   

<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/001.png" width="50%">
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/002.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/003.png" >

<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/004.png" >

### model _order
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/005.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/006.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/007.png" >

### model fields
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/008.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/009.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/010.png" >

### model decimal precision

```
cost_price = fields.Float('Book Cost', digits=dp.get_precision('Book Price'))
```

<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/011.png" >

### model relational fields
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/012.png" >

```
<form>
	<group>
		<group>
			<field name="name"/>
			<field name="author_ids" widget="many2many_tags"/>
			<field name="state"/>
			<field name="pages"/>
			<field name="notes"/>
			<field name="cost_price"/>
			<field name="retail_price"/>
			<field name="currency_id"/>
		</group>
		<group>
			<field name="short_name"/>
			<field name="publisher_id"/>
			<field name="date_release"/>
			<field name="date_updated"/>
			<field name="cover" widget="image" class="oe_avatar"/>
			<field name="reader_rating"/>
		</group>
	</group>
	<group>
		<field name="description"/>
	</group>
</form>
```

<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/013.png" >

### model category

<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/014.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/015.png" >

### model constraint

<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/016.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/017.png" >

### model computed field
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/18.png" >

### model related model field
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/019.png" >

### model reference
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/020.png" >

### model inheritance
could not find change in database
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/021.png" >


### model abstract model
added active field in library_book
when clicked toggle button record disappear

### model inheritance delegation
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/022.png" >

### model methods and xml header buttons
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/023.png" >


### model methods error message
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/024.png" >

### model methods create records of other model
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/025.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/026.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/027.png" >

### model methods update records aka write
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/028.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/029.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/030.png" >

### model inheritance view and model
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/030.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/031.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/032.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/034.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/033.png" >

### module call with context
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/035.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/036.png" >



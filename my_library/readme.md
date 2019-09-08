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
```python
cost_price = fields.Float('Book Cost', digits=dp.get_precision('Book Price'))
```
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/011.png" >
### model relational fields
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/012.png" >

&lt;form&gt;
	&lt;group&gt;
		&lt;group&gt;
			&lt;field name="name"/&gt;
			&lt;field name="author_ids" widget="many2many_tags"/&gt;
			&lt;field name="state"/&gt;
			&lt;field name="pages"/&gt;
			&lt;field name="notes"/&gt;
			&lt;field name="cost_price"/&gt;
			&lt;field name="retail_price"/&gt;
			&lt;field name="currency_id"/&gt;
		&lt;/group&gt;
		&lt;group&gt;
			&lt;field name="short_name"/&gt;
			&lt;field name="publisher_id"/&gt;
			&lt;field name="date_release"/&gt;
			&lt;field name="date_updated"/&gt;
			&lt;field name="cover" widget="image" class="oe_avatar"/&gt;
			&lt;field name="reader_rating"/&gt;
		&lt;/group&gt;
	&lt;/group&gt;
	&lt;group&gt;
		&lt;field name="description"/&gt;
	&lt;/group&gt;
&lt;/form&gt;

<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/013.png" >
### model category

<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/014.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/015.png" >

### model constraint

<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/016.png" >
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/017.png" >

### model computed field
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/018.png" >

### model related model field
<img src="https://github.com/hanminghe/myodoo12tests/blob/master/img/019.png" >
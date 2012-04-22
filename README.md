iGEMsoft
========
The listing of iGEM Software division projects is on the web:
http://igem.synbioreview.com/

How it works:
-------------
.js eg "data.js" contains the listing of the data.

.html eg "index.html" is the template page

Exhibit 3.0 runs the JavaScript to display the page
see Exhibit 3.0 for generic docs: http://www.simile-widgets.org/exhibit3/

How to update
------------

1. Starting with the googlespreadheet iGEMSoftwareLinks https://docs.google.com/spreadsheet/ccc?key=0AkuvTGMlkqD1dFNUR1F0cGdzRmdyUFBfX0VXY3VhbVE
2. Remove the columns up to "year"
3. Find/Replace all \t <tab> chars
4. Put in the following as the header row: "year	team	label	description	category	url	update	status	contact	dependency	free"
5. Download as Text -this will make a tab separated value (TSV) file.
6. Use Babel http://service.simile-widgets.org/babel/ to convert to Exhibit JSON.
7. Replace all "\'" with "'", the "\" <escape> char is not needed and throws an error.  
8. Rename file to data.js and test the updated data

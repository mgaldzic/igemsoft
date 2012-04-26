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
2. Make a Copy - name using date. eg 20120425iGEMSoftwareLinks
3. Remove the 1st 2 columns, up to "year"
4. Sort (Range) by Description. This puts the rows with a description at the top.
5. Delete all rows without descriptions.
6. Find/Replace all \t, \<tab\>, "	" chars with a \<space\>, " ".
7. Put in the following as the header row, best to copy from another spreadsheet: "year	team	label	description	category	url	update	status	contact	dependency	free"
8. Download as Text -this will make a tab separated value (TSV) file.
9. Use Babel http://service.simile-widgets.org/babel/ to convert to Exhibit JSON.
10. Replace all "\'" with "'", the "\" \<escape\> char is not needed and throws an error. Eg in vi use: <code>:% s/\\'/'/g </code>
11. Test the new/updated data, submit pull request

Exhibit Refrence Docs
---------------------
http://simile-widgets.org/wiki/Reference_Documentation_for_Exhibit

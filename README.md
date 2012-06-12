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

1. Starting with the googlespreadheet iGEMSoftware https://docs.google.com/spreadsheet/ccc?key=0AkuvTGMlkqD1dGJoU2pGNmQwLTUyRmtwVmlrOEwxMWc
2. Make a Copy - name using date. eg 20120612iGEMSoftware
3. Find/Replace all \t, \<tab\>, "	" chars with a \<space\>, " ".
4. Download as Text - creates a tab separated value (TSV) file.
5. Use Babel http://service.simile-widgets.org/babel/ to convert to Exhibit JSON.
6. Replace all "\'" with "'", the "\" \<escape\> char is not needed and throws an error. Eg in vi use: <code>:% s/\\\'/'/g </code>
7. Test the new/updated data, submit pull request

Exhibit Refrence Docs
---------------------
http://simile-widgets.org/wiki/Reference_Documentation_for_Exhibit

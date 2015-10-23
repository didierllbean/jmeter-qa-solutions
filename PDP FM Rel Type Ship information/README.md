<h1>PDP FM Rel Type Ship information</h1>

Created for ticket like: https://jira.llbean.com:8443/browse/ECCR-36731
This can be used to test if any html content is in a page. How to use:
Download code and open it in JMeter. Clean the xml file and leave only two columns, and name them page and title. Replace every ocurrence of , with (.) a regex that means any symbol, once. Save it with any name with a .csv extension.
Go to JMeter, in Test Plan, go to CSV Data Set Config (double clicking on the left panel's icon) and change the name to the name you put to the .csv file.
Also, open the tab View Results Tree and put a name to the .xml output.

Click the run file, and wait until the stop button is disabled. Open the .xml file with a text editor, and start checking the links.
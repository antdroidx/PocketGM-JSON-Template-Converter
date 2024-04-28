This is a conversion tool to convert the In-Game created JSON file back to a format that can be edited in the Master Template for PocketGM 3

Step 1. Using the in-game editor, download the roster json file.

Step 2. Convert the JSON to CSV using an online tool  (https://www.convertcsv.com/json-to-csv.htm)

Step 3. Copy and paste the CSV data into the INPUT tab

Step 4. Go to the Convert Tab, and Copy and paste (as text!) everything from Column A to Column BL into the PGM Master Template spreadsheet. Copy it into the INPUT tab there!

Step 5. The potential value is not copied over. This requires some user input. I recommend using the following formula:=IFERROR(INT(IF(E6<27,RANDBETWEEN(0,((224-W6)/4)^0.8/(27-E6))+RANDBETWEEN(0,(V6-2018)),0)),0)

This will give a randomized potential rating based on age and draft class. (2018 is the year where potential starts to slow down ~recommend using 5 years from date)

Step 6. Make edits as desired in the INPUT tab!

Step 7. Export the OUTPUT tab of the Template to CSV and use https://www.convertcsv.com/csv-to-json.htm to convert back to a JSON file that can be used in the game!

Antdroid - 04-28-2024


# Final-Project-Part2
You will design a program that manages the inventory of an electronics store. You will need to use a number of concepts that you learned in class including: use of classes, use of dictionaries and input and output of comma delimeted csv files. Input: a) ManufacturerList.csv -- contains items listed by row. Each row contains item ID, manufacturer name, item type, and optionally a damaged indicator b) PriceList.csv -- contains items listed by row. Each row contains item ID and the item price. c) ServiceDatesList.csv â contains items listed by row. Each row contains item ID and service date. Example ManufacturerList.csv, PriceList.csv and ServiceDatesList.csv are provided for reference. Your code will be expected to work with any group input files of the appropriate format. Manufacturers can and will likely be different as will the items. You can reuse parts of your code from Part 1.
CIS 2348, Spring 2021
Final Project Part2
You will design a program that manages the inventory of an electronics store. You will need to use a
number of concepts that you learned in class including: use of classes, use of dictionaries and input and
output of comma delimeted csv files.
Input:
a) ManufacturerList.csv -- contains items listed by row. Each row contains item ID,
manufacturer name, item type, and optionally a damaged indicator
b) PriceList.csv -- contains items listed by row. Each row contains item ID and the item price.
c) ServiceDatesList.csv â contains items listed by row. Each row contains item ID and service
date.
Example ManufacturerList.csv, PriceList.csv and ServiceDatesList.csv are provided for reference. Your
code will be expected to work with any group input files of the appropriate format. Manufacturers can
and will likely be different as will the items.
You can reuse parts of your code from Part 1.
Required Output:
1) Interactive Inventory Query Capability
a. Query the user of an item by asking for manufacturer and item type with a single query.
i. Print a message(âNo such item in inventoryâ) if either the manufacturer or the
item type are not in the inventory, more that one of either type is submitted or
the combination is not in the inventory. Ignore any other words, so ânice Apple
computerâ is treated the same as âApple computerâ.
ii. Print âYour item is:â with the item ID, manufacturer name, item type and price
on one line. Do not provide items that are past their service date or damaged. If
there is more than one item, provide the most expensive item.
iii. Also print âYou may, also, consider:â and print information about the same item
type from another manufacturer that closes in price to the output item. Only
print this if the same item from another manufacturer is in the inventory and is
not damaged nor past its service date.
iv. After output for one query, query the user again. Allow âqâ to quit.
Commit all your .py files on Github. Provide a link on BlackBoard. Name all your files with the starting
pharase âFinalProjectâ for example FinalProjectInput.py
Comment your code extensively. Include comment block with your name and student ID at the top of
every .py file.
Presentation:
You have to create a short presentation of your project: maximum 3 minutes.
Describe your approach and the structure of your code (including your choices) for both Class Projects
Part 1 and 2.
1) Create a PowerPoint (maximum 4 slides)
2) Add voice over comments to each slide
3) Save as a video (MP4)
4) Upload to Microsoft STREAM (you need to login with your UH account)
5) Give access to everybody
Provide the link to your video on BlackBoard

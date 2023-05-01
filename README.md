Download Link: https://assignmentchef.com/product/solved-cis355a-lab-4
<br>
<p class="ui header product-top-header" title="CIS355A Lab 4 Solution">Objective/Purpose of the program

Stocks4U needs to develop an app for you to manage your stock purchases.You should be able to store a list of stock purchases, view the individual stocks, add and remove stocks.

You can code the GUI by hand or use NetBeans GUI builder interface.

The GUI should have two tabs usingJTabbedPane.

·         One tab (“Show stocks”) should have

o   a JList to display all the stock purchases;

o   a text field or label to display information about a particular stock; and

o   a JButton to remove a stock.

·         One tab (“Add stock”) should have textboxes, labels, and a button to input a stock.

Create a Stock class to manage the stock activity. It should have private instance variables of

·         company name;

·         number of shares;

·         purchase price; and

·         current price.

Create a default and parameterized constructor.

Create sets/gets for all instance variables.

Create a get method to calculate and return the profit or loss. This would be calculated as

Number of shares * (current price – purchase price).

Create toString to display the name of the stock.

As you add stocks, they are displayed in the JList.

If you select an element in the JList, the gain or loss is displayed in the label or text field.

If you select an element in the JList and click Remove, the stock is removed from the list.

Analysis/Design

Describe the approach/structure of program.What classes/functions were used?

Two class:

·         Stock

·         StockGUI

Describe classes and funcstions:

Class Stock

–          companyName

–          numberShares

–          currentPrice

–          purchasePrice+    getCompanyName()

+    setCompanyName(name)

+    getNumberShares()

+   setNumberShares(n)

+   getCurrentPrice()

+   setCurrentPrice(cPrice)

+   getPurchasePrice()

+  setPurchasePrice(price)

+  toString()

+   getValue()

Class StockGUI

+   removeStockClick()

+   addStockClick()

+  showListStock()

Testing/Results

Does your program satisfy all requirements of the lab?

If yes, how did you test it? Indicate test cases used, expected values, and show results with screen shots.  For example:

CaseDescriptionTest DataExpected ResultActual Result1Test  calculate profit or lossName: Intel

Quantity: 1

Current Price: 100

Purchase Price: 80Loss of -20Loss of -202Test remove stockStock List: Intel, Apple, Microsoft

Remove AppleStock List: Intel, McrosoftStock List: Intel, Mcrosoft3Test  add stockStock List: Intel, Apple, Microsoft

Add Amazon stockStock List: Intel, Apple, Microsoft, Amazon

Stock List: Intel, Apple, Microsoft, Amazon

4Test valid dataStock price 123aaHandle the error: Invalid numberError: Invalid input data

If any requirements are NOT met, document the known issues. What did you do to try to solve them?

Make sure you demonstrate in your testing the parts that are working correctly.

5/5 - (5 votes)
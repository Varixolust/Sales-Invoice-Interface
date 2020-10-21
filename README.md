# Sales-Invoice-Interface
Use Java Swing application to design this


Requirements


Sales Interface:
Upon successful login, the user can then use the Sales interface to record sales and generate receipt for
the customer. Study the sample interface given – you may change the design but ensure that all
information given is in your interface.
1 | P a g e
Tilly’s Bakery has just opened up so she sells only five items at the moment. The sales person will enter
only the 5 x item codes (1001,1002,1003....) and quantity (5x blank JTextboxes). Your program must read the item code and apply the correct rate to
calculate the amount due for each item. The item code and the quantity must be stored in two
ArrayLists.
A customer may purchase less than 5 items – so some textboxes may be empty, ensure that you
encounter for this scenario and provide relevant error handling so that all transactions are successful.
Once the user clicks on the Show SubTotals button – the total amount to be paid by the customer is
displayed as shown below:
2 | P a g e
The salesperson then enters the amount given by the customer and clicks on the Checkout button –
which then generates the receipt showing the details of the transaction as shown below.
Some things to note:
 Ensure that all monetary values are formatted to 2 decimal places
 To format the output in the text area use: String.format(),
System.getProperty("line.separator"), jtextarea.append() funtions.
 When doing string comparisons use the equals() function:
boolean isstrequal = string1.equals(string2);
3 | P a g e
 Ensure that your program can validate user input.
 Implement try…catch block to cater for exception-handling

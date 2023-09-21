# How to add leading zeros in excel numerical column?

Let say you are getting a csv file with numerical column with 10 digit number. If you are opening the file in excel, Voila for some rows of the numerical column you are able to see less than 10 digits. <br>
This is because in csv the all columns are text by default, by opening it in excel it will convert the strings(texts) so to avoid this you can use power query to open the same file in excel without changing the types of the column.

Else you can also add a use a text formula as below: <br>
```=Text(A2,"0000000000")```

This will add the leading zeros for that numerical column.

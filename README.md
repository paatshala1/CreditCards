# CreditCards
To automate the credit cards processing (from pdf, through xls and xmls to validation)

The proccess begins with the bank statement, it's a pdf file, so it must be read and converted into a table (using Pandas); after that it's necesary to read each expenses report and its invoices.

With all this information we validate:
1. The expenses report versus the bank statement
2. The expenses report versus the invoices received

Finally, some Excel files are created to review the results

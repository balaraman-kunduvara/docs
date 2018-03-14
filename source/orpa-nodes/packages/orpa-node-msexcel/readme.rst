
Opens an xlsx or xls file spreasheet from a specified location and reads
the contents. The contents can then be passed to downstream node or
saved to a store variable

**Inputs:**

-  Name: A Name for this read-excel instance
-  File Path: choose the location from where the spreadsheet can be read
-  Sheet: specify the name of the sheet to be read (E.g. Sheet 1)
-  Read Mode: specify the mode used for reading. This can be Full
   Content,Rows,Colummns,Region

   -  **Full Contents** - Fetches the entirer contents of the specified
      sheet
   -  **Rows** - A comma separated list of Numbers of the Rows that are
      to be fetched.
   -  **Columns** - A comma separated list of Names(e.g. A, B, AA etc)
      of the columns that are to be fetched
   -  **Region** - A region notation as deinfed by this MSDN article
      (`Range Notation<`_). Only single range expression is supported.

-  Output Formats: The output of the read operation can be a Simple JSON
   (Array of Arrays or Colmn Header indexed objects) with only the data
   or a more descriptive format. Details can be found from the xlsx
   project

   -  **As Json** - Uses the simple JSON format
   -  **Use Column Labels** - Use column headers such A,B etc to index
      the data rather using Array of Array. Only for JSON mode
   -  **Remove Empty Rows** - Removes Empty Rows fromm a JSON output.
      Only for JSON mode

-  Timeout: specify the timeout during lookup for the title operation.

**Outputs:**

``msg.error`` When an error happens contains the error message from
underlying Excel reading

``msg.payload`` contains the data read from spreadsheet

.. _Range Notation<: https://msdn.microsoft.com/en-us/library/bb211395(v=office.12).asp

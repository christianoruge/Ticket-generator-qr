# Ticket-generator-qr

This app creates tickets with a qr-code for text-output.

You need: 
- An png image file for the tickets. Format should be 4:3.
- A xlsx or csv list of participants. Columns should be 1: ID/Nr, 2: Date, 3: Full name and 4: Ticket category. 
- A thought on which text to be displayed when scanned. The following codes can be placed inside the text: {date} = date, {billettnummer} = ID/nr, {navn} = full name, {billettype} = ticket category and {ls} = new line. 

Exports are: 
- A folder called "QR-koder", containing all QR-codes as image files
- A folder called "Billetter", containing all tickets as pdf-files
- An Excel-file called "Bestillingsliste" with all participants, and a column to make comments, i.e. mark at arrival.

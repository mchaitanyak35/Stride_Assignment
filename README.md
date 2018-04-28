# Stride_Assignment
Assignment as the second round of screening process

1. Information extraction from PDF documents. There are 4 PDF documents in the zip file which are stock contracts used in banks. You need to build an NLP based IE system which can extract the following information from the document. There is a subsection called 'Rounding' in 'Paragraph 11: Elections and Variables' section. You need to extract


Currency
Amount
Rounding (up / down/ nearest) If not mentioned, take it as 'nearest' by default.

for 'Delivery Amount' and 'Return Amount'.

Eg: In the file '16017sec.pdf' here are the values.

Delivery Amount: Currency: USD  Amount: 10,000  Rounding: up

Recall Amount: Currency: USD  Amount: 10,000  Rounding: down

 A few pointers on this problem


·      Do not process PDF directly. Use some third party tools to convert it to text.
·      Some strings can be uniquely identified in the text. Use that to narrow down search space.
·      Look into POS tagging and Named Entity Recognition. These NLP techniques which will be helpful to crack this problem.

2. Identify noun phrases from given input text. The bold part in the below text are noun phrases
Eg: Today is a very great day. Indian politicians are very corrupt.
The algorithm should take text as input and return noun phrases as output.

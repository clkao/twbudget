#
#### parser for Taiwan Central Government Budget spreadsheet

Install livescript:

   npm i -g LiveScript

Download raw data from http://www.dgbas.gov.tw/ct.asp?xItem=26269&CtNode=5389&mp=1
convert to csv, and do:

    livescript parse.ls --file input.csv --year 2013 > output.csv


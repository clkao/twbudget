#
#### parser for Taiwan Central Government Budget spreadsheet

Install livescript:

   npm i -g LiveScript

Download raw data from http://www.dgbas.gov.tw/ct.asp?xItem=26269&CtNode=5389&mp=1
(look for 歲出機關別 預算表 Excel)
convert to csv, and do:

    lsc parse.ls --file input.csv --year 2013 > output.csv


## License

CC0

Use parse_ar.ls for 歲入預算表


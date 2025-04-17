# ZPL Label definition files

## Label Template

ZPL is a Zebra Printing Language definition files, that can be stored in the Zebra Label printers.

## Printing

Once stored in the Zebra Label Printer, can print only sende the variables defined in the template file.

## Usage

/script contains shell scripts to print the label, send the printer name, label quantity and data as parameters.
copy the scripts to /usr/local/bin/


---

cp printlabel10 /usr/local/bin/
printlabel10 [PRINTER] [UPCEAN] [SKU] [PRODUCTNAME] [SHIPMENT] [SHIPMENTLINE] [MATCH RULE] [QUANTITYLINE] [QUANTITY]
---

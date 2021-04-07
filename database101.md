# Database 101

I will try to organize my way of unifying datas to upload on our lab's database. this is my idea for now, so it could be updated at any time.



---

## 1. Look for the columns that could be unified.

When we recieve 2 or more datasheets, the first thing we should do is to look for similar or identical columns that could be sorted under a same column. 



| name  | age  | country |
| ----- | ---- | ------- |
| Sam   | 18   | Korea   |
| Anne  | 28   | US      |
| Chris | 20   | Russia  |

| name  | age  | city    |
| ----- | ---- | ------- |
| Henry | 30   | Daegu   |
| June  | 21   | Boston  |
| Gary  | 33   | Chicago |

For the 2 sheets above, we could refine the city and country columns into country and unify the column.



 ## 2. Barcoding data

When organizing data, we need to assign unique names or **barcodes** to individual data so we could identify each data. You could orgnize the barcodes by your own standards(if you have), but these barcodes must be included:

1. Aliquote barcode: barcode for every single aliquote
2. Sample barcode: barcode for tumor samples 
3. File barcode: barcode for unique data files(usually use md5 info)
4. Patient barcode: barcode for every patient

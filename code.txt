
# create  Good and service tax (GST) calculator.


CP = float(input('Enter the cost of the Product: '))
CGST = float(input('Enter tax % imposed by center, CGST: '))
SGST = float(input('Enter tax % imposed by state, SGST: '))
total = 0 
Amount_CGST = ((CGST/100) * CP)
Amount_SGST = ((SGST/100) * CP)
total = CP + Amount_CGST +Amount_SGST
print('Total cost of product: Rs ',total)


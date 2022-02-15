## intent:greet
- hello
- hi
- ad
- hey

## intent:inform
- số điện thoại của mk là [0962882084](phone_number)
- sđt [0363733398](phone_number)
- tên của mình là [nguyễn đình phương](name)
- mình tên là [Nguyễn Văn B](name)
- [Bành Thị La](name)
- [0333580303](phone_number), đây là sđt của mình
- địa chỉ là [124 trần đại nghĩa](address), ngay sau bưu điện [hà nội](locations)
- mình ở [124 hoàng quốc việt](address)
- [23A lê thanh nghị](address)
- [13a giải phóng](address) ở gần bến xe [giáp bát](locations)

## regex:phone_number
- [0-9]{10}

## regex:name
- [a-zA-Z\s]+

## regex:address
- [0-9a-zA-Z]{1,10}.+

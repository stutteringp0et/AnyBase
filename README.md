Create a base numbering system to meet your needs.  

Designed to create short urls based on a decimal id number - the default charset contains the unreserved URL characters and is good up to base65. 

Using AnyBase is simple.  Simply, initialize an object with or without a charset and use it to encode or decode a number.

'''
$b65 = new AnyBase();
$original = 1000000;
$encoded = $b65->encode($original); // '3FIE'
$decoded = $b65->decode($encoded); // 1000000
'''

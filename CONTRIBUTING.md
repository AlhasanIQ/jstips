## #1 - String to Number transformation
> date 12/31/2015 by @alhasaniq

When you want to convert a string to a number ( Integer / Flaot )

Use ` "1234" *1 ` instead of ` Number( "1234" ) ` or ` parseInt( "1234" ) ` or ` parseFloat( "1234" ) ` .. why ? :

1. you wont have to worry about the number type (int/float)

2. it is slightly faster ( dont believe me ? ask [jsperf](http://jsperf.com/string-to-integer-transformation) ). 

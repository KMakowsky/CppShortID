**C++ ShortID**<br/>
===========<br/>
**Create Youtube-Like IDs With PHP/Python/Javascript/Java/SQL and NOW also with C++**<br/>
For more infos visit:<br/>
http://kvz.io/blog/2009/06/10/create-short-ids-with-php-like-youtube-or-tinyurl/<br/>
<br/>
Thanks to **Kevin van Zonneveld** who published the original PHP Version of the algorithm.

```cpp
string ShortID::Encode(9007199254740989); //returns FpGNnX2Ef
long ShortID::Decode("FpGNnX2Ef"); //returns 9007199254740989
```

* Non-numbers return an error
```
"potato" >> "potato no, YOU deal with this"
```
* Mixed numbers and non-numbers filter to the numbers only
```
POTATO 55 >> evaluated as 55
```
* If value equals the value of a symbol, return the symbol
```
" 5 >> V"
```
* Values equaling sum of any combination of symbols (one of each) returns the symbols in order of descending value.
```
16 >> XVI
```
* Value is subtracted by adding an element out of order of descending value of symbols.
```
4 >> IV
```
* Fewest number of symbols are returned
```
4 >> IV
NOT
4 >> IIII
16 >> XVI
NOT
16 >> IIIIXX
```
* Multiple symbols within descending value order add values together.
```
25 >> XXV
```

# digit_to_word

Convert an `int` to a `String` representing the english words for said number.

#### Example
```
1 -> one
25 -> twenty-five
857 -> eight hundred fifty-seven
43021 -> forty-three thousand twenty-one
```

## Getting Started

Install the package then simply call `DigitToWord.translate(11345)`

#### Example
```dart
var num = 954;
var numberAsString = DigitToWord.translate(num);
print(num) /// nine hundred fifty-four
```

**Note**: This package maxes out at billions. Anything over 999,999,999,999 will return an error message. 
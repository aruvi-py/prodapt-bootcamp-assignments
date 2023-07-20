# ASSIGNMENT 03.01
## Roman to Hindu-Arabic
Write a java function that converts an input of type String that contains a roman numeral to an integer in its Hindu-Arabic form.

### CodeRunner: Pre-filled code

```
class Solution {
	public static int toHinduArabic(String roman) {
		//your code here
	}
}
```

### Test Cases
---------------
|Input | Expected output|
|------|----------------|
|`System.out.println(Solution.toHinduArabic("III"));` | 3|
|`System.out.println(Solution.toHinduArabic("XXVII"));` | 27|
|`System.out.println(Solution.toHinduArabic("LVIII"));` | 58|
|`System.out.println(Solution.toHinduArabic("CXXIII"));` | 123|
|`System.out.println(Solution.toHinduArabic("DCXLI"));` | 641|
|`System.out.println(Solution.toHinduArabic("CCCXLIII"));` | 343|
|`System.out.println(Solution.toHinduArabic("MMMDCCXXIV"));` | 3724|
|`System.out.println(Solution.toHinduArabic("MMMMMCDLXIX"));` | 5469|





# ASSIGNMENT 03.02
## Hindu-Arabic to Roman
Write a java function that converts an input of type int and returns a String that contains its Roman numeral representation.

### CodeRunner: Pre-filled code

```
class Solution {
	public static int toRoman(int hinduArabic) {
		//your code here
	}
}
```

### Test Cases
---------------
|Input | Expected output|
|------|----------------|
|`System.out.println(Solution.toHinduArabic(27));` | XXVII|
|`System.out.println(Solution.toHinduArabic(64));` | LXIV|
|`System.out.println(Solution.toHinduArabic(544));` | DXLIV|
|`System.out.println(Solution.toHinduArabic(697));` | DCXCVII|
|`System.out.println(Solution.toHinduArabic(177));` | CLXXVII|
|`System.out.println(Solution.toHinduArabic(499));` | CDXCIX|
|`System.out.println(Solution.toHinduArabic(8726));` | MMMMMMMMDCCXXVI|
|`System.out.println(Solution.toHinduArabic(6399));` | MMMMMMCCCXCIX|




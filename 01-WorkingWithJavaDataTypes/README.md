# Working with Java data types
## Use primitives and wrapper classes, including, operators, parentheses, type promotion and casting
### Primitive data types
| Data type | Size | Description|
| --- | --- | --- |
|`char`| 2 bytes | Stores a single character/letter or ASCII values |
|`byte`| 1 bytes | Stores whole numbers from -128 to 127 |
|`short`| 2 bytes | Stores whole numbers from -32,768 to 32,767 |
|`int`| 4 bytes | Stores whole numbers from -2,147,483,648 to 2,147,483,647 |
|`long`| 8 bytes | Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |
|`float`| 4 bytes | Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits |
|`double`| 8 bytes | Stores fractional numbers. Sufficient for storing 15 decimal digits |
|`boolean`| 1 bit | Stores true or false values |

Examples:
```java
char letter = 'a';
byte myByte = 100;
short myShort = 5000;
int myInt = 2548752;
long myLong = 45487841235754L; // The value must end with 'l' or 'L'
float myFloat = 1548.45478F; // The value must end with 'f' or 'F'
double myDouble = 5457.4578452121548D; // The value must end with 'd' or 'D'
boolean myBoolean = true; // false
```

#### Primitive number types are divided into two groups:

**Integer types** stores whole numbers, positive or negative (such as 123 or -456), without decimals. Valid types are `byte`, `short`, `int` and `long`. Which type you should use, depends on the numeric value.

**Floating point types** represents numbers with a fractional part, containing one or more decimals. There are two types: `float` and `double`.

#### Use float or double?
The **precision** of a floating point value indicates how many digits the value can have after the decimal point. The precision of `float` is only six or seven decimal digits, while `double` variables have a precision of about 15 digits. Therefore it is safer to use `double` for most calculations.

#### Scientific Numbers
A floating point number can also be a scientific number with an "e" to indicate the power of 10:

```java
float f1 = 35e3f;
double d1 = 12E4d;
```

---

## Handle text using String and StringBuilder classes

---

## Use local variable type inference, including as lambda parameters

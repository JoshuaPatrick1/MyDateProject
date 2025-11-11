-------------------------
MyDate
-------------------------
- year: int
- month: int   // 0-based (0 = January)
- day: int
-------------------------
+ MyDate()                     // no-arg constructor
+ MyDate(elapsedTime: long)    // constructor with milliseconds
+ MyDate(year: int, month: int, day: int) // constructor with fields
+ getYear(): int
+ getMonth(): int
+ getDay(): int
+ setDate(elapsedTime: long): void
-------------------------

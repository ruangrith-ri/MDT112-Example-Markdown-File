# MDT112 Project:Smart farm
For MDT112 Student

## Header
ชื่อ นางสาว อารียา จิรพงษ์สวัสดี ชื่อเล่น แพร รหัสนักศึกษา 60080501622 Gitgub Profile link PearAreeya
ชื่อ นางสาว อิสรียากร เพ็ชรวงศ์ ชื่อเล่น มาย รหัสนักศึกษา 60080501623 Gitgub Profile link mindblrr
ชื่อ นางสาว ปีย์รดา อินทรโชติ ชื่อเล่น เนย รหัสนักศึกษา 61080501612 Gitgub Profile link Noeypeerada
## รายละเอียดโปรเจค
Smart farm ประดิษฐ์เป็นโมเดลขึ้นมาเสหมือนจริง จะเป็นฟาร์มที่มี led แสดงสถานะความชื้น
ถ้าร้อนหลอดไฟที่ติดก็จะเป็นสีแดง ถ้าเย็นก็สีน้ำเงิน และถ้าปกติสีเขียว
วัดอุณหภูมิความชื้นด้วย DHT22 แสดงผลผ่านหน้าจอLCD แสดงค่าว่าตอนนี้ความชื้นเท่าไหร่
ถ้าร้อนเกินไปจะระบายความร้อนด้วยพัดลมระบายอากาศ 
ตรวจจับควันด้วย MQ-2 มีbuzzer เตือนถ้ามีควันเกินกำหนดตรวจจับควันได้ด้วย

## Lists

1. First ordered list item
2. Another item

* Unordered list can use asterisks
- Or minuses
+ Or pluses
+ pluses

## Link

[reference](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Image

![alt text For Logo 1][logo]

![alt text For Logo 2][logo]

[logo]: https://github.com/ruangrith-ri/MDT112-Example-Markdown-File/blob/master/images/icon48.png "Logo Title Text"

## Code and Syntax Highlighting

Inline `code` has `back-ticks around` it.

### C Example

```c
int main() {
  int y = SOME_MACRO_REFERENCE;
  int x = 5 + 6;
  cout << "Hello World! " << x << std::endl();
}
```

### C++ Example

```cpp
int main() {
  int y = SOME_MACRO_REFERENCE;
  int x = 5 + 6;
  cout << "Hello World! " << x << std::endl();
}
```

## Table

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

## Blockquotes

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

> Blockquotes are very handy in email to emulate reply text
> This line is part of the same quote.

Quote break.

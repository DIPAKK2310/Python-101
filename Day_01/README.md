# Mutable & Immutable
🟩 Mutable Data Types in Python

These can be changed:

| Type | Example | Notes |
|:---|:---:|---:|
|list |	[1, 2, 3]|	you can push, pop, change items
| dict (dictionary)	| {"a": 1}	|change keys/values
|set	|{1, 2, 3}	|add/remove values
|bytearray	|bytearray(b"abc")	|used in low-level stuff
---
```bash
    a = [1, 2, 3]
    a[0] = 100
    print(a)   # [100, 2, 3]

```

🟩 Immutable Data Types in Python

These can be changed:

|Type | Example | 
|:--- |:---: |
|int  |	10  |
|float | 10.5	|
|bool |"Dipak" |	
|str(string)| bytearray(b"abc") |
|tuple	|(1, 2, 3)|
|frozenset	|frozenset({1,2,3})|
|bytes	|b"abc"|
|NoneType	|None|

## It cannot change 
```bash
 name = "Dipak"
 name[0] = "A"   # ❌ Error → strings cannot be     changed
 
```
## If you do
```bash
name = "Dipak"--->old string
name = "Akash"---> it creates new string 
```

# 🎯 Quick Trick to Remember
If it has curly braces {} or square brackets [] → mutable

- list → [ ]

- dict → { key: value }

- set → {1, 2, 3}

If it uses normal values or round brackets ( ) → immutable

- int, float, bool

- string " "

- tuple ( )
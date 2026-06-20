# JavaScript String Methods

String methods JavaScript me text (string) ko manipulate karne ke liye use hote hain.

## 1. length
String ki length batata hai.

```js
let str = "Nishant";
console.log(str.length);
```

**Output:**
```
7
```

---

## 2. toUpperCase()
String ko uppercase me convert karta hai.

```js
let str = "nishant";
console.log(str.toUpperCase());
```

**Output:**
```
NISHANT
```

---

## 3. toLowerCase()
String ko lowercase me convert karta hai.

```js
let str = "NISHANT";
console.log(str.toLowerCase());
```

**Output:**
```
nishant
```

---

## 4. charAt()
Kisi specific index ka character return karta hai.

```js
let str = "Nishant";
console.log(str.charAt(2));
```

**Output:**
```
s
```

---

## 5. indexOf()
Character ya word ka first index return karta hai.

```js
let str = "JavaScript";
console.log(str.indexOf("S"));
```

**Output:**
```
4
```

---

## 6. includes()
Check karta hai ki string me value hai ya nahi.

```js
let str = "JavaScript";
console.log(str.includes("Script"));
```

**Output:**
```
true
```

---

## 7. startsWith()
Check karta hai string kis word se start ho rahi hai.

```js
let str = "JavaScript";
console.log(str.startsWith("Java"));
```

**Output:**
```
true
```

---

## 8. endsWith()
Check karta hai string kis word se end ho rahi hai.

```js
let str = "JavaScript";
console.log(str.endsWith("Script"));
```

**Output:**
```
true
```

---

## 9. slice()
String ka kuch part nikalta hai.

```js
let str = "JavaScript";
console.log(str.slice(0, 4));
```

**Output:**
```
Java
```

---

## 10. replace()
String ke kisi part ko replace karta hai.

```js
let str = "Hello World";
console.log(str.replace("World", "Nishant"));
```

**Output:**
```
Hello Nishant
```

---

## 11. trim()
Extra spaces remove karta hai.

```js
let str = "   Hello   ";
console.log(str.trim());
```

**Output:**
```
Hello
```

---

## 12. split()
String ko array me convert karta hai.

```js
let str = "HTML,CSS,JS";
console.log(str.split(","));
```

**Output:**
```js
["HTML", "CSS", "JS"]
```

---

## 13. concat()
Do strings ko jodta hai.

```js
let first = "Hello";
let second = " Nishant";

console.log(first.concat(second));
```

**Output:**
```
Hello Nishant
```

---

## 14. repeat()
String ko multiple times repeat karta hai.

```js
let str = "Hi ";
console.log(str.repeat(3));
```

**Output:**
```
Hi Hi Hi
```

---

## 15. substring()
String ka specific part return karta hai.

```js
let str = "JavaScript";
console.log(str.substring(0, 4));
```

**Output:**
```
Java
```

---

# Summary

| Method | Use |
|----------|----------|
| length | Length find karne ke liye |
| toUpperCase() | Uppercase me convert |
| toLowerCase() | Lowercase me convert |
| charAt() | Character find |
| indexOf() | Index find |
| includes() | Value check |
| startsWith() | Start check |
| endsWith() | End check |
| slice() | Part nikalna |
| replace() | Replace karna |
| trim() | Spaces remove |
| split() | Array banana |
| concat() | Strings jodna |
| repeat() | Repeat karna |
| substring() | Part nikalna |

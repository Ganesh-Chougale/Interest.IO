`https://fsymbols.com/draw/`  


### 🥉 1. [ASCII Art](w) – **Most Basic**

**Definition:** Art made using **only characters from the ASCII standard (0–127)**
Examples: A-Z, a-z, 0-9, basic symbols like `@`, `#`, `/`, `\`, `|`, etc.

#### Example:

```
 /\_/\  
( o.o ) 
 > ^ <
```

#### ✅ Pros:

* Works on **any terminal/editor**
* **Lightweight**
* Extremely **compatible**

#### ❌ Cons:

* **Limited characters = limited detail**
* No color, no shading

---

### 🥈 2. [Monospace Art](w)

**Definition:** Any text art aligned properly using **monospace fonts** (each char takes equal width). It can be ASCII or Unicode.

#### Example:

*(Same as ASCII if only basic chars used)*

```
 /\_/\  
( o.o ) 
 > ^ <
```

#### ✅ Pros:

* Allows **clean layout**
* Works across **dev environments**
* Keeps code-art **well-aligned**

#### ❌ Cons:

* Still **visually limited** if not using extended characters
* **Font-dependent** layout

---

### 🥇 3. [ANSI Art](w)

**Definition:** Extension of ASCII art using **ANSI escape codes** for **color**, **positioning**, etc. Used in BBS (80s–90s).

#### Example: *(Simulated with color tags, actual output needs terminal)*

```terminal
[31m /\_/\ [0m  
[32m( o.o )[0m  
[34m > ^ < [0m
```

#### ✅ Pros:

* **Colored output**
* Retro feel, works in **old-school terminals**
* Custom cursor, effects

#### ❌ Cons:

* Needs ANSI-compatible terminal
* **Harder to read** raw
* Code becomes **cluttered**

---

### 🏆 4. [Unicode Art](w) – **Most Advanced**

**Definition:** Uses **all Unicode characters** including block elements, emojis, math symbols, lines, etc.

#### Example:

```
ᓚᘏᗢ
```

or more elaborate:

`````
 ／ﾌﾌ 　　　　　 ム｀ヽ  
/ ノ)　　 ∧　　）　ヽ  
/ ｜　　(´・ω・`）ノ⌒(ゝ._,ノ  
/　ﾉ⌒7⌒ヽーく　 ＼　／  
丶＿ ノ　　 ノ､　　|　|  
　　 `ヽ `ー-'_人`ー'ﾉ  
　　　　￣````　````  
`````

#### ✅ Pros:

* **High detail**, expressive
* Can use **emoji, lines, math**
* Great for **modern terminals**

#### ❌ Cons:

* **Not supported in old editors**
* Misaligned if **font isn't monospace**
* Some symbols don't display everywhere

---

### 📊 Summary Table

| Feature        | ASCII Art   | Monospace Art   | ANSI Art           | Unicode Art      |
| -------------- | ----------- | --------------- | ------------------ | ---------------- |
| Char Set       | Basic (127) | Any (monospace) | ASCII + ANSI codes | All Unicode      |
| Colors         | ❌           | ❌               | ✅                  | ✅ (emoji/blocks) |
| Font Dependent | ❌           | ✅               | ✅                  | ✅✅✅              |
| Compatibility  | ✅✅✅         | ✅✅              | ❌                  | ❌                |
| Detail Level   | ❌           | ❌               | ✅                  | ✅✅✅              |
| Terminal Use   | ✅           | ✅               | ✅                  | ✅ (modern only)  |

---

### 🎯 TL;DR

* Use **ASCII** for max compatibility.
* Use **Monospace** for clean layout.
* Use **ANSI** for retro color effects.
* Use **Unicode** for expressive, modern art.
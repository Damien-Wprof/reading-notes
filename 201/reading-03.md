#  Readings: HTML Lists, Control Flow with JS, and the CSS Box Model

---

## 🧱 Learn HTML

### ❓ When should you use an unordered list in your HTML document?
Use an unordered list when you need to present a list of items and the order does **not** matter.

---

### ❓ How do you change the bullet style of unordered list items?
By using the `list-style-type` CSS property.

---

### ❓ When should you use an ordered list vs an unordered list?
Use an **ordered list** when the sequence of items matters.  
Use an **unordered list** when it does not.

---

### ❓ Describe two ways you can change the numbers on list items in an ordered list
You can change numbering by setting the `type` attribute, such as:
- `1` (default)
- `a` / `A`
- `i` / `I`

---

## 🎨 Learn CSS

### ❓ Describe margin and padding as characters in a story  
**_“The Box Model”_**

- **Margin** is the legendary knight guarding the **outside** of the border.
- **Padding** is the legendary knight protecting the **inside** of the border.

Margin controls space outside the element, while padding controls space between the content and the border.

---

### ❓ List and describe the four parts of the box model
1. **Content** – The actual text or image
2. **Padding** – Space between content and border
3. **Border** – The outline around padding and content
4. **Margin** – Space outside the border

---

## 🧠 Learn JavaScript

### ❓ What data types can you store inside of an array?
An array can store **any data type**, including numbers, strings, booleans, objects, and even other arrays.

---

### ❓ Is the `people` array valid? How do you access its values?

```js
const people = [
  ['pete', 32, 'librarian', null],
  ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'],
  ['bill', null, 'artist', null]
];
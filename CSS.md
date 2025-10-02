# 🌐 **CSS Topics List (with Use Cases)**

### **1. CSS Basics**

* **Selectors** → किस element पर style लगाना है (`h1`, `.class`, `#id`)
* **Properties & Values** → क्या style लगाना है (`color: red;`)
* **Colors & Backgrounds** → element को रंग, image, gradient देना

👉 **Use case:** Text color change करना, background image लगाना।

---

### **2. CSS Box Model**

* **Content, Padding, Border, Margin**
* **Box-sizing: border-box**

👉 **Use case:** Proper spacing देना elements के बीच।

---

### **3. CSS Units**

* **Absolute Units**: px, cm, in
* **Relative Units**: %, em, rem, vh, vw

👉 **Use case:** Responsive design बनाना (screen size के हिसाब से)।

---

### **4. Typography**

* **Fonts** (font-family, font-size, font-weight, line-height)
* **Text styling** (color, text-align, text-transform, text-shadow)

👉 **Use case:** Attractive headings, paragraphs readable बनाना।

---

### **5. Colors & Gradients**

* Color formats → HEX, RGB, HSL
* Gradients → linear, radial

👉 **Use case:** Button, backgrounds attractive बनाना।

---

### **6. CSS Display & Visibility**

* `block`, `inline`, `inline-block`
* `none`, `visibility: hidden`

👉 **Use case:** Element कैसे दिखेगा या छुपेगा।

---

### **7. Positioning**

* `static`, `relative`, `absolute`, `fixed`, `sticky`

👉 **Use case:** Header fix करना, tooltip place करना।

---

### **8. Flexbox (1D Layout)**

* `display: flex`
* `justify-content`, `align-items`, `flex-wrap`, `gap`

👉 **Use case:** Navbar, button group, cards row।

---

### **9. Grid (2D Layout)**

* `display: grid`
* `grid-template-rows/columns`, `grid-area`, `gap`

👉 **Use case:** Page layout, dashboard, gallery।

---

### **10. CSS Sizing**

* `width`, `height`, `min/max-width`, `min/max-height`

👉 **Use case:** Container को fixed / responsive size देना।

---

### **11. Borders & Shadows**

* `border`, `border-radius`
* `box-shadow`, `text-shadow`

👉 **Use case:** Buttons, cards attractive बनाना।

---

### **12. Backgrounds**

* `background-color`, `background-image`
* `background-size`, `background-repeat`, `background-position`

👉 **Use case:** Hero section image, banners।

---

### **13. CSS Overflow**

* `overflow: hidden, scroll, auto`

👉 **Use case:** Scrollable div बनाना।

---

### **14. CSS Transitions & Animations**

* Transition → smooth effect (hover पर color change)
* Animation → keyframes से movement / effects

👉 **Use case:** Hover effects, loaders, animated buttons।

---

### **15. CSS Transform**

* `translate`, `rotate`, `scale`, `skew`

👉 **Use case:** Image zoom, rotating cards।

---

### **16. Responsive Design**

* **Media Queries** → अलग-अलग screen size पर अलग styles।
* **Units** → %, em, rem, vh, vw

👉 **Use case:** Mobile-friendly website।

---

### **17. CSS Z-index**

* कौन सा element ऊपर या नीचे दिखेगा।

👉 **Use case:** Modal box, dropdown menu।

---

### **18. CSS Pseudo-classes & Pseudo-elements**

* **Pseudo-class**: `:hover`, `:focus`, `:nth-child()`
* **Pseudo-element**: `::before`, `::after`

👉 **Use case:** Hover effects, extra decoration without extra HTML।

---

### **19. CSS Variables**

* `--main-color: blue;`
* `color: var(--main-color);`

👉 **Use case:** पूरे project में एक ही जगह से color change करना।

---

### **20. CSS Functions**

* `calc()`, `min()`, `max()`, `clamp()`

👉 **Use case:** Dynamic sizing (जैसे width = 100% - 50px)।

---

### **21. CSS Advanced Concepts**

* **Transitions vs Animations**
* **Clip-path, Masking** → complex shapes बनाना
* **Filters** → blur, brightness, grayscale
* **Grid + Flexbox combo layouts**

👉 **Use case:** Modern UI effects, unique layouts।

---


## 1. **CSS Syntax & Selectors**

👉 CSS (Cascading Style Sheets) का काम है **HTML elements को style देना** – जैसे color, size, position, spacing आदि।

### CSS Rule ka Structure

```css
selector {
  property: value;
}
```

* **selector** → किस element पर style apply करनी है (जैसे `p`, `h1`, `.class`, `#id`)
* **property** → कौन सा style change करना है (जैसे `color`, `font-size`, `margin`)
* **value** → उस property ka value (जैसे `red`, `20px`)

### Example

```css
h1 {
  color: blue;         /* text color */
  font-size: 30px;     /* text size */
}

p {
  color: gray;
  line-height: 1.5;
}
```

---

### **Types of CSS Selectors**

1. **Element Selector** → किसी tag को target करना

   ```css
   p { color: red; }
   ```

2. **Class Selector** (`.`) → किसी group of elements को target करना

   ```css
   .highlight { background: yellow; }
   ```

3. **ID Selector** (`#`) → unique element को target करना

   ```css
   #main { padding: 20px; }
   ```

4. **Universal Selector** (`*`) → सारे elements पर apply होगा

   ```css
   * { margin: 0; padding: 0; }
   ```

5. **Group Selector** (`,`) → multiple selectors को combine करना

   ```css
   h1, h2, p { font-family: Arial; }
   ```

6. **Descendant Selector** → nested elements

   ```css
   div p { color: blue; }   /* div ke andar wale p */
   ```

---

✅ **Use case**:
Selectors help करते हैं **किस element को style देना है ये define करने में।**
Without selectors, CSS useless है क्योंकि पता ही नहीं चलेगा style कहाँ apply करनी है।

---

## **2. Colors & Units**

### **1️⃣ Colors in CSS**

CSS में colors element के **text, background, borders** आदि में use होते हैं।

#### **Ways to define colors**

1. **Color Name**

```css
p {
  color: red;
}
```

2. **HEX Code**

```css
h1 {
  color: #ff0000; /* red */
}
```

3. **RGB**

```css
div {
  background-color: rgb(0, 255, 0); /* green */
}
```

4. **RGBA** (opacity)

```css
div {
  background-color: rgba(0, 0, 255, 0.5); /* blue with 50% transparency */
}
```

5. **HSL**

```css
p {
  color: hsl(240, 100%, 50%); /* blue */
}
```

---

### **2️⃣ CSS Units**

Units element का **size, spacing, position** define करने के लिए use होते हैं।

#### **Absolute Units**

* `px` → pixels, fixed size
* `cm, mm, in` → print media

```css
div {
  width: 200px;
  height: 100px;
}
```

#### **Relative Units**

* `%` → parent element ke respect me
* `em` → relative to font-size of parent
* `rem` → relative to root (`html`) font-size
* `vh` → 1% of viewport height
* `vw` → 1% of viewport width

**Example:**

```css
div {
  width: 50%;      /* parent ka 50% width */
  font-size: 2rem; /* root font-size ka double */
  height: 50vh;    /* screen height ka 50% */
}
```

---
##Examples

## 🔹 1. `% (Percentage)`

* **Meaning:** किसी property को **parent element के respect** में set करता है।
* **Use Cases:**

  * Width, height, padding, margin आदि flexible बनाने के लिए
  * Responsive layout में useful

**Example:**

```css
.parent {
  width: 400px;
  height: 200px;
  background: lightblue;
}

.child {
  width: 50%;  /* parent width ka 50% */
  height: 50%; /* parent height ka 50% */
  background: orange;
}
```

➡️ Child ka size **parent ke 50%** hoga.

---

## 🔹 2. `em`

* **Meaning:** Relative to **font-size of its parent**
* **Use Cases:**

  * Font size flexible rakhne ke liye
  * Padding, margin ko font size ke respect me scale karne ke liye

**Example:**

```css
.parent {
  font-size: 20px;
}

.child {
  font-size: 2em; /* 2 * parent font-size = 40px */
  padding: 1em;   /* 1 * parent font-size = 20px */
}
```

💡 **Tip:** em depends on **parent font-size**, agar parent change hua → child bhi adjust hoga

---

## 🔹 3. `rem`

* **Meaning:** Relative to **root (html) font-size**, usually 16px by default
* **Use Cases:**

  * Font size ko globally consistent rakhne ke liye
  * Responsive design me predictably scale karne ke liye

**Example:**

```css
html {
  font-size: 16px;
}

p {
  font-size: 2rem; /* 2 * 16px = 32px */
}
```

💡 Difference from `em`:

* `em` → parent pe depend karta hai
* `rem` → hamesha root (html) pe depend karega

---

## 🔹 4. `vh` (Viewport Height)

* **Meaning:** 1vh = **1% of viewport height** (screen ki height)
* **Use Cases:**

  * Full screen layouts
  * Hero sections, fullscreen images, height responsive elements

**Example:**

```css
.hero {
  height: 100vh;  /* screen ki height ka 100% */
  background: lightgreen;
}
```

---

## 🔹 5. `vw` (Viewport Width)

* **Meaning:** 1vw = **1% of viewport width** (screen ki width)
* **Use Cases:**

  * Responsive typography
  * Full width elements
  * Spacing elements relative to screen size

**Example:**

```css
h1 {
  font-size: 5vw;  /* font size screen width ke 5% ke equal */
}
```

---

### 🔑 **Quick Guide: When to Use**

| Unit  | Best For                                                    |
| ----- | ----------------------------------------------------------- |
| `%`   | Width, height, padding, margin (parent-relative)            |
| `em`  | Font size, spacing relative to parent font size             |
| `rem` | Font size, spacing relative to root font size (consistent)  |
| `vh`  | Full height sections, responsive layout                     |
| `vw`  | Responsive width, scaling text/elements according to screen |

---

### ✅ **Use Cases**

1. **Colors** → Text, backgrounds, borders attractive बनाना।
2. **Units** → Responsive design और spacing control करना।

---

💡 **Tip:**

* Absolute units → fixed design (desktop focused)
* Relative units → responsive design (mobile + desktop)

---



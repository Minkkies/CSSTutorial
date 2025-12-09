# CSS Tutorial Notes 📚

บันทึกเรียนรู้ CSS ที่ครอบคลุมตั้งแต่พื้นฐานไปจนถึงเทคนิคขั้นสูง

## 📖 เกี่ยวกับ Repository นี้

Repository นี้เป็นคอลเล็กชั่นของบันทึก CSS ที่ครบถ้วน ประกอบด้วย:
- **แนวคิดพื้นฐาน** - Syntax, Selectors, การใส่ CSS
- **Layout & Positioning** - Flexbox, Grid, Position, Float
- **Styling** - Colors, Typography, Borders, Shadows
- **Responsive Design** - Media Queries, Breakpoints
- **Advanced Features** - Animations, Transitions, Transforms
- **ตัวอย่างโปรเจกต์** - Cards, Sliders, Galleries, Navigation

เหมาะสำหรับผู้เริ่มต้นและผู้ที่ต้องการทบทวนความรู้ CSS

---

## 📚 เนื้อหาหลัก

### 1️⃣ กลุ่มพื้นฐาน (Fundamentals)
- **CSS Syntax** - Selector, Property, Value
- **Three Ways to Insert CSS** - Inline, Internal, External
- **CSS Selectors** - Tag, Class, ID, Attribute
- **5 ประเภท CSS Selector** - Parent-Child, Base Class, Direct Child, Adjacent, Attribute

### 2️⃣ Layout & Positioning
| เทคนิค | คำสั่ง | ใช้งาน |
|--------|--------|--------|
| **Flexbox** | `display: flex;` | จัดเรียงแนวแถว/คอลัมน์ |
| **Grid** | `display: grid;` | จัดวางแบบตาราง |
| **Position** | `position: static/relative/absolute/fixed/sticky` | จัดตำแหน่งอิสระ |
| **Float** | `float: left/right` | เลย์เอาต์แบบเก่า |

### 3️⃣ Typography & Colors
- **Font Properties** - font-family, font-size, font-weight, font-style
- **Text Formatting** - text-align, text-transform, text-decoration
- **Colors** - color, background-color, border-color
- **Gradients** - linear-gradient, radial-gradient

### 4️⃣ Spacing & Borders
- **margin vs padding** - ช่องว่างนอก vs ใน
- **border** - ขนาด, รูปแบบ, สี
- **border-radius** - มุมโค้ง

### 5️⃣ CSS Units (หน่วยวัด)
| หน่วย | ความหมาย | ใช้งาน |
|-------|----------|--------|
| `px` | Pixel คงที่ | ขนาดตายตัว |
| `%` | % ของ Parent | ทำให้ยืดหยุ่น |
| `em` | ขนาด Font ของ Parent | ปรับสัมพันธ์กัน |
| `rem` | ขนาด Font ของ Root | ใช้ง่าย, อิสระ |
| `vh/vw` | ความสูง/กว้างหน้าจอ | Element เต็มจอ |

### 6️⃣ Responsive Design
- **Media Queries** - `@media screen and (max-width: 768px)`
- **Breakpoints** - 
  - 📱 Mobile: max-width 640px
  - 📱 Tablet: 640px - 768px
  - 💻 Desktop: 1024px+
- **Fluid Layouts** - Flexbox & Grid responsive

### 7️⃣ Animations & Transitions
- **Transitions** - การเปลี่ยนแบบค่อยๆ
- **Transforms** - rotate, scale, translate
- **@keyframes** - Animation แบบตั้งแต่ต้น

### 8️⃣ Pseudo-classes & Pseudo-elements
- **`:hover`, `:active`, `:focus`** - Interactive states
- **`:nth-child()`, `:first-child`, `:last-child`** - Selection
- **`::before`, `::after`** - เพิ่มเนื้อหาใน CSS

### 9️⃣ Advanced Components
- **Cards** - ตัวอย่าง hover effects
- **Image Slider** - Aspect ratio, scroll-snap
- **Pinterest Layout** - Multi-column gallery
- **Navigation Menu** - Desktop vs Mobile

---

## 🎮 Interactive Learning Resources

- 🐸 [Flexbox Froggy](https://flexboxfroggy.com/#th) - เกมเรียน Flexbox
- 🎨 [Google Fonts](https://fonts.google.com/) - นำเข้า Font ได้ง่าย
- 📐 [Material Design Breakpoints](https://m3.material.io/foundations/layout/applying-layout/window-size-classes) - Layout guidelines
- 🎯 [Tailwind CSS Responsive](https://tailwindcss.com/docs/responsive-design) - Responsive patterns

---

## 📖 แหล่งอ้างอิงหลัก

1. **W3Schools CSS Reference**
   - URL: https://www.w3schools.com/CSS/default.asp
   - ครอบคลุม CSS ตั้งแต่พื้นฐานถึงขั้นสูง

2. **Mikelopster YouTube Channel**
   - URL: https://youtu.be/KCYxFXIAn_4?si=SOL-E_LZ-FCaFnKX
   - วิดีโอ Tutorial CSS เข้าใจง่าย

---

## 🗂️ โครงสร้างโปรเจกต์

```
CSSTutorial/
├── README.md           (ไฟล์นี้)
├── CSSnote.md          (บันทึกรายละเอียด)
├── img/                (รูปตัวอย่างและ GIF)
│   ├── syntax.png
│   ├── selector.PNG
│   ├── margin-padding.jpg
│   ├── flexbox*.gif
│   ├── grid.gif
│   ├── card.png
│   ├── slide.png
│   └── ... (อื่นๆ)
└── .gitattributes
```

---

## 🚀 Quick Start

### 1. CSS Syntax พื้นฐาน
```css
selector {
  property: value;
}
```

### 2. Common Setup
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

### 3. Center Content
```css
body {
  max-width: 1200px;
  margin: 0 auto;
}
```

---

## 📌 Tips & Best Practices

✅ **ใช้ `rem` แทน `px`** - ง่ายต่อการ scale  
✅ **Mobile-first approach** - ออกแบบ mobile ก่อน  
✅ **ใช้ Flexbox** สำหรับเลย์เอาต์ 1 แนว  
✅ **ใช้ Grid** สำหรับเลย์เอาต์ซับซ้อน  
✅ **ทดสอบ responsive** ที่ 640px, 768px, 1024px  

---

## 📝 ตัวอย่างเนื้อหา

### ✨ Flexbox Example
```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
}
```

### ✨ Grid Example
```css
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}
```

### ✨ Responsive Example
```css
/* Desktop */
@media screen and (min-width: 1024px) {
  .container {
    grid-template-columns: repeat(3, 1fr);
  }
}

/* Mobile */
@media screen and (max-width: 640px) {
  .container {
    grid-template-columns: 1fr;
  }
}
```

---

## 💡 สิ่งที่ได้เรียนรู้

1. ✅ CSS Syntax และ Selectors
2. ✅ Layout techniques (Flexbox, Grid, Float, Position)
3. ✅ Responsive Design dengan Media Queries
4. ✅ Animations & Transitions
5. ✅ Advanced patterns (Cards, Sliders, Galleries)
6. ✅ Best practices & optimization

---

## 🤝 นำเสนออย่างไร

บันทึกนี้จัดเรียงเป็นหมวดหมู่ 9 กลุ่ม โดยใช้:
- 📋 ตาราง (Tables) - เปรียบเทียบ
- 💻 Code examples - ตัวอย่างจริง
- 🖼️ Visual GIFs - แสดงผล
- 📌 Links - อ้างอิงข้อมูล

---

หากมีคำถามหรือต้องการเพิ่มเติม สามารถศึกษาจาก [CSSnote.md](CSSnote.md)
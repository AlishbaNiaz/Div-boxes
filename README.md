# Div-boxes
For practise purposes.
# CSS Transforms, Transitions & Effects Practice

This project demonstrates the use of **CSS transitions, transforms, shadows, and background properties** through different styled boxes.

---

## Features Implemented

### **1. Box1 - Transition on Width**
- **Effect:** Width changes smoothly when hovered.  
- **Properties Used:**
  - `transition: width 2s ease-in 0.5s;` → 2 seconds transition, ease-in speed curve, and 0.5s delay.
- **Hover Result:** Width expands from `100px` to `600px`.

---

### **2. Box2 - Translate & Rotate**
- **Effect:** Moves `200px` right and `200px` down, and rotates `90deg`.  
- **Properties Used:**
  - `transform: translate(200px, 200px) rotate(90deg);`

---

### **3. Box3 - Skew**
- **Effect:** Skews box along the **X-axis** by `20deg`.  
- **Properties Used:**
  - `transform: skewX(20deg);`

---

### **4. Box4 - Shadow**
- **Effect:** Adds a green shadow to the box.  
- **Properties Used:**
  - `box-shadow: 2px 2px 5px green;` → 2px horizontal, 2px vertical offset, 5px blur.

---

### **5. MyPic - Background Image & Transparency**
- **Effect:** Adds a background image and makes the box 50% transparent.  
- **Properties Used:**
  - `background-image: url("download (13).jpg");`
  - `background-size: cover;`
  - `opacity: 50%;`

---

## Purpose
This project is created for **learning and practicing CSS**:
- Transition & hover effects
- Transformations (translate, rotate, skew)
- Shadows
- Background images & opacity

---

## How to Use
1. Create an `index.html` file with corresponding div elements:
   ```html
   <div id="box1"></div>
   <div id="box2"></div>
   <div id="box3"></div>
   <div id="box4"></div>
   <div id="myPic"></div>

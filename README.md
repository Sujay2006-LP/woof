## 🎨 UI & Theming Overview

The **Woof** app is built using **Material Design principles**, focusing on consistency, accessibility, and modern UI practices. The implementation combines color, typography, shape, and layout components to create a clean and engaging user experience.

---

## 🌈 Color System

The color system is designed to maintain clarity, hierarchy, and usability across the app.

### Key Highlights

- Uses a **primary color** to define brand identity  
- Includes **secondary and supporting colors** for accents  
- Maintains proper **contrast ratios** for accessibility  
- Structured to support **light and dark themes**  

### 🎯 Color Roles

| Role            | Purpose |
|-----------------|--------|
| **Primary**     | Main UI elements (buttons, app bar) |
| **On Primary**  | Text/icons on primary color |
| **Secondary**   | Supporting accents |
| **Background**  | Screen background |
| **Surface**     | Cards and containers |
| **Error**       | Error states |

---

## 🔤 Typography

Typography is used to establish strong visual hierarchy and readability.

### Implementation

- Applied **Material Typography guidelines**  
- **Abril Fatface** → Used for **dog names** (bold, expressive)  
- **Montserrat** → Used for **dog age and supporting text** (clean, readable)  
- Clear distinction between **primary and secondary text content**  

---

## 🔷 Shape System

Shape customization enhances the overall look and feel of the app.

- Implemented **rounded corners** for cards and images  
- Used **Material Shape system**  
- Ensures **consistency across UI components**  

---

## 📱 App Bar (Top Navigation)

- Implemented **CenterAlignedTopAppBar**  
- Provides a **balanced and modern header layout**  
- Keeps the app title centered for better visual alignment  
- Follows **Material 3 guidelines** for top app bars  

---

## 🎬 Interactive UI & Animations

The app now includes dynamic interactions to improve user experience and engagement.

### 🔽 Expandable Content

- Added **Expand More / Expand Less functionality**  
- Allows users to toggle additional dog information  
- Built using **state-driven UI (remember + mutableStateOf)**  

### 🎞️ Smooth Animations

- Implemented `animateContentSize()` for smooth layout transitions  
- Avoids abrupt UI changes during expansion and collapse  

### 🌊 Spring-Based Motion

- Used **spring animation** with:
  - Medium stiffness  
  - Medium damping ratio  
- Creates a balanced and natural movement effect  

### 🎨 Interactive Icon Feedback

- Icons dynamically change color based on state (expanded/collapsed)  
- Provides clear visual feedback to the user  

### 🐶 Enhanced Content Display

- Each dog card now reveals **detailed information on interaction**  
- Improves usability and content depth  

---

## 🌙 Dark Mode Support (Optional)

- Designed to adapt to **low-light environments**  
- Uses darker surfaces with lighter text  
- Maintains **WCAG contrast standards**  

---

## ♿ Accessibility

- Ensures **sufficient contrast** between text and background  
- Avoids reliance on color alone (uses text/icons as well)  
- Follows **inclusive design practices** from Material guidelines  

---

## 📌 Notes

- UI elements are **modular and scalable**  
- Theming is centralized for **easy updates and consistency**  
- Built as part of learning and applying **modern Android UI development practices**  

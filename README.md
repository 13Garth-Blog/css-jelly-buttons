# Jelly Button Stylesheet

**Author**: 13Garth  
**Version**: 1.0.0  

A modern, gamified, and glossy button library built with CSS. Jelly Buttons are designed to be vibrant, animated, and responsive, with built-in theming for primary, secondary, success, danger, warning, info, light, and dark variations. Perfect for mobile-first designs!

---

## Features

- **Responsive**: Optimized for all screen sizes, including mobile.
- **Themed Variations**: Supports primary, secondary, success, danger, warning, info, light, and dark buttons.
- **Glossy Look**: Subtle shine overlay for a polished, modern appearance.
- **Gamified Animations**: Includes jelly-like scaling animation on hover and active states.
- **Customizable**: Easy to modify using CSS variables.

---

## Button Variations

| **Size**    | **Class**         | **Description**                        |
|-------------|-------------------|----------------------------------------|
| Small       | `jb-s`            | For compact button designs             |
| Normal      | `jb-n` (default)  | Standard button size                   |
| Large       | `jb-l`            | For prominent, eye-catching buttons    |

| **Theme**    | **Class**         | **Description**                          |
|--------------|-------------------|------------------------------------------|
| Primary      | `jb-primary`      | Vibrant blue, great for main actions      |
| Secondary    | `jb-secondary`    | Slate-themed, perfect for subtle buttons  |
| Success      | `jb-success`      | Lime green, ideal for positive actions    |
| Danger       | `jb-danger`       | Coral red, for warnings and deletions     |
| Warning      | `jb-warning`      | Bright gold, highlights critical actions  |
| Info         | `jb-info`         | Coral orange, perfect for informational use |
| Light        | `jb-light`        | Khaki-themed, elegant and subtle          |
| Dark         | `jb-dark`         | Dark slate for a bold statement           |

---

## Usage

### HTML Structure

```html
<div class="jelly-container">
  <!-- Small Buttons -->
  <button class="jb-btn jb-s jb-primary">Small Primary</button>
  <button class="jb-btn jb-s jb-success">Small Success</button>
  
  <!-- Normal Buttons -->
  <button class="jb-btn jb-n jb-info">Normal Info</button>
  <button class="jb-btn jb-n jb-danger">Normal Danger</button>
  
  <!-- Large Buttons -->
  <button class="jb-btn jb-l jb-warning">Large Warning</button>
  <button class="jb-btn jb-l jb-dark">Large Dark</button>
</div>

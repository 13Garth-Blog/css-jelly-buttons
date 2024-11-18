# Jelly Button Stylesheet

**Author**: 13Garth 

**Version**: 1.0.0 

**CodePen**: https://codepen.io/13garth/pen/bGXJPBP / Jelly Button CSS 

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

### HTML Structure & Testing Template

> [!NOTE]
> Bootstrap is optional

```
<div class="container">
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
			<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
	<div class="row col-12 mx-auto p-0 text-center">
		<h4 class="display-4">
			Jelly Button CSS
		</h4>
	</div>
	<br>
	<div class="jelly-container">
		<!-- Jelly Button Class List -->
		<!--  Small Buttons -->
		<button class="jb-btn jb-s jb-primary">Small Primary</button>
		<button class="jb-btn jb-s jb-secondary">Small Secondary</button>
		<button class="jb-btn jb-s jb-success">Small Success</button>
		<button class="jb-btn jb-s jb-info">Small Info</button>
		<button class="jb-btn jb-s jb-warning">Small Warning</button>
		<button class="jb-btn jb-s jb-danger">Small Danger</button>
		<button class="jb-btn jb-s jb-light">Small Light</button>
		<button class="jb-btn jb-s jb-dark">Small Dark</button>
		<hr>
		<!-- Normal Buttons -->
		<button class="jb-btn jb-n jb-primary">Normal Primary</button>
		<button class="jb-btn jb-n jb-secondary">Normal Secondary</button> 
		<button class="jb-btn jb-n jb-success">Normal Success</button>
		<button class="jb-btn jb-n jb-info">Normal Info</button>
		<button class="jb-btn jb-n jb-warning">Normal Warning</button> 
		<button class="jb-btn jb-n jb-danger">Normal Danger</button>
		<button class="jb-btn jb-n jb-light">Normal Light</button>
		<button class="jb-btn jb-n jb-dark">Normal Dark</button>
		<hr>
		<!--  Large Buttons -->
		<button class="jb-btn jb-l jb-primary">Large Primary</button>
		<button class="jb-btn jb-l jb-secondary">Large Secondary</button>
		<button class="jb-btn jb-l jb-success">Large Success</button>
		<button class="jb-btn jb-l jb-info">Large Info</button>
		<button class="jb-btn jb-l jb-warning">Large Warning</button>
		<button class="jb-btn jb-l jb-danger">Large Danger</button>
		<button class="jb-btn jb-l jb-light">Large Light</button>
		<button class="jb-btn jb-l jb-dark">Large Dark</button>
	</div>
	<hr>
	<div>
		<!-- Default Bootstrap Buttons with jelly button CSS -->
		<button type="button" class="btn btn-primary">Primary</button>
		<button type="button" class="btn btn-secondary">Secondary</button>
		<button type="button" class="btn btn-success">Success</button>
		<button type="button" class="btn btn-danger">Danger</button>
		<button type="button" class="btn btn-warning">Warning</button>
		<button type="button" class="btn btn-info">Info</button>
		<button type="button" class="btn btn-light">Light</button>
		<button type="button" class="btn btn-dark">Dark</button>

		<button type="button" class="btn btn-link">Link</button>
	</div>
	<br>
</div>
```

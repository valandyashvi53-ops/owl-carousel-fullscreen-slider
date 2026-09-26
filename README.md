# owl-carousel-fullscreen-slider
Responsive full-screen image slider built using HTML, CSS, jQuery, Owl Carousel 2, and Animate.css with custom slide animations, navigation buttons, and dots.
# 🦉 Owl Carousel Full-Screen Image Slider

owl-carousel-fullscreen-slider/
│
├── index.html
├── i1.jpg
├── i2.jpg
├── i3.jpg
├── i4.webp
├── i5.jpg
└── README.md

A modern **full-screen image slider** built using **HTML, CSS, jQuery, Owl Carousel 2, and Animate.css**.

This project displays images in a full-screen carousel with smooth navigation, dots, and different animation effects for each slide.

## 🌐 Live Demo

You can deploy this project using **GitHub Pages** and add your live demo link here:

`https://your-username.github.io/owl-carousel-fullscreen-slider/`

## 📸 Features

* 🖼️ Full-screen image slider
* 📱 Responsive design
* 🦉 Owl Carousel 2 integration
* ✨ Animate.css slide animations
* ⬅️ Previous and Next navigation buttons
* 🔘 Carousel dots navigation
* 🔄 Infinite loop
* 🎞️ Different animation effects for slides
* ⚡ Smooth slide transition
* 🎨 Simple and clean UI
* 🚫 No external backend required

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* jQuery
* Owl Carousel 2
* Animate.css

## 🎬 Animation Effects

Each slide uses a different Animate.css effect:

| Slide | Animation            |
| ----: | -------------------- |
|     1 | Fade In              |
|     2 | Back In Right        |
|     3 | Zoom In              |
|     4 | Fade In Down         |
|     5 | Light Speed In Right |

## 📂 Project Structure

```text
owl-carousel-fullscreen-slider/
│
├── index.html
├── i1.jpg
├── i2.jpg
├── i3.jpg
├── i4.webp
├── i5.jpg
└── README.md
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/owl-carousel-fullscreen-slider.git
```

### 2. Open the project folder

```bash
cd owl-carousel-fullscreen-slider
```

### 3. Run the project

Open `index.html` in your browser.

You can also use **VS Code with Live Server** for development.

## ⚙️ Configuration

The carousel is configured with:

```javascript
$(".owl-carousel").owlCarousel({
    items: 1,
    loop: true,
    margin: 0,
    nav: true,
    dots: true,
    smartSpeed: 800,
    autoplay: false
});
```

## ✨ Animation Handling

The project dynamically applies a different animation when the active slide changes.

```javascript
var animations = [
    "animate__fadeIn",
    "animate__backInRight",
    "animate__zoomIn",
    "animate__fadeInDown",
    "animate__lightSpeedInRight"
];
```

When the carousel changes slides, the previous animation class is removed and the corresponding animation is applied to the new active image.

## 📱 Responsive Design

The slider uses:

```css
width: 100%;
height: 100vh;
```

and images are displayed using:

```css
object-fit: contain;
```

This allows the slider to occupy the complete browser viewport.

## 📚 External Libraries

This project uses the following CDN resources:

* jQuery
* Owl Carousel 2
* Animate.css

## 📄 License

This project is open-source and available for learning and personal use.

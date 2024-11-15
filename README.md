# GSAP Responsive Animation Project

This project demonstrates how to create responsive animations using **GSAP** and **ScrollTrigger** based on the window size (desktop and mobile). The animations are triggered and adjusted accordingly, ensuring that they are optimized for different screen sizes.

## Features

- **Responsive Animations**: Animations are applied only on desktop-sized screens (width >= 768px). On mobile, simpler animations are applied without ScrollTrigger.
- **GSAP Integration**: The project utilizes GSAP for animating elements like `.card`, `.card-2`, and `.card-3`.
- **ScrollTrigger**: Scroll-based animations are applied on desktop screens, allowing for scroll-triggered animation effects.
- **Dynamic Updates**: The animations are adjusted dynamically when the window is resized from desktop to mobile or vice versa.

## Technologies Used

- **GSAP** (GreenSock Animation Platform)
- **ScrollTrigger** for scroll-based animations
- **JavaScript** for controlling the animation logic and responsive behavior

## How It Works

1. **Window Size Detection**: The JavaScript code detects the current window width to check if the screen size is classified as desktop or mobile.
2. **Responsive Animations**:
   - **Desktop**: Animations use GSAP's `to()` method to animate `.card`, `.card-2`, and `.card-3` with specific X, Y coordinates and ScrollTrigger effects.
   - **Mobile**: Simpler animations (such as opacity and scaling) are applied without ScrollTrigger.
3. **Animation Adjustment on Resize**: When the window is resized, the project automatically adjusts the animations to match the new screen size, removing unnecessary animations and triggers.

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/gsap-responsive-animation.git
```

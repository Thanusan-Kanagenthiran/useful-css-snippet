# Blob Shapes CSS  

This project contains CSS code for creating blob-like shapes using background images and colors, along with animations to morph their shapes over time.  

- `blob`: Creates a static blob shape with a background color
- `blob-image`: Creates a static blob shape with a background image.
- `blob-animation`: Creates a blob shape with a background color and applies an animation to morph its shape over time.   
- `blob-image-animation`: Creates a blob shape with a background image and applies an animation to morph its shape over time.  

Certainly! The blob shape in the provided CSS is created using the border-radius property. This property is typically used to create rounded corners for elements, but by providing multiple values, you can create more complex shapes, including blob-like forms.

In the CSS code, the border-radius property is used with percentage values to create irregular shapes resembling blobs. Here's a breakdown of how it works:   

```css
.blob-image {
    border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%;
}
```
The first set of values (`60% 40% 30% 70%`) determines the horizontal curvature of the blob.
The second set of values (`60% 30% 70% 40%`) determines the vertical curvature of the blob.

By adjusting these percentage values, you can modify the shape of the blob. For instance, increasing the first value and decreasing the second value will make the blob wider horizontally and narrower vertically, and vice versa.
   

In the provided CSS code, the @keyframes rule is used to define animations for morphing the blob shapes over time. Here's how it's used:

```css
@keyframes animate {
    0%, 100% {
        border-radius: 73% 27% 66% 34% / 50% 49% 51% 50%;
    }
    34% {
        border-radius: 37% 63% 47% 53% / 50% 49% 51% 50%;
    }
    67% {
        border-radius: 57% 43% 28% 72% / 64% 22% 78% 36%;
    }
}
```
Three keyframes are defined: **0%**, **34%**, and **67%**. 

At **0%** and **100%**, the `border-radius` is set to `73% 27% 66% 34% / 50% 49% 51% 50%`. 
At **34%**, the `border-radius` is set to `37% 63% 47% 53% / 50% 49% 51% 50%`.
At **67%**, the `border-radius` is set to `57% 43% 28% 72% / 64% 22% 78% 36%`.

These keyframes define the shape of the blob at different points in the animation timeline. By transitioning between these keyframes, the blob shape smoothly morphs from one configuration to another, creating the illusion of movement or transformation.

Thank you for exploring Blob Shapes CSS! We hope this resource inspires you to create visually engaging designs with ease. Experiment with the provided CSS classes and animations to add unique blob shapes to your projects. If you have any questions or need further assistance, feel free to reach out. Happy designing!

[Thanusan Kanagenthiran](https://www.linkedin.com/in/thanusan-kanagenthiran)

[MIT](https://choosealicense.com/licenses/mit/)
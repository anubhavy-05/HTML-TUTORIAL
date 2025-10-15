# Lecture 10 — CSS Animation (Moving Circle)

A simple demo where a circular div moves horizontally and changes color using CSS keyframes and the animation shorthand.

## Files
- index.html — markup; links style.css
- style.css — styles and keyframes

## Run
- Keep index.html and style.css in the same folder.
- Open index.html in a browser (double-click) or use VS Code Live Server.

## Key CSS
```css
div {
  height: 200px;
  width: 200px;
  border-radius: 50%;
  position: absolute;
  top: 100px;
  left: 100px;
  border: 2px solid black;
  text-align: center;
  background: antiquewhite;
  animation: colorAnimate 2s ease-in 0s infinite normal;
}

@keyframes colorAnimate {
  from { left: 0px; background: brown; }
  to   { left: 200px; background: blue; }
}
```

## Troubleshooting
- If the animation does not run, ensure style.css contains only CSS (no HTML) and the link href in index.html is correct.
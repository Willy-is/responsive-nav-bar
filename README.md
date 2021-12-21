# Responsive Nav Bar UI Component

In this project, the navigation bar was designed by using media query in CSS and responsive units; em & rem.

# Wide screen

<img width="800" alt="wide-screen-view" src="https://user-images.githubusercontent.com/57608628/146876782-555b139b-d2f3-4f47-aabb-e12049ab9ff2.png">

# Small screen

<img width="800" alt="small-screen-view" src="https://user-images.githubusercontent.com/57608628/146876852-c78eb727-e90d-422a-9368-d5b484a67383.png">

<br></br>

## HTML

The wide screen and small screen were sectionised by the block level, and Block Element Modifier ([BEM](http://getbem.com/introduction/)) was used to name the HTML components as below photos.
<img width="800" alt="BEM" src="https://user-images.githubusercontent.com/57608628/146879033-918932a1-caf8-4e3b-be53-3f370c59f71f.png">

<br></br>

## CSS

In CSS, the custom properties for the colours and border radius size were declared under the `:root`. To make it responsive, media query is used.

```css
@media
```

Furthermore, responsive units such as **em** & **rem** are used instead of ~~px~~ in order to be more fluid.

- rem: font and screen
- em: padding

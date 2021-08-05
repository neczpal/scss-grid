# Sass Basic

## Flexbox based grid system

### [Demo Page](https://neczpal.github.io/scss-grid/)

### How to Build

* #### Install sass `npm install -g sass`

* `npm run build` - Builds the [`style.scss`](https://github.com/neczpal/scss-grid/blob/master/src/scss/style.scss)

### How to Run

* Open the index.html in `dist/index.html`

### Configurable variables

* Column count
* Breakpoints
* Container class name
* Container width
* Container padding by each breakpoint
* Column class name
* Column modifier postfix name
* Column padding by each breakpoint


```SCSS
$config: (
        grid: (
                columnCount: 12,
                breakpoint: (
                        mobile: 640px,
                        tablet: 960px,
                        desktop: 1280px
                )
        ),
        container: (
                classname: container,
                maxWidth: 1280px,
                padding: (
                        default: 5px,
                        mobile: 6px,
                        tablet: 7.5px,
                        desktop: 9px
                )
        ),
        column: (
                classname: column,
                postfix: (
                        default: default,
                        mobile: mobile,
                        tablet: tablet,
                        desktop: desktop
                ),
                padding: (
                        default: 10px,
                        mobile: 12px,
                        tablet: 15px,
                        desktop: 18px
                )
        )
);
```

### Further resources

* #### [Sass playground](https://www.sassmeister.com/)
* #### [Sass documentation](https://sass-lang.com/documentation)
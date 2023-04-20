# advanced-css-using-variables

## 1) user-defined variables (easy to maintain, changes)
 html {
    --color-grey-100: rgb(236, 236, 236);
    --color-grey-400: rgb(105, 105, 105);
    --color-grey-600: rgb(58, 58, 58);
    --color-grey-900: rgb(41, 41, 41);
    
    --color-primary-300: rgb(167, 226, 255);
    --color-primary-700: rgb(0, 170, 255);

    --size-1: 18px;
    --size-5: 50px;

    background-color: var(--color-grey-100);
    font-family: 'Krub', sans-serif;
    font-weight: 400; 
  }
  
## 2) CSS Transformations & transitions
  -`Transformation`
    - Move / change appearance of element, e.g. when hovering
      -.card-container:hover {
        transform: scale(2);
        }

  - `Transition`
    - Smooth transition from initial to transformed state.
    - Applied to "initial state" of the element, not on event triggering the transition.
      - transition: transform 0.5s ease-out 1s;
        - property : transform
        - dueration : 0.5s
        - timing function : ease-out
        - delay : 1s

## 3) Scalable Vector Graphics (SVG)
  - XML based markup language to describe two-dimensional vector graphics.
  - Text based description of skalable images that can be rendered by the browser.
    - heroicons.dev // heroicons.com 
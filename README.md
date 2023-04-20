# advanced-css-using-variables

## 1) user-defined variables
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
  
## 2) easy to maintain, changes

# Css Utilities

## Description
Taildwind CSS like utilities for *Bootstrap 3* and any other CSS project;

### Installation
- ```npm install git+https://github.com/Yismen/css-utilities.git -D```
### Usage
- Imports:
    - With a sass compiler: ```@import "~dainsys-css-utilities/build/css-utilities.css";```
    - Or with webpack from ```node_modules/dainsys-css-utilities/src/_utilities.scss```
### API:
- Breakpoints
  - Eeach class will have a prefix according to a min-width media query.
    - `sm:` : `@media (min-width: 750px)`;
    - `md:` : `@media (min-width: 992px)`;
    - `lg:` : `@media (min-width: 1200px)`;
    - `xl:` : `@media (min-width: 1400px)`;
- Display classes
    - `.flex` : {display: flex;}
    - `.block` : {display: block;}
    - `.content` : {display: content;}
    - `.table` : {display: table;}
    - `.grid` : {display: grid;}
- Flex properties
    - Flex Directions
        - . `.flex-direction-column` : {flex-direction: column;}
        - . `.flex-direction-row` : {flex-direction: row;}
        - . `.flex-direction-column-reverse` : {flex-direction: column-reverse;}
        - . `.flex-direction-row-reverse` : {flex-direction: row-reverse;}
    - Align Items
        - . `.align-items-baseline` : {align-items: baseline;}
        - . `.align-items-center` : {align-items: center;}
        - . `.align-items-flex-end` : {align-items: flex-end;}
        - . `.align-items-flex-start` : {align-items: flex-start;}
- Margins
    - Maring All Arounds
        -`.m-0` : {margin: 0rem;}
        -`.m-1` : {margin: 0.25rem;}
        -`.m-2` : {margin: 0.5rem;}
        -...
        -`.m-92` : {margin: 23rem;}
    - Margin Left
        - `.ml-0` : {margin-left: 0rem;}
        - `.ml-1` : {margin-left: 0.25rem;}
        - `.ml-2` : {margin-left: 0.5rem;}
        -  ...
        -  `.ml-92` : {margin-right: 23rem;
    - argin Right
        - mr-0` : {margin-right: 0rem;}
        -  `.mr-1` : {margin-right: 0.25rem;}
        -  `.mr-2` : {margin-right: 0.5rem;}
        -  ...
        -  `.mr-92` : {margin-right: 23rem;}
    - argin Top
        -  `.mt-0` : {margin-top: 0rem;}
        -  `.mt-1` : {margin-top: 0.25rem;}
        -  `.mt-2` : {margin-top: 0.5rem;}
        -  ...
        -  `.mt-92` : {margin-top: 23rem;}
    - Margin Bottom
        -  `.mb-0` : {margin-bottom: 0rem;}
        -  `.mb-1` : {margin-bottom: 0.25rem;}
        -  `.mb-2` : {margin-bottom: 0.5rem;}
        -  ...
        - `.mb-92` : {margin-bottom: 23rem;}
    - Margin Horizontal
        -  `.mx-0` : {margin-left: 0rem; margin-right: 0rem;}
        -  `.mx-1` : {margin-left: 0.25rem; margin-right: 0.25rem;}
        -  `.mx-2` : {margin-left: 0.5rem; margin-right: 0.5rem;}
        -  ...
        -  `.mx-92` : {margin-left: 23rem; margin-right: 23rem;}
    - Margin Vertical
        -  `.my-0` : {margin-top: 0rem; margin-bottom: 0rem;}
        -  `.my-1` : {margin-top: 0.25rem; margin-bottom: 0.25rem;}
        -  `.my-2` : {margin-top: 0.5rem; margin-bottom: 0.5rem;}
        -  ...
        -  `.my-92` : {margin-top: 23rem; margin-bottom: 23rem;}
- Paddings
    - All margins, but starting with `p`
- Widths
    - `w-25` : {width: 25%;}
    - `w-50` : {width: 50%;}
    - `w-75` : {width: 75%;}
    - `w-100` : {width: 100%;}
- Heights
    - `h-25` : {height: 25%;}
    - `h-50` : {height: 50%;}
    - `h-75` : {height: 75%;}
    - `h-100` : {height: 100%;}
- View Heights
    - `vh-10` : {height: 10%;}
    - `vh-20` : {height: 20%;}
    - `vh-30` : {height: 30%;}
    - ...
    - `vh-100` : {height: 100%;}
- Font Heights
    - `fw-10` : {font-weight: 10%;}
    - `fw-20` : {font-weight: 20%;}
    - `fw-30` : {font-weight: 30%;}
    - ...
    - `fw-100` : {font-weight: 100%;}
- Visibility
    - `visible` : {visibility: visible}
    - `invisible` : {visibility: hidden}
    - `collapse` : {visibility: collapse}
  - Letter Spacing
      - `.letter-spacing-0` : {letter-spacing: 0rem;}
      - `.letter-spacing-1` : {letter-spacing: 0.25rem;}
      - `.letter-spacing-2` : {letter-spacing: 0.5rem;}
      - ...
      - `.letter-spacing-32` : {letter-spacing: 8rem;
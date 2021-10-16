# Perfume

This is a multi-page website that demonstrates an online perfume shop.  

<img src="https://github.com/qianhuiwei/Perfume/blob/main/pageDemo.png" width="500"/>

## Check out the page
Open the link below (Chrome or Safari recommended):  
https://qianhuiwei.github.io/Perfume/


## Features
* Worked with the [Adobe XD design specs](https://xd.adobe.com/view/dc5ebe5c-3e56-4981-a010-158b5ded0e72-890d/specs/).
* Designed and customized styles using Bootstrap 5.
* Managed CSS with SCSS.
* Developed with mobile-first RWD.
* Imported icons from [Material icons](https://material.io/tools/icons/).
* Tested with Chrome and Safari.

## Customized SCSS Variables
```scss
// colors
$theme-colors: (
  "primary":    #916019,
  "secondary":  #AC8A46,
  "light":      #818A91,
  "dark":       #8D8D8D,
  "gray-1":     #E0E0E0,
  "gray-2":     #CED4DA,
  "gray-3":     #A5A5A5,
  "gray-4":     #848484,
  "gray-5":     #707070
) ;

// spacing
$spacer: 1rem / 4; //4px
$spacers: (
  0: 0,
  1: $spacer,          //4px
  2: $spacer * 2,     
  3: $spacer * 3,     
  4: $spacer * 4,    
  5: $spacer * 5,     // 20px
  6: $spacer * 6,     
  7: $spacer * 7,     
  8: $spacer * 8,    
  9: $spacer * 9,    
  10: $spacer * 10,   // 40px
  11: $spacer * 11,  
  12: $spacer * 12,   
  13: $spacer * 13,   
  14: $spacer * 14,   
  15: $spacer * 15,   // 60px
  16: $spacer * 16,  
  17: $spacer * 17,   
  18: $spacer * 18,   
  19: $spacer * 19,   
  20: $spacer * 20,   // 80px
) ;

// body
$body-color: #000;

// links
$link-decoration: none;

// font-sizes
$font-sizes: (
  1: 40px,
  2: 32px,
  3: 28px,
  4: 24px,
  5: 20px,
  6: 14px
) ;

# <img src="https://sass-lang.com/assets/img/styleguide/color-1c4aab2b.png" style="position: relative; top: 5px;" height="80" /> 


## Placeholder Mixin in SCSS

```CSS
@mixin placeholder {
  ::-webkit-input-placeholder {@content}
  :-moz-placeholder           {@content}
  ::-moz-placeholder          {@content}
  :-ms-input-placeholder      {@content}  
}

@include placeholder {
    font-style:italic;
    color: white;
    font-weight:100;
}
```

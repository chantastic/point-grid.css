# point.css
Point-based layout system in CSS on a modular scale

## Install
npm:
`npm install point.css`

browser:
`<link rel="stylesheet" href="//unpkg.com/point.css" />`

## Use
```
<div class="m-1 p-3">
  This has .5rem margin and 2rem padding.
</div>
```

## All the code
```css
/*! point.css */
.m-1{margin:.5rem}
.m-2{margin:1rem}
.m-3{margin:2rem}
.m-4{margin:4rem}
.my-1{margin-top:.5rem;margin-bottom:.5rem}
.my-2{margin-top:1rem;margin-bottom:1rem}
.my-3{margin-top:2rem;margin-bottom:2rem}
.my-4{margin-top:4rem;margin-bottom:4rem}
.mx-1{margin-right:.5rem;margin-left:.5rem}
.mx-2{margin-right:1rem;margin-left:1rem}
.mx-3{margin-right:2rem;margin-left:2rem}
.mx-4{margin-right:4rem;margin-left:4rem}
.mt-1{margin-top:.5rem}
.mt-2{margin-top:1rem}
.mt-3{margin-top:2rem}
.mt-4{margin-top:4rem}
.mr-1{margin-right:.5rem}
.mr-2{margin-right:1rem}
.mr-3{margin-right:2rem}
.mr-4{margin-right:4rem}
.mb-1{margin-bottom:.5rem}
.mb-2{margin-bottom:1rem}
.mb-3{margin-bottom:2rem}
.mb-4{margin-bottom:4rem}
.ml-1{margin-left:.5rem}
.ml-2{margin-left:1rem}
.ml-3{margin-left:2rem}
.ml-4{margin-left:4rem}
.p-1{padding:.5rem}
.p-2{padding:1rem}
.p-3{padding:2rem}
.p-4{padding:4rem}
.py-1{padding-top:.5rem;padding-bottom:.5rem}
.py-2{padding-top:1rem;padding-bottom:1rem}
.py-3{padding-top:2rem;padding-bottom:2rem}
.py-4{padding-top:4rem;padding-bottom:4rem}
.px-1{padding-right:.5rem;padding-left:.5rem}
.px-2{padding-right:1rem;padding-left:1rem}
.px-3{padding-right:2rem;padding-left:2rem}
.px-4{padding-right:4rem;padding-left:4rem}
.pt-1{padding-top:.5rem}
.pt-2{padding-top:1rem}
.pt-3{padding-top:2rem}
.pt-4{padding-top:4rem}
.pr-1{padding-right:.5rem}
.pr-2{padding-right:1rem}
.pr-3{padding-right:2rem}
.pr-4{padding-right:4rem}
.pb-1{padding-bottom:.5rem}
.pb-2{padding-bottom:1rem}
.pb-3{padding-bottom:2rem}
.pb-4{padding-bottom:4rem}
.pl-1{padding-left:.5rem}
.pl-2{padding-left:1rem}
.pl-3{padding-left:2rem}
.pl-4{padding-left:4rem}
.t-1{top:.5rem}
.t-2{top:1rem}
.t-3{top:2rem}
.t-4{top:4rem}
.r-1{right:.5rem}
.r-2{right:1rem}
.r-3{right:2rem}
.r-4{right:4rem}
.b-1{bottom:.5rem}
.b-2{bottom:1rem}
.b-3{bottom:2rem}
.b-4{bottom:4rem}
.l-1{left:.5rem}
.l-2{left:1rem}
.l-3{left:2rem}
.l-4{left:4rem}
```

## Options
If you're in a situation where `rem` isn't a usable value, there are fixed pixel versions available.

[7-point.css](./7-point.css)  
[8-point.css](./8-point.css)  
[10-point.css](./10-point.css)  

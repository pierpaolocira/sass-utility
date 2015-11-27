# sass-utility
Utilities for Sass CSS extension language

Hot to use

Import
@import "rgbas";

Define an RGBa variable
$lightGray: rgba(204, 204, 204, 0.5);

Use it (double parentesis are mandatory for a Sass issue)
@include background-color-rgba(($lightGray));

# System of margins with SASS (SCSS).

Spacing for components to be reusable.

How to use in HTML:

    <div class="m16"></div>
    <div class="m16-only-mobile"></div>
    <div class="m16-only-tablet"></div>
    <div class="m16-only-desktop"></div>
    <div class="m16-only-larger"></div>

How to use in SCSS:

Import file.

    @include system-margins('mobile');

    @media screen and (min-width: 768px) {
        @include system-margins('tablet');
    }

    @media screen and (min-width: 992px) {
        @include system-margins('desktop');
    }

    @media screen and (min-width: 1200px) {
        @include system-margins('larger');
    }

Example: https://codepen.io/feermooraes/pen/zWgeay


# bootstrap5-checkout-example

\*So far, easiest way seems to be just copy the svg entirely from site, no downloading.

0. npm i bootstrap-icons
1. Take bootstrap-icons.svg file out of bootstrap-icons folder,
   but it in the same directory as your index HTML file.

<svg class="bi" width="32" height="32" fill="currentColor">
            <use xlink:href="bootstrap-icons.svg#heart-fill" />
          </svg>
2. Go to bootstrap-icons folder, go to icons, copy and paste into an
img folder, a file holding the svg icon you want.

img/alarm-fill.svg

3.                 <img src="./img/alarm-fill.svg" width="100" alt="alarm-fill" />

=> this way won't let you change its color

4.  :root {
    --css-variables: url("");
    }

    .circle {
    width: 10;
    height: 10;
    background-image: var(--circle);
    }


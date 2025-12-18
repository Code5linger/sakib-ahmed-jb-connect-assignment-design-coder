/\*
CSS Best Practice (Cristina Gordon, Design+Code)
Box (Position, Display, Width, Margin, ...)
Text
Background
Border
Other (Alphabetically )

For fonts, use rem
html {
font-size: 62.5%;
}

.text {
font-size: 1.6rem;
}

.text div {
font-size: 2.4rem;
}

box model,padding,border,margin — use pixels

For width/height, it'll depend on whether I want the element to be a fixed size, or a relative size. I might want one div to always be 250px wide, while another one should be 50% of the available space.

For color, use hsl or oklch

\*\*\*\* CSS Guideline
-P- React for Designers > 02. BasicStylingCSS > 4:49 >
Default Font Size in between 15-20 PX
-webkit-font-smoothing: antialiasing;
line-height: 1.3;
font-weight
Set `a` style after body f

CSS Reset https://piccalil.li/blog/a-more-modern-css-reset/

https://www.toptal.com/developers/webdevchecklist
https://chromewebstore.google.com/detail/web-developer-checklist/iahamcpedabephpcgkeikbclmaljebjp?hl=en-US
https://chromewebstore.google.com/category/extensions/productivity/developer?hl=en-US

https://www.sitepoint.com/web-development-checklists/

https://www.hotjar.com/web-design/checklist/

https://redbooth.com/hub/web-development-checklist/

https://www.browserstack.com/guide/website-design-checklist

https://www.digitalsilk.com/digital-trends/website-design-checklist/

---

body {
line-hight: 1
}

BEM Naming COnvention

:root {
--color-primary-400: #00a1ab;
--color-primary-500: #3741a0;

--color-accent-400: #00cdac;
--color-accent-500: #114243;

--color-neutral-100: #fff;
--color-neutral-100: #fafafa;
--color-neutral-300: #e5e3e8;
--color-neutral-400: #4e4e4e;
}

---

.bg--light {
--bg: var(--color-neutral-400);
--fg: var(--color-neutral-100);

color: #4e4e4e;
background: linear-gradient(-45deg, #e5e3e8, #fafafa);
}

.button {
display: inline-block;
text-decoration: none;
padding: 0.5em 0.75em;
border-radius: 0.25em;
text-transform: uppercase;
font-weight: 700;
background: var(--bg, var(--color-primary-400));
color: var(--fg, var(--color-neutral-100));
}

\*/

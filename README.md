![image](https://user-images.githubusercontent.com/6764957/83363763-7d5c1a80-a3ce-11ea-95fb-2df3dd5aad34.png)

> **Easy ways to add design flair, user delight, and whimsy to your product!**

*The Spark Joy philosophy is explained in further detail [in my book](https://learninpublic.org/), check it out if you'd like to explore how this approach applies to a lot more than design utilities.*

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Web Design in 4 minutes](#web-design-in-4-minutes)
- [CSS/UI Templates](#cssui-templates)
- [Spacing](#spacing)
- [Layout](#layout)
- [Typography](#typography)
- [Colors](#colors)
- [Icons and Favicons](#icons-and-favicons)
- [Diagramming](#diagramming)
- [Wireframing](#wireframing)
- [Graphics and SVG Illustrations](#graphics-and-svg-illustrations)
- [Pure CSS Tricks](#pure-css-tricks)
- [Background Stuff](#background-stuff)
- [Spinners](#spinners)
- [Animations & Transitions](#animations--transitions)
- [Individual HTML Elements](#individual-html-elements)
- [Design Software](#design-software)
- [Canvas](#canvas)
- [WebGL](#webgl)
- [3D](#3d)
- [Video](#video)
- [Onboarding](#onboarding)
- [Misc Genres (Handwriting, Pixel, ASCII styles)](#misc-genres-handwriting-pixel-ascii-styles)
- [Other Lists like this one](#other-lists-like-this-one)
- [Helpful podcasts/talks/articles](#helpful-podcaststalksarticles)
- [More Free Stuff](#more-free-stuff)
- [Paid Premium Services](#paid-premium-services)
- [Courses](#courses)
- [Interaction/Design Inspo](#interactiondesign-inspo)
- [Mock APIs](#mock-apis)
- [Copy and Emails](#copy-and-emails)
- [Random Stuff That Doesn't Fit Anywhere](#random-stuff-that-doesnt-fit-anywhere)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Web Design in 4 minutes

Keep it simple: https://jgthms.com/web-design-in-4-minutes/

## CSS/UI Templates

HTML/CSS nice templates

- https://www.free-css.com/
- https://www.creative-tim.com/
- https://wickedtemplates.com using Tailwind v2 (and [wickedblocks](https://blocks.wickedtemplates.com/))
- https://www.tailwind-kit.com/ free tailwind component kit
- https://themeselection.com/
- https://html5up.net/
- https://frontendor.com/ using bootstrap
- https://cruip.com/ HTML, React, Vue.js, and Tailwind templates

### Serious CSS Frameworks 

#### Heavier CSS Frameworks

bigger learning curve, may have js, but more OOTB)

  - Bootstrap
  - [Foundation](https://get.foundation/sites/docs/)
  - [Blaze UI](https://www.blazeui.com/)
  - [PatternFly](https://www.patternfly.org/v4/documentation/core/components/aboutmodalbox)
  - [UIKit](https://getuikit.com/docs/introduction)
  - Utility CSS
    - [Bonsai CSS](https://www.bonsaicss.com/)
    - [Tailwindcss](https://tailwindcss.com/)
  - Web Components
    - [Weightless](https://weightless.dev/elements/checkbox)
    - [Shoelace](https://shoelace.style/)

### Drop-in CSS Frameworks

lighter, no js. preview some of these with https://sites.yax.com/

  - [Spectre.css](https://picturepan2.github.io/spectre/getting-started/installation.html)
  - https://purecss.io/
  - https://ajusa.github.io/lit/
  - https://screencss.com/
  - https://andybrewer.github.io/mvp/
  - https://github.com/xz/new.css
  - https://github.com/oxalorg/sakura
  - https://native-elements.dev/
  - https://watercss.kognise.dev/
  - https://jenil.github.io/chota/ 
  - https://github.com/susam/spcss
  - https://elementcss.neocities.org/
  - https://codepen.io/web-dot-dev/pen/abpoXGZ the base classes for web.dev/learn/csss
  - Collections of even more:
    - https://github.com/dohliam/dropin-minimal-css
    - https://github.com/dbohdan/classless-css
    - https://github.com/ubershmekel/cssbed
    - https://thesephist.github.io/paper.css/ and https://thesephist.github.io/blocks.css/
    
Superlight: [58 bytes of css to look great nearly everywhere](https://jrl.ninja/etc/1/)

```css
main {
  max-width: 38rem;
  padding: 2rem;
  margin: auto;
}
```

### Fun CSS Frameworks

focus is fun

  - https://www.getpapercss.com/ (handrwritingey css similar to roughjs)
  - https://terminalcss.xyz/

focus is brutalism

- https://secretgeek.github.io/html_wysiwyg/html.html This page is a truly naked, brutalist html quine.
- https://mrcoles.com/demo/markdown-css/ CSS to make HTML markup look like plain-text markdown.

focus is fun/nostalgia

- [NES.css](https://github.com/nostalgic-css/NES.css): NES.css is a NES-style(8bit-like) CSS Framework.
- [PSone.css](https://github.com/micah5/PSone.css): PS1 style CSS Framework, inspired by NES.css.
- [LaTeX.css](https://latex.now.sh/)
- Operating System CSS
  - [98.css](https://github.com/jdan/98.css): A Windows 98 inspired framework for building faithful recreations of old UIs.
    - [Office 97 clipart in svg format](https://archive.org/details/mso97clipart)
  - [XP.css](https://github.com/botoxparty/XP.css): A Windows XP inspired framework for building faithful recreations of operating system GUIs. An extension of 98.css.
  - [7.css](https://khang-nd.github.io/7.css/)
  - [Commodore 64 CSS](http://pixelambacht.nl/2013/css3-c64/)
  - DOS: [BOOTSTRA.386](https://github.com/kristopolous/BOOTSTRA.386): A vintage 1980s DOS inspired Twitter Bootstrap theme
- [Text UI CSS](https://github.com/vinibiavatti1/TuiCss): bios like UI's
- [New Dawn](https://github.com/npjg/new-dawn): A mac classic After Dark inspired stylesheet.
- [Geocities Bootstrap theme](https://code.divshot.com/geo-bootstrap/)
- more https://dev.to/iainfreestone/10-resources-for-recreating-old-school-retro-user-interfaces-today-hkj

focus in futurism
  
- Arwes - Futuristic Sci-Fi and Cyberpunk Graphical User Interface Framework for Web Apps https://arwes.dev/
- http://augmented-ui.com/ - Futuristic, Sci-Fi shaping for any element

### CSS Resets

more control in exchange for more work on your part.

  - eric meyer v2 https://meyerweb.com/eric/tools/css/reset/
  - https://github.com/jensimmons/cssremedy css working group's reset if it didnt have to worry about tech debt 
  - https://github.com/tiaanduplessis/nanoreset
  - https://nicolas-cusan.github.io/destyle.css/
  - https://hankchizljaw.com/wrote/a-modern-css-reset/
  - https://gist.github.com/DavidWells/18e73022e723037a50d6
  - http://necolas.github.io/normalize.css/ (yes, technically does more than a reset)
    - https://github.com/sindresorhus/modern-normalize is a smaller version that just supports latest Chrome, Firefox, and Safari
    - Tailwind's https://tailwindcss.com/docs/preflight/ is built atop normalize
  - https://github.com/kripod/css-homogenizer - a modern take on Eric Meyer's Reset, based upon direct comparison between user agent style sheets.
  - Jamie Kyle CSS preset https://twitter.com/buildsghost/status/1360343126510981122?s=20

### CSS A11y Checkers

- https://github.com/jackdomleo7/Checka11y.css
- https://ffoodd.github.io/a11y.css/
- https://github.com/mike-engel/a11y-css-reset
- chrome extension https://chrome.google.com/webstore/detail/a11ycss/iolfinldndiiobhednboghogkiopppid?hl=en


### Tailwind Component Libraries

- https://github.com/thedevdojo/tails
- http://tailwindcomponents.com/
- https://tailwindui.com/components
- https://merakiui.com/
- https://www.gustui.com/
- https://mertjf.github.io/tailblocks/
- https://shuffle.dev/ Tailwind visual builder


## Spacing

More. Spacing. Please.

[Double your whitespace](https://learnui.design/blog/7-rules-for-creating-gorgeous-ui-part-1.html#rule-3-double-your-whitespace)

## Layout

- https://gedd.ski/post/article-grid-layout/
- css grid generators 
  - https://grid.layoutit.com/
  - https://cssgrid-generator.netlify.app/
- https://every-layout.dev/
- https://csslayout.io/ ([github](https://github.com/phuoc-ng/csslayout))
- Visual Hierarchy https://youtu.be/qZWDJqY27bw

special topic - responsive media

- https://piccalil.li/tutorial/build-a-responsive-media-browser-with-css/

## Typography

typography matters https://twitter.com/kvncnls/status/1399077512014086150?s=21

### Fonts

<details>
  <summary>For speed, use System Font Stacks (incl. Segoe and Roboto)</summary>
  
  ([what are these?](https://css-tricks.com/snippets/css/system-font-stack/))
  - GitHub: `font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Noto Color Emoji",  "Segoe UI Emoji", "Segoe UI Symbol";`
  - [VS Code Autocomplete](https://twitter.com/kudapara/status/1093553125661773825?s=20): `font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif`
  - [`font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif;`](https://twitter.com/_etiennemartin/status/1221114860479696896?s=20)
  - [`font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
  "Roboto", "Oxygen", "Ubuntu", "Helvetica Neue", Arial, sans-serif;`](https://twitter.com/laurosilvacom/status/1221138641923141632)
  - [`font-family: ‘system-ui’, sans-serif;`](https://twitter.com/esojrafael/status/1221107296127729664?s=20)
    - the ['system-ui' generic font family is new, standardizing name across Safari, Firefox and Blink](https://www.chromestatus.com/feature/5640395337760768)
  - [Sanitize.css](https://github.com/csstools/sanitize.css#typography-uses-the-default-system-font): 
  
```css
  html {
    font-family:
      system-ui,
      /* macOS 10.11-10.12 */ -apple-system,
      /* Windows 6+ */ Segoe UI,
      /* Android 4+ */ Roboto,
      /* Ubuntu 10.10+ */ Ubuntu,
      /* Gnome 3+ */ Cantarell,
      /* KDE Plasma 5+ */ Noto Sans,
      /* fallback */ sans-serif,
      /* macOS emoji */ "Apple Color Emoji",
      /* Windows emoji */ "Segoe UI Emoji",
      /* Windows emoji */ "Segoe UI Symbol",
      /* Linux emoji */ "Noto Color Emoji";
  }
  code, kbd, pre, samp {
    font-family:
      /* macOS 10.10+ */ Menlo,
      /* Windows 6+ */ Consolas,
      /* Android 4+ */ Roboto Mono,
      /* Ubuntu 10.10+ */ Ubuntu Monospace,
      /* KDE Plasma 5+ */ Noto Mono,
      /* KDE Plasma 4+ */ Oxygen Mono,
      /* Linux/OpenOffice fallback */ Liberation Mono,
      /* fallback */ monospace;
  }
```

  - [Some systems come with good premium fonts](https://twitter.com/MatiasEduardoPR/status/1093508700378144768?s=20) - Apple OSes have `“avenir next”, “avenir”, “proxima-nova”`
  
</details>

- Consider your site personality
  - Elegant/Classic: serif like [`Freight Text`](https://fonts.adobe.com/fonts/freight-text), [`Adobe Garamond`](https://fonts.adobe.com/fonts/adobe-garamond), [`PT Serif`](https://fonts.google.com/specimen/PT+Serif)
  - Playful: rounded sans serif like [`Proxima Soft`](https://fonts.adobe.com/fonts/proxima-soft)
  - Plain/Safe: neutral sans serif like [`Freight Sans`](https://fonts.adobe.com/fonts/freight-sans), [`Inter`](https://rsms.me/inter/), [`Proxima Nova`](https://fonts.adobe.com/fonts/proxima-nova)
  - Sciency/technical: squared off (geometric) sans like [`DIN`](https://fonts.adobe.com/fonts/din-2014), [`Industry`](https://fonts.adobe.com/fonts/industry)
  - monospace fonts: https://devfonts.gafi.dev/
  - Variable fonts: https://whirlybirdie.com/
  - Novelty: http://velvetyne.fr/
  - [use a Uniwidth font (not monospace) for interface design](https://uxdesign.cc/uniwidth-typefaces-for-interface-design-b6e8078dc0f7)
  - [14 free programming fonts](https://twitter.com/zenorocha/status/1359508613606199301?s=20)
- Free fonts that are great with examples (thanks [@edadams](https://github.com/sw-yx/spark-joy/issues/22))
  - Google Fonts - ([see Harry Roberts on Google Font loading perf](https://csswizardry.com/2020/05/the-fastest-google-fonts/) - you should [self host this](https://wicki.io/posts/2020-11-goodbye-google-fonts/))
    - https://bueltge.de/free-web-font-combinations/
    - [40 best google fonts by Typewolf](https://www.typewolf.com/google-fonts)
    - [50 selections of google fonts](https://www.notion.so/e873b52e0cc54f2981acc430417ba61d?v=05acdd40b0564920be69f5347f619bc3)
    - [Noto Sans](https://www.google.com/get/noto/)
    - [Fira Sans](https://fonts.google.com/specimen/Fira+Sans) - related to [Fira Code](https://github.com/tonsky/FiraCode) for devvy stuff
    - [Raleway](https://fonts.google.com/specimen/Raleway)
    - [Open Sans](https://fonts.google.com/specimen/Open+Sans)
    - [Recursive](https://www.recursive.design/) - 1 variable font that can handle both monospace and UI usecases, very versatile
    - Cavivanar https://twitter.com/atav1k/status/1178096244490723328?s=19
    - Jack Butcher faves
      - Rubik
      - Work Sans
      - IBM Plex Family (Mono, Sans, Serif)
  - Fontshare 50 free fonts https://www.fontshare.com/
    - [Erik Kennedy picks from these](https://twitter.com/erikdkennedy/status/1374382006658723840?s=20)
  - Premium-looking Free Fonts https://learnui.design/blog/ultimate-guide-similar-fonts.html
    - Apercu · Avenir · Circular · DIN · Futura · Gotham · Helvetica · Proxima Nova · Times New Roman
  - Chivo https://www.latinxswhodesign.com/
  - [Lato](http://www.latofonts.com/) Well known, very readable, pretty, client favorite
  - [Libre Franklin](https://beautifulwebtype.com/libre-franklin/) Elegant and thin
  - [IBM Plex Sans](https://www.ibm.com/plex/) Loads of weights, beautifully done
  - [Clear Sans](https://01.org/clear-sans)
  - [Atkinson Hyperlegible](https://brailleinstitute.org/freefont) from Braille institue
  - [Inter](https://rsms.me/inter/) [Rasmus'](https://rsms.me/) typeface carefully crafted & designed for computer screens.
  - [Jetbrains Mono](https://www.jetbrains.com/lp/mono/) - Monospace font for devvy stuff
  - Handwritten Fonts - great for presentations, annotated illustrations
    - https://www.urbanfonts.com/fonts/handwritten-fonts.htm
    - Caveat and Reenie Beanie on google fonts  https://twitter.com/round/status/1178090890004455424?s=19
- https://fontsarena.com/ 
- "Open Source Beautiful Fonts" [by Gontijo](https://twitter.com/gontijodesign/status/1394624373823348737)
- Font Pairing
  - https://fontpair.co/ 
  - https://fontjoy.com/ 
  - http://femmebot.github.io/google-type/
  - https://www.boldwebdesign.com.au/
  - https://justmytype.co/
  - https://bueltge.de/free-web-font-combinations/
  - Canva has a great tool: https://www.canva.com/font-combinations/
  - https://www.colorsandfonts.com/font-pairings
- [Font variants and oldstyle numbers](https://www.jonathan-harrell.com/blog/better-typography-with-font-variants/)
- steve schoger blessed typekit fonts **for UI's**
  - proxima nova
  - aktiv grotesk
  - acumin pro
  - Museo Sans ([example](https://youtu.be/ZJj7uNdzPpM?t=566)) and similar from [TypeKit](https://fonts.adobe.com/fonts?browse_mode=default&filters=cl:ss,rc:p,ns:uc)
- https://practicaltypography.com/system-fonts.html
- https://practicaltypography.com/free-fonts.html
- eye catching fun fonts
  - https://www.haleyfiege.fun/fonts
  - pixel fonts https://twitter.com/castpixel/status/1281345373336985612?s=20
- CSS 3D text https://markdotto.com/playground/3d-text/
- JS 3D text https://bennettfeely.com/ztext/ 
- TypeSpiration https://typespiration.com/ premade font pairings for you
- more opinions places
  - https://muffingroup.com/blog/best-free-fonts/
  - https://type-scale.com/
  - https://practicaltypography.com
  - http://thinkingwithtype.com/
  - https://typographyforlawyers.com/
  - http://webtypography.net/intro/
  - https://www.youtube.com/watch?v=Vd6jZR-GknA 
  - [6 ways to justify font choices in your designs](https://learnui.design/blog/justifying-font-choices.html)
  - [statistical data on font usage](https://dribbble.com/stories/2021/04/26/web-design-data-fonts)
   

<details>
  <summary> Premium fonts and some examples </summary>
  
  - Proxima Nova https://a16z.com/ (on Typekit)
  - Graphik https://type.today/en/Graphik
  - https://www.typewolf.com/
  - Arida Black (maggie's font) https://www.myfonts.com/fonts/latinotype/arida/black/
  - [Dank Mono](https://dank.sh/)
  - Tekton https://twitter.com/round/status/1178090204562968576?s=19
  
you can learn more about proofing premium fonts here https://www.typography.com/blog/text-for-proofing-fonts

</details>

#### Font Loading Strategy

- https://github.com/zachleat/web-font-loading-recipes
- https://iainbean.com/posts/2021/5-steps-to-faster-web-fonts/
- Everything [Harry Roberts](https://twitter.com/csswizardry) writes
  - [Google Fonts strategy](https://csswizardry.com/2020/05/the-fastest-google-fonts/)
  
     ```html
      <!--
        - 1. Preemptively warm up the fonts’ origin.
        -
        - 2. Initiate a high-priority, asynchronous fetch for the CSS file. Works in
        -    most modern browsers.
        -
        - 3. Initiate a low-priority, asynchronous fetch that gets applied to the page
        -    only after it’s arrived. Works in all browsers with JavaScript enabled.
        -
        - 4. In the unlikely event that a visitor has intentionally disabled
        -    JavaScript, fall back to the original method. The good news is that,
        -    although this is a render-blocking request, it can still make use of the
        -    preconnect which makes it marginally faster than the default.
        -->

      <!-- [1] -->
      <link rel="preconnect"
            href="https://fonts.gstatic.com"
            crossorigin />

      <!-- [2] -->
      <link rel="preload"
            as="style"
            href="$CSS&display=swap" />

      <!-- [3] -->
      <link rel="stylesheet"
            href="$CSS&display=swap"
            media="print" onload="this.media='all'" />

      <!-- [4] -->
      <noscript>
        <link rel="stylesheet"
              href="$CSS&display=swap" />
      </noscript>
      ```
- `font-display: optional` [may be good](https://css-tricks.com/a-font-display-setting-for-slow-connections/)
  - but harry roberts [doesnt like it](https://csswizardry.com/2020/05/the-fastest-google-fonts/#comparisons-and-visualisations)
- don't load fonts if `prefers-reduced-data` [see Kilian Valkhof](https://css-tricks.com/responsible-conditional-loading/)

### Line Height

https://www.thegoodlineheight.com

### Line Width

Don't forget setting `max-width` - betweeen 60-75chars is good.

- https://pearsonified.com/characters-per-line/
- https://grtcalculator.com/
- https://www.charactercountonline.com/
- https://charcounter.com/en/

### Kerning and char spacing

<details>
<summary>
Don't forget setting Leading on your h1 text and minding kerning:
</summary>

![https://hottips.imgix.net/2020/07/044-tracking-animation.gif](https://hottips.imgix.net/2020/07/044-tracking-animation.gif)

- https://creativemarket.com/blog/whats-the-difference-between-leading-kerning-and-tracking
- https://99designs.com/blog/tips/11-kerning-tips/

</details>

Note: `vw` has known a11y issues: Preserve Zooming. [Sara Soueidan](https://twitter.com/SaraSoueidan/status/1121645149983891457?s=20) recommends wrapping with `calc`, e.g. `font-size: calc(16px + .3vw);`

You may wish to use `max-width: 60ch` on content. [Note on the `ch` unit not being EXACTLY 60 chars](https://meyerweb.com/eric/thoughts/2018/06/28/what-is-the-css-ch-unit/)

### Font Sizing

DON'T GO CRAZY WITH FONT SIZES. 

- Try to use 1-2 sizes and vary other things like weight, space/leading, color, casing.
- Don't rely on varying fontsize to control hierarchy - also use font weight (normal = 400/500, heavy = 600/700) and color
  - Don't go under font weight 400, use a lighter color or smaller fontsize instead
- Fluid typography with [`clamp`](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp): `font-size: clamp(1.125rem, 1rem + 2vw, 1.5rem)`
  - [CSS Tricks](https://css-tricks.com/design-v18/) v18: `font-size: clamp(2rem, calc(2rem + 1.2vw), 3rem);`
  - Another responsive typography fallback - [`font-size: calc(1rem + 2px + ((100vw - 550px) / 250))`](https://twitter.com/Kikobeats/status/1093620157912616966?s=20) - you can [fit text to screen width](https://twitter.com/shshaw/status/1240647643388395521?s=20) 
  - demo it with this https://fluid-typography.netlify.app/
- [Inter/Tailwind font-size combo](https://twitter.com/samselikoff/status/1204412222593568769?s=20)
- [BAD, SLOW fontsize calc](https://twitter.com/drewml/status/1115339490179072000?s=20)
- [Complete font-size notes](https://manishearth.github.io/blog/2017/08/10/font-size-an-unexpectedly-complex-css-property/)


### Typography Talks

- Typography for Developers (2hrs) https://www.youtube.com/watch?v=agbh1wbfJt8
- Adam Argyle on Typography https://www.youtube.com/watch?v=aaro26rK61o&t=874s
- Web Typography (48mins) https://www.youtube.com/watch?v=hbIZX6tE9JY
  1. Don't trust computers
  2. Use the default font size for paragraph text
  3. Adjust type size according to reading distance
  4. Adjust the font size if the typeface requires it
  5. Set tables to be read
  6. Resize display text as you would an image
  7. Reduce your playload
  8. Optimise page render timing
- https://www.youtube.com/watch?v=OgsHSVsNRdg

### Other Typography Resources

- Typography in 10 minutes https://medium.com/nextux/become-a-typography-nerd-in-under-10-minutes-5a7eda093cb3
- Font smoothing - [explained](https://szafranek.net/blog/2009/02/22/font-smoothing-explained/), [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/font-smooth)
- Tool for learning what fonts other people use https://fontanello.oktavilla.se/
- [FlowType.js](https://simplefocus.com/flowtype/)
- [FitText](https://css-tricks.com/viewport-sized-typography/)
- if all letters at the same height all caps this is called [Majuscule](https://www.wordgenius.com/words/majuscule)
- International fonts stack https://www.figma.com/blog/when-fonts-fall/
- In future, try out [leading-trim](https://medium.com/microsoft-design/leading-trim-the-future-of-digital-typesetting-d082d84b202) 
- https://piccalil.li/tutorial/improve-the-readability-of-the-content-on-your-website
- css podcast primer on typography https://thecsspodcast.libsyn.com/tcp036-v2

If building a collaborative design tool that offers font choice, see how Figma does it https://youtu.be/kVD-sjtFoEI

## Colors

Pick a primary "brand" color to match your personality. [DO NOT OVERUSE IT.](https://twitter.com/steveschoger/status/1299372332579008515)

- Blue: safe, familiar
- Gold: expensive, sophisticated ([Examples](https://twitter.com/erikdkennedy/status/948914185596960768), [again](https://twitter.com/erikdkennedy/status/1331236629571362816?s=20))
- Pink: fun, not so serious

You can also have a grey for secondary content, and lighter grey for tertiary content.

Don't use system default/named colors, too brutal. Soften it a bit. "[Never use black](https://ianstormtaylor.com/design-tip-never-use-black/)" has been proposed as a rule, but [this is debated](https://news.ycombinator.com/item?id=24303042).

1 in 12 men and 1 in 200 women have color blindness. Make sure to check that important distinctions can be perceived. 

- https://twitter.com/LoanReads/status/1313974210151305218?s=20
- https://www.colourblindawareness.org/colour-blindness/

<details>
<summary>
Example blueish palette
</summary>
  
  

Monotone: 

- White-ish Card background: #FCFCFC
- Blueish-Black icons: #1C1E20
- Lighter text on white: #485963
- Bluish background: #202D34

Multicolor:

- Black: #1d1d1d.
- purple: #b066ff;
- blue: #203447;
- lightblue: #1f4662;
- blue2: #1C2F40;
- yellow: #ffc600;
- pink: #EB4471;
- white: #d7d7d7;

</details>


<details>
<summary>  
You may or may not want to use generic names if you want it swappable for dark mode:
</summary>
  
Example [yellowish palette](https://codepen.io/oliviale/full/XyqQYL):


- primary-light: #FFD151 mustard
- primary-dark: #FFAE03 UCLA gold
- secondary-success: #20A39E light sea green
- secondary-warning: #EF5B5B sunset orange
- secondary-info: #08D377 dark cerulean
- grays: #E8E9E9, #D1D3D4, #BABDBF, #808488, #666A6D, #4D5052, #333537, #1C1D1E

Examples: https://dev.to/dcodeyt/add-dark-mode-to-your-websites-with-css-5bh4

**Note - THIS IS DISPUTED!!!** Even Slack's impl has separate light and dark theming.

> The problem is "primary" isn't a color, it's a measure of contrast in the current context. On the same page you might have a white panel with a black button and a black panel with a white button, and both of those buttons are "primary" even though they are different colors. - [Adam Wathan](https://twitter.com/adamwathan/status/1291724757402976257?s=20)

</details>

One liner dark mode (careful about perf!): `filter: invert(100%) hue-rotate(180deg);` - more [filters here](https://svelte.dev/repl/defc901c5f434ed4a76161605cf1db76?version=3.29.0)

### Palette Generators

- https://colorgen.dev/
- https://color.adobe.com/create
- https://www.colorsandfonts.com/
- https://colorswall.com/
- https://coolors.co/
- https://colorsinspo.com
- https://huey.design/ Rapid color palettes across the rainbow
- https://duo.alexpate.uk/
- https://colorhunt.co/
- https://2colors.colorion.co/
- https://dribbble.com/colors/4030e8
- https://palettte.app/ (advanced tool; try importing the default palettes)
- https://www.paletter.app/ - Create Professional Color Palettes from a Single Color
- http://colours.neilorangepeel.com/category/red/
- https://www.colorbox.io (by Lyft Design https://design.lyft.com/)
- Consider [darker/lighter color variations](https://learnui.design/blog/color-in-ui-design-a-practical-framework.html)
- https://croncolor.com/color-tool
- https://leonardocolor.io/?colorKeys=%236fa7ff&base=ffffff&ratios=3%2C4.5&mode=CAM02
- https://happyhues.co/
- https://www.colourlovers.com/ *recommended by Tracy Osborn*
- https://flatuicolors.com/
- https://colorsupplyyy.com/
- [chroma.js color palette helper](https://gka.github.io/palettes/#/9|s|00429d,96ffea,ffffe0|ffffe0,ff005e,93003a|1|1)
- https://palx.jxnblk.com/
- https://hotpot.ai/assistant/color_assistant Get suggestions for palettes, gradients, and text colors. Hit the space bar for ML-powered ideas.
- https://tltemplates.com/tool/color/tailwind-color Tailwind inspired color generator
- https://yeun.github.io/open-color/
- http://khroma.co/ neural network generated color palettes
- https://learnui.design/tools/data-color-picker.html Color picker for data visualizations
- https://learnui.design/tools/accessible-color-generator.html Accessible color generator
- https://maketintsandshades.com/ Generate tint and shades from hex code
- Tailwind:
  - https://tailwind.ink/
  - https://www.tailwindshades.com/
  - https://tailwind.simeongriggs.dev
  - https://javisperez.github.io/tailwindcolorshades/
  - https://tailwind-color-picker.jessarcher.com
- Special usecases: 
  - Pick colors from an image https://imagehive.co/
  - Mix colors in pure CSS https://css-tricks.com/mixing-colors-in-pure-css/
  - [HSLuv](https://www.hsluv.org/comparison/) color space is preferable to HSL. [Palette generator](https://colors.madscience.design/)



### Color Gradients

- gradients https://mybrandnewlogo.com/color-gradient-generator
- CSS Gradient Text https://twitter.com/argyleink/status/1281623252662489088/photo/2
- https://mycolor.space/gradient Generate a CSS Color Gradient
- https://webgradients.com/ free collection of 180 linear gradients 
- https://uigradients.com/#Petrichor
- https://learnui.design/tools/gradient-generator.html (to avoid [the "gray zone" problem](https://css-tricks.com/the-gray-dead-zone-of-gradients/))
- Adam Argyle conic CSS gradient examples https://www.conic.style/
- https://www.grabient.com/
- ANIMATED GRADIENTS https://www.gradient-animator.com/
- Subtle gradients by bumping only saturation on HSL (thanks [argyleink](https://twitter.com/argyleink/status/1197205254623780864)) - You can [really take this to the extreme](https://twitter.com/argyleink/status/1216815958917992450?s=20)!


### Color knowledge

<details>
  <summary> Not tools but still important so here they are </summary>

- [A Beginner’s Guide to Applying Color in UI Design](https://georgefrancis.dev/writing/a-beginners-guide-to-applying-color-in-ui-design/?ref=sidebar)
- [Sarah Drasner on Color](https://css-tricks.com/nerds-guide-color-web/)
- [Louisa Barret on Color](https://www.youtube.com/watch?v=NdKAUXAvt8E)
- [Erik Kennedy on HSB](https://learnui.design/blog/the-hsb-color-system-practicioners-primer.html)
- [Erik Kennedy on color variations](https://learnui.design/blog/color-in-ui-design-a-practical-framework.html)
- [JustinMezzell on Color](https://medium.com/@JustinMezzell/how-i-work-with-color-8439c98ae5ed) - advanced stuff on picking color tone/temperature
- [Justin Baker on Color Theory](https://medium.muz.li/the-ultimate-ux-guide-to-color-design-4d0a18a706ed)
- [Convertkit on Color Theory](https://convertkit.com/color-theory)
- [How to pick more beautiful colors for your data visualizations](https://blog.datawrapper.de/beautifulcolors/)
- [How to do Dark Mode right](https://darkmodedesign.xyz/)
- [Inventorying and naming a Color Palette at UXPin](https://medium.com/@marcintreder/design-system-sprint-2-one-color-palette-to-rule-them-all-d0114ed1f659)
- [Reasoning about Color](http://notes.neeasade.net/color-spaces.html) some light reading on color spaces and transforms (eg "pastelize" operation) 
- [Picking your palette](https://refactoringui.com/previews/building-your-color-palette/) 

(fun) [history of primary colors](https://publicdomainreview.org/essay/primary-sources)

</details>

## Icons and Favicons

### Favicons

Don't forget them!

  - [How to Favicon in 2021](https://css-tricks.com/how-to-favicon-in-2021/)
  
     ```html
    <link rel="icon" href="/favicon.ico"><!-- 32×32 -->
    <link rel="icon" href="/icon.svg" type="image/svg+xml">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png"><!-- 180×180 -->
    <link rel="manifest" href="/manifest.webmanifest">
     ```
     
     ```json
     // manifest.webmanifest
     {
        "icons": [
          { "src": "/192.png", "type": "image/png", "sizes": "192x192" },
          { "src": "/512.png", "type": "image/png", "sizes": "512x512" }
        ]
      }
     ```
  - [the 6 favicon types you need](https://evilmartians.com/chronicles/how-to-favicon-in-2021-six-files-that-fit-most-needs)
  - **[Real Favicon generator](https://realfavicongenerator.net/)** - pop in an image, get back a favicon! The most comprehensive one for all platforms (Windows, iOS, Android)
  - [Favicon.io](https://favicon.io/) - Generate a favicon from text, from an image, or from an emoji. Download in .ico and .png formats
  - [FontIcon](https://gauger.io/fonticon/) - Generate favicons and images from Font Awesome icons
  - [Favicon Generator](http://tools.dynamicdrive.com/favicon/) - another one
  - https://textmoji.app/ small text icons meant for Slack but also can use for faviconning
  - [SVG Favicon maker](https://formito.com/tools/favicon) - supports emojis and 2 letter favicons with custom fonts
  - SVG favicons are modifiable by scroll percentage
    - you can https://css-tricks.com/svg-favicons-and-all-the-fun-things-we-can-do-with-them/
    - put the scroll percentage! https://css-tricks.com/how-i-put-the-scroll-percentage-in-the-browser-title-bar/

### `<link rel="">` tags and opengraph

Ideas of things you can include based on my own site.

```html
  <link rel="icon" type="image/png" href="/favicon.png" />
  <link rel="webmention" href="https://webmention.io/www.swyx.io/webmention" />
  <link rel="pingback" href="https://webmention.io/www.swyx.io/xmlrpc" />
  <meta name="theme-color" content="#818CF8">
  <title>{frontmatter.title} ∊ swyx.io</title>
  <link rel="canonical" href={canonical} />
  <meta property="og:url" content={swyxioURL} />
  <meta property="og:type" content="article" />
  <meta property="og:title" content={seoTitle} />
  <meta name="Description" content={seoDescription} />
  <meta property="og:description" content={seoDescription} />
  {#if frontmatter.cover_image}
    <meta property="og:image" content={coverImage} />
  {/if}
  <meta
    name="twitter:card"
    content={frontmatter.cover_image ? 'summary_large_image' : 'summary'} />
  <meta name="twitter:domain" content="swyx.io" />
  <meta name="twitter:creator" content="@swyx" />
  <meta name="twitter:title" content={seoTitle} />
  <meta name="twitter:description" content={seoDescription} />
  <meta
    name="twitter:image"
    content={frontmatter.cover_image ? frontmatter.cover_image : 'https://www.swyx.io/swyx-ski.jpeg'} />
  <meta name="twitter:label1" value="Last updated" content="Last updated" />
  <meta name="twitter:data1" value={metaDate} content={metaDate} />
  <meta name="twitter:label2" content="Read Time" />
  <meta name="twitter:data2" content={readTime} />
```

other boilerplates to use

- https://github.com/joshbuchea/HEAD
- https://www.matuzo.at/blog/html-boilerplate/

### Icons

#### Logos (incl company logos)

- https://logosear.ch/ superfast metasearch of 200k svg logos from GitHub
- https://seeklogo.com/
- https://www.iconfinder.com/iconsets/payment-method-1
- https://www.logology.co/
- https://www.svgrepo.com/ Browse 300.000+ SVG Vectors and Icons 
- https://iconsear.ch/ instant search of 50k svg icons from GitHub and GitLab
- https://macosicons.com/  icons intended to replace mac desktop icons
- https://awsicons.dev/ AWS icons

#### General & Misc

**Important**: Note on [icon accessibility](https://css-tricks.com/accessible-svg-icons/). [Don't use icon fonts.](https://www.irigoyen.dev/blog/2021/02/17/stop-using-icon-fonts/)

- Icon + text: use `<svg aria-hidden="true">`
- Icon only: `<svg role="img"><title>foo</title>...</svg`. Pick from [Aria roles](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles) list.
- Icon with link: `<a href="/" aria-label="Good Label"><svg aria-hidden="true" ... ></svg></a>`

> Note you can put gradients on SVG icons manually https://play.tailwindcss.com/yM2N8GpEUK

- ⭐ https://www.heroicons.com/ Steve schoger's (somewhat limited) svg iconset. another viewer: https://heroicons.dev/
- ⭐ https://phosphoricons.com/ 3000+ fully customizable free SVG and PNG icons
- ⭐ https://tablericons.com/ 937 Fully customizable free SVG icons
- https://iconic.app/
- https://icons.modulz.app/ Radix Icons - >250 15×15 icons designed by the Modulz team. - some great app icons
- **icon metasearch** (list of lists of icons)
  - https://icones.netlify.app/
  - https://www.iconbolt.com/
  - https://iconduck.com/ 104,808 free open source icons
- https://thenounproject.com/ Every icon you can think of, in PNG or SVG formats. They offer over 20 million icons, with built-in customization colors like size and color. Requires login, needs creative commons attribution or $3 download
- https://nucleoapp.com/ Nucleo is a beautiful library of 30635 icons, and a powerful application to collect, customize and export all your icons. $99 lifetime purchase.
  - https://nucleoapp.com/tool/icon-transition SVG Icon Transitions Generator
- https://hotpot.ai/free_icons 5,000+ free icons. Customize colors, size, and other properties. PNG, JPG, iOS, Android, PDF. No svg.
- **https://iconmonstr.com/** Discover 4486+ free icons in 310 collections. SVG, EPS, PSD, PNG. [OK without attribution, don't sell it](https://iconmonstr.com/license/).
- https://icomoon.io/ - 450 icons, SVG, PDF, EPS, Ai, PSD. Paid tier goes up to 1600 icons.
- https://orioniconlibrary.com/ has customizable colors and packs eg for ecommerce
- https://material.io/resources/icons/?style=baseline
- https://icons8.com/l/fluent/ colored "microsoft style" icons
- https://icons8.com/emoji emoji style customizable icons
- https://icons8.com/line-awesome fontawesome-like icons
- http://www.entypo.com/
- https://simpleicons.org/ 
- http://github.com/propublica/weepeople A typeface of people sillhouettes, to make it easy to build web graphics featuring little people instead of dots.
- Bootstrap Icons https://github.com/twbs/icons
- https://systemuicons.com/
- https://icons.mono.company/
- https://iconscout.com/unicons and https://github.com/Iconscout/react-unicons
- https://feathericons.com/
- https://www.zondicons.com/
- https://linearicons.com/free
- animated icons http://www.transformicons.com/builder.html
- https://game-icons.net/
- Covid 19 icons - https://design.dev/ 
- https://kenney.nl/ public domain game assets
- https://www.iconshock.com/social-media-icons/ A pack of 300 social media icons (PNG & Vector) and a set of animated icons (Lottie and AE), which cover all the trendiest social media networks nowadays.
- brand icons
  - http://simpleicons.org/ icons for every brand like graphql, adobe xd, youtube, etc
  - https://css.gg/ 700+ Customizable & Retina-Ready app icons — entirely built in CSS 
  - https://worldvectorlogo.com/
  - https://www.vectorlogo.zone/ - consistently formatted SVG logos
- React Icons
  - https://github.com/miukimiu/react-kawaii
  - https://reactsvgicons.com/
  - https://react-icons.netlify.com/#/icons/fa (typically fontawesome). note that there is some tree shaking issues in the discussions. you may wish to use the https://github.com/meronex/meronex-icons fork instead
  - https://github.com/bytedance/IconPark - more than 1,200 high-quality icons, and introduces an interface for customizing your icons. across React, Vue, SVG, PNG.
  - https://github.com/useAnimations/react-useanimations
  
> You may like: [Free Fundamentals of Icon design in 1 hour course by MDS](http://introtoicons.com/)


**premium/paid icons**

- http://shape.so/ 4300+ Icons & Illustrations (by Meng To)
- https://logobly.com/ create custom logos
- https://hatchful.shopify.com/ more custom logos
- https://radicalicons.com/ use `radicaldesign`
- https://symbolicons.com/
- 🔥 https://streamlineicons.com/ (used in [Glide Apps](https://twitter.com/glideapps/status/1199396690182230016))
- https://www.iconfinder.com/
- https://www.flaticon.com/
- https://gumroad.com/l/primaries
- https://gumroad.com/l/gPEAU ios 14 icons from traf - for inspo, mainly


## Diagramming

Before you get to the tools - some good thinking (and lists of tools) on architecture diagrams:

- https://nocomplexity.com/documents/arplaybook/businessarchitecture.html
- https://sportebois.medium.com/better-architecture-diagrams-for-agile-teams-actionable-tips-and-lessons-e76627dc4315
- https://c4model.com/ (c4 modeling [more from Simon](https://dev.to/simonbrown/how-to-review-a-software-architecture-diagram-6p0))
- http://fmc-modeling.org/ FMC modeling - only rectangles and round things

### General Purpose Diagramming

- https://excalidraw.com/ (free, open source)
- https://miro.com/ - freemium, used by Maggie
- https://www.draw.io/ - now [shifted](https://www.diagrams.net/blog/move-diagrams-net) to https://www.diagrams.net/ (free) - has [VS Code extension](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)
- https://inkscape.org/ (free)
- https://whimsical.com/ ($10/mo)
- https://www.lucidchart.com/
- https://www.gliffy.com/
- https://diagrams.net/
- https://www.ilograph.com/
- https://zenuml.com
- https://www.simplediagrams.com/
- [Microsoft Visio](https://www.microsoft.com/en-sg/microsoft-365/visio/flowchart-software)
- https://www.plectica.com/
- more tools - [see hn thread](https://news.ycombinator.com/item?id=21513337)

### Sequence Diagrams

- https://www.websequencediagrams.com/
- https://swimlanes.io/  a simple online tool for creating sequence diagrams.
- https://bramp.github.io/js-sequence-diagrams/
- https://sequencediagram.org/
- https://playground.diagram.codes/
- http://sdedit.sourceforge.net/ Quick Sequence Diagram Editor (but doesnt seem active)

Specifically for BPMN: https://bpmn.io/

### Entity Relationship Diagrams

- https://dbdiagram.io/home

### Cloud Architecture diagrams 

useful eg if needs logos

- Amazon architecture icons: https://aws.amazon.com/architecture/icons/ as well as the software that has them built in
  - https://awsicons.dev/ AWS icons
- https://www.draw.io/
- https://www.lucidchart.com/
- https://www.omnigroup.com/omnigraffle/ (used by tim bray)
- https://www.ilograph.com/
- https://www.cloudcraft.co/ focused on AWS
- https://www.cloudskew.com/
- https://arcentry.com/ (interactive/realtime) - discontinued!

the 5 types of arch diagrams https://www.readysetcloud.io/blog/allen.helton/the-5-types-of-architecture-diagrams/


### Code-based Graph tools

- graphviz/dot - useful inside jupyter
- mermaid https://mermaid-js.github.io/mermaid/
- http://blockdiag.com/en/
- python's `diagrams` https://pypi.org/project/diagrams/
- https://structurizr.com/
- https://plantuml.com/
- https://github.com/mhlabs/cfn-diagram visualize cloudformation -> draw.io 
- https://wavedrom.com/ (OSS) - Digital Timing Diagram or Waveform from simple textual description.
- way more tools here: https://xosh.org/text-to-diagram/



## Wireframing

- balsamiq
- https://wireflow.co/ free open source visual designer for user flows. collaborative.


## Graphics and SVG Illustrations

Hipster Logo Generator? any others?

- https://hipsterlogogenerator.com/

Backend entity/ ERD /SQL diagramming 

- SQL https://drawsql.app/
- Cloud AWS/Azure/GCP diagrams https://www.cloudskew.com/

DIY illustration

- Wobble paint https://www.lexaloffle.com/bbs/?tid=40058

### Device Mocks 

Mocking your browser/phone

- Browser: https://shooot.bourhaouta.com/, https://screenshot.rocks/
- Books: https://diybookcovers.com/3Dmockups/ 
  - https://3d-book-css.netlify.app/ and https://3dbook.xyz/
  - book cover advice https://convertkit.com/how-to-make-an-ebook-cover
- Macbook: https://magicmockups.com
- animate them, why not https://deviceful.app/
- phone/watch: https://www.rotato.xyz/
- other devices https://deviceshots.com/
- 3D mocks: https://things.morflax.com/styles
- 🔥 [Facebook Design Devices](https://facebook.design/devices)
- [Shotsnapp](https://shotsnapp.com/)
- https://www.ls.graphics/devices-mockups
- in context: [Device Mock-Up Inspiration](https://onepagelove.com/tag/devices)
- [Lstore Graphics](https://www.ls.graphics/) – Includes video
- [Creative Market](https://creativemarket.com/templates/mockups/mobile-web) device mockups

### Illustrations

- https://www.reddit.com/r/FreeIllustrations/top?t=all
- :star: https://undraw.co/ An open-source illustrations website, where you can change the colors of the illustrations online before downloading.
- :star: https://www.humaaans.com/ diverse, customizable human svgs
  - https://fresh-folk.com/ is similar
- :star: https://www.blackillustrations.com/ "Beautiful, FREE illustrations of black people for your next digital project"
  - hire custom designs via https://www.illustratorhub.com/
- :star: https://www.vecteezy.com/ High quality vector graphics with worry-free licensing for personal and commercial use.
- :star: https://streamlineicons.com/ux/ illustrations to go with Streamline icons
- https://icons8.com/illustrations (previously ouch.pics)
- :star: https://blush.design/ good random generator by Pablo Stanley.  Made for Sketch, Figma, InVision Studio and Adobe XD.
- :star: https://www.freepik.com/ Graphic resources for everyone: Find Free Vectors, Stock Photos, PSD and Icons
- https://www.pixeltrue.com/
  - https://www.pixeltrue.com/frontliner-heroes 24 high-quality Covid illustrations.
  - https://www.pixeltrue.com/free-illustrations free vector illustrations
- https://www.seekpng.com/ 1m+ Transparent PNG Images For Free
- https://freellustrations.com/ 
- https://2.flexiple.com/scale/all-illustrations One new high-quality, open-source illustration each day. Use our color-picker to adapt the illustrations to your brand identity! 
- https://2.flexiple.com/scale/home
- https://illustrationkit.com/ Free vector illustrations for personal & commercial projects no attribution required
- https://www.glazestock.com/
- https://openclipart.org/
- https://iradesign.io/ Build your own illustrations, Using our gradients and hand drawn sketch components.
- https://gallery.manypixels.co/ ManyPixels offer free svg illustrations with the possibility to customize the color as well.
- https://generator.opendoodles.com/ illustrations with color generator for svgs
- https://www.openpeeps.com/ a hand-drawn illustration library to create scenes of people.
- https://opengameart.org/
- https://usesmash.com/ Smash Illustrations features trendy characters and simple illustrations for free in commercial and personal use. It features more than 250+ objects and characters, and 20+ unique scenes so you can compose them however you like.
- https://control.rocks/ 
- https://mixkit.co/free-stock-art/ Mixkit is the Unsplash of illustrations, or that is their objective. It features many illustration categories and also stock videos and music, all free of charge.
- https://delesign.com/free-designs/graphics/
- https://illlustrations.co/ 100 beautiful illustrations, designed by Vijay Verma during a 100 days of illustrations challenge.
- https://isometric.online/ This website offers a searchable list of nice and free isometric illustrations.
- https://www.glazestock.com/ 
- https://lukaszadam.com/illustrations  library of Free Illustrations and Icons for everyone.
- https://design.dev/ some illustrations in PS/sketch/etc. requires account.
- https://www.manuelalangella.com/retroooo-folks/ Retroooo Folks is a vector-based Mix-and-Match library of hand-drawn sketches, created for Adobe Illustrator, Sketch and Adobe Draw.
- https://woobro.design/
- https://pimpmydrawing.com/
- https://www.drawkit.io/ Hand-drawn vector illustration resources for your next project
- https://www.karthiksrinivas.in/charco  A set of 16 handcrafted illustrations for your web & app projects. This set includes categories like 404 error, no internet connection, no service, fatal error, page not found, something went wrong, under construction and many more.
- https://www.veila.me/freebies/scandinavian-houses-free-vector-images
- https://absurd.design/
- https://github.com/MariaLetta/mega-doodles-pack
- https://iradesign.io/
- https://autodraw.com Google AI assisted drawing
- https://hotpot.ai Free or paid. Create icons, app screenshots, MacBook/browser mockups, social media posts, and other graphics for mobile apps and browser extensions.
- https://www.magicpattern.design/examples - one-click web editor for illustration patterns. It's perfect for branding landing pages, social media posts and featured images. Requires Google signup.
- https://gumroad.com/l/just sketch me (paid) 
- https://error404.fun/ 404 page illustrations

Illo's in context: https://onepagelove.com/tag/illustrations

### 3D illustrations

- https://www.isometriclove.com/ Cute Isometric Objects For Your Design
- https://www.handz.design/ 3d hand gestures
- https://isoflat.com/ Isometric and flat graphic resources 
- https://www.shapefest.com/ 160,000+ high resolution PNG images of beautiful 3D shapes
- https://powerpeopleplatform.com/ delicious design library of 3D avatars

Learn 3d illo in blender https://polygonrunway.com/

### DIY Graphic Design

- https://snappa.com/
- https://www.canva.com/
- https://www.fotojet.com/ esp for photo collages
- https://studio.polotno.dev/

### Stock Photos and Videos

- :star: https://unsplash.com/ of course
- https://www.flickr.com/creativecommons/
- https://isorepublic.com/
- https://negativespace.co/
- stock photo metasearch
  - https://www.everypixel.com/ 
  - https://www.chamberofcommerce.org/findaphoto/
  - https://zoomstock.com/ t-SNE stock photo search 
  - https://www.goodfreephotos.com/ 27k free and public domain photos, images, clipart, pics and vectors 
  - https://visualhunt.com/ search 354m high quality creative commons licensed photos
- art focus
  - https://artvee.com/ public domain art (in particular check out the [NASA collection](https://artvee.com/?s=nasa&post_type=product&product_cat=0))
- startups
  - https://startupstockphotos.com/
- faces
  - https://www.nappy.co/ "Beautiful, high-res photos of black and brown people. For free."
- nature
  - https://freenaturestock.com/
  - http://imagebase.net/
  - https://visualsofearth.com/c/ nature, space, desert, etc. mobile focused.
- travel
  - http://photos.bucketlistly.com/ A free creative common collection of over 5000+ travel photos from all over the world anyone can use.
- color
  - https://500px.com/ (premium - search by color)
- misc/novelty
  - http://www.ghibli.jp/info/013251/ studio ghibli free backgrounds
  - https://gratisography.com/ quirky/whimsy
  - https://covers.alphacoders.com/by_category/4/2/twitter-header
  - https://foter.com/ furniture
  - https://picjumbo.com/
  - https://photos.icons8.com/creator/ Create custom stock photos
  - https://generated.photos/ AI-generated stock photos
  - https://photos.icons8.com/
  - https://duotone.shapefactory.co/?f=f56468&t=27184f&q=_&i=oMpAz-DN-9I (unsplash with duotone filter)
  - https://allthefreestock.com/
  - https://thenounproject.com/search/photos/?q=happy
- lists of more resources
  - random low quality list https://www.mattcrampton.com/blog/mega_list_of_free_image_sites_for_blogging/
  - https://github.com/neutraltone/awesome-stock-resources
  - https://burst.shopify.com/ Burst from Shopify - Free stock photos for everyone
- Paid
  - https://deathtothestockphoto.com/
  - https://www.stocksy.com/ (premium)

Image modification for hover effects: https://photomosh.com/

### Stock Videos

- https://pexels.com
- https://pixabay.com/videos
- https://mixkit.co

### Avatars

- lo-fi autogenerated avatars
  - https://boringavatars.com/
  - https://robohash.org/
  - identicons https://idbloc.co/blog/product/update/2019/05/09/toggles-identicons-and-beauty.html
  - https://github.com/emeraldpay/hashicon
- instead of showing people's faces, try stippling https://github.com/pshihn/stippled-image
- https://en.gravatar.com/
- https://unavatar.now.sh/ grab social images from username/email
- http://avatars.adorable.io/#demo
- https://multiavatar.com
- https://personas.draftbit.com/ A playful avatar generator for the modern age.
- https://avataaars.com/ and https://getavataaars.com/
- https://bigheads.io/
- https://joeschmoe.io/ An illustrated avatar collection for
developers and designers
- https://amritpaldesign.com/toy-faces Toy Faces is a fun diverse library of 3D avatars for your design mockups and personal use.
- https://gumroad.com/l/siKBl 3d diverse avatars, paid

## Pure CSS Tricks

- MAKE SURE TO CHECK OUT https://components.ai
- https://twitter.com/JoshWComeau/status/1170358024319492097?s=20
- Sarah Drasner picks https://codepen.io/collection/nMgKxJ?cursor=ZD0xJm89MCZwPTEmdj0yNjc5NTQ1
- CSS3 3D Buttons http://simurai.com/archive/buttons/#
- Lea Verou CSS Secrets https://twitter.com/swyx/status/982786353216843776?s=20
  - CSS3 Patterns https://leaverou.github.io/css3patterns/
- CSS 3D Text https://markdotto.com/playground/3d-text/
- 3D CSS hover effects https://polypane.app/css-3d-transform-examples/
- set cursor to emoji using SVG https://twitter.com/mgechev/status/1354300680807329793?s=20
- swipey image grids using SVG https://www.cassie.codes/posts/swipey-image-grids/
- animated focus https://twitter.com/argyleink/status/1387072095159406596
    
    ```css
    @media
     (prefers-reduced-motion: no-preference) {
      :focus {
        transition: outline-offset .25s ease;
        outline-offset: 5px;
      }
    }
    ```
- glassy glassmorphism [codepen](https://codepen.io/a-trost/pen/dypQzwq), [in context](https://codepen.io/TurkAysenur/pen/ZEpxeYm)

    ```css
    .blur-and-rotate {
      border-radius: 20px;
      backdrop-filter: blur(20px) hue-rotate(120deg);
      -webkit-backdrop-filter: hue-rotate(120deg);
    }
    ```
- Shadows
  - Box shadows https://brumm.af/shadows
    - drop shadows - eg -1px left -1px top - makes buttons look stamped
    - text shadows
    - experiment with multiple shadows on one element
    - https://getcssscan.com/css-box-shadow-examples
  - Card border Generator https://card.surge.sh/
  - CSS Scroll Shadows https://css-scroll-shadows.now.sh/
  - Conic gradient borders https://twitter.com/argyleink/status/1282889809782927360
  - Components.ai box shadows https://components.ai/box-shadows
  - Emoji Shadows https://codepen.io/dienhn/pen/xxErveM
  - Neuomorphism Generator https://neumorphism.io/#f3d2c3
    - primer on skeuo vs flat vs neuomorphism https://uxdesign.cc/tridimensionality-of-skeuomorphism-flat-design-and-neumorphism-bc9d705a5cc7

```css
border-radius: 50px;
background: #f3d2c3;
box-shadow:  20px 20px 22px #cfb3a6, 
             -20px -20px 22px #fff2e0;
```

- Blend Modes
  - [`background-blend-mode` color-burn, lighten, multiply are cool](https://codemenatalie.com/blog/background-blend-mode-property/)
- CSS clip path
  - https://labs.jensimmons.com/#shapes 
  - https://bennettfeely.com/clippy/ 
  - https://youtu.be/u9bDe3Bw0sA
  - CSS tricks clip path animation tutorial https://css-tricks.com/animating-with-clip-path/
  - slanted image gallery with clip path https://24ways.org/2019/flexible-captioned-slanted-images/


### SVG/Canvas Masking

- JPG/PNG to SVG 
  - core tool http://potrace.sourceforge.net/
  - https://picsvg.com/
  - https://svgurt.com/#/
  - https://codepen.io/jesstelford/pen/PaBMrL small dynamic SVG placeholders
  - https://github.com/woltapp/blurhash small dynamic SVG placeholders for blurring up
- SVG to JSX
  - https://omatsuri.app/svg-to-jsx
  - https://svg2jsx.com/
  - https://react-svgr.com/playground/
- SVG editors
  - https://boxy-svg.com/
  - https://editor.method.ac/
  - https://vecta.io/ collaboration tools for teams, and also supporting diagrams, Autocad drawings, Vision stencils and drawings.
  - https://macsvg.org/ light open-source macOS application for SVG editing and animations
  - https://github.com/SVG-Edit/svgedit fully-fledged SVG editor for sophisticated SVG editing. 
- SVG Compression
  - https://jakearchibald.github.io/svgomg/
  - SVGO https://www.smashingmagazine.com/2021/03/svg-generators/#svg-compression
- SVG assets manager
  - https://svgx.app/ free desktop SVG asset manager which allows you to keep all SVGs in one place. You can bookmark, search and preview SVG icons, live-edit the SVG markup, preview the icons in dark mode and copy/paste markup and CSS with one click. By default it also uses SVGO for SVG optimizations. Available for Mac and Windows.
  - https://iconset.io/ You can drag icons from Iconset directly into Sketch, Figma, Adobe XD and pretty much anything else, without plugin or extension installs. Plus, you can also sync icons across devices via Dropbox or similar services, and publish and share your icon sets. Available for Mac and Windows.
- SVG Sprites generator https://svgsprit.es/  context https://www.smashingmagazine.com/2021/03/svg-generators/#svg-sprites-generator
- Transparent fill SVG and color in on Hover - [Codepen](https://codepen.io/m4r1vs/pen/qVReQz)
- https://speckyboy.com/css-svg-canvas-masks/
- https://www.blobmaker.app/ generate some fancy blobs.
- https://squircley.app/ generator of organic shapes for any kind of visuals or background images. You choose the rotation, the scale, the “curvature” and the fill color, and the tool takes care of the rest.
- https://inkscape.org/
- https://svg-path-visualizer.netlify.app/
- https://svgcrop.com/ remove blank space automatically
- https://msurguy.github.io/svg-cropper-tool/ more refined control of cropping with additional options for cropping style — circle, polygon, custom shape
- SVG Polygon Generator https://codepen.io/winkerVSbecks/full/wrZQQm/ allows you to define the number of sides, radius, spacing and it generates a <polygon> SVG element for you.
- https://rawgraphs.io/ SVG Data Visualization Generator -  sunburst, circular dendrogram or multiple convex hull, for example. with tutorials: https://rawgraphs.io/learning
- svg and text effects
  - https://pavellaptev.github.io/warp-svg/
  - https://css-tricks.com/animate-blob-text-with-svg-text-clipping/
  - more text effects https://letsbuildui.dev/articles/css-text-effects-five-minimal-examples
- animate an existing svg https://svgartista.net/
- `mix-blend-mode: screen` is [really good for SVG icons, with hover](https://ishadeed.com/article/blending-modes-css/)
- SVG animations
  - SVG icon transitions https://blog.nucleoapp.com/create-2-state-svg-powered-animated-icons-76ed19160a7e
    - https://nucleoapp.com/tool/icon-transition
  - scroll based svg text path animation https://www.youtube.com/watch?v=Tae96ze3xwY
  - stroke path animation https://css-tricks.com/a-trick-that-makes-drawing-svg-lines-way-easier/
  - https://maxwellito.github.io/vivus-instant/ animate svg strokes
  - https://svgartista.net/ basic fill and stroke animations
  - https://www.svgator.com/ dedicated editor for SVG animations with plenty of dedicated panels for everything from skewing to stroke path and filters
  - GSAP, SVG.js (http://www.svgjs.com/), Lottie

## Background Stuff

### Background Gradients and Patterns

Not just for background backgrounds - applying gradients and background images to text is super underrated. Examples:

- [https://philcoffman.com/](https://user-images.githubusercontent.com/6764957/64589989-7985f500-d374-11e9-9d8a-2a8888df6981.png)
- [https://css-tricks.com/](https://user-images.githubusercontent.com/6764957/64590103-beaa2700-d374-11e9-8a84-95ab4826a577.png)

Background Radial Bursts behind images:

- https://cssgradient.io/
- https://youtu.be/U4z-wph1NyI
- https://onepagelove.com/tag/gradients

![https://hottips.imgix.net/2020/07/063-burst.jpg?w=1200&auto=compress](https://hottips.imgix.net/2020/07/063-burst.jpg?w=1200&auto=compress)

#### Background Gradients

Make sure to see the [Color Gradients](#color-gradients) section to generate gradients

```css
background-image: linear-gradient(
  120deg,
  hsl(200 50% 90%) 0%,
  hsl(200 100% 90%) 100%
);
```

https://meshgradient.com/ swirly backgrounds like apple

#### Background Patterns

- https://leaverou.github.io/css3patterns/
- https://github.com/bansal-io/pattern.css
- http://www.heropatterns.com/ SVG Repeating Patterns Generator
- https://www.wowpatterns.com/free-vector-art thousands of freevector patterns, based on shapes, organic shapes as well as themes, such as animals, beach, city and people, festivals, florals etc.
- https://www.transparenttextures.com/
- https://www.toptal.com/designers/subtlepatterns/ (exports png though :( )
- https://pattern.flaticon.com/ (create a bg pattern of icons)
- https://coolbackgrounds.io/
- https://tabbied.com/ abstract Doodles with generated patterns
- https://css-doodle.com/
- https://hero-generator.netlify.app/ hero picture CSS generator
- https://www.gradientmagic.com/
- https://kumiko-generator.netlify.app/
- http://thepatternlibrary.com/
- https://msurguy.github.io/flow-lines/ produces random geometric lines, and we can adjust the formulas and distances between the shapes drawn
- http://svgbackgrounds.com/
- https://haikei.app/ - web app to generate unique SVG shapes, backgrounds, and patterns 
- https://pattern.monster/ 180 patterns, and you can filter them by mode and color, and search
- http://iros.github.io/patternfills/ - plenty of black-and-white patterns, also available from the command line
- https://www.kennethcachia.com/plain-pattern/ allows you to upload an SVG shape (or use one of the existing ones) and it creates a repeating pattern which can be exported as SVG.
- http://www.patternify.com/ CSS Pattern generator that allows you to define a pattern in a 10×10 grid
- https://www.magicpattern.design/tools/css-backgrounds library of pure CSS background patterns like ZigZag or diagonal ones.
- https://bgjar.com/
- https://products.ls.graphics/paaatterns/
- https://notchris.net/patterns/ (Really simple SVG Patterns using single unicode characters.)
- https://doodad.dev/pattern-generator/ (Pattern generator that exports to png, jpg and svg.)
- wave dividers
  - https://www.shapedivider.app/ generate custom shape dividers 
  - https://svgwave.in/ 
  - https://getwaves.io/ generate SVG waves
  - https://wavelry.vercel.app/ choose between sharp, linear and smooth waves
  - https://www.outpan.com/app/9aaaf27303/svg-gradient-wave-generator adjust amplitudes, smoothness, saturation and hues
  - https://loading.io/background/m-wave/ generate waves, and even animate them
  - https://haikei.app/ full fledged generate SVG assets, from layered waves to stacked waves and blob scenes
  - svg waves generator https://codepen.io/jh3y/full/poEvKxo
  - https://wweb.dev/resources/css-separator-generator

### Background Illustrations

- https://freellustrations.com/

### Background Stock Photos



#### Misc Backgroundy Stuff

- CSS Doodle https://css-doodle.com/
- CSS backgroundy patterns https://leaverou.github.io/css3patterns/
- this guy https://twitter.com/yuanchuan23
- Generative Gradients http://generative-placeholders.glitch.me/
  - Generateive SVG https://dev.to/georgedoescode/a-generative-svg-starter-kit-5cm1
- Image Placeholders - blurring - https://blurha.sh/ (and gatsby image and nextjs image)
- Dimming/coloring text on background images https://coder-coder.com/background-image-opacity/
- [True Grit Texture Supply](https://www.truegrittexturesupply.com/) PNG textures (paid)
- Remove backgrounds https://www.remove.bg/ from images, https://www.unscreen.com/ for gif/video
- colorizing black and white images https://demos.algorithmia.com/colorize-photos

## Spinners

- web components https://wc-spinners.cjennings.dev/
- Spinners https://tobiasahlin.com/spinkit/
- Buttons, hover, inputs, and loaders https://cssfx.netlify.com/
- Conic gradient loader in CSS - [Codepen](https://codepen.io/keithclark/pen/aEbEoo)
- React, Vue and Angular Spinners https://github.com/JoshK2/react-spinners-css
- https://andrew.wang-hoyer.com/experiments/svg-animations/
- Single Element CSS Spinners https://projects.lukehaas.me/css-loaders/

## Animations & Transitions

- Buttons, hover, inputs, and loaders https://cssfx.netlify.com/
- general http://animista.net
  - animate an existing svg https://svgartista.net/ (by the same people as animista)
- general https://animejs.com/
- motion graphics https://github.com/mojs/mojs
- general https://daneden.github.io/animate.css/
- general https://ianlunn.github.io/Hover/
- Burgers https://march08.github.io/animated-burgers/
- Burgers http://negomi.github.io/react-burger-menu/
- Layout https://github.com/aholachek/react-flip-toolkit
- Hover and loaders: https://www.csswand.dev/
- Graphic animations: https://lottiefiles.com/
  - https://www.pixeltrue.com/free-illustrations lottie animations
- HTML animation? https://tumult.com/hype/ (paid)
- Page Transitions with swup https://github.com/swup/swup ([css tricks](https://css-tricks.com/page-transitions-for-everyone/))
- css animation without keyframes https://animxyz.com/docs/
- React
  - https://react-simple-animate.now.sh/
  - https://github.com/brunnolou/react-morph
  - https://github.com/kitze/react-genie
  - Page transitions https://github.com/joerez/react-transitions/
  - https://animxyz.com/docs/ has react and vue integration

## Individual HTML Elements

- links https://cssanimation.rocks/animating-links/
- tooltips on hover https://kazzkiq.github.io/balloon.css/
- put scroll margin on [everything with an `id`](https://piccalil.li/quick-tip/add-scroll-margin-to-all-elements-which-can-be-targeted)
  ```css
  [id] {
    scroll-margin-top: 2ex;
  }
  ```
- Link and Button hover effects https://www.youtube.com/watch?v=ceNMP-aQkQ4
- Image modification for hover effects: https://photomosh.com/
- shrinking header on scroll https://css-tricks.com/how-to-create-a-shrinking-header-on-scroll-without-javascript
- https://smolcss.dev/ more simple CSS tricks for responsive elements
- prefer click menus over hover menus https://css-tricks.com/in-praise-of-the-unambiguous-click-menu/
- how to make settings https://web.dev/building-a-settings-component/



### Buttons

- https://frontend.horse/articles/buttons-that-spark-joy/
- https://cssbuttons.vercel.app/ cssbuttons: HTML & CSS Buttons Collection Built in React
- moving lightsource on hover css buttons idea https://jsfiddle.net/pixel67/ZxZ6B/28/
- Button without ugly focus ring with Tailwind:
  -  `focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2`
  -  for links `focus:shadow-outline focus:outline-none`

### Forms

- Accessible Styled Forms https://github.com/scottaohara/a11y_styled_form_controls
- accessibility for all elements https://www.smashingmagazine.com/2021/03/complete-guide-accessible-front-end-components/ 
- Form Design Best Practices https://medium.com/nextux/form-design-best-practices-9525c321d759
- Form Wizard https://medium.com/nextux/how-to-design-a-form-wizard-b85fe1cc665a
- Complex Forms https://medium.com/nextux/form-design-for-complex-applications-d8a1d025eba6
- Form Validation UX https://medium.com/nextux/forms-need-validation-2ecbccbacea1
- Form Validation https://www.bram.us/2021/01/28/form-validation-you-want-notfocusinvalid-not-invalid/
  - use `input:not(:focus):not(:placeholder-shown):valid` for non freakout UX
- WTF Forms: Nicer Forms eg Radio Buttons with pure CSS https://github.com/mdo/wtf-forms
- Output-inspired form: https://twitter.com/steveschoger/status/1171429842442522625
- show button when placeholder-shown:  https://codepen.io/liamj/pen/vYYLGZj
- Toggles: https://jnkkkk.github.io/MoreToggles.css/allToggles.html
- 3D LED switch: https://codepen.io/jkantner/pen/VwaBomY
- The Crazy Egg Guide to Great Form UI and UX https://www.crazyegg.com/blog/guides/great-form-ui-and-ux/
- Best practice, research insights and examples by Geri Reid https://gerireid.com/forms.html

### Tables

- https://www.uxbooth.com/articles/designing-user-friendly-data-tables/
- https://medium.com/nextux/design-better-data-tables-4ecc99d23356
- https://twitter.com/erikdkennedy/status/1329787833058353154?s=20
- [A table with both a sticky header and a sticky first column](https://css-tricks.com/a-table-with-both-a-sticky-header-and-a-sticky-first-column)

### Sound

- https://www.zapsplat.com/
- https://www.myinstants.com/index/se/
- https://www.youtube.com/audiolibrary/music?nv=1
- https://icons8.com/music
- https://freesound.org/
- https://pixabay.com/music/
- https://cchound.com/ 100% free, quality CC audio
- https://www.pianobook.co.uk/ as hundreds of no-charge sample libraries (many pianos, lots of other things).
- podcast intros
  - https://aaraalto.com/sounds a few brief guitar samples for podcast transitions 
  - https://transistor.fm/free-podcast-intro-music/ free podcast intro music

Paid:

- https://www.epidemicsound.com/
- https://artlist.io/ - may have better licensing https://www.youtube.com/watch?v=mYU6XhORomg but no fx
- https://www.soundstripe.com/ (cheapest) here's a comparison https://www.youtube.com/watch?v=1YBjY79axRo
- https://www.bensound.com/ 


Tools:

- https://www.audacityteam.org/
- https://joshwcomeau.com/react/announcing-use-sound-react-hook/
- https://source-separation.github.io/tutorial/landing.html

### Lightweight Charts/Dataviz

- https://rbitr.github.io/ChartS.css/
- https://chartscss.org/
- Sparkline fonts in text: https://github.com/aftertheflood/sparks and https://www.scribbletone.com/typefaces/ff-chartwell

### Nice React Components

- https://react-smooth-range-input.now.sh/
- Theme-ui-sketchy - https://github.com/beerose/theme-ui-sketchy roughjs components with themeui
- React Physics Dragger https://react-physics-dragger-demo.netlify.com/
- [React-Designer](http://react-designer.github.io/react-designer/): Easy to configure, lightweight, editable vector graphics in your react components.
- `<Foldable>` from [Folding the DOM](https://www.joshwcomeau.com/posts/folding-the-dom/)
- React Hamburger Icons https://hamburger-react.netlify.com/
- React Curved Arrow https://react-curved-arrow.nickjanssen.com/
- Spinners
  - https://github.com/tienpham94/react-awesome-spinners - requires styled components
  - https://github.com/davidhu2000/react-spinners
  - https://github.com/JoshK2/react-spinners-css
  - https://github.com/JoshK2/react-spinners-css
  - https://www.npmjs.com/package/react-loaders-kit - 200kb tho
  - https://github.com/adexin/spinners-react
  - https://gooey-react.netlify.app/examples/rotating-loader/
- PDF viewer https://react-pdf-viewer.dev/

### React Toasting

- https://cogoport.github.io/cogo-toast
- https://fkhadra.github.io/react-toastify/

### React Gamification

- https://github.com/thedevelobear/react-rewards
- React Confetti https://alampros.github.io/react-confetti/
- React DOM Confetti https://daniel-lundin.github.io/react-dom-confetti/

### Misc Weird fun stuff

- Perspective stairstep text effects https://codepen.io/jamc92/details/KaMLvY (in action: http://tennentbrown.co.nz)
- Split text animations https://web.dev/building-split-text-animations/
- Duotone blend modes: https://jmperezperez.com/duotone-using-css-blend-modes/
- Decovar Font with Text shadows: https://codepen.io/mandymichael/details/dJZQaz (and other [Variable Fonts by Mandy](https://variablefonts.dev/))
- Drop shadows: `box-shadow: 10px 12px 0.5rem rgba(0,0,0,0.5);`
- Expanding Search buton and text from Ana Tudor [mentioned here](https://dev.to/chriscoyier/learn-about-css-custom-properties-through-clever-uses-of-them-2fjo)
- ClippyJS https://www.smore.com/clippy-js
- Rythm.js - make your page dance https://okazari.github.io/Rythm.js/
- XKCD chart https://timqian.com/chart.xkcd/
- Netflix slide-in menu - [Codepen](https://codepen.io/FlorinPop17/pen/KKPBgeQ)
- Peek Href on Links - [2min video](https://www.youtube.com/watch?v=zMZckWl_B4c&feature=youtu.be)
- [Gooey Effect with SVG and Filters](https://css-tricks.com/gooey-effect/)
- More on [SVG filters](https://www.smashingmagazine.com/2021/03/svg-generators/#svg-filters-color-matrix-mixer)
- [Backdrop Filters and Multiple Inner Shadows](https://twitter.com/MengTo/status/1311029761490198528?s=20)
- [Swyx CSS Filter toy](https://svelte.dev/repl/defc901c5f434ed4a76161605cf1db76?version=3.29.0)
- [CSS motion blur on css tricks](https://css-tricks.com/how-to-create-a-realistic-motion-blur-with-css-transitions/)
- [Instagram filters created with CSS filters, by Una](https://una.im/CSSgram/)
- [CSS only hover effect with Headers](https://codepen.io/oliviale/pen/YgzNzK)
- [SVG iPhone mock and animated notification transition](https://codepen.io/sdras/pen/LYELqPX)
- RoughJS Annotation - https://roughnotation.com/
- Greensock GSAP scroll trigger demo with a ThreeJS Plane model https://codepen.io/ste-vg/pen/GRooLza
- little HTML tricks that are handy https://htmldom.dev/
- https://1stwebdesigner.com/css-effects/
- great svg ideas https://twitter.com/cassiecodes/status/1383432725059674112?s=20

## Design Software

- Image editing/Export to SVG/Object Removal/Photoshop - [Photopea](https://www.photopea.com/)
- online SVG editor - https://yqnn.github.io/svg-path-editor/
- GIMP alternative - https://glimpse-editor.org/
- Image modification for hover effects: https://photomosh.com/
- Make photo 16x9 small tool https://photo16x9.com/
- Enlarge low res images with ML: https://twitter.com/addyosmani/status/1353616560057815041
- Lunacy - https://icons8.com/lunacy Graphic design software with built-in assets
- Website design feedback collaboration - [Pagereview.io](https://pagereview.io/)
- Invision https://www.invisionapp.com/inside-design/design-resources/
- Scenes
  - https://www.ls.graphics/scene-creators
- UI kit collections
  - https://www.ls.graphics/ui-ux-tools
- Responsive Dev Browsers
  - FOSS https://responsively.app/
  - http://sizzy.co/ (paid)
  - https://polypane.app/ (paid)
  - [more alternatives](https://www.reddit.com/r/webdev/comments/f6ah78/responsive_website_testing_any_alternative_to/)

### Figma

- https://100dailyui.webflow.io/ Free Figma library of products, elements,
and screens.
- https://blush.design/ -  Free Customizable Illustrations With Figma Plugin
- https://www.figmafreebies.com/

### Sketch

- http://freebiesketch.com/
- https://www.sketchappsources.com/
- Apple design resources https://developer.apple.com/design/resources/

### Generative Design Tools

- Image modification for hover effects: https://photomosh.com/
- http://components.ai/

## Canvas

- Trianglify http://qrohlf.com/trianglify/
- generative artistry https://generativeartistry.com/
- Canvas Cards https://canvas-cards.glitch.me/
- Open Processing https://www.openprocessing.org/

## WebGL

- [Curtains.js](https://www.curtainsjs.com/) ([example](https://codepen.io/martinlaxenaire/post/webgl-enhanced-drag-slider-tutorial-with-curtains-js-part-3))

## 3D

ThreeJS

- LowPoly 3D models from Google https://poly.google.com/search/duck
- https://www.kukla-kit.com/ Huge pack of 3D elements accessible directly from Figma.

BabylonJS

- https://babylonjs.medium.com/babylon-js-4-2-simplicity-reimagined-965f88d0fad

## Video

- stock video https://www.pond5.com/
- https://animoto.com/ - drag and drop video maker
- https://biteable.com/ - video maker with templates
- https://powtoon.com - videos and presentations for engaging and explaining
- https://storycreatorapp.com/ - Simple online video editing for digital creators
- make video demos https://glitterly.app/
- https://storycreatorapp.com/
- https://www.fiverr.com/search/gigs?query=explainer%20videos&source=top-bar&search_in=everywhere&search-autocomplete-original-term=explainer%20videos
- https://www.medialuv.com/
- https://videohive.net/
- https://invideo.io/ - video maker with templates

Tutorials from successful Youtubers

- https://www.youtube.com/watch?v=N6-Q2dgodLs
- florin pop https://www.youtube.com/watch?v=vcKkRrNBdVI

## Onboarding

- https://www.appcues.com/ show people things they need as they need them
- React Curved Arrow https://react-curved-arrow.nickjanssen.com/

## Misc Genres (Handwriting, Pixel, ASCII styles)


### RoughJS Tools

- RoughJS Animated Annotation - https://roughnotation.com/
- https://excalidraw.com/
- https://alias-rahil.github.io/handwritten.js/

### Pixel Art

- http://pixelartmaker.com/
- https://nostalgic-css.github.io/NES.css/
- SNES music https://www.zophar.net/music/nintendo-snes-spc

### ASCII Art

- https://fatiherikli.github.io/archetype/
- https://textik.com/#a4ec12a68785f25f
- http://asciiflow.com/
- https://monodraw.helftone.com/
- text to diagramming tools [list](https://smusamashah.github.io/text-to-diagram)

### Perf

- https://tinypng.com/
- https://resizeimage.net/

<details>
<summary>
Sample meta tags with preconnects
</summary>


```jsx
        <link rel="icon" type="image/png" href="/temporal-icon.png" />
        <meta name="theme-color" content="#317EFB"/>
        <meta property="title" content="Temporal.io: Build Invincible Apps" />
        <meta property="og:title" content="Temporal.io: Build Invincible Apps" />
        <meta name="description" content="Temporal is the open source runtime for running mission critical code that runs atop unreliable, distributed services at any scale." />
        <meta property="og:description" content="Temporal is the open source runtime for running mission critical code that runs atop unreliable, distributed services at any scale." />
        <meta property="og:image" content="https://temporal.io/logo-font-straight-dark.svg" />
        <meta property="og:url" content="http://temporal.io" />
        <meta property="twitter:title" content="Temporal.io: Build Invincible Apps" />
        <meta property="twitter:description" content="Temporal is the open source runtime for running mission critical code that runs atop unreliable, distributed services at any scale." />
        <meta property="twitter:image" content="https://temporal.io/logo-font-straight-dark.svg" />
        <meta property="twitter:card" content="summary_large_image" />
        <meta name="twitter:site" content="@temporaltech" />

        {/* resource hints */}
        <link rel="preconnect" href="https://fonts.gstatic.com" />
        <link rel="preconnect" href="https://www.youtube.com" />
        <link rel="preconnect" href="https://yt3.ggpht.com" />
        <link rel="preconnect" href="https://static.doubleclick.net" />
        <link rel="preconnect" href="https://googleads.g.doubleclick.net" />
        <link rel="preconnect" href="https://i.ytimg.com" />
        <link rel="preconnect" href="https://s.ytimg.com" />
        <link rel="preconnect" href="https://www.google-analytics.com" />

        <script
          async
          src="https://www.googletagmanager.com/gtag/js?id=[Tracking ID]"
        />

        <script
          dangerouslySetInnerHTML={{
            __html: `
                  window.dataLayer = window.dataLayer || [];
                  function gtag(){dataLayer.push(arguments);}
                  gtag('js', new Date());
                  gtag('config', '[Tracking ID]');
              `,
          }}
        />
```


</details>



## Other Lists like this one

- https://a11yresources.webflow.io/ 
- https://www.getstark.co/library/
- https://github.com/bradtraversy/design-resources-for-developers
- https://tiny-helpers.dev/
- https://www.uigoodies.com/
- https://www.uplabs.com/
- https://github.com/neutraltone/awesome-stock-resources
- https://nodesign.dev/
- https://github.com/LisaDziuba/Awesome-Design-Tools
- https://github.com/goabstract/Awesome-Design-Tools
- https://github.com/emmabostian/design-inspiration
- https://undesign.learn.uno/
- https://dev.to/theme_selection/best-design-resources-websites-every-developer-should-bookmark-1p5d
- https://dev.to/joserfelix/40-high-quality-free-resources-for-web-development-10o3

## Helpful podcasts/talks/articles

- [How do I learn design?](https://www.codenewbie.org/podcast/how-do-i-learn-design) (CodeNewbie)
- [Design foundations for developers](https://syntax.fm/show/196/design-foundations-for-developers) (Syntax)
- [Design tips for developers](https://syntax.fm/show/068/design-tips-for-developers) (Syntax)
- [Tactical design advice for developers](https://changelog.com/podcast/333) (The Changelog)
- [UI Design for Developers](https://designcode.io/ui-design-for-developers) (Meng To)
- [Learning How to Design](https://shoptalkshow.com/343/) (ShopTalk)
- [Laws of UX](https://lawsofux.com/) 
- [100 Things I Know About Design](https://odannyboy.medium.com/100-things-i-know-about-design-8e50f7b1818b)
- https://learnui.design/blog/4-rules-intuitive-ux.html
  - Obey the Law of Locality 
  - Anything But Dropdowns
  - Pass the Squint Test
  - Teach By Example
- https://littlebigdetails.com/
- web interface handbook https://imperavi.com/books/web-interface-handbook/
- [Design Principles](https://principles.design/)
- https://twitter.com/mrcndrw/status/1283078825870532609
- https://internetdevels.com/blog/the-10-commandments-of-user-interface-design ([infographic](https://www.designmantic.com/blog/infographics/the-10-commandments-of-ui-design/))
- 3 most common mistakes of UI design by [MDS](https://robhope.com/yo-mds)
  - too many font sizes used. Try to use 1-2 sizes and vary other things like weight, negative space, color, casing.
  - don't over rely on strict mathematical spacing - use optical alignment instead - make judgments based on the needs of the layout.
  - consistent color usage. Tappable = one color. dont make titles and buttons same color. mind accessibility.
- [Simple Layout checklist](https://docs.google.com/file/d/0B0gPtgNVonXPT1NsWGpKZWZKV1U/edit)
  - [ ] Clear idea of purpose, target audience, where/how long it will be seen
  - [ ] Information hierarchy (vary size, contrast, position)
  - [ ] Clear visual structure - pick the most suitable way to group elements
  - [ ] Space - leave enough whitespace. Too much > too little
  - [ ] Alignment - use as few lines as possible
- [Human Interface Guidelines from Apple, Microsoft, Elementary OS, IBM, etc](http://www.geofcrowl.com/blog/articles/2020/2/17/collection-higs/)
- 50 UI tips https://fifty.user-interface.io/
  - https://fifty.user-interface.io/50_ui_tips.pdf
- Steve Schoger - [little details of visual ui design](https://twitter.com/swyx/status/1206234577821286406?s=20)
  - [ ] add a bit of color to your greys
  - [ ] saturate greys when using a colored background
  - [ ] consider temp when saturating greys
  - [ ] use a consistent corner radius
  - [ ] use consistent icon set
  - [ ] use font size to emphasize impt info
  - [ ] use color to create a hierarchy
  - [ ] use consistent spacing scale
  - [ ] use color to draw attention
  - [ ] offset box-shadows
  - [ ] easy on the link styles
  - [ ] use contrast to create balance
  - [ ] pick an appropriate line height
  - [ ] use alignment to clean up your design
  - [ ] give actions hierarchy
  - [ ] consider spacing instead of borders
  - [ ] use color to create depth and hierarchy
  - [ ] use good fonts
- [Buffer Design tips](https://buffer.com/library/social-media-design-tips)
  - [ ] Color: emotion, personality
  - [ ] Balance: symmetry, asymmetry
  - [ ] Lines: straight lines for harmony, curved for movement. guide the eyes
  - [ ] Typography: 3 max, san-serif for web, kerning for headlines
  - [ ] Add Contrast with shapes, color, element sizes
  - [ ] Scale: size elemnts differently to draw attention or demonstrate concept
  - [ ] Proximity: group related items together. connect colors, fonts, shapes
  - [ ] Hierarchy: most impt elements first
  - [ ] Repetition: consistency of fonts, colors, logos
  - [ ] Direction: F, E, Z pattern. Put key info in left
  - [ ] Space: use space to amplify other objects
- Simple design: https://www.anthonyhobday.com/simpledesign/ (rec by [Hey designer](https://twitter.com/jonasdowney/status/1280620028774305792/photo/1))
- [Refactoring UI](https://refactoringui.com/)
  - Starting from Scratch
    - Choose a personality
    - Don't design too much
    - Detail comes later
  - Hierarchy
    - Size isn't everything
    - Emphasize by de-emphasizing
  - Layout and Spacing
    - Establish a spacing/sizing system
  - Designing Text
    - Keep your line length in check
  - Working with Color
    - Ditch hex for HSL
  - Creating Depth
    - (to be continued)
  - Emulate a light source
    - (to be continued)
  - Working with Images
    - (to be continued)
  - Finishing Touches
    - (to be continued)
- [Tracy Osborn Checklist](https://www.youtube.com/watch?v=uKpfO331DY4&list=WL&index=4)
  - Reduce Clutter
    - use ColourLovers for color palettes
    - Fonts - max 2. Use fancy fonts sparingly
    - more whitespace
    - break up walls of text with bullet points
    - big clear CTA buttons
  - Headlines: talk benefits not details. short.
- [Design Details: Principles of Design](https://designdetails.fm/episodes/220880) - Design Details' most downloaded episode of all time!
- [7 Rules for Creating Gorgeous UI](https://learnui.design/blog/7-rules-for-creating-gorgeous-ui-part-1.html)
  - Light comes from the sky
  - Black and white first
  - Double your whitespace
  - Learn the methods of overlaying text on images
  - Make text pop — and un-pop
  - Use only good fonts
  - Steal like an artist

## More Free Stuff

- [Canva Design School](https://designschool.canva.com/)
- [Degreeless.design](https://www.degreeless.design/#basics)
- Free tier software https://free-for.dev/#/
- https://github.com/Vincenius/link-list
- Public API's for demos https://github.com/public-api-lists/public-api-lists
- Demo HTML
  - https://github.com/cristurm/nyan-cat
  - https://github.com/netlify/netlify-drop-demo-site/archive/master.zip
- [The Design Newsletter](https://learnui.design/newsletter.html)

## Paid Premium Services

- Design Pickle
- Manypixels
- Contentfly (copywriting)

## Courses

- for the 4 minute version: https://jgthms.com/web-design-in-4-minutes/
- for the 4 hour version: https://frontendmasters.com/courses/design-for-developers/
- for the 4 week version: https://refactoringui.com/book
- for the 4 month version: https://learnui.design/ 995/1495/2495. 48 lessons, 26 hours
- weekly lessons drip fed over email https://hackdesign.org/
- i may be signing up for https://shiftnudge.com/ .. its super expensive tho
- upcoming design for devs book from adrian twarog https://www.enhanceui.com/
- meng to https://designcode.io/ui-design-for-developers
- the non-designer's design book https://www.amazon.co.uk/Non-Designers-Design-Book-Robin-Williams/dp/0133966151
- Copywork
  - https://www.frontendpractice.com/
  - https://www.codewell.cc/

## Interaction/Design Inspo

- Dribbble ofc
- https://pageflows.com/
- https://uimovement.com/
- https://uidesigndaily.com/
- https://www.siteinspire.com/
- https://www.landingfolio.com
- http://www.cssmania.com/
- https://www.uisources.com/
- [Codrops](https://tympanus.net/codrops/2019/06/04/inspirational-websites-roundup-5/)
- https://collectui.com/
- https://theanimatedweb.com/
- https://pageflows.com/
- https://goodui.org/ "leaked ab tests" 
- http://ui-patterns.com/
- https://uigarage.net/
- https://pttrns.com/

### Game design inspo

- https://interfaceingame.com/
- https://www.gameuidatabase.com/
- movie UIs https://www.pushing-pixels.org/fui/
- game movie and other fantasy UIs https://www.saji8k.com/kit-fui/

## Mock APIs

free or mock data apis for demos

- Simple Data
  - http://quotes.rest/ 
  - https://api.chucknorris.io/
  - https://jokeapi.dev/
  - https://dev.to/dailydevtips1/15-better-lorem-ipsum-generators-3f99
- Placeholder Pictures
  - https://source.unsplash.com/
  - https://github.com/imsky/holder
  - https://lorempixel.com/
  - http://placeimg.com/
  - https://picsum.photos
  - Blanks
    - http://placehold.it/300x300
  - Animals
    - https://placedog.net/
    - https://placebear.com/
    - http://placekitten.com/
  - Food
    - http://placebeer.com/
    - https://baconmockup.com/
  - Actors
    - https://www.placecage.com/
    - https://placekeanu.com/
    - https://www.stevensegallery.com/
    - https://www.fillmurray.com/
  - https://assetroulette.com/
    - Get a random image: `<img src="https://api.assetroulette.com/random_image">`
    - Get a random meme image: `<img src="https://api.assetroulette.com/random_meme">`
    - Get a random image from Unsplash: `<img src="https://api.assetroulette.com/random_unsplash">`
    - Get a random CSS definition for base classes: `<link rel="stylesheet" href="https://api.assetroulette.com/random.css">`
  - https://dog.ceo/
- Users
  - https://randomuser.me/
  - https://jsonplaceholder.typicode.com/
- Relational Data
  - https://swapi.dev/ - theres a graphql swapi as well
  - https://pokeapi.co/api/v2/
- Misc
  - https://openweathermap.org/guide
  - https://github.com/public-apis/public-apis
  - https://public-apis.io/ (A Directory of Free Public & Open Rest APIs)
  - https://github.com/Marak/faker.js - generate fake pdf https://aws.amazon.com/blogs/aws/new-for-aws-lambda-container-image-support/
  - https://github.com/Rolstenhouse/unofficial-apis
  - https://devresourc.es/tools-and-utilities/public-apis 
  - https://free-for.dev/#/?id=apis-data-and-ml


## Copy and Emails

- https://www.goodemailcopy.com/
- https://www.swipefiles.co/


## Random Stuff That Doesn't Fit Anywhere

- https://10ideesrecuesenuxdesign.castoretpollux.com/en/

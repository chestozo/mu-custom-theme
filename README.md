# mu-custom-theme

## Setup
- activate new theme
- delete .. child theme and Avada main theme
- delete fus.. core plugin
- delete LayerSlider WP plugin
- delete random content plugin
- install Bootstrap 3 Shortcodes plugin (by Filip Stefansson; it is this one https://github.com/filipstefansson/bootstrap-3-shortcodes)
- set menu as primary menu
- screen options - link target - tick
- set target blank for external links in menu
- fix page title if needed? (the only problem - is the home page where description is added. Maybe we can keep it like this? check with G)
- Index page
  - screen options - slug - tick
  - <del>add manually slider to page content `[rev_slider home]`</del> (now it is in `header.php`)
  - set slug as `home`
  - fix html
    - last 2 one_third columns remove style `style="margin: 0 auto;"`
- Subscription page
  - html
    - remove `style="text-align: left;"` and `style="text-align: right;"` for the 1st and last columns
    - add ` parent_class="mtv-subscription-tiles"` to the first column
- LS page
  - update embed code (wrap it)
- FAQ page
  - replace `fusion_tabs` with `tabs` and `fusion_tab` with `tab`
  - wrap it into `div.mtv-faq-tabs`
  - wrap image into `[img responsive=true]`, remove sizes
  - add after `<br/>`
- Terms page
  - wrap image into `[img responsive=true]`
  - add after `<br/>`
- Contacts page
  - wrap image into `[img responsive=true]`
  - add after `<br/>`
  - fix `</p>` inside one of the columns

NOTE
- I've changed `.thumbnail` class to `.mtv-thumbnail` (it was interfering with bootstrap standard class).

DONE
- we forgot to check alerts (in js code)
- it took 40 mins instead of 15


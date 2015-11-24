# mu-custom-theme

## Setup
- activate new theme
- deactivate fus.. core plugin
- deactivate random content plugin
- deactivate LayerSlider WP plugin
- install Bootstrap 3 Shortcodes plugin (it is this one https://github.com/filipstefansson/bootstrap-3-shortcodes)
- set menu as primary menu
- set target blank for external links in menu
- fix page title? (the only problem - is the home page where description is added. Maybe we can keep it like this? check with G)
- Index page
  - <del>add manually slider to page content `[rev_slider home]`</del> (now it is in `header.php`)
  - set slug as `home`
  - fix html
    - last 2 one_third columns remove style `style="margin: 0 auto;"`
- Subscription page
  - html
    - remove `style="text-align: left;"` and `style="text-align: right;"` for the 1st and last columns
- LS page
  - update embed code (wrap it)
- FAQ page
  - replace `fusion_tabs` with `tabs` and `fusion_tab` with `tab`
  - wrap it into `div.mtv-faq-tabs`
  - wrap image into `[img responsive=true]`
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

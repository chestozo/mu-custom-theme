# mu-custom-theme

## Setup
- activate new theme
- diactivate fus.. core plugin
- diactivate random content plugin
- download as archive and install https://github.com/filipstefansson/bootstrap-3-shortcodes
- set menu as primary menu
- Index page
  - <del>add manually slider to page content `[rev_slider home]`</del> (now it is in `header.php`)
  - set slug as `home`
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
- I've changed `.thumbnail` class to `.mtv-thumbnail` (it was interfaring with bootstrap standard class).

# Description
Nag screen removal extension for Opera, Firefox, and Chrome.

# Offending Divs
- Facebook (Can scroll continuousuly)
	- .pagelet_growth_expanding_cta
	- .pop_dialog
- Pintrest (Can scroll continuously unless on indivisual posts)
	- .ModalManager .Module (on pages)
	- .Module .Nags (on indivisual posts) (can not scroll, need to change class of containing div from noscroll to none)
	- Classless div to delete sometimes appears on opera (same as issue 2)

- Tumblr (Can't scroll further)
	-  class "register_prompt windowed-slide windowed" (no scrolling impares use of site, deemed not resonable to remove)

# TODO
 1) Figure out how to remove the class="noScroll" from they body tag on pintrest
 
 2) Opera sometimes displays a different nag screen without a class tag on pintrest (only on katt's pc)
 
 3) Port to Firefox
 
 4) Create UI for enabling/disabling + icon.

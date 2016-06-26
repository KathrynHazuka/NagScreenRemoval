# NagScreenRemoval
Nag screen removal extension for Opera, Firefox, and Chrome.

# Offending Divs
- Facebook (Can scroll continuousuly)
	- .pagelet_growth_expanding_cta
	- .pop_dialog
- Pintrest (Can scroll continuously unless on indivisual posts)
	- .ModalManager .Module (on pages)
	- .Module .Nags (on indivisual posts) (can not scroll, need to change class of containing div from noscroll to none)
	
- Tumblr (Can't scroll further)
	-  class "register_prompt windowed-slide windowed" (no scrolling impares use of site, deemed not resonable to remove)

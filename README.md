# NagScreenRemoval
Nag screen removal extension for Opera, Firefox, and Chrome.

# Offending Divs
- Facebook (Can scroll continuousuly)
	- .pagelet_growth_expanding_cta
	- .pop_dialog
- Pintrest (Can scroll continuously)
	- .ModalManager .Module (on pages)
	- .Module .Nags (on indivisual posts) (can not scroll, need to change class of containing div from noscroll to none)
	- <div style="background: rgba(0, 0, 0, 0.85) none repeat scroll 0% 0%; transition: height 0.5s cubic-bezier(0.26, 0.87, 0.74, 0.93) 0s; bottom: 0px; color: rgb(255, 255, 255); height: 100%; position: fixed; width: 100%;" is = null>
	
- Tumblr (Can't scroll further)
	-  class "register_prompt windowed-slide windowed" (impares use of site, deemed not resonable to remove)

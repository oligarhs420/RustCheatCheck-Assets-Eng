OOF.LV

Credits:

@sexgamer
@NotEagle

example image - https://i.imgur.com/XKgZKnd.png

===============================================================
Plugin - https://hlmod.ru/resources/rust-check-cheats.1437/ or use this new fork -
https://hlmod.ru/threads/check-cheats-fork
===============================================================

1. Edit - overlay_downloads2.ini (For forked version edit - CheckCheats_resources.ini)



overlay_cheats/ban_cheats.vmt

overlay_cheats/ban_cheats.vtf

==>

OOF_LV_ASSETS/cheatcheck_ooflv.vmt

OOF_LV_ASSETS/debil_check.vtf


2. Edit Line 120 & Recompile - CheatsCheck.sp



GiveOverlay(clientChoose, "overlay_cheats/ban_cheats");  ==> GiveOverlay(clientChoose, "overlay_cheats/cheatcheck_ooflv");

================

For forked version Edit line 412 - GiveOverlay(clientChoose, "overlay_cheats/ban_cheats_v10");  ==> GiveOverlay(clientChoose, overlay_cheats/cheatcheck_ooflv");


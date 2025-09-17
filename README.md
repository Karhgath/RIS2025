# RIS2025
RIS2025 related files

Official RiS2025 Doc: https://docs.google.com/document/d/1vWqZa7-2AYW3N_LOAvrzCC3EGl3pWZlbxSkrCdjo0Rk/edit?tab=t.0#heading=h.m1il6rk5f6xh

## How to use the .cfg file

- The **RIS2025-X.cfg** file for RiS is the main file and cannot be duplicated - the final official file will be called **RIS2025-OFFICIAL.cfg** and you will need to remove any previous files lying around (e.g. ALPHA, BETA)
- Download the repo, it uses the standard GameData structure. Be sure to copy the _GameData/RIS2025_ folder in _{ksp}/GameData_.
- Before launching the game, please open the file if you want to change your starting launch site
  
## Launch Site Selection
- A config in the file allows you to set your starting Launch Site and where your starting LC is built.
- At the top of the file is a list of all sites, commented out (with // ). If you want/need to start at a location other than The Cape, uncomment the site you want to use.
- Make sure only 1 @DefaultSite is uncommented
- Extra sites from RSS-LaunchSitesAddon are also included: https://github.com/leudaimon/RSS-LaunchSitesAddon

For example, this would force you to start at Baikonur.

	//@DefaultSite = jp_uchinoura
	//@DefaultSite = kp_sohae
	//@DefaultSite = kr_naro
	@DefaultSite = kz_baikonur
	//@DefaultSite = mh_omelek
	//@DefaultSite = nz_mahia
	//@DefaultSite = ru_kasputin_yar

# TYPO3 CMS 11.5 AOE Patches

### cms-backend

`FE-rendering-gridelements.diff`

[BUGFIX] fix FE-rendering of gridElements (config of gridelements could not be determined by loading pages-ts-config)

`Load-FlexForm-Sections-on-new-before-save.diff`

[BUGFIX] Load FlexForm Sections on new before save
FlexForm Section can be added before content element is saved.
This is done by ensuring that processedTca have a value for list_type.

Earlier the pi_flexform was ignored as the default values on create
before save was empty.

Resolves: #81684
Releases: master, 11.5, 10.4, 9.5
Change-Id: I62e03cbbd93e8785f58c24dad1e573e8b5e0202b


### cms-frontend

`Add-hook-to-page-is-being-generated.diff`

[FEATURE] Add hook to customize "page is being generated" temporary page

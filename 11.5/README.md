# TYPO3 CMS 11.5 AOE Patches

### cms-backend

`FE-rendering-gridelements.diff`
[BUGFIX] fix FE-rendering of gridElements (config of gridelements could not be determined by loading pages-ts-config)


### cms-frontend

`Add-hook-to-page-is-being-generated.diff`
[FEATURE] Add hook to customize "page is being generated" temporary page

`Fix-frontend-preview-on-restricted-pages.diff`
[BUGFIX] Fix frontend-preview on restricted pages.
         The bug is fixed in TYPO3 v11.5.6. So, you only need this bugfix, if you don't use the latest TYPO3-version!


### gridelements

`fix-moving-of-content-elements-into-gridelements.diff`
This patch belongs to gridelements-extension in version 10.x - NOT version 11.x!
This patch is deprecated - instead of this, use the patch `fix-several-bugs-in-gridelements-v10.diff`!
[BUGFIX] fix moving of content elements into gridelements

`fix-several-bugs-in-gridelements-v10.diff`
This patch belongs to gridelements-extension in version 10.x - NOT version 11.x!
So, you need this patch, if you use gridelements-extension v10.x together with TYPO3 v11.x!
[BUGFIX] fix copy+paste of content elements in TYPO3-BE (in module 'page')
[BUGFIX] fix moving of content elements (especially in gridelements)
[BUGFIX] fix moving+editing+deleting of content elements (especially in gridelements) in workspaces

`fix-backend-layout-wizard-element-not-found.diff`
This patch fixes the 'Class 'TYPO3\CMS\Backend\View\Wizard\Element\BackendLayoutWizardElement' not found' 
Error on creating a Backend Layout in gridelements 11.x

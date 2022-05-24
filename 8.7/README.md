# TYPO3 CMS 8.7 AOE Patches

### cms-backend

`FE-rendering-gridelements.diff`

[BUGFIX] fix FE-rendering of gridElements (config of gridelements could not be determined by loading pages-ts-config)

### cms-core

`Add-domain-record-to-trusrted-HTTP-HOST.diff`

[FEATURE] add "DOMAIN_RECORD" to trusted HTTP_HOST configuration, use queryBuilder

`Update-tstamp-of-record-when-sorting-will-be-updated.diff`

[BUGFIX] DataHandler-Bugfix: When "sorting"-field of DB-record will be updated, then the "tstamp"-field of that
         DB-record should also be updated (@see https://forge.typo3.org/issues/90841).

### cms-extbase

`Extends-exception-message.diff`

[TASK] exception-message should contain more information why the object could not been created

`81208-workspace-mm-relations.diff`

[BUGFIX] Invalid SQL query when previewing a workspace with translated relations

### cms-frontend

`Add-hook-to-page-is-being-generated.diff`
`Increase-cObjectDepthCounter.diff`

[FEATURE] Add hook to customize "page is being generated" temporary page
[TASK] Increase cObjectDepthCounter from 50 to 100 to increase nesting of elements


# TYPO3 CMS 7.6 AOE Patches

### cms-backend

`FE-rendering-gridelements.diff`

[BUGFIX] fix FE-rendering of gridElements (config of gridelements could not be determined by loading pages-ts-config)

`Rendering-of-inline-flexforms-in-gridelements.diff`

[BUGFIX] Fix rendering of inline flexform fields in TCEFORM

### cms-core

`Add-domain-record-to-trusrted-HTTP-HOST.diff`

[FEATURE] add "DOMAIN_RECORD" to trusted HTTP_HOST configuration, use queryBuilder

`Update-tstamp-when-sorting.diff`

[BUGFIX] CD-157807: When "sorting"-field of DB-record will be updated, then the "tstamp"-field of that DB-record should also be updated

### cms-extbase

`Extends-exception-message.diff`

[TASK] exception-message should contain more information why the object could not been created

### cms-frontend

`Add-hook-to-page-is-being-generated.diff`

[FEATURE] Add hook to customize "page is being generated" temporary page

`Remove-workaround-for-firefix-bug.diff`

[TASK] Remove workaround for Firefox bug resolved years ago


### cms-rtehtmlrea

`regression_with_chrome.diff`

[BUGFIX] Regression with Chrome 73

See: https://github.com/FriendsOfTYPO3/rtehtmlarea/issues/26

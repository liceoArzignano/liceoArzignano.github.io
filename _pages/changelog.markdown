---
layout: page
title: Changelog
permalink: /changelog/
---

## 1.0.18
* 4aa238e Home: remove unused RemoteConfig
* ef3ada0 Marks, Events, News: use autoincrement for id
* 7708d30 Bold: lint cleanup
* be0f72d Backup: support restoring backups created with different db versions
* 1f313e8 Editor: animate the right editText for marks
* d94e6d4 Safe: fix fingerprint management for older devices
* 9762a8a Settings: show right category color for api19- device
* e96a88a Editor: improve date picker
* 7c7c4bd Editor: do not ask to save changes if nothing has changed
* a42baa0 Editor: do not show empty tags
* cbe2a96 Editor: properly hide the tags layout when editing marks
* 863a5b6 Res: adaptive icon
* e1a4f5d Home: expose important suggestions
* 64eb13e Res: improve home card strings
* 737b07d Bold: update deps
* 52e9ff7 Safe: support login with fingerprint
* fa06282 Marks, Events, News: optimize search queries
* 4ae05b2 Events: add tags
* dd2a14d Bold: don't use kotlin stdlib, legacy devices don't work with it
* 53b782e Home: update cards content
* 07e4ea9 Events, News: make header dividers more informative
* 48c87ad Mark: update subjects recyclerview's items style
* ec71bf4 Marks, Events, News: polish enter/exit transitions
* 72f26ee Build: update kotlin
* f6888c9 Intro: fixes for legacy devices
* 1edac5d Bold: bump to 1.0.18
* ba61d52 Safe: destroy the asyncTasks when activity gets destroyed
* 8f6a535 Home: hide logo view on legacy devices
* 55e7fa4 Res: show emoji only on api21+
* ce45bdc Bold: redesign
* 9038d8c Safe: update mod revision
* ee21e29 Time: DAY_OF_YEAR != DAY_OF_MONTH
* a796e95 Mark: sync item ui with news and events
* c1d672c Safe: run encryption operations in an async task
* bb0a58d Events: add emoji to event categories
* 8877c66 Res: tune colors
* 2c2b92d Bold: hello kotlin
* 46bf201 Home: add shortcut cards
* d12e8a6 Bold: lint cleanup
* f105f1a Bold: refactor -2 classes to normal names
* 61d3ac5 Bold: remove Realm
* e56aea6 Bold: support api26
* 1a21297 Res: improve strings
* ff7823e Marks: fix quarter detection
* 3e0019e Marks, Events, News: migration to SQL
* 8d72602 Home: cleanup
* b326d20 Marks: improve quarter detection logic
* 9095dee Backup: add new year helper
* 97bf39b Bold: bump deps
* 8213500 Res: fix statusbar color on api21+
* 26d0fc6 Home: fix remoteconfig cache expire time for prod
* 51624ec Home: animate transition on card click
* bc7b8e9 Bold: Remove .idea project files
* fe1e063 Feedback: remove
* ba49d53 Res: commonize toolbar layouts
* 90b935b Marks: circular progress bar: draw a background circle
* 76c5ee3 Update gradle plugin
* 1829380 OnBoarding: show toast hint for long press items actions
* 875d5bf Bold: lint cleanup
* 4ffdfe1 Backup, Safe: match feedback help style
* 71e087d Backup: display a progress dialog while backing up
* 879721f Res: don't make the pencil run away
* db6af2b Build: update deps
* 63a459c Safe_mod: update revision
* 9bc9f4d Home: animate only once
* c9e6e90 Home: rearrange drawer list
* 3d89cf0 Update submodule


## 1.0.17

* f141562 Bold: bump to 1.0.17
* 5ffc8dd Home: animate added cards
* 7957f89 Feedback: fix on production builds
* 7c8b158 Backup: fix classNotDef exception
* 800102e Res: fix and improve strings
* 87ae488 Feedback: introduce feedback
* c7d6a2b Home: make cards clickable
* 775c938 Editor: refactor and cleanup
* fdc32a2 OnBoarding: fetch looper from arg
* b6d6b72 Bold: proguard: keep SearchView widget
* 3698816 News: explicity mark private news with custom message
* cd31377 Bold: fix toolbar up action
* 457888c Bold: improve code readability
* c2d744f Res: fix english strings typos
* b9a4752 Event, news: show actions on long press
* c5c5e7c Marks: animate circular progress bar only one time
* 8741a29 Bold: optimize tablet UI
* 43d35b0 Bold: support 2.25:1 aspect ratio devices
* 1924392 Bold: lint cleanup
* bfd85e6 Marks: new Filter marks UI
* 0866174 Home: remove unused code
* 82f8edd Home: add missing fitsystemwindow for collapsingtoolbar
* 6032e34 Safe: define input type for fields
* 48c693c Marks, Events, News: clean up list UI (pt 2)
* 3933353 Res: fix it translation typo
* a73eb2e Home: fix events card appareance
* 33029ea Bold: refactor Utils class to utils package
* 473e540 Bold: lint cleanup
* af418f7 News: update list ui to match event list
* bda085a Events: clean up event list
* 1665a93 Marks, Events, News: optimize recyclerviews
* ebf6cfa Bold: update deps
* daa1a74 Analytics: log some actions
* f34aa3b Build: bump google play services libraries
* 6dfa44f Events: fix notification message
* cdeb2e7 Home: add help link to navigation drawer
* cc867d8 Bold: lint cleanup
* 8a434be Build: compile firebaseCrash only for release builds
* 1428691 OnBoarding: fix animations on api 21->23
* 5561c6d Firebase: debug notifications on debug builds
* fbd7521 safe_mod: update
* 2a96406 Manager: import date to time picker when editing
* 7f8e26d Viewer: allow only one line for title text
* 580c668 Safe_mod: update
* 66fd814 OnBoarding, Viewer: fix avd animation on api21->23 devices
* c67a011 Build: versioning for play store
* b89284a Bold: bump support libraries
* 1504fb0 Bold: add firebase remote config
* 5b52d5f Bold: bump deps
* 0c41fb8 Bold: re-enable release proguard config for release builds
* dc8ffb7 Bold: enable firebase crash reporting
* 5e72101 Home: add share app to navigation drawer
* 4f4b8c8 OnBoarding: fix for legacy and non-GMS devices
* bf39705 Settings: switch to preferenceCompat
* ec635ca Build: bump libraries
* 6450143 Bold: fix more codacy issues
* b00429c Bold: fix some codacy-reported errors
* 5a43dcb Bold: add codacy badge
* 2dbc29f Settings: add safe status entry
* 4f13b71 Bold: it's OSS
* 05d2209 OnBoarding: beautify teh onboarding ux
* b73fb7f News: add deep link
* a11440f Safe: don't do safetynet checks when loading SafeActivity
* 2414903 Events: optimize date query
* 8479758 Bold: fix variable naming
* eb04777 Viewer: sync ui with news details
* ffc8d66 Marks, Events, News: fix recyclerview touch listener
* 20d128d Events: implement by-date view
* 29f416a Res: update strings
* f9f3843 Marks, Events: fix minor ui issues
* efde330 Bold: lint cleanup
* 7a6d2c4 Bold: declare SettingsActivity as app preference activity
* f457eee Open Source push
* 35c680c Bold: gitignore google-services.json
* 6e1ae07 OnBoarding: fix radio address selector
* 9257013 Safe: switch to new module
* 0e324a2 Safe: strip out encryption module
* 52ce19e OnBoarding: new onBoard experience
* 2bd363a Safe: enhance security checks
* 1a75f96 Build: bump libraries
* 8102144 Events, News: case insensitive search
* a00fb14 Marks, Events: date should be Date
* 4a288f9 Bold: lint cleanup
* f16f23d Marks: improve Ux
* e8436c2 Firebase: update json format for bold_sleeper
* e7b0607 Home, News: make sure custom tabs service is connected before unbinding
* 10e8e4b Build: update gradle
* 17a2bd8 Marks: make sure data is fetched before adapters are built
* 05c79b5 Home, News: stop the chrome memory leakage
* 7748285 Bold: refactor to respect LoD
* 7bb402f Res: simplify address icons
* 721ce88 Build: update dependencies
* 280c26f Mark: fix average ui issues
* 58186e7 Safe: ship a new 256bit key
* c05a946 Safe: remove deprecated Crypto provider
* 6a6328c Build: update PlayServices to 10.0.0
* f854f89 Home: workaround for drawer animation lag when doing heavy operations
* 1ca4f0d Marks: improve list transition animations
* 0658c04 Bold: lint cleanup
* 7e80494 Analytics: send config on app start
* 342912d Bold: switch to lambdas
* d91a7bd Build: add retrolambda
* 46d88a0 Marks: fix OutOfBoundArray when viewing new mark average
* ab7c882 Res: fix some strings
* 5b0f082 Safe: improve dialog behaviour
* ddf98b9 Safe: improve password hints
* f6ccd5e Viewer: don't add delay if we are not animating edit button
* 81faa99 Main: cleanup
* 4e57164 Res: reformat xml files
* 6ab0615 News: use BigTextStyle for notifications
* 7f67fb3 Res: switch to vectorDrawables for events icons
* e783d93 Bold: enable compatVectorFromResources on legacy devices
* cbab9d9 Safe: enable password toggle
* 5dc5970 Events: cleanup notification service
* 5a86b53 Marks, Events, Editor: fix navigation
* 30bb5f3 Marks, Events, News, Safe: fix empty status alignment
* 5973539 Build: update android support library
* d07fe61 Viewer: turn into bottom sheet dialog
* 4cc39be Safe: animate layout changes
* e875e71 Safe: fix scrollView wave effect
* 6d57d0f Safe: new login dialog
* f0242a1 Marks, Events, News: beautify empty status icons
* 77c3af1 Safe: inform user content has been locked onPause()
* 52c3ae4 Build: switch to stable gradle android plugin
* c437b3b Makrs: fix average title align
* f561bfe Viewer: add right padding to text
* cfa07ca Viewer: fix share message for events
* d67df4d News, Events: avoid NPE when setting OnQueryTextListener


## 1.0.16

* abd5273 Bold: bump version to 1.0.16
* a11a608 Res: update strings
* c2e01b1 Build: bump materialTapTargetPrompt
* c0ece4a Build: update dictionary
* 3ead8f5 Backup: update backup list
* 60209c4 Safe: unbreak LinuxPRGNSecureRandom on api16 and 17 devices
* 4a064cb Marks: avoid out of range error
* 75f1327 Home: make recyclerview match_parent height
* ca4c2a5 Safe: show exit confirmation dialog when clicking back button in toolbar too
* c8c0beb Safe: don't set SECURE_FLAG for debug builds
* 2d56a28 Home: don't show empty events card
* a629f91 OnBoarding: cleanup
* c584ccd Bold: fix event shortcut strings
* 4f5e662 Bold: lint cleanup
* 55bd1c0 Firebase: add students topic
* 58f81a8 Safe: fix inverted strings
* 5a970a9 Safe: show data usecase
* 0fbce91 Home: set HomeTextCardTitle max lines to 1
* f606edf News: add some new features
* 1d64ac2 Build: fix play services version
* afe7142 News: avoid failure when casting Context to Activity
* 3ebe3a8 Home: prevent NPE when creating notification
* 5925dc5 Home: add news card
* 18c6c7a Home: fix empty cards appareance
* 649b4d4 Bold: add shortcuts
* dff1374 Bold: lint cleanup
* a7fcf86 Build: update gplay version
* cbf856b Home: refactor out cards as recyclerview items
* 7956f26 Events, News: implement search
* 40999a6 Build: update support library to 25.0.0
* 432713d Marks, Events, News: add empty states
* c588d69 Bold: refactor and fixup variables naming
* abd674e Res: remove unused layout file
* 8e425df Res: fix id names
* 2ecfdcf News: allow the user to turn off news notifications
* 8d40d35 Bold: introduce News
* 060c5a0 Build: compile aganist api 25
* 59d05a0 Firebase: subscribe to address-based topic
* 4efe542 Backup: cleanup UI
* ce9c801 Res: reorder layout entries
* 02b02f6 Firebase: support for remote url from message
* fe432d5 Manager: fix month in dialog picker
* cecfe4d Res: update strings
* f633a71 Bold: remove pointless cmake build directory
* 48da0e8 Backups, Events, Marks: switch to RecyclerView
* 6c05a93 Firebase: rewrite notification service for BoldRemote support
* ed3e99c Res: fix typo
* 05eac11 Editor: fix multilines note input appareance
* fb4f473 Viewer: define its own light theme
* e80fd3d Manager: bug hunting season
* c937cfc Bold: MainActivity and Utils cleanup
* 173202a Home: add option to see the whole changelog when app is updated


## 1.0.15

* 009e563 Bold: bump version to 1.0.15
* 6a4d721 Build: update deps
* fd91f65 Res: update pre-kk fab drawables colors
* 259304f Bold: lint cleanup
* 783e339 Average: improve layout
* cb56873 Viewer: cleanup UI
* d677550 Manager: fix subject selector visibilty
* 7dd3520 Events: fix notification message
* 64fdca4 Build: update deps
* 7c1ef54 Bold: lint cleanup
* f8fc931 Home: redesign
* 105f934 Event: new categories
* 0107d38 Mark: refactor content to note
* 6695c0d Event: add notes
* 6fb3308 Manager: make elements smaller
* 02564ae Settings: make sure user has apps for backup
* fcbec54 Res: fix up subjects
* fb6937d Firebase: improve notification
* e9c4164 build: update deps
* a38c6ca [2/2] Manager: update UI
* 27a4773 Analytics: log user sharedpreferences config when settings are opened
* 10196f7 Bold: update javadoc
* 4acaea5 Marks: fixes for teachers
* 6e5ad89 Revert "Icon: update color to match school diary"
* 39c5202 Marks: improvements
* f4e45f7 Manager: show the right message for subject selector button when not in edit mode
* 6a1ae16 Res: bring back accidentally changed accent colors
* afb7a9d Res: set the right config_quarter_change date
* d6891b6 Res: update strings and translations
* e1433f6 Icon: update color to match school diary
* aab4f84 Safe: cleanup
* a05aabd OnBoarding: ask address first time user reachs the home
* 91b1575 Res: update events and addresses colors
* 5698f8d Marks, Events: improve list layout
* decafbd Bold: lint cleanup
* a1bc566 Safe-addon: hax to guard aganist invalid bytes errors
* 1862a6b Safe: new Safe "engine"
* 67a8a3b Safe: onBackKeyPressed warning dialog and JNI crash fix
* d6f0726 Manager: update UI
* 1d91500 Res: string updates and fixes
* 3fb7613 Bold: lint cleanup
* 06a3cf1 Bold: introduce Firebase support
* c8903cc Analytics: remove google analytics
* e7c3561 Safe: don't encrypt empty strings
* 918eac4 Realm: update plugin version and remove unused methods in RealmController class
* 5bce208 Home: add lastest marks card
* 2fdaa9e OnBoarding: update pics and descs


## 1.0.14

* c95ab28 Bold: bump version to 1.0.14
* a4533b6 Backup: explain that it's not possible to create backups in debug builds
* 22f3700 Settings: show contact info before about
* 0860931 Events: finish() eventListactivity onBackPressed()
* 100b702 Manager: minor fixes
* b5a647b Res: update italian strings
* a119f5e Safe: security improvements
* 645fd38 External: drop materialShowCaseView in favour of MaterialTapTargetPrompt
* 9b1b199 Manager: fix N MultiWindows Ui issues
* 5a42806 Safe: remove ShowEye
* d22136a Build: update deps
* 00400e8 Res: update strings
* 9de3dac Marks: quarters
* c86732a [TMP] gradle: workaround for gradle failure
* 5180273 Bold: lint cleanup
* 2ac5e5d Build: update build.gradle
* c5321ce Bold: refactor
* 3e9b9b9 Bold: new icon
* b3b6ac2 Viewer: fix share string for mark


## 1.0.13

* efbe80b Bold: bump version to 1.0.13
* d45c85e Bold: new icon
* 8f1cf2d Events: the sooner, the latter
* fe789be Backup: improve Ui
* 90898c2 Safe: fix minor issues
* d22b313 Bold: GDrive realm backup
* 6227aac Events: onBootReceiver: make sure realm is initialized
* 5e6b7c2 Bold: lint cleanup
* 61f88b7 Build: arch flavours
* 251673c Bold: realm all the things
* 5c5e77d Res: update and fix strings
* db45872 Bold: cleanup
* f769923 Manager: if we created nothing, show nothing
* 15e6fb7 External: import InkPageIndicator library
* 89056cf Editor & Viewer: improve Ui/Ux
* 3e4dd56 Events: make sure notifications appear the right day
* a39e6d6 Res: fix paddings
* 67ee12f Events: declare onBootReceiver intent arguments explicitely
* 2014a89 Manager: always init the right value for mark preview
* 457d2a9 Marks: create average list dynamically
* 1d1dba7 Marks: guard aganist npe
* 2ff031b Safe: don't try to decrypt stuffs if there's nothing to decrypt
* 272075d Events: fix notification and bootreceiver
* e318f79 Res: update iconography for pre-lp devices
* 0192fa6 Marks: make sure AverageListFragment is initialized
* c8f03b6 Home: Don't show user icon on api20< devices


## 1.0.12

* 6a4a7a9 Bold: bump to 1.0.12
* a251d8e Bold: lint optimizations
* d7d34ab External: brand new Benefits OnBoarding experience
* bdb7c73 External: import slimmed down and customized MaterialShowcase Lib
* 9dc11e4 Utils: animFabIntro: make target touchable
* a522a5b Events: sort ListArray with sql query by date
* 8f4d4e5 Bold: lint optimizations
* ed8ae4c Marks: DatabaseConnection: fix memory leak
* bee3e23 Build: debug builds should be debuggable
* 4888987 Bold: use formattable strings instead of strings chains
* 0055467 Manager: fix npe
* f5c8de9 OnBoarding: better experience


## 1.0.11

* ff59a4b Bold: Bump to 1.0.11
* dd3cc82 Events: add notifications
* 6e45c80 Res: resize png drawables
* 99e39a7 Marks: fix onBackPressed behaviour in MarkView
* b321351 Bold: remove random selector
* ede83ad Bold: initial release
* 7d8f3b0 Initial (git) commit

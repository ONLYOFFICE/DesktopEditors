# Change log
## 4.2.2
### Fixes
#### All Editors
* Do not perform save if there is no changes to save
* Fix a rare problem with saving file with specific type of Chart
* Fix problems with copy-paste

#### Document Editor
* Fix problem with losing changes while several users enter text at same time (bug #33726)
* Fix bug with positioning of cursor after function InsertContent.

#### Spreadsheet Editor
* Fix wrong order of elements in equations (bug #34029)
* Fix entering symbols with diacritical sign (bug #33908)
* Fix horizontal scroll by trackpad (bug #27197)
* Fix assembling files with Ranges in rare cases
* Fix convert xlsx to csv
* Fix `Match` formula return value in some cases (bug #33735)

#### Presentation Editor
* Fix a problem with saving file with notes, copied from Document Editor
* Fix a problem with saving file with chart, copied from Presentation Editor


## 4.2.1
### New Features
#### All Editors
* Ability to set dash type for shapes
* Better support of HiDPI systems

#### Document Editor
* Ability to open and edit Footnotes
* Ability to insert number of pages in document
* Redone Version History. Ability to hide minor features.

#### Spreadsheet Editor
* Add ability to insert Equations in Spreadsheet Editor
* Ability to open and edit Sparklines
* Add new formula `SUMIFS`
* Ability to select data from drop-down menu in context menu
* Add multiselect support
* Add rotation of 3D Charts
* Update and improve visual styles for all chart types
* Bring back `Freeze Panes` in `View Settings` menu
* New algorithm for calculating cell height

#### Presentation Editor
* Add ability to insert Equations in Presentation Editor

### Fixes
#### Document Editor
* Fix broken `Insert number of page` button
* Fix problem with duplicate of last hieroglyph
* Fix problem with changing chart type from 2D to 3D

#### Spreadsheet Editor
* Fix problem with empty cell while changing sparklines

#### x2t
* Improve compatibility with `doc` format

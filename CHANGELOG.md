# Change log
## 4.3.2
### New Features
#### Editors
* Full support of high-dpi monitors
* Ability to set alternative text for shapes

#### Document Editor
* Undo in Fast co-edit
* Do not hide `All changes saved` in bottom toolbar
* Adding and editing Footnotes
* New languages for spellchecker (43 in total)

#### Spreadsheet Editor
* Support `AVERAGEIFS`, `COUNTIFS`, `SUMIFS` formulas
* Formulas refactoring and improvements
* Totally new Cell Format window with more options
* Sort options window while sorting ranges
* Added direction of sort on filter buttons
* Added filter condition at statistical information
* Added special paste feature 
* Added support of surface chart
* New cell borders styles (11 in total)

#### Presentation Editor
* Undo in Fast co-edit

#### Convertion
* Optimization and speed-up
* Better support of all formats, including (but not limited to):

##### DOC
* Background page

##### XLS
* Data validation
* Decryptor

##### ODF
* Global settings for documents
* SVG refactor
* Background page (image, pattern, gradient)
* Convert smart art
* Sheet/Workbook views
* Support convert OLE objects (and other embedded)

##### RTF
* Generate replacement text hyperlink if absent
* Office digital signatures
* Extended drawings
* Custom shapes
* Text in drawing shapes

### Fixes
#### Document Editor
* Fixed an issue with drag-n-drop a table inside a footnote (bug #33548)
* Fixed an issue with crop of shape group (bug #33110)

#### Spreadsheet Editor
* Fixed an issue with absolute reference when inserting a new row (ONLYOFFICE/DocumentServer#41)
* Fixed an issue with onDocumentStateChange event (ONLYOFFICE/DocumentServer#88)
* Fixed an issue with formulas translation (ONLYOFFICE/DesktopEditors#23)
* Fixed an issue with password-protected xlsx (ONLYOFFICE/DesktopEditors#24)
* Fixed an issue with non-breaking space (ONLYOFFICE/DesktopEditors#26)
* Fixed an issue with AVERAGEA formula with text format
* Fixed an issue with broken workbook after list copy (bug #33588) 
* Fixed an issue with formula recalculation by F4 hotkey (bug #32901)
* Fixed an issue with SUMIFS formula (bug #33602)
* Fixed an issue with inserting image size (bug #33604)
* Fixed an issue with zero values sparklines (bug #33612)
* Fixed an issue with changing number format while changing regional format (bug #31395)
* Fixed an issue with replacing formula delimiters (bug #33608)
* Fixed an issue with cell size while drag'n'drop (bug #33607)
* Fixed an issue with cursor size in @2x (bug #33606)
* Fix broken files if changing style of unsupported charts (bug #34650)
* Fix stack error while copying a big array of formula data
* Fix rendering 3d diagram in small area (bug #34632)
* Fix change chart's range while applying preset


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

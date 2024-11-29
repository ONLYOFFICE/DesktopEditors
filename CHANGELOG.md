# Change log

## 8.2.2

### Fixes

#### All Editors

* Fixed displaying some chart types when opening the `DOCX` or `PPTX` documents
* Fixed availability of buttons on the right panel when the zoom is higher than 200%
* Fixed application launch on macOS Big Sur with the Apple Silicone architecture
* Fixed crash of the editor when detaching a tab with a document, opened from
  the cloud portal, into a separate window
* Fixed the ability to return to the current document from the version history or
  show the file if a new version was build on the portal DocSpace/Workspace

#### Document Editor

* Fixed stopping work of the editor when working with the Text box in the Header
  if it contains the page number
* Fixed slow scrolling of documents if the document extends the visible area
* Fixed stopping work of the editor when comparing some `DOCX` documents
* Fixed text selection when clicking on a paragraph with Justified alignment

#### Spreadsheet Editor

* Fixed stopping work of the editor when deleting a formula from a cell in
  some `XLSX` files
* Fixed disappearing formulas when opening some `XLSX` files
* Fixed the ability to scroll a sheet horizontally using `Shift` + `Mouse wheel`
* Fixed stopping work of the editor when merging all cells on a sheet
* Fixed loss of graphic objects rendering after rotating them in the Sheet
  Right-to-left mode
* Fixed missing the Multi-Select/Clear Filter of Slicer buttons after scrolling
  horizontally or vertically

#### PDF Editor

* Fixed stopping work of the editor when adding a matrix in a math equation
* Fixed the short-term absence of an image added by one of the users in co-editing
* Fixed incorrect selection of paragraphs/columns in the Select tool mode when
  opening `XPS`/`OXPS`/`PDF` files

#### Forms

* Fixed the status of unsaved changes presence when clicking Complete & Submit
  quickly during filling in a form in DocSpace

## 8.2.1

### Fixes

#### All Editors

* Fixed appearance of an extra argument when switching from a linear equation
  to a professional one
* Fixed navigation via menu instead of moving around text when using the Alt key
  and keyboard arrows
* Fixed inconsistency in the appearance of labels as compared to other editors when
  opening some documents with charts
* Fixed the ability to add some `TIF`/`TIFF` images to documents
* Fixed switching to an incorrect directory when selecting the Open file location
  option for an unsaved template
* Fixed an incorrect format when exporting a document to an image if the application
  is connected to DocSpace
* Fixed an incorrect format when repeated exporting a document from the portal
  if it was previously exported to an image
* Fixed a problem with parallel installation of `EXE`/`MSI` x86 packages on a 64-bit
  system (Windows)
* Fixed switching the application to the RTL interface
* Fixed installing the application with the English (United Kingdom) localization
  instead of English (United States) (macOS Intel Chip)
* Fixed repeated switching of the application theme to the system one (macOS)
* Fixed inconsistency in displaying mathematical equations to the Dark document
  mode (macOS)
* Fixed inconsistency between scroll bar styles in the Local templates section and
  the selected application theme
* Fixed inconsistency in the Document Info page styles on Windows XP

#### Document Editor

* Fixed an issue with calculating spacing before for a paragraph in block-level sdt
* Fixed an issue with cell selection after removing table rows
* Fixed calculating footnotes in the extreme case when there is no space even
  for 1 line
* Fixed an issue with the exact row height support when opening `DOCX` files
* Fixed the input window overlay on text in the Japanese (Microsoft IME) layout
* Fixed inconsistency in displaying numbered lists as compared to other editors
  when opening some `DOCX` documents
* Fixed appearance of a frame around the paragraph inserted from other sources
* Fixed the presence of artifacts when applying strikethrough or double
  strikethrough in a formula
* Fixed calculation of a math equation that was split into multiple lines
* Fixed text offset in autoshapes when opening some `DOCX` files
* Fixed table offset in header when opening some `DOCX` files
* Fixed text offset when opening some `DOCX` files
* Fixed saving some `SVG` images when exporting `DOCX` to `PDF`
* Fixed removing a section break after converting some `RTF` files to `DOCX`
* Fixed removing the Title and Tag properties when moving the Content Control
  that contains an image
* Fixed losing the Drop-down list that was added and modified in the Reviewing mode
* Fixed duplicating an input field when moving the Content Control using the mouse
* Fixed shifting focus from the Check Box to other elements after changing
  its state in some `DOCX` documents
* Fixed losing the OLE object contents when exporting some `DOCX` files to `HTML`

#### Spreadsheet Editor

* Fixed correct work of data validation specified with the `LEFT` formula
* Fixed consideration of the time zone when inserting a date using `Ctrl` + `;`
* Fixed stopping work of the editor when copying the cell, containing
  a link to an external file
* Fixed stopping work of the editor when changing the column width using a stylus
* Fixed long opening of some `XLSX` files which causes stopping work of the editor
* Fixed displaying autoshapes containing a macro mechanism
* Fixed losing changes when using special paste after building some `XLSX` files
* Fixed the value type error when recalculating the `IF` function in some
  `XLSX` files
* Fixed appearance of extra pages when previewing or printing some `XLSX` files
* Fixed appearance of borders after inserting cells copied from third-party applications
* Fixed appearance of an extra warning when editing a link to an external data source
* Fixed selecting fractional numbers using Goal Seek
* Fixed incorrect rounding when using the `ROUNDUP` function
* Fixed creating data array as a result of calculating the `VLOOKUP` function
  if the argument is not an array
* Fixed the rendering artifacts for some cases when scrolling the content of
  the sheet
* Fixed the dependence of the scroll step on the system scale
* Fixed displaying the drop-down list button
* Fixed the ability to apply the AutoFilter to an imported range
* Fixed the ability to use the space in a name of a protected range
* Fixed jumps when scrolling a sheet using selection with the `Shift` key and
  keyboard arrows
* Fixed the ability to choose cells after scrolling an area frozen with
  the Freeze Panes option if there are other cells below them
* Fixed the position of the comment window when expanding the panel with them
* Fixed overlapping the cell content by a comment in the Sheet Right-to-left mode
* Fixed layering of line number when scrolling a sheet in the Sheet
  Right-to-left mode
* Fixed duplicating the comment marker in the Sheet Right-to-left mode
* Fixed shifting of column guides when resizing them in the Sheet Right-to-left mode
* Fixed shifting of graphic objects when opening the toolbar in the Sheet
  Right-to-left mode
* Fixed shifting of the equation field when entering values in the Sheet
  Right-to-left mode
* Fixed highlighting of an added equation after after restarting the editor
* Fixed displaying the equation auxiliary menu when switching to the Sheet
  Right-to-left mode
* Fixed displaying the comment after activating the Sheet Right-to-left mode
* Fixed shifting of conditional formatting icons after enabling the Sheet
  Right-to-left mode
* Fixed missing graphic objects in some `XLSX` files on horizontal scrolling
  in the Sheet Right-to-left mode
* Fixed moving graphic objects after their rotation in the Sheet Right-to-left mode
* Fixed the displayed number of rows or columns exceeding specification limits
* Fixed inconsistency between the style of row and column headers and the Gray
  application theme

#### Presentation Editor

* Fixed missing a chart when opening some `PPTX` files
* Fixed inline check and numbering bullet check in presentation mode for math equations
* Fixed the watermark position when using protection in the DocSpace room
* Fixed missing graphic elements in the presenter mode when demonstrating some
  `PPTX` files
* Fixed changing the color scheme when opening some `PPTX` files
* Fixed the ability to apply columns for a group of SmartArt objects
* Fixed applying object formatting performed on a parent slide in
  the Slide Master mode

#### Forms

* Fixed the ability to delete the field with the Lock property if
  the Fixed size setting is enabled
* Fixed the absence of the ability to submit a completed form if it contains
  the Date & Time field with the Required property
* Fixed the work of composite input in fields with the Comb of characters property
* Fixed the ability to insert an image from storage or URL to the form field
* Fixed the absence of the ability to go to the Signature field using
  the toolbar buttons
* Fixed the ability to put the cursor to the same paragraph after creating
  an Inline Text Field
* Fixed moving a form field located in a table after activating the Fixed size
  field property
* Fixed the size of the Signature field track when switching from the Edit to
  View mode and vice versa
* Fixed stopping navigation through fields using the Previous/Next Field buttons
  in some forms

#### PDF Editor

* Reworked loading of fonts required for page rendering due to page
  hang out in collaborative mode
* Fixed stopping work of the editor when printing some `PDF` files
* Fixed stopping work of the editor when opening some `PDF` files
* Fixed stopping work of the editor after receiving an autoshape with text in co-editing
* Fixed the issue with different text shaping in collaboration mode
* Fixed different appearance of documents after transferring an image in co-editing
* Fixed the appearance of a deleted page after re-saving some `PDF` files
* Fixed shifting of a table when adding rows using Tab
* Fixed applying fill when creating some formulas
* Fixed displaying styles of some formulas in co-editing
* Fixed clearing all elements when erasing one of them with the Erase tool
* Fixed missing Text call out after the file formation
* Fixed losing a comment in co-editing if another user replied to it
* Fixed the distortion of the bulleted list after editing some `PDF` files
* Fixed missing notifications about inactivity when working with `PDF` files for
  a long time
* Fixed recording of checkbox state changes in `PDF` files
* Fixed losing an autoshape shadow when opening some `PDF` files
* Fixed changing the color of some images after inserting them and saving the
  `PDF` file
* Fixed changing the color of hieroglyphs when exporting some `PDF` files to images
* Fixed rotation of the modified page content after saving some `PDF` files
* Fixed missing added changes on preview or after printing some `PDF` files
  from the portal
* Fixed incorrect selector behavior when selecting lines in some `PDF` files
* Fixed the ability to enter text after pasting from the clipboard
* Fixed the appearance of a warning when pasting text via the Paste button on
  the toolbar
* Fixed missing contents on the preview of the added page when editing some
  `PDF` files

#### Convert

* Fixed the appearance of an error when opening the result of converting
  `PDF` to `DOCX` in third-party editors
* Fixed stopping work of the editor after opening the result of converting some
  `XLSX` to `XLSB`
* Fixed endless conversion of some `ODP` files to `PPTX`
* Fixed the Segmentation fault error during the conversion of some `ODP`
  files to `OTP`
* Fixed the Segmentation fault error during the conversion of some `DOCX` files to
  `HTML`/`DJVU`/`EPUB`
* Fixed crash when converting some `DOCX` files to `HTML`/`DJVU`/`EPUB` or
  image file formats
* Fixed an error when converting some `XLS` to `XLSX`
* Fixed the appearance of an error when opening the result of converting `XPS` to
  `DOCX` in third-party editors
* Fixed the appearance of an error when opening the result of converting `ODP`/`OTP`/`FODT`
  to `PPTX` in third-party editors
* Fixed the appearance of an error when opening the result of converting `ODT` to
  `DOCX` in third-party editors
* Fixed data loss in a table when converting `DOCX` to `RTF`
* Fixed layering of hieroglyphs in the `EMF` images when opening some `XLSX` files
* Fixed document structure corruption when opening some `EPUB` documents
* Fixed cropping the `EMF` images after converting some `DOCX` files to an image
* Fixed writing the formula calculation result when exporting `XLSX` to `CSV`
* Fixed considering the availability of the VBA macros when converting
  the `XLSB` files
* Fixed corruption of links to sheets containing non-Latin characters after
  exporting to the `ODS` format

## 8.2.0

### New features

#### All Editors

* Optimization of script loading to speed up opening all editors
* Own rendering of some SmartArt objects instead of recorded images in the file
* Updated dictionaries for Spellcheck and Hyphenation
* Support for new types of charts for opening: Histogram, Waterfall, and Funnel
* Improved display of Chart labels for Date axes, Values, and Categories
* Improved touch screen support in the full version of editors
* A gray theme has been added to the settings page
* Menu items in the File menu have been regrouped and icons have been added
* Theme and toolbar settings are moved to a separate Appearance category in
  the File menu - Advanced Settings
* Added the Tab style setting - view of tabs (Fill or Line) in
  the File menu - Advanced Settings
* Added the Use toolbar color as tabs background setting
* Ability to add custom fields to the file information
* Ability to view/add/edit custom fields without pressing the Apply button
* Reorganized fields with file information in the File menu - Info
* Improved work with the Lists of languages - the name of the language and region
  is now duplicated in English
* Implemented search in the Language list by name and in the target
  language, as well as in English
* The installation path selection page is disabled for security reasons;
  forced display of the page is possible using the `/enabledirpage` key (EXE package)
* Added support for local templates; currently restricted to creating
  documents from preinstalled templates only
* Added the application translation into English (Great Britain, en-GB)
* Updated icons of formats in the Create New and Recent files list
* A hint in English has been added to the Interface language list on
  the settings page

#### Document Editor

* Support for old CheckBox types
* Added the ability to Insert the contents of a third-party document
* New numbered list presets for Arabic interface
* Added the highlight of deleted text in the selected file version
* Ability to add and edit complex fields using field instructions

#### Spreadsheet Editor

* Improved support for smooth scroll
* Support for iterative calculations
* Added the ability to switch the direction of cell placement
* Added a button for setting the number format with separators to the toolbar
* Ability to display pages in real scale in the Print preview window
* The Pivot Table toolbar tab is only displayed when using the pivot table,
  and is otherwise hidden
* The Pivot Table settings right panel now unfolds when adding a new Pivot Table
* Added the ability to display trendlines (Equation on chart) to
  the Chart - Advanced Settings
* Added preview window when opening local `CSV` files

#### Presentation Editor

* Acceleration of opening files due to rendering the slide before loading of images
* Implemented a more visual way of selecting animation from the extended list
* Added the `Random` transition

#### Forms

* Added a Signature field with the ability to upload a prepared image

#### PDF Editor

* Added ability to save `PDF` files to the storage
* Added correct processing of cropped/combined shapes when opening files
* Added Gradient support
* Improved text recognition

### Fixes

#### Security

* Fixed the XSS injection in the Tooltip of the Animation Pane
* Fixed the vulnerabilities in the `FormattedDiskPagePAPX`,
  `SectionPropertiesMapping`, `FormattedDiskPageCHPX`, and `XORCrypt` functions leading
  to Heap Buffer Overflow when converting to the `DOC` format
* Fixed the vulnerabilities in the `ECMADecryptor`, and `DirTree` functions
  leading to Buffer over-read when converting to the `DOC` format
* Fixed the vulnerability in the Update Service leading to Directory
  Traversal Escalation of Privilege
* Fixed the vulnerabilities in the `findNextBorderPixel` and `pixFewColorsOctcubeQuantMixed`
  functions, leading to Heap-buffer overflow (CVE-2020-36278, CVE-2020-36281)

## 8.1.1

### New features

#### All Editors

* In the image upload filters, the `TIFF` format is added

### Fixes

#### All Editors

* Fixed saving the selected theme after removing the application with data
  cleaning and a new installation (Linux)
* Fixed crash of the application when launching, if reconnection via RDP occurs (Windows)
* Fixed mixed up icons of shortcuts for creating a Document/Spreadsheet in
  the Start menu (MSI package) [#1627](https://github.com/ONLYOFFICE/DesktopEditors/issues/1627)
* Added an item for creating a new `PDF` form to the application context menu (Linux)
* Fixed missing Image button in the SmartArt objects of the Picture type
* Fixed work of the `highlight-toolbar-tab-underline` parameter in the custom themes

#### Document Editor

* Active header and footer editing mode is no longer taken into consideration
  in the print preview [#1623](https://github.com/ONLYOFFICE/DesktopEditors/issues/1623)
* Fixed crash when applying an autocorrect command in an expression
* Fixed crash when copying or cutting an image pasted from the clipboard
* Fixed crash when pasting a copied list using Keep text only
* Fixed crash when moving autoshape
* Fixed crash in TextShaper when using composite input
* Fixed scroll to target when updating the position of a view port in
  collaborative editing [#2428](https://github.com/ONLYOFFICE/DocumentServer/issues/2428)
* Added the ability to prevent scrolling to the current position when
  performing any action
* Fixed review types for added paragraphs
* Fixed missing the current change in review when receiving spellcheck variants
* Fixed the recalculation of the document when changing the autohyphenation option
* Fixed spaces when converting table to text
* Fixed an issue with collecting related levels for the current numbering level
* Added table to track revisions check when adding new table or new row to the table
* Fixed an issue with simple text paste when track revisions is turned on
* Fixed freeze when moving through review changes
* Implemented display/accept/reject for review change of a table cell
* Fixed an issue with accepting/rejecting review changes inside
  a block-level sdt [#2669](https://github.com/ONLYOFFICE/DocumentServer/issues/2669)
* Fixed an issue with recalculating table
* Fixed clearing table cells before moving them
* Fixed cursor moving down when selected table cells
* Fixed display of images when opening some `DOCX` files
* Fixed an issue with reading numbering properties in styles and refactor
  using `AscWord.NumPr` class
* Fixed clearing the text properties for an inline-level sdt and merge
  method for `TextPr`
* Fixed incorrect display of autoshape shadow transparency when the `No Fill`
  option is activated
* Fixed display of non-printing characters when opening some `DOCX` files in
  the viewing mode

#### Spreadsheet Editor

* Fixed crash in TextShaper after replacing the entered text in the autoshape
* Fixed crash for some usages of the `IMPORTRANGE` formula
* Fixed incorrect formula conversion when using a link to a file
* Fixed crash when opening some `XLSX` files [#2782](https://github.com/ONLYOFFICE/DocumentServer/issues/2782)
* Fixed inserting an empty column after moving a column with data [#2499](https://github.com/ONLYOFFICE/DocumentServer/issues/2499)
* Fixed changing line height after applying Merge and Wrap Text, if the text
  extends the cell boundaries
* Colors of row and column headers when hovering the cursor now correspond
  to color schemes
* Fixed formula calculation if there is an intersection with a formatted table [#1558](https://github.com/ONLYOFFICE/DesktopEditors/issues/1558)
* Fixed formula calculation if they contain named ranges
* Fixed creating named ranges in languages with ligatures
* Fixed applying a number format when calculating a formula in the total
  row of a formatted table
* Fixed display of shadow of objects after scrolling a sheet
* Fixed updating of the `IMPORTRANGE` formula arguments after updating external links

#### Presentation Editor

* Fixed crash after applying Reset slide in certain `PPTX` files
* Fixed crash after copying a slide in the Normal mode and pasting in
  the Slide Master mode
* Fixed crash when opening the Notes and handouts insertion menu
* Fixed the issue with weak characters in RTL at the end of the line
* Fixed presence of the Insert image from file / Insert image from URL buttons
  for SmartArt objects of the Picture type in the Master Slide mode
* Fixed the issue: formatting on layouts in the Add Slides button is displayed after
  the changes are made again in the Slide Master mode
* Fixed display of the name when inserting a Table placeholder
* Fixed applying a theme to the added slide
* Fixed display of a comment when switching to the Slide Master mode
* Fixed the size of placeholders on layouts after removing placeholders on the parent
  layout and applying Duplicate Slide Master
* Fixed work of the Play/Pause buttons in the viewing window in the Slideshow mode
* Fixed layering of objects when they are grouped when opening
  some `PPTX` files [#2573](https://github.com/ONLYOFFICE/DocumentServer/issues/2573)
* Fixed work of internal hyperlinks when using the Next Slide parameters
* Fixed work of `Enter` / `Space` / `Arrow Right` / `Arrow Left` keys in
  the Slideshow mode
* Fixed reset of object selection after copying using Drag-and-drop
* Fixed display of shadow in the Slideshow mode
* Fixed duplicating Slide Master when moving it using Drag-and-drop in
  the `Slides` tab
* Fixed display of text formatting applied on the parent layout
* Fixed incorrect date indication in Header and Footer
* Fixed applying Background theme after creating a custom theme via `Slide`
  settings and using the Apply to All Slides option
* Fixed display of custom theme layout when opening some `PPTX` files
* Fixed marker overlapping when moving it along the Animation Pane timeline

#### Forms

* Fixed creating a new form via the File menu on macOS
* Fixed crash when filling in fields in some forms [#2768](https://github.com/ONLYOFFICE/DocumentServer/issues/2768)
* Prevent a checkbox from toggling when moving it
* Fixed the conversion of a fixed form to an inline
* Improved finding anchor position around inline forms
* Fixed the ability to change data in fields when submitting the form

#### PDF Editor

* Fixed printing `PDF` files from a cloud provider
* Changed the default tool from Hand to Selection
* Added the ability to disable the mini panel when selecting text in Advanced Settings
* Fixed crash when opening some `PDF` files
* Fixed crash after several deletions of pages and insertion of a graphic element
* Fixed crash when removing table rows when editing some `PDF` files
* Fixed stopping work of the editor after exiting without saving changes
* Fixed crash when moving around a table using `Tab`
* Fixed crash when opening Page Thumbnails in some `PDF` files
* Fixed highlighting of hyperlinks when opening `PDF` files
* Fixed work of composite input in comments
* Fixed filling with color instead of image when opening some `PDF` files
* Fixed work of Undo after changing the text orientation in the `PDF` file
* Fixed transparency of a Watermark when opening some `PDF` files
* Fixed offset of the Select toolbar when selecting words in some `PDF` files
* Fixed text content loss when opening some `PDF` files
* Fixed the Text box content loss after exporting the `PDF` file
* Fixed saving objects located after a link

#### Convert

* Fixed crash when converting some `XLS` files to `XLSB`
* Fixed crash when exporting `DOCX` documents, containing autoshapes, to `HTML`
* Fixed crash when opening some `DOC` and `DOCX` files
* Fixed crash when converting some `XLSM` files to `XLSB`
* Fixed stopping work of the editor when opening some `XLSX` files,
  containing EMF images
* Fixed compliance with the `PDF/A` format after exporting a `DOCX` document
* Fixed an error when opening in third-party editors the `XLSX` file obtained
  when converting `XLSB`
* Fixed text loss in `SVG` images after exporting the `DOCX` document
  to a different format
* Fixed display of presentation theme after exporting some `PPTX` to `PDF/A`
* Fixed the "Decimal" and "Use 1000 separator" options loss
  when exporting `XLSX` to `ODS` [#821](https://github.com/ONLYOFFICE/DesktopEditors/issues/821)

## 8.1.0

### New Features

* Switching to the creating forms in the `PDF` format
* Added the ability to disable the `Connect to cloud` page via
  the `--lock-portals` key
* Added a window to restart the application if the settings marked with
  the asterisk are applied (Windows, Linux)
* Added the `Use graphics acceleration` option to the application settings
* Added the progress of unpacking downloaded update to the `About` page (Windows)
* Added the ability to open a file by specifying its name in the terminal (Linux)
* Updated images for the error pages
* Added the translation into Serbian (sr-Latn-RS, Serbian (Latin, Serbia and Montenegro))
* Added a button to select a local file in the hyperlink insertion dialog window
* Changes in program interface: manageable functional buttons, Replace button is
  now on the Home tab, Copy style, Clear style, Select all
* Autoshape shadowing settings
* Updated the set of color themes available in editors
* Added internal help in Portuguese (pt-BR)
* Added Arabic to all regional settings
* Added a title and a button to close the panel to the `Chat` panel

#### Document Editor

* New button on the top toolbar for changing document editing mode: `Editing`,
  `Reviewing`, `Viewing`
* Added tooltips for new or updated functionality (displayed when loading the
  editor or when switching to the corresponding tab)
* Implemented the ability to set the format for page numbering
* Added support for the page color
* Updated built-in paragraph styles
* New items in the indents menu for opening the right panel and managing paragraph
  indents, the ability to manage paragraph indents via the top toolbar
* Color theme button is now on the Layout tab
* Mail merge button is now on the Collaboration tab
* Line spacing options updated
* Improved work of the algorithm for displaying numbers and punctuation in
  Arabic text for the Neutral and Weak classes
* Improved fitting for paragraphs with main `RTL` direction

#### Spreadsheet Editor

* New languages added: ligature support
* Selected cells are highlighted on their respective row/column numbers
* New functions: `GETPIVOTDATA`, `IMPORTRANGE`
* New function category: Custom based on jsdoc
* Version history update: edited cells are highlighted
* Users get custom protected range cells viewing rights
* Implemented the ability to copy/move sheets between opened books
* Changed the appearance of the sheet list in the embedded viewer in accordance
  with the styles of the main spreadsheet editor

#### Presentation Editor

* New slide settings on the right panel: show background graphics, reset background
  to the theme background, apply settings to all slides
* Added `Animation` pane
* Added a mode for editing master slides and templates
* Updated the player interface for playing audio/video files (Windows and Linux)

#### Forms

* When adding a fixed form, now it is inserted without wrapping in front of the text
* The color of the  Picture placeholder corresponds to the color of the role
  for this form
* The thickness of the frame for required fields is now 2 px with any zoom
* Added a button to switch to the editing mode (similar to the button in
  the editor header) for forms opened in the View or Fill forms mode

#### PDF Editor

* Added buttons for switching editing/viewing (annotations) modes to
  the toolbar and the editor header
* Added tooltips for new or updated functionality (displayed when loading
  the editor or when switching to the corresponding tab)
* In the Edit mode, it's possible to add various objects (using the `Home`
  and `Insert` tabs) and configure them using the right panel and context menu
* Added the ability to add, delete or rotate pages using the context
  menu and the toolbar
* Added a mini toolbar for adding annotations when selecting text

### Fixes

#### Security

* Fixed vulnerabilities in the PtgName::assemble, PtgNameX::assemble,
  PtgParen::assemble, PtgRef3d::assemble, PtgList::assemble and
  PtgArea3d::assemble methods which cause crash when converting `XLS` to `XLSX`
* Fixed the vulnerability in the `CDataStream::ReadEmrTextBase` method which causes
  crash when converting `ODP` to `PDF`
* Fixed the vulnerability in the `GlobalsSubstream::UpdateDefineNames` method which
  causes crash when converting `XLS` to `XLSX`
* Fixed the vulnerability in the `WorkBookStream::UpdateXti`, `WorkBookStream::UpdateXti`,
  methods which causes crash when converting `XLS` to `XLSX`
* Fixed Heap Buffer Overflow when converting `EPUB` to `PDF`
* Fixed the vulnerability in the `CPPTUserInfo::LoadExternal` method which allows
  writing a file to a folder with restricted access when converting `PPT` to `PPTX`
* Fixed vulnerabilities which allow reading data from a third-party file when
  converting `OOXML` to `ODF` and vice versa
* Fixed Heap Buffer Overflow in the `CSvmFile::Read_META_BMP` method when
  converting `ODP` to `PPTX`

## 8.0.1

### Fixes

* Significantly increased the speed of unpacking the update package through
  the built-in update service for future releases (Windows)
* Fixed the table alignment on a page after printing
* Renamed the form template creation button to PDF Form
* Changed the font family for Arabic language on the application main
  page
* Fixed the Open Document dialog window language if the Arabic interface is
  set in the system
* Fixed changing the text direction in the User Name field when changing
  the keyboard layout if the RTL UI is enabled
* The RTL UI mode is hidden on Windows XP
* Fixed applying a password when opening local files on Windows XP
* Fixed the translation in the drop-down lists of options for the 'Disabled'
  state in the application settings
* Fixed the description of the `DOCX` format in the Save As dialog

#### Document Editor

* Fix crash when clicking comment inside a math equation
* Fix crash when using the Insert caption feature with the Include
  chapter number option
* Fix crash when inserting a copied image using Ctrl
* Fix a problem with rendering collaboration highlight
* Fix an issue with highlighting searching results in some `DOCX` files
* Fix display of highlighting a comment added to RTL text
* Fix text label for Table of Contents in the RTL UI
* Fix an issue with shaping text with different direction (RTL and LTR)
* Improve the calculation of the cursor position in case when it is
  between text with different directions (RTL and LTR)
* Fix an issue with correction of a text selection when passing
  through a complex field
* Fix an issue with calculating the current cursor position while
  selecting elements in table
* Fix selection for the hidden part of complex fields
* Fix an issue with selection draw and cursor positioning in complex
  fields
* Fix position of diacritics when typing in Arabic
* Hide non-printing characters in header/footer label
* Decrease the height of the header/footer label

#### Spreadsheet Editor

* Fix stopping work of the editor when exporting some `XLSX` files to
  `PNG`/`JPEG`
* Fix display of the DBNum1 number format when opening some XLSX files
* Fix display of the Currency format when exporting some `XLSX` to `ODS` and
  reopening
* Fix appearing artifacts when inserting an image via Drag-n-Drop and
  moving it
* Fix saving the current sheet only when exporting a work book to `PNG`/`JPEG`
* Fix display of the #REF! error when adding the VLOOKUP formula with an argument
  which is a reference to another file

#### Presentation Editor

* Fix stopping work of the editor when opening some `PPTX` files
* Fixed the app crash when pressing the `Command` + `,` keyboard shortcut in
  Presenter View (macOS)
* Fixed closing the application when opening a local presentation in its
  own window mode and launching the Presenter View

#### Forms

* Fix crash when expanding the Date field in the forms edited in third-party
  editors
* Fix closing a drop-down list in some PDF forms with the Turn on screen reader
  support option enabled
* Change the default date-time format for a DatePicker form

#### PDF Editor

* Fix crash when opening some `DjVu` files
* Fix annotations offset when exporting to PDF
* Fix the color of the worksheet borders with the light interface theme

#### Security

* Fixed the vulnerability in 'PIVOTVIEW::loadContent' method when converting `XLS`
  to `XLSX`
* Fixed the vulnerability in 'GlobalsSubstream::UpdateXti()' method when converting
  `XLS` to `XLSX`
* Fixed the vulnerability in 'ChartSheetSubstream::recalc' method when converting
  `XLS` to `XLSX`
* Fixed the vulnerability which leads to buffer overflow when converting `ODP` to
  `PPTX`
* Fixed the vulnerability which allows adding a third party file to a document while
  converting `HTML` to `DOCX`
* Fixed the ability to execute the PowerShell commands when converting `DOC` to `PDF`

#### Convert

* Fixed files corruption after converting some `ODT` files to `DOCX`
* Fixed adding the excess 'Default Extension="docxf" parameter when converting
  `DOCXF` to `DOCX`
* Fixed display of a date as a number when opening some `XLS` files
* Fixed losing contents of the cell with an added comment after exporting to
  `ODS`
* Fixed files corruption after converting some `DOC` files to `DOCX`
* Fixed document appearance in another editors after export some `DOCX`
  files
* Fixed data loss when converting some `DOC` to `DOCX`
* Fixed stopping work of some `XLS` to `CSV` conversion
* Fixed files corruption after converting some `ODS` files to `XLSX`
* Fixed data loss on opening some `TXT` files
* Fixed files corruption after converting some `XLSB` files to `XLSX`

## 8.0.0

### New Features

#### All Editors

* Add the ability to encrypt `PDF` files
* Add the Moodle provider
* Add the ability to upload local themes to the Desktop Editors (Windows, Linux)
* Add shortcuts to the Start menu for creating new files to EXE package (Windows)
* Add a list of recent files and the ability to pin them via the context menu of
  the application in Jump List (Windows)
* All logos in the application and installation packages have been updated
* VC Redist 2013 is excluded from the default installation package and
  is not required for the application to work (Windows)
* Add the ability to Select/Deselect all formats on the MSI installer
  file associations page
* Add OS compatibility manifests for executable files (Windows)
* Improved the updates section and the update service for future versions of
  the application (Windows)
* Adapt styles of window control buttons in accordance with OS design (Linux)
* Change the widget for displaying downloads from the portal and the download
  indicator (Windows, Linux)
* Move adding a comment to the entire document from the bottom of the comments
  panel to the settings button
* Add a button for adding a comment to text to the header of
  the comments panel (similar to the button in the toolbar)
* Add the interface translation into Arabic (ar-SA, Arabic - Saudi Arabia)
* All buttons that do not fit in height should be placed into
  More button: category buttons, as well
  as plugins that were opened in the left panel
* Add the setting to enable support for Screen readers
* Add RTL support (beta) to the editors UI

#### Document Editor

* Add partially support for bidirectional text

#### Spreadsheet Editor

* Add the new Goal Seek functionality
* Add the new Series tool for creating number sequences
* Implement a wizard for inserting charts: display a list of recommended charts and
  previews for all types of charts based on the selected data
* Expand cell filling settings
* Add the Expand/Collapse menu item to the toolbar and the context menu
  of Pivot tables
* Add the ability to center a sheet horizontally and vertically when printing
* Add the ability to get a link to the selected range in the viewing mode

#### Presentation Editor

* Add the ability to set the final color for animation effects that change color
* Make animation effect icons inactive if the effect cannot be applied to an object
* Add partially support for bidirectional text

#### Forms

* Switching from the `OFORM` to `PDF` format containing forms in accordance
  with the OOXML format
* Dialog for converting old `OFORM` files to `PDF`
* For the radio button field, add the setting for the name of the selected
  element (Radio button choice)
* Add a chain of tips when working with DOCXF files

### Fixes

#### Security

* Fix vulnerability which allows adding a third-party audio file to a document
  when converting PPT to PPTX (65056)
* Fix vulnerability which leads to buffer overflow when converting ODP to PDF (65915)
* Fix vulnerability which leads to buffer overflow when converting PPT to PPTX (66085)
* Fix vulnerability which allows performing manipulations on the client machine when
  converting HTML to DOCX (63779)
* Fix XSS in the Shape name field when applying an Animation (65186)
* Fix XSS in the Math Autocorrect field when saving the field value (65187)
* Fix XSS in the Spreadsheet Editor cell when opening the Number format list (65881)
* Fix XSS in the Sheet name value when applying Search (65909)
* Fix  XSS in the Custom Number Format when opening a list (65941)
* Fix XSS in the Dropdown List field when opening it (65082)

## 7.5.1

### Fixes

#### All Editors

* Fixed print options (range) tuning for documents and presentations
* Fixed some security issues
* Fixed opening files with size more than 100 MB
* Fixed some issues with composite input
* Fixed issues preventing the application from working on MacOS version < 12.0 ([#1399](https://github.com/ONLYOFFICE/DesktopEditors/issues/1399))
* Fixed working with blocked text fields in dialog boxes
* Improved quality of the SVG images added to the documents ([#102](https://github.com/ONLYOFFICE/DesktopEditors/issues/102))
* Fixed the main window hanging when closing the application after
  working with several document tabs
* Fixed signing of documents/spreadsheets using SVG images

#### Document Editor

* Fixed incorrect painting inserted Text Art
* Fixed an error when combining/comparing documents

#### Spreadsheet Editor

* Fixed issue when cell border became hidden due to hide row with part of
  merged cell
* Fixed equation transformation for Linear/Professional mode switching from
  context menu
* Fixed print issue for Header/Footer
* Fixed crashing of the editor after creating file from password protected XLTX

#### Presentation Editor

* Fixed error on click Header & Footer in Insert tools panel
* Fixed crashing in the Reporter mode on changing slide from end demonstration
* Fixed saving presentations with media files for compatibility with other editors

#### PDF Editor

* Fixed saving document through "Save copy"
* Fixed incorrect processing editor's config (editorType)
* Fixed issue for plugin "Send" when there is no email client installed
* Fixed opening help for PDF editor and files opened for viewing (XPS, DjVu)

## 7.5.0

### New Features

#### All Editors

* Added support for interface scales >200% (225, 250, 275, 300, 350, 400, 450, 500)
* Files from the "Recent files" list of the application have been added to
  the "File" > “Open Recent” section, according to the editor formats
* Updated VLC libraries (for Windows)
* Updated the “About” page and the “Check for updates” block (for Windows)
* Added a list of changes to deb/rpm packages (for Linux)
* Added a warning when the application is closing if several files are opened
* The "Last used" option has been added to the editors settings for
  "Default Zoom Value"
* Add a menu for quick access to the most popular symbols to the button
  for inserting symbols
* Support for SVG images
* Add a setting to hide the toolbar for equation
* Add hints for images in SmartArt objects
* Add the ability to open files protected with a password in the embedded viewer
* Add the ability to edit points of the autoshape border to the right panel
* Only Ctrl + ./Ctrl + , keyboard shortcuts are now used for
  superscript/subscript characters
* Change keyboard shortcuts for moving through the text on macOS:
  * Cmd + Arrow Left – moving to the beginning of the line
  * Cmd + Arrow Right – moving to the end of the line
  * Option + Arrow Left – moving one word to the left
  * Option + Arrow Right  – moving one word to the right
  * Removing one word to the left: Ctrl + Backspace replaced with Option + Delete
  * Removing one word to the right: Ctrl + Fn + Delete replaced with
    Option + Fn + Delete.

#### Document Editor

* Automatic hyphenation
* Change the selection logic, add the “Smart paragraph selection” option
  in Advanced Setting
* Add the “Remove content control when contents are edited” option to content
  control settings
* Change behavior of the Accept/Reject review buttons in the toolbar
* Disable the Zoom out action for the Ctrl + Numpad keyboard shortcut due to
  the conflict with inserting an em dash
* Change the keyboard shortcut for strikeout text formatting on macOS:
  Ctrl + 5 replaced with Cmd + Shift + X
* Change the keyboard shortcut for inserting ellipsis on macOS:
  Ctrl + Option + . replaced with Option + ;

#### Spreadsheet Editor

* The ability to display only formulas in cells
* Trace precedents / dependents
* New function: SORTBY
* Added presets for "Margins" and the ability to show/hide "Print titles" in
  the "File" > "Print" menu
* Add the ability to set a number format in the field settings for pivot tables
* The Show details feature for working with a Pivot Table
* Improvement of the ability to open data on a new sheet by double-clicking
  a value in a Pivot Table
* Autocompletion for days of the week and months when stretching a cell value
* Drag-and-drop for columns and rows
* Add filters by date and the ability to display data with the "Date" format
  in the form of a tree in the Autofilter window
* Inserting images into headers/footers
* External data update for the currently edited source file
* The last used Delimiter and Encoding setting for CSV files is now stored
  locally on the client side
* The ability to insert page breaks from the Layout toolbar
* Add the ability to open the source for external links
* Add the Alt + Down keyboard shortcut for opening the Autofilter window
  when the header of a column with a filter is selected

#### Presentation Editor

* Add the "Morph" transition
* Assigning names to objects in advanced settings
* The "Number slides from" option has been added to the slide size settings
* Notes and Handouts in headers/footers settings
* Slide placeholders have alternative descriptions
* SmartArt insertion is available via a slide placeholder
* Add the ability to navigate to the specific slide with the consecutive
  pressing of the *slide number* + Enter when previewing a presentation
* Change the keyboard shortcut for starting a presentation on macOS:
  Cmd + Shift + Return is used

#### PDF Editor

* Support for the PDF form, annotations, comments and drawings

#### Forms

* Bring settings on the right toolbar to unified appearance

### Fixes

#### Security

* Fix vulnerability which allows reading data from memory when converting
  DOC to DOCX
* Fix vulnerability which allows adding a third party image to a document when
  converting HTML to DOCX

#### Plugins

* Restore working capacity from China

## 7.4.1

### New Features

#### All Editors

* Fixed vulnerabilities with checking the integrity of a digital signature,
 after manipulations with the document structure
* Editors now display the correct error when trying to write a file, opened
 in another application
* Fixed an error that occurs when opening multiple files using drag'n'drop
* Fixed an issue when opening templates which contain slashes in their names
* Fixed incorrect name for the next tab after closing and saving the document
 in front of it
* The latest changes in the file are now included when sending via the Send plugin,
 if they have not been saved
* Fixed the processing of the link, that ends with `default.aspx`, when connecting
 to the Workspace portal
* The Open file location button for a document opened from the portal in a separate
 window without the main one now works
* Fixed working with tabs when documents are opened from the portal and the user
 logs out on the Connect to cloud page
* Fixed online help for macOS systems
* Updated sets of application icons for Jump List (Tasks) on Windows systems
* All components in Windows installation packages are now digitally signed
* A large number of fixes and improvements to the MSI installation package

#### Document Editor

* Fixed displaying of non-printing characters after calling the print preview window

#### Spreadsheet Editor

* Fixed displaying of a document when printing to PDF if the width/height
 of columns/rows were changed
* Fixed the scroll bar display in the filtering window for legacy systems

#### Presentation Editor

* Fixed an error during slideshow auto-run and with system scale >200%
 when opening multiple files using drag'n'drop

## 7.4.0

### New Features

#### All Editors

* The Templates section with online form search has been added to the main page
* The application now uses system (native) dialog boxes
* Added application update service for Windows systems
* The pages in the File menu have been redesigned and correspond to a single style
* The print preview window has added Print to PDF button and the ability to specify:
 page range, number of copies, printing on both sides
* The Draw tab has been added to the Editors toolbar
* The Eyedropper tool and hints for color names have been added to the color
  selection menu
* Added the ability to copy style between graphic objects
* The Save as picture item has been added to the context menu of graphic objects
* Added opacity settings for fill and borders of graphic objects: autoshapes,
  charts, images and others
* Added support for Radar charts
* Added formats for opening in Editors: MHTML, SXC, ET, ETT, SXI, DPS, DPT,
  SXW, STW, WPS, WPT
* Column headers have been added in some dialog windows with lists
* The number of results found has been added to the search box
* Added regional settings for the Danish language (Dansk (Danmark))
* Added help in Turkish
* Added a new Plugin Manager

#### Document Editor

* Added the ability to merge documents
* The ability to change the width and spacing of each column independently
  has been added to the column settings window
* Expanded the number of settings for numbered and multi-level lists
* Added the Recently used section in the lists menu for the current document
* Added the ability to apply the list from the List Options window
* Added the ability to export a document as PNG/JPG images
* Added a list of exceptions for autocorrect capital letters

#### Spreadsheet Editor

* Add the support for new functions: SEQUENCE, XMATCH, EXPAND, FILTER,
  ARRAYTOTEXT, SORT
* Added translation of formulas into Armenian
* The ability to change the case of text has been added to the Home toolbar
* Page Break Preview mode has been added to the View toolbar
* In the Print range settings, the Current sheet option has been replaced with
  Active sheets
* The ability to set First page number has been added to the print settings
* Long/short date formats have been added to the drop-down list of cell formats
* Items for working with pivot tables have been added to the context menu
* The Protect sheet settings window now includes Allow edit ranges
* Added the ability to export a spreadsheet as PNG/JPG images

#### Presentation Editor

* Added a list of exceptions for autocorrect capital letters

#### Forms

* The position of the forms with the Fixed size field option is now calculated
  from the beginning of the page
* Fixed rendering of the frame at the active field for forms with the Fixed
  size field option
* Ability to add a new form without leaving the current one
* Filling in the view mode (the View Form button remains)
* In Edit mode, the current shape has the same fill as all the others
* It is forbidden to fill out forms inside a document sheet in Edit mode
* Since it is forbidden to fill out forms in Edit mode, the default value
  setting (Default value) has been added to the right panel
* Optimized the work of subforms inside complex forms

### Fixes

* `Same as system` item has been removed from the application settings
  (Interface theme) for Linux systems
* All editors received countless fixes

## 7.3.3

### Fixes

#### All Editors

* Fix the application vulnerability CVE-2022-48422 which allows to load a library
  from the current directory (for Linux) (Bug 60244)
* Fix the application vulnerability CVE-2023-30186 with memory exhaustion
  during work with `NativeEngine` function (Bug 60433)
* Fix display of the editor window minimized in the Maximize mode (Bug 58402)
* Fix moving the file placed in a separate window (for Linux) (Bug 45037)
* Fix display of the application window when connecting the second monitor (Bug 60899)
* Fix the year in the About section (for MacOS) (Bug 61421)
* Fix a new file name when creating in Polish interface language (Bug 60764)
* Fix display of the Help contents (Bug 61144)
* Fix an encrypted file name when saving, if it is specified in Cyrillic (Bug 61243)
* Fix display of the More button when the application scaling is more than
100% (Bug 61219)
* Fix crash of the editor when opening a document in a separate window (Bug 61262)
* Fix display of the Print to PDF button in the Print preview window for German
interface language (Bug 61510)

#### Spreadsheet Editor

* Fix hangup of the editor when printing the XLSX file (Bug 61019)
* Fix display of the Edit formatting rule window when the interface
scaling is 125% and 175% (Bug 60952)
* Fix printing a spreadsheet if the page size settings are specified (Bug 61214)
* Fix changing the date format when saving the workbook to PDF (Bug 56499)
* Fix saving data to the PDF format from the XLSX file (Bug 60334)

#### Presentation Editor

* Fix crash when uploading a presentation to the Private Room (Bug 51001)
* Fix display of the presentation themes in the Private Room with the
Classic, Green leaf, Lines, Safaryi templates (Bug 61430)

#### Forms

* Fix crash when opening the OFORM files (Bug 61142)

#### PDF

* Fix endless loading of the PDF file (Bug 60923)
* Fix printing an empty sheet in the PDF files (Bug 61192)

## 7.3.0

### New Features

#### All Editors

* Unified appearance for tooltips (Windows, Linux)
* Window shadow effect (Windows only)
* Jump List (Tasks) for the application shortcut in the start menu and
taskbar (Windows 7 and later)
* Abandoning the third-party update window and reworking the Check for updates
automatically option (Windows 7 and later)
* Dialog windows (file manager and print) are replaced with the system
ones (Linux only)
* Support for xdg-desktop-portal in the file dialog window (Linux only)
* Use the file name when printing to PDF by default (Linux only)
* Equation quick access panel
* 3D Rotation settings for 3D charts
* Display of chart error bars (for opening only)
* Inserting Smart Art objects
* Uzbek dictionaries for spell checking: `Uzbek (Cyrillic)` and `Uzbek (Latin)`
* Presets for inserting horizontal and vertical text boxes
* Ability to hide left and right panel on the `View` tab of the top toolbar
* Width of the styles / themes panel now fits the whole number of items
* Grouping for table templates
* Cell styles in the OLE object editor
* Ability to resize dialog windows for editing charts, OLE objects, and mail
merge recipients
* Unified appearance for dialog windows, context menus, toolbar, etc.
* Optimizing display of comments
* Changed metafiles conversion to SVG
* Reading and writing PDF are combined in a single library to optimize work
* Quick print function (Windows, Linux)
* Changed default logic of work with local documents locked for editing
(Windows, Linux)

#### Document Editor

* Support for entering equations in two modes (Unicode and LaTeX)
* Ability to protect a document by setting a restriction on editing
* Button for accessing to statistics in the status bar
* Support of relative links to local files

#### Spreadsheet Editor

* Watch Window
* Ability to select multiple items using Ctrl/Shift in the Watch Window
* Support for new functions: `TEXTBEFORE`, `TEXTAFTER`, `TEXTSPLIT`, `VSTACK`,
`HSTACK`, `TOROW`, `TOCOL`, `WRAPROWS`,  `WRAPCOLS`, `TAKE`, `DROP`, `CHOOSEROWS`,
`CHOOSECOLS`
* Support for updating links to external files and the ability to create these links
* Ability to add a link between files within the portal using Paste Special
* Ability to insert data from the XML file (XML Spreadsheet 2003 is supported)
* Changed preview size for cell styles
* Support of relative links to local files

#### Presentation Editor

* Support for entering equations in two modes (Unicode and LaTeX)
* Guides and Gridlines settings in the `View` tab and the context menu
* Tooltips when moving guides and the ability to remove the selected guide
* Paste Special parameters for a slide
* Ability to save a shape (graphic object) as a picture in the context menu

#### Forms

* New fields: `Date and time`, `Zip Code`, `Credit Card`
* Managing roles: adding, editing, removing roles, assigning them to fields
* Ability to preview the `DOCXF` file from the point of view of each created role

### Fixes

* Fix the XSS vulnerability when creating a new style
* Changed the Signature Setup window
* New captions to fields
* Show sign date option is enabled by default when adding a signature
* Tip in the Instructions for signer field
* Fixed application path when installing MSI in non-English locales (DesktopEditors#1157)
* All editors received countless fixes

## 7.2.1

### New Features

* Add support for the `REGISTER_NONE` and `REGISTER_<file type>` parameters to
set associations during silent installation of msi package (Windows only).

### Fixes

#### All Editors

* Major improvements in the fonts render engine. Removal of `Alternative input` settings
* Fix opening the "Open Files" window (Bug #33107)
* Fix image loss when printing a file on Linux (Bug #59266)
* Fix image cropping when printing a file (Bug #59263)
* Fix the application crash when printing the PPTX file (Bug # 59354)
* Fix the application crash when printing the PDF file which contains a raster
image (Bug #59161)
* Fix printing images in the OXPS files (Bug #59226)
* Fix printing 3D charts (Bug #59187)
* Fix printing the current page of the XLSX file (Bug #59208)
* Fix proportions when printing on a sheet which does not coincide with
the original format (Bug #59223)
* Fix simultaneous opening of several application windows by shortcut (Bug # 36633)
* Fix updating data about the VCRedist 2013 package installation (Bug #58771)
* Fix switching to the correct tab when opening a file with Drag'n'Drop (Bug #59024)
* Fix image rotation when printing a file (Bug #59258)
* Fix closing a document which are opened in separate window using
the context menu (Bug #58347)
* Fix choosing a certificate when signing a document on Linux (Bug #59116)
* Bring the Contrast Dark theme name to a single view in the application
settings (Bug #58753)
* Fix the problem with the window focus when clicking on the document area (Bug #56672)
* Change the name of the system theme in the application settings from
System default to Same as system (Bug #59010)

#### Document Editor

* Fix numbering in Portuguese or Basque language (Bug #59091)
* Fix the problem with review types when splitting a paragraph (Bug #58512)
* Fix the problem with the special paste button (Bug #59149)
* Fix crash on opening docx (Bug #59212)
* Fix the problem with reading the `rPrChange` property and review such
files (Bug #59205)
* Fix scrolling in the co-edit view mode (Bug #57928)
* Fix the problem with performing the global undo (Bug #59270)
* Fix the problem with setting the bold property for text in the complex
script (Bug #59289)
* Fix the special paste position (Bug #59139)
* Fix saving a document in the Final / Original modes (Bug #59347)
* Fix the problem with updating content of a Ref field (Bug #58606, Bug #59278)

#### Spreadsheet Editor

* Fix hangup on opening the xlsx file (Bug #58112)
* Fix special paste via hotkeys (Bug #59148)

#### Presentation Editor

* Fix animations problems (Bug #59301)
* Fix opening the pptx file (Bug #59308)

#### PDF Viewer

* Fix search highlight (Bug #59069)
* Fix tooltip language for preview (Bug #59087)

#### Forms

* Implement saving text field formats to PDF (Bug #58901)
* Add a default form key when creating new forms
* Fix image track display (Bug #59120)
* Fix the problem with highlight of a fixed form (Bug #59105)
* Fix duplicating fixed forms when saving to PDF
* Fix saving a form field format (Bug #58901)
* Fix the problem with converting a complex field to a fixed form (Bug #59262)
* Fix field detection in selection (Bug #59278)
* Fix the problem with entering text to a form (Bug #59290)
* Fix the context menu for some forms files (Bug #59278)
* Fix the problem with working with complex fields and simple fields (Bug #59345)
* Fix keys list problems (Bug #59377)
* Fix the problem with canceling filling in the form on form blur (Bug #59373)
* Fix the problem with a key of complex forms (Bug #59374)
* Fix the complex form filling problem for forms with the same key (Bug #59375)
* Fix the problem with printing form borders filled with placeholders (Bug #59378)

## 7.2.0

### New Features

#### All Editors

* Show warning on macros execution if connection to another host. Fix CVE-2021-43446
* Vector printing if the page does not contain gradient fills
* Removed the restriction on the minimum window size
* Top toolbar optimizations for smaller screens
* Added the ability to choose "Contrast Dark" or "System default" interface
  theme
* Redone of icons in header line
* Redone of settings page in the editors
* New interface languages - "Portuguese (Portugal)" and "Armenian"
* Improved color selection component
* The ability to disable the alternative menu in the editors
* Completely redesigned search inside the document
* New hotkeys for "Special Paste"
* Added "Cut" and "Select All" buttons to the toolbar next to Copy/Paste
* Major improvements in Font engine (For languages like Bengali or Sinhala)
  (only in Document Editor and Presentation Editor)
* Ligatures support
* Ability to insert tables as OLE object
* Support for images as a bulleted list and the ability to work with them
* Major improvements in "EMF" and "WMF" files rendering

#### Document Editor

* Ability to remove Header/Footer from toolbar
* Ability to insert current heading in TOC
* New warning if there is no TOC in document
* Navigation panel renamed to "Headings"
* Major improvements in "pdf", "djvu", "xps" convert to "docx"
* Correct display greek letters as numbered list items

#### Spreadsheet Editor

* Ability to "Switch rows and columns" for Chart
* New "Italiano (Svizzera)" language for regional settings
* Row number highlight for filter
* Remove "First sheet" and "Last sheet" from bottom toolbar
* Selection of copied range
* Pivot table option - "Auto-fit column widths on update"
* 1904 date system support

#### Presentation Editor

* Animation with Custom path
* New advanced settings "Placement" tab for graphic images
* Added VLC libs so codecs are not required for video and audio playback

#### Forms

* Search in embedded and forms mode
* Change field width for "Comb of characters"-enabled field
* Ability to set tag for field
* New "Format" and "Allowed Symbols" settings for field
* New field types - "Phone number", "Email Address" and "Complex Field"

### Fixes

* Various fixes and updates for all components

## 7.1.1

### Fixes

#### All Editors

* Fix rendering list of fonts if there is a lot of fonts (Bug #46495)
* Fix rendering of some Chinese fonts (Bug #48564)
* Update help entries

#### Document Editor

* Fix lost text box in Header (Bug #56940)
* Fix incorrect table width for some doc file (Bug #56901)
* Fix convert of some docx files (Bug #57068, Bug #57177)
* Fix color of SmartArt figures in docx -> odt convert (Bug #57104)
* Fix page count in specific doc file (Bug #57334)
* Fix insert page with merge cells and drag'n'drop (Bug #57305)
* Fix zoom while touch-pad scrolling (Bug #56029)
* Hide "Create new" for offline pdf/djvu/xps files

#### Spreadsheet Editor

* Fix all sheets display while saving as pdf (Bug #49163)
* Fix zoom change with touch-pad on MacOS (Bug #57249)

#### Presentation Editor

* Fix re-save of some pptx files (Bug #57070)
* Fix test align for some ODP files (Bug #57214)
* Fix saving SmartArt in groups (Bug #57112)
* Fix crash on drawing animation labels by shape track

#### PDF Viewer

* Fix lost text in PDF -> ODT (Bug #57274)
* Fix calling translate plugin (Bug #53808)

## 7.1.0

### New Features

#### All Editors

* Use system scaling option for screen on Windows 10 and later
* New menu for inserting shapes (with list of recent used)
* Ability to edit points of a selected shapes
* Ability to open new diagram types: Pyramid, Bar (Pyramid), vertical and
  horizontal cylinders, vertical and horizontal cones
* Ability to crop a selected image to shape
* Ability to see your file protection password when entering it
* Support for SmartArt objects without converting into a group of objects
* New UI language on Windows/Linux (Galego/Galician)
* New UI languages on macOS (Belarusian, Bulgarian, Catalan, Danish, Dutch,
  Finnish, Galego, Greek, Hungarian, Indonesian, Japanese, Korean, Latvian,
  Norwegian, Romanian, Slovene, Swedish, Turkish, Ukrainian, Vietnamese, Lao)
* Gradient fill icon shows the chosen colors

#### Document Editor

* Ability to convert PDF/XPS files into editable files
* New toolbar tab: View
* Ability to accept/reject changes from the context menu
* Ability to use special symbols when searching within documents
* Ability to add a period with a double-space
* Add Chinese/Japanese/Italian language to Watermark settings
* New viewer for PDF, XPS, DjVu files with major performance improvements
  All operations are performed on the client side.
* Ability to use the Page Thumbnails panel and to display the document's
  contents on the left sidebar for PDF files
* Support for external and internal links in PDF opening
* Ability to use Hand/Select tools in PDF viewer
* The Document Info section of the Data tab contains information about PDF,
  XPS, DjVu files

#### Spreadsheet Editor

* Using a built-in preview panel before printing out a spreadsheet
* New view settings: Combine sheet and status bars, Always show toolbar,
  Interface theme, Show frozen panes shadow
* New currencies as per ISO 4217 without needing to change the locale
* Using tips when working with formulas for tables
* Ability to set a text qualifier when importing text from TXT/CSV
* Support for XLSB files for opening

#### Presentation Editor

* New toolbar tabs: Animation, View
* Animations can be added to the presentation
* Ability to duplicate slides using the Add slide menu
* Ability to move a slide to beginning/end using a slide context menu
* Ability to add a period with double-space

#### Forms

* Ability to zoom a form

### Fixes

* All components received countless fixes

## 7.0.2

### Fixes

Fix the problem with locking files when opened from mounted network locations (Linux)

## 7.0.1

### New Features

#### All Editors

* Spelling language detection (Windows only)

#### Spreadsheet Editor

* `French (Switzerland)` regional setting (Bug #53978)

### Fixes

#### Document Editor

* Fix changes in text position (Bug #54485)
* Fix JS error while changing font in some files (Bug #55280)
* Fix the problem with calculating the position
  of flow objects lying in a table cell (Bug #51933)
* Fix the problem with calculating the position of
  a drawing object in the header (Bug #55398)
* Fix the problem with calculating header/footer.
  Forbid to change the page number of a header
  when calculation in progress (Bug #55403)
* Fix the problem with calculating the position
  of a drawing lying in a table cell
  with vertical alignment to the bottom or center (Bug #55406)
* Fix the problem with calculating page count stage (Bug #55458)
* Fix the problem with text position calculation for rotated table cells (Bug #54200)
* Fix `Shift + (` shortcut (Bug #55356)

#### Spreadsheet Editor

* Fix opening protected workbook in Excel (Bug #55027)
* Fix JS error while Find and Replace empty cell (Bug #54999)
* Fix compatibility of some files with Excel (Bug #54956)

#### Presentation Editor

* Fix shape position in slideshow mode (Bug #55068)

#### Forms

* Fix problem float characters limit (Bug #55410)

## 7.0.0

### New Features

* Added Liferay provider connection options
* Added kDrive provider connection options
* Added ability to launch editor in a single window
* New UI languages (Belarusian, Bulgarian, Catalan, Danish, Dutch, Finnish,
  Greek, Hungarian, Indonesian, Japanese, Korean, Latvian, Norwegian, Romanian,
  Slovene, Swedish, Turkish, Ukrainian, Vietnamese, Lao)
* 125% and 175% interface scaling support (Windows, Linux)
* Ability to setup editor launch mode
* New sort types for Comment left sidebar
* Ability to call menu entries by pressing `alt+key`
* New canvas zoom options (up to 500%)

#### Document Editors

* Completely new mode for creating, filling and sharing forms
* Dark Mode (dark canvas background and other interface changes)
* New settings to change review mode `Track Changes Display`
* Ability to select local file for `Mail Merge` for cloud-stored files
* New setting for AutoFormat as you type -> hyperlinks and network paths

#### Spreadsheet Editor

* Version History
* Ability to protect spreadsheet files and separate sheets
* Ability to show other users cursor in co-edit mode
* Ability to separate sheets and status bar
* `pt-br` formulas description and translation
* Do not loose Query Table data
* Copy sheet with drag-n-drop with holding `ctrl`

#### Presentation Editors

* Ability to display animations
* Slide animation settings moved to top Tab
* New setting for AutoFormat as you type -> hyperlinks and network paths
* Ability to save presentation to `JPG` and `PNG`

### Fixes

* All components received countless fixes

## 6.4.2

### Fixes

#### All Editors

* Fixed interaction with Community server
* Fixed theme initialization in app loader
* Fix JS errors while copy chart from Document Editor
  to Presentation Editor (Bug #52844)

#### Documents Editor

* Fix JS error while comparing some specific docx files (Bug #52909)
* Fix JS error while undo in compare mode (Bug #52865)

#### Spreadsheet Editor

* Fix lost gradient in some files (Bug #52801)

## 6.4.1

### New Features

* Major improvements in support of chart styles
* Ability to Resolve all comments
* Change list symbols render
* Add chart styles for users with visual impairment
* Add ability to use tab\shift+tab in some controls
* Ability to view unique user link count on info page
* Improved render of CJK fonts in PDF files

### Document Editor

* Ability to convert text to table
* Ability to convert table to text
* Auto-capitalize first letter
* New review mode: Simple markup

### Spreadsheet Editor

* Ability to add/remove/edit conditional formatting
* Ability to add sparklines
* Change select by pressing `tab` + `enter`
* Data import from txt, csv
* Add setting for hyperlink auto-correction
* Freeze panes presets
* Setting for `show zeros` in cells
* Chain comments support
* Add argument names to function wizard

### Presentation Editor

* Version History
* Ability to hide notes panel
* Auto-capitalize first letter

### Fixes

* All components received countless fixes

## 6.3.1

### New Features

* Added Seafile provider connection options
* Interface Themes support
* 150% interface scaling support (Windows, Linux)
* Spellchecker implemented as SharedWorker. No more back-end service for spellchecker
* Ability to add file to favorites (must be supported on DMS side)
* Password protection support
* New chart types (lines and scatter)
* Check hyperlinks for 2083 symbol length

### Document Editor

* Wrapping for shapes in Top Toolbar
* Indents settings in Paragraph Right Sidebar
* Change Register operation in Top Toolbar
* Change List Level operation
* Export to html, fb2, ePub

### Spreadsheet Editor

* Add new chart type - combo
* Redone Chart Advanced Setting with more axis settings
* Add ability to set axis label format
* New date format "YYYY-MM-DD" (ISO 8601)
* Cell Indent setting in Table Right Sidebar
* Opening of Microsoft Office XML 2003 files
* Group and Ungroup operation for Pivot Tables
* XLOOKUP function

### Presentation Editor

* Slide opacity setting
* Setup columns in shape via Top Toolbar
* Presentation Animations are saved after export from our editor

### Fixes

* All editors received countless fixes

## 6.2.0

### New Features

#### All Editors

* Ability to use Tab/Shift+Tab in some dialog windows
* Change color of loader to darker one
* Ability to setup font size 300pt (409pt for Spreadsheets)
* Implemented a new Document Server integration scheme
* Ability to protect documents, spreadsheets and presentations using a digital signature

#### Document Editor

* Ability to insert Table of Figures

#### Spreadsheet Editor

* Ability to insert slicers in pivot tables
* Data Validation settings
* Ability to cancel auto-expansion of tables
* Support of custom number format
* GROWTH, TREND, LOGEST, UNIQUE, RANDARRAY functions support

#### Presentation Editor

* Ability to setup auto-format as you type
* Buttons for increase-decrease font size

### Fixes

* All editors received countless fixes

## 6.1.0

### New Features

#### All Editors

* Complete redone html-based formats (`ePub`, `mht`, `html`)
* `fb2` format can be opened in viewer
* Redone gradient control and ability to set custom angle for gradient fill
* New icons in context menu
* Add support of AutoFormat as you type
* Apply button in File menu always visible
* Ability to copy comment from left sidebar
* Translate plugin uses Google Translate, instead of Yandex

#### Document Editor

* Ability to show line numbering
* Ability to add cross-reference
* Add support of endnotes
* Ability to edit AutoCorrect list
* Select Data button in Chart Editor

#### Spreadsheet Editor

* Ability to work with sheet view (available only for paid version)
* Support of editing data ranges in Chart
* Redone cell editor height change
* New cursor for column\row hover
* Ability to hide freeze pane shadow
* Pivot Table can be inserted from `Insert` tab

### Fixes

* All components received countless fixes

## 6.0.2

### Fixes

#### All Editors

* Fix problem with insert BMP image in doc (Bug #47276)

## 6.0.1

### Fixes

#### All Editors

* Actualize Help

#### Document Editor

* Fix losing comments added to docx (Bug #46770)

#### Spreadsheet Editor

* Fix pivot refresh in R1C1 (Bug #46052)

#### Convert

* Fix error while opening specific xls (Bug #46728)

#### Back-end

* Fix several vulnerabilities
* Fix Path Traversal vulnerability via `download as` params
* Fix ER_DATA_TOO_LONG: Data too long for column 'callback' at row 1
* Fix problem with generating new presentation theme (Bug #46754)

## 6.0.0

### New Features

#### All Editors

* Option to adjust application interface scaling (Windows, Linux)
* Autofit settings for shape
* Ability to insert special characters
* Autorun settings for macros
* Selecting an image from storage for watermarks, shapes and slides filling
* Added an autocorrection list
* Redesign of color selection component
* Ability to change a position and size of chart elements
* Hotkey Ctrl + 0 for zoom resetting
* Changed a behavior of hiding icons in tabs when editor window is reducing

#### Document Editor

* Ability to insert date and time
* Ability to print selection in view mode
* Converting an equation from old formats
* Changed placeholder for content controls
* Redone the algorithm the justifying of a paragraph with condensing spaces

#### Spreadsheet Editor

* Full support of pivot tables
* Autofilter settings in pivot tables
* Support of open all existing in file conditions for data bar conditional formatting
* Support of open all existing in file gradients for data bar conditional formatting
* Full support of slicers for format tables
* Special paste settings
* Ability to move a sheet from one workbook to another
* Internal link to named range
* Print titles
* New component for cells selection
* Ability to remove duplicate values
* Ability to insert function via Function Arguments dialogue
* Wrap Text and Shrink to Fit settings in right toolbar
* Vertical Text option in text orientation settings
* Ability to change the function in Total Row for formatted table
* Delimiter settings for Special Paste and Text to Columns dialogue
* LINEST function
* Hotkeys Ctrl+Shift+'Plus sign' and Ctrl+Shift+'Minus sign' for date and time insertion
* Hotkey Shift+F3 for a function insertion
* Status bar settings
* New mouse actions for work with format tables

#### Presentation Editor

* Changed interface for internal link
* Ability to print selection in view mode
* Redesign of bullet and numbering list menu

### Fixes

* All editors received countless fixes

## 5.6.4

### Fixes

#### Back-end

* Fix several vulnerabilities in convertion app (Bug #46348, Bug #46352, Bug #46353,
  Bug #46384, Bug #46434, Bug #46436)
* Fix vulnerability in TXT converter (Bug #46437)
* Fix Path Traversal vulnerability via image upload params (Bug #46113)
* Fix Path Traversal vulnerability via `savefile` param (Bug #46037)
* Fix Path Traversal vulnerability via Convert Service param (Bug #45976)

## 5.6.0

### New features

#### All Editors

* Support of Private Rooms plugin (ONLYOFFICE Enterprise Edition 11.0 needed as well)
* Possibility to gain access to some features of commercial versions Document Server

### Fixes

#### All Editors

* Fixed opening zero-bytes files created with MS Office folder menu
* Fixed an issue with opening long path files (Bug 45117)
* Added ability to run an application with system title bar by
  --system-title-bar flag (Linux) (Bug 43189) (#271)
* Fixed an unexpected application window behavior after presentation showing was
  ended (Bug 44968)
* Fixed an unexpected application behavior after undocking window with presenter
  mode (Bug 45483)
* Fixed an ability of resizing application windows on macOS (Bug 45135)
* Fixed an issue with connecting to cloud servers if url contains spaces (Bug 42293)
* Fixed an issue with restoring application window after some scenarios (Bug 45292)
* Fixed a dialog window displaying while all application windows is closing
  (Bug 44974)
* Fixed a window title scaling on HiDPI displays in some scenarios (Bug 45060)
* Fixed a duplication of print button after undocking PDF-viewer window (Bug 45170)
* Some translations in dialog windows was improved
* Fixed a position of application window after printing operations was canceled
  (Bug 45003)
* Fixed an issue with displaying artifacts on about page in some scenarios (Bug 44684)
* Fixed an issue with displaying artifacts after installation on Windows 10 was
  finished (Bug 45089)
* Fixed an issue with user name updating while document is opened (Bug 45254)
* Added user name limitation in field (Bug 44742)
* Fixed an issue with locking modal dialogues while print dialogue in opened and
  updocked (Bug 42791)
* Fixed an editor tab position after window is attaching (Bug 44749)
* Added custom title for Windows Apps entry in Add or Remove Programs
* Fixed unexpected system rebooting after VSRedis installation
* Fixed displaying of dialogue windows on some linux color schemes (Bug 31995)

#### Document Editor

* Fixed in issue with autocolor feature for graphical objects in some DOCX user
  files (Bug 45460)
* Fixed an issue with increasing font size in some DOCX user files (Bug 44852)
* Fixed disabling undo/redo buttons after the documents comparing
* Fixed incorrect displaying of some PDF user files (Bug 45336, Bug 39097, Bug 19078)
* Fixed incorrect displaying of watermark on CJK languages (Bug 45886)
* Fixed an export of some DOCX user files to PDF (Bug 45319)

#### Spreadsheet Editor

* Fixed invalid icon in cells border menu (Bug 45910)
* Fixed an error with copy and past format table in some XLSX files (Bug 45731)
* Fixed an error with format table creation in some XLSX files (Bug 45773)
* Fixed an error with entering big data in last partially view cell (Bug 45653) (#903)
* Fixed an appearance of color selection dialogue box for bullet lists (Bug 45417)

#### Presentation Editor

* Fixed an appearance of color selection dialogue box for bullet lists (Bug 45417)

#### files editing/convertion

## 5.5.1

### New features

#### All Editors

* Multi-Window mode (Windows, Linux)
* Loading speed improvements
* `Symbol table` now is system component, not a plugin
* New button `Top Toolbar -> Collaboration -> Remove comments`
* Replace `Default Size` button to `Actual Size`

#### Document Editor

* Ability to remove table cells
* Ability to insert several rows\columns
* Ability to add titles for shapes, table and levels
* New options for margins
* New options for bullet lists
* Ability to draw and erase table
* Ability to edit gutter and mirror margins

#### Spreadsheet Editor

* Added support of reading drop-down lists.
* Added support of reading data validation.
* Ability to recalculate all formulas
* New scale options
* New options for cell fill
* Ability to set Cell Snapping
* Sheets multi-select
* Bullets and numbering options from context menu
* Ability to change bullets marker
* New spellchecker options
* Ability to sort by several columns\rows
* Option for setting separators

#### Presentation Editor

* Ability to add object to slide template
* Ability to reset slide
* New list settings
* Ability to add object to placeholder

### Fixes

#### All Editors

* All components received countless fixed
* Localization improvements
* Fixed some security issues
* Fix some more issues with user files

#### Document Editor

* Fixed an issue with comment duplication in other editors (bug #44689)

#### Spreadsheet Editor

* Better support of TIME function (bug #44849)

#### files editing/convertion

* Fixed some security issues
* Fixed an issues with DOC, RTF and XLSX formats(bug 44756) (bug 44934) (bug 44840)
* Fixed corrupting of mime-type after some DOCX editing (Bug 44957)

## 5.4.2

### Fixes

### All Editors

* Improved compatibility with macOS 10.15 Catalina

#### Document Editor

* Fix the problem with removing previously added text by
  other user in the review mode (bug #43183)
* Fix the problem with moving text in the review mode
  (bug #43238)
* Fix the problem of inserting a table over another table
* Fix the problem with reviewed numbering
* Fix some problems with watermarks

#### Plugins

* Fix starting PhotoEditor plugin (bug #42473)
* Fix issues with YouTube plugin

## 5.4.1

### New Features

#### All Editors

* More options for Paragraph Spacing
* Ability to set paragraph Outline level
* Ability to get current color scheme
* Redone Document Info page
* Better and more templates for tables
* Select languages using keyboard (bug #24317)
* Ability to show shadow for images/shapes
* Add mentions to comments
* Show multi-gradient fill in shapes (bug #40719)

#### Document Editor

* Ability create new style - next style same as previous
* Ability to add watermarks
* Ability to save docx in mode compatible with old versions
* Add tooltip for table styles

#### Spreadsheet Editor

* Ability to change look of chart elements
* Ability to set Headers and Footers
* New options for working with formulas
* Ability to group data
* Spellchecker
* Ability to resize autofilter window
* Show the number of cells in autofilter window
* Save 10 last used functions
* Set default value for regional settings (bug #41549)
* Asynchronous loading of formulas

#### Presentation Editor

* New themes for slides
* Ability to set Headers and Footers
* Ability to insert slide number
* Ability to insert date/time
* Add tooltip for table styles

### Fixes

#### All Editors

* Fix detecting document info as document change (bug #42717)
* Fix paste in canvas after opening settings
* Fix some issues with loading of translations

#### Document Editor

* Fix the problem with drawing a track around a content control (bug #42657)
* Fix the problem with accept/reject in case when moved text gets into selection
  (bug #42665)
* Fix the problem with deleting text that was previously added by the same user
  (bug #41242)
* Fix "No image uploaded" for Watermark background (bug #42832)
* Fix rules unit of measurements (bug #42608)
* Fix some watermark bugs
* Fix style list in `Create New Style` window on small window size (bug #42799)
* Fix changing display mode for track changes (without plugins tab)

#### Spreadsheet Editor

* Fix opening some files with pivot table without pivot style
* Fix JS error in `SUBTOTAL` function (bug #42833)
* Fix scale options while printing (bug #34704)
* Fix adding image from storage (bug #42789)
* Fix auto-sum icon
* Fix button icons (chat, comments)

#### Presentation Editor

##### doc

* Fix extended comments

##### docx

* Fix bookmarks saving inside hyperlink

##### xls

* Fix marker filters in some xls (bug #42239)
* Fix image size in save to xls (bug #42618)
* Fix group data display (bug #42216)

##### xlsx

* Fix tooltip for data validation (bug #42667)
* Fix Excel recovery error for files with comments (bug #42968)
* Remove reply duplicates (bug #42969)

##### odf

* Fix error in headers/footers
* Fix print areas (bug #42654)
* Fix column width (bug #42790)
* Fix cell color (bug #42932)
* Fix link to formatted as table (bug #42938)

## 5.3.5

### New Features

#### Plugins

* Translations for Photo Editor plugin

### Fixes

#### All Editors

* Fix connection to Community Server v10.0.4
* Fix bugs in encryption mode

#### Document Editor

* Fix JS error while undo insert empty row in table (bug #41995)
* Fix the problem with adding an equation inside a hyperlink
* Fix crash while opening file with math created by aspose

#### Presentation Editor

* Fix background color of slide

#### x2t

* Decode xlsx escaped chars (bug #36575, #41890)

## 5.3.4

### No public release

## 5.3.3

### Fixes

#### All Editors

* Improved HiDPI screens compatibility
* Added Chinese as UI language
* New placements for undo-redo, save and print button in top toolbar
* 250 document languages (mostly without spellchecker)
* Completely redone font engine (Better support of CJK fonts and much more)
* Ability to flip and rotate shape/images
* Ability to crop images
* Adding bookmark do not close bookmark window
* Comments are show in all edit-view modes
* New hotkeys on MacOS
* Add options for objects align (align to page, margin, slide)
* New hints for shapes (Bug #20091)
* Completely new photo editor plugin
* Plugin for sending document via system email client
* Fix some more problems with SVG
* Fix a lot of bugs with drawings positioning

#### Document Editor

* Formulas in Tables
* Save as DOTX, PDF-A, OTT
* Show review changes in view mode
* Can't remove review changes of another user
* Can't remove a comments of another user
* Add description for moved text and move to changed text in Review mode
* Get link to bookmark
* Search selected text
* Add support for calculating tabs in word2013 style that lies to the
 right of the right margin
* Fix JS error while scrolling in mail merge window (bug #41787)
* Fix JS error while opening some specific docx (bug #41847)
* Fix JS error while using final mode in review mode (bug #41846)
* Fix the problem with updating positions in the inner
  classes within a paragraph (bug #41848)
* Do not add changes to reviews with changes of the text properties
  if in fact there have been no changes (bug #41833)
* Fix critical bug on setup hideContentControlTrack property
* Fix show changes of second user if show changes disabled (bug #41576)
* Fix the problem with accepting/rejecting review changes
* Fix JS error while entering text in content control in specific docx (bug #41687)
* Fix the problem with calculating numbering value with merged cells (bug #41699)
* Fix JS error while undo entered text in review mode (bug #41708)
* Fix deleting whole TOC field after selecting it (bug #41714)
* Fix showing numbering as changes for review in specific document (bug #41518)
* Fix opening Modelling_scholarly_communication_report_final1.docx (bug #41717)
* Fix crash on refresh recalculated data
* Fix bug with moving object in group
* Fix the problem with rendering WMF files (bug #41495)

#### Spreadsheet Editor

* Български, Svenska (Finland), Svenska (Sverige) number format
* Translates of formulas to Italian
* Go to link by click, not control click
* `ASC`, `BETAINV`, `HYPERLINK` formulas
* Support of Print areas
* Ability to set exact text orientations in degrees
* Text to column Wizards
* Paste Text Wizard
* Save as XLTX, PDF-A, OTS
* Support of Array Formula
* Icon and Data Bars Conditional Formatting
* Gradient and Texture cell fill
* Show hint with function/arguments description when typing function
* Show min and max values in status bar
* Distribute objects
* Redone cut cell process (cell not removed after cut immediately)
* Fix JS error for `Replace all` in some cases (bug #41760)
* Fix column index error while insertion
* Fix add changes to history on drawing sparklines
* Fix undo moved cell in print area (bug #41723)

#### Presentation Editor

* Save as POTX, PDF-A, OTP
* Add font rendering option
* Search and replace text
* Internal hyperlinks: entering the slide number manually
* Possibility to insert audio/video content

## 5.2.8

### Fixes

* Major bugfix for interaction with Nextcloud and ownCloud portals

## 5.2.4

### New features

* Added an option to change the UI language
* Added an option to change the user name
* Improved HiDPI screens detection
* Extended the list of providers for collaborative portals (ownCloud, Nextcloud)
* Added encryption options (test mode)

#### All editors

* Add warning when open file protected with password
* Don't show resolved comments by default in Document and Spreadsheet editor
* Customize availability of help in the editor
* Add File and Plugins tabs for viewers
* Mark username by color in the comments, review changes, chat messages
* Show edit-mode users in format
* Don't duplicate online users in the left chat panel
* Sort comments in the popover by ascending creation time

#### Document Editor

* Ability to work with bookmarks
* Ability to add/change hyperlinks anchored to bookmarks/headings
* Change numbering value, start/continue numbering
* Ability to continue numberings
* Content controls settings (highlight and appearance)
* Review changes and comments are in combined window
* Add page presets А0, А1, А2, А6 (bug #36583)
* Enable closing chart dialog while loading (bug #36870)
* Change encoding format for txt files (bug #36998)
* Add mode for filling forms
* Enable closing window when save to txt
* Enable inserting shapes when shape is selected
* Check new revisions in fast co-editing mode
* Save track-changes option for file key

#### Spreadsheet Editor

* Cell settings in the right panel
* Add Layout tab: save margins, page size, orientation for sheets,
 align/arrange, group/ungroup objects (shapes, images, charts)
* Added hint for autofilters
* Change encoding format for csv files (bug #36998)
* Save page options to file before printing
* Add ability to view Combo Charts
* Enhanced completely rewritten scroll
* Support of R1C1 references style

#### Presentation Editors

* Add hints to presentation themes (bug #21362)
* Add presenter preview in the viewer (bug #37499)
* Enable closing chart dialog while loading (bug #36870)

### Fixes

#### All editors

* Update translations
* Fix position for zoom buttons in the toolbar
* Fix tab 'File' lost active state when click inner panels
* Fix `Replace image by url` in context menu (#37651)
* Fix copy comments from comment balloon (#37666, #35896)
* Fix footnote dialog layout (#37660)
* Fix error while changing shape connector (bug #37788)
* Fix error while changing default tab in shape (bug #38084)
* Fix opening custom color for shape (bug #37841)
* Fix comment loss from other user (bug #37570)
* Fix bug with cff fonts (glyph loader)
* Fix error while `ctrl+s` in chart editor (bug #39254)
* Remove 'command+h' hotkey for MacOs
* Fix special paste icon while inserting ClipArt (bug #39462)
* Show conversion error in case of pdf renamed to docx
* Fix bug with solid fill without color
* Fix opening presenter view on ownCloud\Nextcloud (bug #39559)
* Fix bug when apply new font (current font name and new name are empty)
* A lot of bug fixed in all editors

#### Document Editor

* Fix getting parent cell in blocklevelstd
* Fix justify chinese text (#37659)
* Fix setting option Realtime collaboration changes to "ViewAll"
* Fix protected document window layout (#37658)
* Disable bookmarks in the document headers (bug #38957)
* Fix opening docx with track changes and math created by aspose
* Fix problem with reading the Id of a content control
* Fix crash in `CNumberingLvlLegacy.ReadFromBinary`
* Fix problem with selecting tables
* Fix the problem with replacing misspelled word
* Fix the critical issue with locking the document on the undo in the fast collaboration
* Fix lost `Hide Degree` menu entry for equations (bug #39135)
* Fix the problem when recalculating in co-editing
* Fix the problem with processing the pageDown button in co-editing
* Fix error while deleting table column (bug #39252)
* Fix problem with render while replacing text (bug #39269)
* Fix problem with saving/loading table state on undo/redo
* Fix showing charts added by macros (bug #39304)
* Fix the problem with calculating a large tables separated by columns
* Fix error after discarding changing font name in combo box
* Fix input of korean, chinese and japanese symbols in Content Control (bug #39724)
* Fix the problem with recalculating a document with large tables
* Fix the problem with accept/reject an uncalculated revision change
* Fix bug with recalculating a document when deleting a section
* Fix the problem with checking complex fields in selection
* Fix the problem with updating cursor in collaborative editing
* Fix bug with moving cursor through a table
* Fix bug with recalculating large tables
* Fix the problem with moving an image inside a large table
* Fix bug with accept/reject the change in review
* Fix the problem with updating current position in table after accepting changes
* Fix bug with special paste of paragraph with numbering
* Fix reading rtf comments
* Fix opening file with image in shape in rtf (bug #37902)

#### Spreadsheet Editor

* Fix enter formula with arrow keys and scroll
* Fix multiselect autofit column width. Autofit only exist columns (#37555)
* Fix formula dependency and file assemble after copying with drag and drop
* Fix out of memory error in case of insert rows in file with many columns
* Fix incorrect error for chart with empty dataset (#37762)
* Fix deleting comments (bug #37772)
* Fix check pane and opening some xlsx files (bug #38113)
* Fix hyphenation position for chinese symbols with wrap
* Fix missed french and spanish formulas
* Fix missed region formats
* Disable table settings when cell is edited
* Fix change active cell in selection across merge. Previously, passing
 through the first cell of the merge range, we fell into the merge range,
 even if it was not selected (through the selection of a row / column)
* Fix selection when selecting row/col/all
* Hide options for headings, gridlines, freeze panes in the viewer (bug #38033)
* Fix losing document after reopen xlsx file (bug #37892)
* Fix open file with unknown picture format
* Fix problems with multichart files (bug #37945, 37946)
* Fix crash on build file with comment changes
* Fix incorrect chart for area with autofilter (bug #39168)
* Fix incorrect select cells while changing formula by keyboard (bug #39181)
* Fix brower hangup in some file with formula (bug #39190)
* Fix incorrect display of doughnut chart with autofilter (bug #39200)
* Fix incorrect `IF` formula values (bug #39233)
* Fix problem with replace count (bug #39273)
* Fix error while copy deleted shape (bug #39312)
* Fix specific error while sorting (bug #39397)
* Fix undo for filter in specific files (bug #39402)
* Fix scroll to end of table (bug #21946)
* Fix sorting first row in some files (bug #39397)
* Fix sorting range if there is filtered data (bug #39410)
* Fix double columns borders (bug #39392)
* Fix rendering last rows in some files (bug #39394)
* Disable cell settings when editor is disconnected
* Fix print and calculate. Speed up prepare cache
* Fix scrolling issues in specific file (bug #39395)
* Fix issue with open only one SheetView to avoid property
  conflicts(tabSelected) (bug #39511)
* Fix freeze while cut paste several columns (bug #37965)
* Fix incorrect `sum` formula for copied sheet (bug #39548)
* Fix error while entering more data than cell width (bug #39623)
* Fix incorrect digit count while using `Decrease Decimal` (bug #39661)
* Fix opening file with 'si', 'formula' without 'ref'
* Fix opening specific file with chart (bug #39902)
* Fix error while copy specific sheet in file (bug #39921)

#### Presentation Editor

* Fix deleting placeholder text in strict co-edit (#37712)
* Fix duplicate comments in exported pptx (#37698)
* Fix specific error while opening empty presentation in comment mode (#37679)
* Fix copy-paste placeholder in fast coedit (bug #37922)
* Fix bug copy/paste slide with picture (bug #37928)
* Fix placeholder titles in Chinese (bug #37927)
* Fix specific error while opening some pptx (bug #39191)
* Fix problem with negative spacing
* Fix error while copy table (bug #39264)
* Fix opening specific ppt file (bug #39901)

#### Back-End

* Bump compatibilityMode setting. Prevent opening files in compatibility mode in
  Word 2016.
* Fix doc, rtf, xls users files
* Fix exporting current list of XLSX to csv (#37579)
* Fix opening specific pptx file (#37589, bug #39747, #39745)
* Fix save comments for presentation (undelete ms office)
* Fix opening specific RTF document (#37500)
* Fix slide theme for ODT export (#37740)
* Fix chart legend in ODS file (#37746)
* Set default value for math nodes with val attribute and COnOfftype
* Fix empty rtf (bug #39172)
* Fix opening some ods (bug #39192)
* graphics - metafile - fix convert to rastr on linux without set fonts
* PptxFormat - fix binary convert mathType version over 3.0
* Fix document structure for specific file (bug #39236)
* Fix opening in MS word some file (bug #39216)
* Fix opening specific docx file (bug #39248)
* Fix open some rtf files (bug #39315)
* Fix selecting row in pdf file (bug #39214)
* Fix crash on empty dash pen
* Fix loss of grouped shape in odt (bug #39467)
* Fix convert of wmf file (bug #39533)
* Fix bug with metadata in UTF16 format
* Fix convert of specific xls (bug #39541)
* OdfFormat - refactoring same auto shapes
* Fix convert vml -> drawing_ml
* Fix bug with calculating inverse matrix in PDF

## 5.1.27

### New features

#### All editors

* New `View Settings` menu in top right corner
* New selector for links type in Spreadsheet and Presentation Editor
* Ability to replace image via context menu (#11493)
* Update translations
* New help entries
* New `no squares` font engine, find best replacement font for `□` characters
* Ability to distribute data in tables
* Fully rewritten composite input for characters
* New header and background color
* Support of shape side panel for images
* Change table size by drag'n'drop
* New bullet list marker - `–`
* Increase supported document size (without media-content)
* New help entries
* Search in help

#### Document Editor

* Implement an East Asian script and line break in hieroglyphs ([sdkjs#300](https://github.com/ONLYOFFICE/sdkjs/pull/304))
* Add hotkey Ctrl+Shift+Num8 - show/hide non printable symbols
* Support of multi comments balloon (bug #37422)
* Ability to set Tab Leader symbols
* Support of Table of Contents
* New `Navigation` left sidebar
* New `Reference` tab
* Changes history in Strict Co-Edit
* Rename `Display Modes` entries for Track Changes
* File tab `Go to documents` opens in new tab
* Ability to set negative top and bottom page margin
* Copy paragraph style will not overwright custom run style
* Special paste of tables

#### Spreadsheet Editor

* Add French translation for formulas
* Ability to select Cell format via context menu (#16272)
* Custom user cell styles are now placed before default ones
* 8 new formulas: `F.TEST`, `FORECAST.ETS`, `FORECAST.ETS.CONFINT`,
`FORECAST.ETS.SEASONALITY`, `FORECAST.ETS.STAT`, `FORMULATEXT`,
`IFS`, `PDURATION`
* New `None` Table Template
* New regional presets - `Deutsch (Schweiz)`, `Español (México)`,
 `Nederlands (Nederland)`, `Slovenčina (Slovenská republika)`
* New date formats `yy/m/d`, `yy/mm/dd`, `yyyy/m/d`
* CSV preview before opening

#### Preseentation Editor

* Add hints to presentation themes (bug #21362)
* Special paste
* Presentation level comments

#### Back-End

* Update `icu` dependency from `5.5` to `5.8`
* Support a lot of features in xls format (macros, controls etc.)
* Speedup of opening ooxml files on 5-10%
* Better compatibility with OpenFormat, RTF
* Fix a lot of error in user-send files in all supported formats

### Fixes

#### All editors

* Fix crash on opening files with empty pie charts ([sdkjs#318](https://github.com/ONLYOFFICE/sdkjs/pull/318))
* Fix undo after copy paste in coedit (bug #37424)
* Fix problems with some thai symbols (bug #37446) ([sdkjs#297](https://github.com/ONLYOFFICE/sdkjs/pull/297))
* Hide empty width glyphs fonts in font picker
* Don't save changes for undo/redo in server build mode
* Change size of image pasted form html
* Fix problem in text selection with Shift
* Fix redundant symbol in cell after undo-redo (#37343)
* Fix problems with icons of some buttons
* Fix sync coedit button in top toolbar and menu (#37377)
* Fix toolbar icons problems

#### Document Editor

* Fix displaying table after html convert (#37472)
* Fix adding comment to whole doc (#37425, [DocumentServer#287](https://github.com/ONLYOFFICE/DocumentServer/issues/287))
  ([sdkjs#319](https://github.com/ONLYOFFICE/sdkjs/pull/319))
* Fix copy Rich Text Content from table (#37546) ([sdkjs#320](https://github.com/ONLYOFFICE/sdkjs/pull/320))
* Fix changing labels of Content Control ([sdkjs#296](https://github.com/ONLYOFFICE/sdkjs/pull/296))
* Fix search text in drawing formats ([sdkjs#292](https://github.com/ONLYOFFICE/sdkjs/pull/292))
* Fix problem with loading pdf renamed to docx ([sdkjs#295](https://github.com/ONLYOFFICE/sdkjs/pull/295))
* Fix right mouse button menu for TOC (#37241)
* Fix usage Clip ParaDrawing by line top and bottom
* Don't clip images in text arts
* Add vertical clip for inline drawing
* Fix problems in drawing inline objects
* Fix bug in calculation text clip rect in documents

#### Spreadsheet Editor

* Fix formula dependency and file assemble after add col/row ([sdkjs#312](https://github.com/ONLYOFFICE/sdkjs/pull/312))
* Fix opening specific xlsx file (#37515) ([sdkjs#316](https://github.com/ONLYOFFICE/sdkjs/pull/316))
* Fix open pivot tables with VALUES ([sdkjs#298](https://github.com/ONLYOFFICE/sdkjs/pull/298))
* Add `CONVERT`, `FTEST`, `HYPGEOM.DIST` formulas
* Add Spanish formula translations
* Fix right mouse button error (#37330)
* Fix inserting hieroglyphs from text editor (#37356)
* Fix bug with enter symbol point in formula autocomplete (#37300)
* Fix bug with enter symbol `_` or `\` in start formula autocomplete (bug #37354)
* Fix bug with enter Chinese numbers in formula autocomplete
* Fix sheet context menu visibility (#37307)
* Fix translations for formulas
* Fix inserting function in opened cell (#37348)
* Correct some formulas translations

#### Presentation Editor

* Fix hieroglyph problem in chart title (#37293)
* Fix chart title focus problem in coedit (#37295)
* Fix object selection problem in coedit (#37336)
* Clamp scroll_central position
* Bug with clearing cached canvas
* Fix bug in calculation of slide layout bounds

#### Back-end

* Fix doc users files with table ([core#71](https://github.com/ONLYOFFICE/core/pull/71))
* Fix opening docx, pptx, rtf, odf usersfiles ([core#75](https://github.com/ONLYOFFICE/core/pull/75))
  ([core#76](https://github.com/ONLYOFFICE/core/pull/76))
* Fix mac related build problems
* ppt - fix shape geometry in files from newest ms office
* Fix font generation
* Fix reopening files with macros (#37323)
* Fix opening some Docx user files
* Fix opening some XLS user files

## 4.8.7

### New features

#### All Editors

* Support for two-factor authentication
* Brazilian Portuguese as new interface languages

#### Spreadsheet Editors

* Add stirkeout, superscript and subscript in top toolbar (bug #26581)

### Fixes

#### All Editors

* Update translations

#### Document Editor

* Fix opening docx file with formula in MS Word (bug #36490)
* Fix JS error while inserting Spreadsheet cell with comment (bug #36506)
* Fix bug with inserting the content control in the math equation.
* Fix reset selection from object in header/footer after keyboard move

#### Spreadsheet Editors

* Fix wrong dependence in formula with 3D Ref after removing sheet
* Fix opening odt with chart
* Fix calculating sparkline in some case (bug #36603)
* Fix printing image outside of printed range (bug #36573)

#### Presentation Editor

* Fix shape blocking in coedit for users with different mode (bug #36435)
* Fix chart `Constant proportions` working only once (bug #36494)
* Fix error while inserting page number from Document Editor (bug #36508)
* Fix error while undo of table (bug #36515)

#### Conversion

* Fix some DOCX, DOC, RTF files from users
* Fix DOCX with MathType equations (bug #36524)

## 4.8.6

### New features

#### All Editors

* Preinstalled plugins set
* Support SSO authorization
* Czech and Slovak languages in interface
* Macros
* Support of fods, fodt, fodp formats

### Fixes

#### All editors

* Fix bug with images paths

#### Document Editor

* JS Error while inserting empty cell to chart title (bug #36441)
* Fix red cross for images in some situations
* Fix bug with creating several synchronize tips
* Fix line end in thumbnails
* Fix paste simple text to equations
* Fix cursor while rotating object (bug #36114)
* Fix opening some docx (bug #35307)
* Fix chart legend blocking in coedit (bug #35492)
* Fix problem with setting tab several time (bug #34923)
* Fix printing in Edge (bug #35323)
* Fix help for moving shape by pixel (bug #34983)
* Fix special paste in fast co-edit (bug #35310)
* Fix duplicates in strict mode after special paste (bug #35312)
* Fixed bug with moving cursor to the start of the document after removing
  content control.
* Fix minor problems with co-edit in real time (bug #35398, #35399, #35400)
* A lot of fixes in translations

#### Spreadsheet Editor

* Fix a.Se is not a function error while opening file (bug #36344)
* Fix error with merge table colors
* Fix merge cells after apply table template (bug #36405)
* Fix JS error for some pivot table styles (bug #36290)
* Check xfIndexNumber when merging styles to avoid errors with column styles
* Fix conditional formatting while changing cell values (bug #36253)
* Fix change shape size by yellow markers (bug #35451)
* Fix case sensitive VLOOKUP and HLOOKUP (bug #35528, DocumentServer#140)
* Fix box for Show empty cells as in Russian (bug #35299)
* Fix sparkline type in setting window (bug #35296)
* Fix error in conditional formatting with formula and offset (duplicate
  variable) (bug #35334)
* Fix error in SEARCH formula (bug #35340)
* Fix freeze pane shadow not hiding (bug #35359)
* Fix showing hidden objects
* Fix VLOOKUP format cell
* A lot of fixes in translations

#### Presentation Editor

* Check buttons layout in reporter mode
* Disable scroll to target in selectwheel (empty selection)
* Fix applying image as background for several slides (bug #36399)
* Fix mouse slide scroll without change zoom (bug #28096)
* Don't disable prev-next buttons for slide demonstration
* Fix presentation demonstration: start from beginning
* Fix notes scroll
* Fix insert text operation duration (bug 36208)
* Fix browser zoom problem with reported pointer
* Fix bug with position of hyperlink tooltip and slide num tooltip
* Fix slide resize bug
* Fix search in text in placeholder (bug #36133)
* Fix layout in reported mode
* Fix js error in Tables_test.pptx (bug #17147)
* Fix comment reply duplication (bug #35408)
* Fix bug with drag-and-drop chart into title
* Fix changing presentation language if no shape selected (bug #35231)
* Fix columns in placeholder (bug #35074)
* Fix connector losing shape after moving shape in group (bug #35317)
* Fix hidden markers for connector on chart and image (bug #35300)
* Fix cell link after copy paste (bug #35362, DocumentServer#122)
* A lot of fixes in translations

#### Plugins

* Fix crash on unknown ole-object resize
* Fix problems with scroll

#### Conversion

* Fix colors schemes for table cells (bug #36322)
* Fix problem with image in footnote (bug #36380)
* Fix saving some files to odt (bug #35389)
* Fix custom shape with connectors in xls
* Fix margins in ods
* Fix convert named range with formulas in ods
* Fix audio wav files in pptx
* Fix old standard ole in pptx

## 4.4.1

### New features

#### Document Editor

* Special Paste
* Rich text content support
* Translates for Paragraph Styles
* View mode with comments
* Option to hide solved comments
* Ability to specify custom columns

#### Spreadsheet Editor

* Formulas with conditional formatting
* Ability to specify custom delimiter for CSV import\export
* Added `ACOT`, `ACOTH`, `ARABIC`, `BASE`, `BETA.DIST`, `BETA.INV`, `BETADIST`,
  `BINOM.DIST`, `BINOM.INV`, `CEILING.MATH`, `CEILING.PRECISE`, `CHIDIST`,
  `CHIINV`, `CHISQ.DIST`, `CHISQ.DIST.RT`, `CHISQ.INV`, `CHISQ.INV.RT`,
  `COMBINA`, `CONCAT`, `CONFIDENCE.NORM`, `CONFIDENCE.T`, `COT`, `COTH`, `CSC`,
  `CSCH`, `DECIMAL`, `EXPON.DIST`, `F.DIST`, `F.DIST.RT`, `F.INV`, `F.INV.RT`,
  `FDIST`, `FINV`, `FLOOR.MATH`, `FLOOR.PRECISE`, `GAMMA`, `GAMMA.DIST`,
  `GAMMA.INV`, `GAMMA.PRECISE`, `GAMMADIST`, `GAMMAINV`, `GAUSS`, `IFNA`,
  `IMCOSH`, `IMCOT`, `IMCSC`, `IMCSCH`, `IMSEC`, `IMSECH`, `IMSINH`, `IMTAN`,
  `ISO.CEILING`, `LOGNORM.DIST`, `LOGNORM.INV`, `NUMBERVALUE`, `PERCENTILE.EXC`,
  `PERCENTILE.INC`, `PERCENTRANK.EXC`, `PERCENTRANK.INC`, `RANK`, `RANK.AVG`,
  `RANK.EQ`, `SEC`, `SECH`, `T.DIST`, `T.DIST.2T`, `T.DIST.RT`, `T.INV`,
  `T.INV.2T`, `TDIST`, `TINV`, `XOR` functions
* Exclude hidden rows from copy, autofill, formatting etc...
* Update active cell color
* Frozen pane now with shadow
* Translates for cell styles
* Search and replace by select
* Option to hide solved comments
* Ability to specify bullets and numbering for text in shape.
* Ability to specify columns for Text Areas
* Ability to add the connectors for the shapes
* Support `Shift+Delete`, `Ctrl+Insert` and `Shift+Insert` for cut/paste

#### Presentation Editor

* Ability to connect shapes via lines
* Ability to specify columns for Text Areas
* Ability to create bullet and number lists in the shapes
* Spellcheker
* Ability to download presentation as ODP

#### Plugins

* New type for plugin window (without borders, shadows, buttons)

#### Convertion

* Speedup for opening ooxml: windows 200%, linux 20%
* Better converting from/to RTF
* Better support of password protected ooxml, binary ms
* Support of password protected ppt

### Fixes

#### Spreadsheet Editor

* Fix duplicate text after carriage return [DocumentServer#109](https://github.com/ONLYOFFICE/DocumentServer/issues/109)

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
* Fixed an issue with changing number format while changing regional format
  (bug #31395)
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

* Fix problem with losing changes while several users enter text at same time
  (bug #33726)
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

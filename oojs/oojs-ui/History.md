# OOjs UI Release History

## v0.8.0 / 2015-02-18
* [BREAKING CHANGE] Make default distribution provide SVG with PNG fallback (Bartosz Dziewoński)

* DEPRECATION: TextInputWidget: Deprecate 'icon' and 'indicator' events (Bartosz Dziewoński)

* ButtonElement: add protected to event handlers (Kirsten Menger-Anderson)
* docs: Make @example documentation tag work (Roan Kattouw)
* TextInputWidget: Hide mixin components when unused (Ed Sanders)
* DropdownWidget: Simplify redundant code (Bartosz Dziewoński)
* Update PHP widgets for accessibility-related changes in JS widgets (Bartosz Dziewoński)
* TabIndexedElement: Allow tabIndex property to be null (C. Scott Ananian)
* ButtonElement: Add description (Kirsten Menger-Anderson)
* Add missing ButtonInputWidget.less and corresponding mixin (Bartosz Dziewoński)
* Various fixes to the PHP implementation (C. Scott Ananian)
* Use Array.isArray instead of $.isArray (C. Scott Ananian)
* TextInputWidget: Use margins for moving the label (Ed Sanders)
* DraggableGroupElement: Add description (Kirsten Menger-Anderson)
* demo: Add horizontal alignment test (Bartosz Dziewoński)
* build: Pass RuboCop, customize settings (Bartosz Dziewoński)
* Widget: Add description (Kirsten Menger-Anderson)
* ButtonInputWidget: Add description and example (Kirsten Menger-Anderson)
* Dialog: Add description and example (Kirsten Menger-Anderson)
* DraggableElement: Add description (Kirsten Menger-Anderson)
* docparser: Add support for 'protected' methods (Bartosz Dziewoński)
* testsuitegenerator: Only test every pair of config options rather than every triple (Bartosz Dziewoński)
* TextInputWidget: Don't add label position classes when there's no label (Bartosz Dziewoński)
* Update JS/PHP comparison test suite (Bartosz Dziewoński)
* tests: Fix the check for properties (Bartosz Dziewoński)
* TextInputWidget: Add missing LabelElement mixin documentation (Ed Sanders)
* Follow-up c762da42: fix ProcessDialog error handling (Roan Kattouw)
* MediaWiki Theme: Add focus state for frameless button (Prateek Saxena)
* TextInputWidget: Allow maxLength of 0 in JS (matching PHP) (Bartosz Dziewoński)
* TextInputWidget: Only put $label in the DOM if needed (Bartosz Dziewoński)
* MediaWiki Theme: Use white icons for disabled buttons (Bartosz Dziewoński)
* Follow-up 6a6bb90ab: Update CSS file path in eg-iframe.html (Roan Kattouw)
* Element: Add description (Kirsten Menger-Anderson)
* PHP: Remove redundant documentation for getInputElement() (Bartosz Dziewoński)
* Some documentation tweaks (Bartosz Dziewoński)
* FieldLayout: Add description (Kirsten Menger-Anderson)
* FieldLayout: Clean up and remove lies (Bartosz Dziewoński)
* FlaggedElement: Add description (Kirsten Menger-Anderson)
* PHP demo: Correct path to CSS files (Bartosz Dziewoński)
* MediaWikiTheme: Resynchronize PHP with JS (Bartosz Dziewoński)
* ButtonWidget: Rename nofollow config option to noFollow (C. Scott Ananian)
* GroupElement: Add description (Kirsten Menger-Anderson)
* IconElement: Add description (Kirsten Menger-Anderson)
* IconWidget: Add description and example (Kirsten Menger-Anderson)
* IndicatorElement: Add description (Kirsten Menger-Anderson)
* InputWidget: Add description (Kirsten Menger-Anderson)
* SelectWidget: Add description (Kirsten Menger-Anderson)
* MediaWiki Theme: Fix border width for frameless buttons' focus state (Prateek Saxena)
* Window: Add description (Kirsten Menger-Anderson)
* WindowManager: Add description (Kirsten Menger-Anderson)
* ButtonGroupWidget: Add description and example (Kirsten Menger-Anderson)
* DropdownWidget: Add @private to private methods (Kirsten Menger-Anderson)
* Refactor keyboard accessibility of SelectWidgets (Bartosz Dziewoński)
* ActionSet: Add description and example (Kirsten Menger-Anderson)
* ActionSet: Add @private to onActionChange method (Kirsten Menger-Anderson)
* ActionWidget: Add description (Kirsten Menger-Anderson)
* ActionSet: Add description for specialFlags property (Kirsten Menger-Anderson)
* DropdownWidget: Add description and example (Kirsten Menger-Anderson)
* ButtonWidget: Add example and link (Kirsten Menger-Anderson)
* IconElement: Add description and fix display of static properties (Kirsten Menger-Anderson)


## v0.7.0 / 2015-02-11
* [BREAKING CHANGE] Remove window isolation (Trevor Parscal)

* DEPRECATION: GridLayout should no longer be used, instead use MenuLayout (Bartosz Dziewoński)

* Fade in window frames separately from window overlays (Ed Sanders)
* Fix initialisation of window visible (Ed Sanders)
* SelectWidget: 'listbox' wrapper role, 'aria-selected' state on contents (Derk-Jan Hartman)
* Cleanup unreachable code from DraggableGroupElement (Moriel Schottlender)
* DraggableGroupElement: Unset dragged item when dropped (Moriel Schottlender)
* Remove inline spacing from ButtonWidget (Roan Kattouw)
* Make sure DraggableGroupElement supports button widgets (Moriel Schottlender)
* demo: Use properties instead of attributes for <link> (Timo Tijhof)
* Revert "Remove inline spacing from ButtonWidget" (Bartosz Dziewoński)
* ToggleSwitchWidget: Accessibility improvements (Bartosz Dziewoński)
* TextInputWidget: Add required attribute on the basis of required config (Prateek Saxena)
* DropdownInputWidget: Fix undefined variable in PHP (Bartosz Dziewoński)
* PHP demo: Just echo the autoload error message, don't trigger_error() (Bartosz Dziewoński)
* demo: Stop inline consoles from generating white space (Bartosz Dziewoński)
* demo: Reorder widgets into somewhat logical groupings (Bartosz Dziewoński)
* demo: Add button style showcase from PHP demo (Bartosz Dziewoński)
* PHP demo: Resynchronize with JS demo (Bartosz Dziewoński)
* Stop treating ApexTheme class unfairly and make it proper (Bartosz Dziewoński)
* PHP demo: Add Vector/Raster and MediaWiki/Apex controls (Bartosz Dziewoński)
* Delete unused src/themes/apex/{raster,vector}.less (Bartosz Dziewoński)
* {Checkbox,Radio}InputWidget: Add missing configuration initialization (Bartosz Dziewoński)
* MediaWiki theme: Use distribution's image type for backgrounds (Bartosz Dziewoński)
* tests: Just echo the autoload error message, don't trigger_error() (Bartosz Dziewoński)
* MediaWiki theme: Fix non-clickability of radios and checkboxes (Bartosz Dziewoński)
* Fix text input auto-height calculation (Ed Sanders)
* MediaWiki theme: Consistent toggle button 'active' state (Bartosz Dziewoński)
* RadioOptionWidget: Make it a <label/> (Bartosz Dziewoński)
* MediaWiki theme: Correct flagged primary button text color when pressed (Bartosz Dziewoński)
* FieldsetLayout: Tweak positioning of help icon (Bartosz Dziewoński)
* TextInputWidget: Use aria-hidden for extra autosize textarea (Prateek Saxena)
* Refactor clickability of buttons (Bartosz Dziewoński)
* Remove usage of this.$ and config.$ (Trevor Parscal)
* build: Bump various devDependencies (James D. Forrester)
* History: Fix date typos (James D. Forrester)
* TabIndexedElement: Actually allow tabIndex of -1 (Bartosz Dziewoński)
* ListToolGroup: Remove hack for jQuery's .show()/.hide() (Bartosz Dziewoński)
* PopupWidget: Set $clippable only once, correctly (Bartosz Dziewoński)
* TextInputMenuSelectWidget: Correct documentation (Bartosz Dziewoński)
* PopupElement: Correct documentation (Bartosz Dziewoński)
* MediaWiki Theme: Rename @active to @pressed in button mixins (Prateek Saxena)
* tools.less: Use distribution's image type and path for background (Prateek Saxena)
* MediaWiki Theme: Fix background color for disabled buttons (Prateek Saxena)
* MenuSelectWidget: Don't clobber other events when unbinding (Bartosz Dziewoński)
* MenuSelectWidget: Codify current behavior of Tab closing the menu (Bartosz Dziewoński)
* DropdownWidget, ComboBoxWidget: Make keyboard-accessible (Bartosz Dziewoński)
* MenuSelectWidget: Remove dead code (Bartosz Dziewoński)
* MediaWiki Theme: Rename active-* variables to pressed-* (Prateek Saxena)
* ButtonWidget: Better handle non-string parameters in setHref/setTarget (C. Scott Ananian)
* Make better use of 'scrollIntoViewOnSelect' in OptionWidgets (Bartosz Dziewoński)
* ButtonWidget: Add "nofollow" option (C. Scott Ananian)
* MediaWiki Theme: Rename @highlight to @active (Prateek Saxena)
* MediaWiki Theme: Use darker color for frameless buttons (Prateek Saxena)
* ButtonWidget: Add documentation (Kirsten Menger-Anderson)

## v0.6.6 / 2015-02-04
* TextInputWidget: Mostly revert "Don't try adjusting size when detached" (Bartosz Dziewoński)
* Use css class instead of jQuery .show()/hide()/toggle() (Moriel Schottlender)
* build: Use karma to v0.12.31 (Timo Tijhof)
* Use standard border colours for progress bars (Ed Sanders)
* Remove disabled elements from keyboard navigation flow (Derk-Jan Hartman)
* Fix BookletLayout#toggleOutline to use MenuLayout method (Ed Sanders)
* Use CSS overriding trick to support RTL in menu layouts (Ed Sanders)

## v0.6.5 / 2015-02-01
* Make BookletLayout inherit from MenuLayout instead of embedding a GridLayout (Ed Sanders)
* ButtonElement: Unbreak 'pressed' state (Bartosz Dziewoński)

## v0.6.4 / 2015-01-30
* InputWidget: Resynchronize our internal .value with DOM .value in #getValue (eranroz)
* demo: Remove nonexistent 'align' config option for a DropdownWidget (Bartosz Dziewoński)
* MediaWiki theme: Reduce size of checkboxes and radio buttons by 20% (Ed Sanders)
* MediaWiki theme: Remove SearchWidget's border now dialogs have outline (Ed Sanders)
* TextInputWidget: Accept 'maxLength' configuration option (Bartosz Dziewoński)
* MediaWiki Theme: Adjust ButtonSelectWidget, ButtonGroupWidget highlights (Prateek Saxena)
* Update OOjs to v1.1.4 and switch to the jQuery-optimised version (James D. Forrester)
* build: Bump devDependencies and fix up (James D. Forrester)
* Seriously work around the Chromium scrollbar bug for good this time (Bartosz Dziewoński)
* Introduce and use TabIndexedElement (Bartosz Dziewoński)
* AUTHORS: Update for the last six months' work (James D. Forrester)
* Set input direction in html prop rather than css rule (Moriel Schottlender)
* Introduce DropdownInputWidget (Bartosz Dziewoński)
* Remove the 'flash' feature from MenuSelectWidget and OptionWidget (Bartosz Dziewoński)
* InputWidget: Clarify documentation of #getInputElement (Bartosz Dziewoński)
* Make sure there is a page before focusing in BookletLayout (Moriel Schottlender)
* Provide default margins for buttons and other widgets (Bartosz Dziewoński)
* OptionWidget: Unbreak 'pressed' state (Bartosz Dziewoński)
* TextInputWidget: Remove superfluous role=textbox (Derk-Jan Hartman)
* MediaWiki theme: Tweak some more border-radii (Bartosz Dziewoński)
* Widget: Set aria-disabled too in #setDisabled (Derk-Jan Hartman)
* Twiddle things (Ed Sanders)
* Add help icon for FieldsetLayout (Moriel Schottlender)
* PopupButtonWidget: Set aria-haspopup to true (Prateek Saxena)
* ToggleButtonWidget: Set aria-pressed when changing value (Derk-Jan Hartman)
* ActionFieldLayout: Add 'nowrap' to the button (Moriel Schottlender)
* demo: Have multiline text in multiline widgets (Bartosz Dziewoński)
* Add inline labels to text widgets (Ed Sanders)
* TextInputWidget: Don't try adjusting size when detached (Bartosz Dziewoński)
* MediaWiki Theme: Adjust MenuOptionWidget selected state (Bartosz Dziewoński)
* ToggleWidget: Use aria-checked (Prateek Saxena)
* MediaWiki theme: Unbreak disabled buttons (Bartosz Dziewoński)
* MediaWiki theme: Fix background issues with disabled buttons (Roan Kattouw)
* ButtonOptionWidget: Add the TabIndexedElement mixin (Derk-Jan Hartman)
* Remove labelPosition check (Ed Sanders)
* Fix opening/closing animation on windows (Roan Kattouw)
* Add MenuLayout (Ed Sanders)
* Add simpler window#updateSize API (Ed Sanders)

## v0.6.3 / 2015-01-14
* DEPRECATION: LookupInputWidget should no longer be used, instead use LookupElement

* MediaWiki Theme: Adjust toolbar popups' border and shadows (Bartosz Dziewoński)
* MediaWiki Theme: Don't use 'box-shadow' to produce thin grey lines in dialogs (Bartosz Dziewoński)
* demo: Switch the default theme from 'Apex' to 'MediaWiki' (Ricordisamoa)
* Toolbar: Update #initialize docs (Bartosz Dziewoński)
* Add an ActionFieldLayout (Moriel Schottlender)
* dialog: Provide a 'larger' size for things for which 'large' isn't enough (James D. Forrester)
* Synchronize ComboBoxWidget and DropdownWidget styles (Bartosz Dziewoński)
* Replace old&busted LookupInputWidget with new&hot LookupElement (Bartosz Dziewoński)

## v0.6.2 / 2015-01-09
* WindowManager#removeWindows: Documentation fix (Ed Sanders)
* Clear windows when destroying window manager (Ed Sanders)
* MediaWiki theme: Slightly reduce size of indicator arrows (Ed Sanders)
* MediaWiki Theme: Remove text-shadow on  button (Prateek Saxena)
* MediaWiki Theme: Fix focus state for buttons (Prateek Saxena)
* MediaWiki Theme: Fix disabled state of buttons (Prateek Saxena)
* MediaWiki Theme: Fix overlap between hover and active states (Prateek Saxena)
* Make @anchor-size a less variable and calculate borders from it (Ed Sanders)
* PHP LabelElement: Actually allow non-plaintext labels (Bartosz Dziewoński)
* MediaWiki Theme: Add state change transition to checkbox (Prateek Saxena)
* Synchronize @abstract class annotations between PHP and JS (Bartosz Dziewoński)
* Add 'lock' icon (Trevor Parscal)
* Don't test abstract classes (Bartosz Dziewoński)
* Element: Add support for 'id' config option (Bartosz Dziewoński)
* testsuitegenerator.rb: Handle inheritance chains (Bartosz Dziewoński)
* TextInputWidget: Add support for 'autofocus' config option (Bartosz Dziewoński)
* tests: Don't overwrite 'id' attribute (Bartosz Dziewoński)

## v0.6.1 / 2015-01-05
* Remove use of Math.round() for offset and position pixel values (Bartosz Dziewoński)
* Update JSPHP-suite.json (Bartosz Dziewoński)
* ButtonElement: Inherit all 'font' styles, not only 'font-family' (Bartosz Dziewoński)
* FieldsetLayout: Shrink size of label and bump the weight to compensate (James D. Forrester)
* IndicatorElement: Fix 'indicatorTitle' config option (Bartosz Dziewoński)
* Error: Unmark as @abstract (Bartosz Dziewoński)
* build: Update various devDependencies (James D. Forrester)
* readme: Update badges (Timo Tijhof)
* readme: No need to put the same heading in twice (James D. Forrester)

## v0.6.0 / 2014-12-16
* [BREAKING CHANGE] PopupToolGroup and friends: Pay off technical debt (Bartosz Dziewoński)
* ButtonGroupWidget: Remove weird margin-bottom: -1px; from theme styles (Bartosz Dziewoński)
* Prevent parent window scroll in modal mode using overflow hidden (Ed Sanders)
* MediaWiki theme: RadioInputWidget tweaks (Bartosz Dziewoński)
* ClippableElement: Handle clipping with left edge (Bartosz Dziewoński)
* Sprinkle some child selectors around in BookletLayout styles (Roan Kattouw)

## v0.5.0 / 2014-12-12
* [BREAKING CHANGE] FieldLayout: Handle 'inline' alignment better (Bartosz Dziewoński)
* [BREAKING CHANGE] Split primary flag into primary and progressive (Trevor Parscal)
* [BREAKING CHANGE] CheckboxInputWidget: Allow setting HTML 'value' attribute (Bartosz Dziewoński)
* MediaWiki theme: checkbox: Fix states according to spec (Prateek Saxena)
* MediaWiki theme: Add radio buttons (Prateek Saxena)
* MediaWiki theme: Use gray instead of blue for select and highlight (Trevor Parscal)
* MediaWiki theme: Copy .theme-oo-ui-outline{Controls,Option}Widget from Apex (Bartosz Dziewoński)
* MediaWiki theme: Add thematic border to the bottom of toolbars (Bartosz Dziewoński)
* MediaWiki theme: Extract @active-color variable (Bartosz Dziewoński)
* MediaWiki theme: Add hover state to listToolGroup (Trevor Parscal)
* MediaWiki theme: Add state transition to radio buttons (Prateek Saxena)
* MediaWiki theme: Make button sizes match Apex (Trevor Parscal)
* MediaWiki theme: Improve search widget styling (Trevor Parscal)
* build: Use String#slice instead of discouraged String#substr (Timo Tijhof)
* Element.getClosestScrollableContainer: Use 'body' or 'documentElement' based on browser (Prateek Saxena)
* testsuitegenerator: Actually filter out non-unique combinations (Bartosz Dziewoński)
* Fix primary button description text (Niklas Laxström)
* Give non-isolated windows a tabIndex for selection holding (Ed Sanders)
* Call .off() correctly in setButtonElement() (Roan Kattouw)
* RadioInputWidget: Remove documentation lies (Bartosz Dziewoński)
* Don't set line-height of unset button labels (Bartosz Dziewoński)
* Temporarily remove position:absolute on body when resizing (Ed Sanders)
* Kill the escape keydown event after handling a window close (Ed Sanders)
* PopupWidget: Remove box-shadow rule that generates invisible shadow (Bartosz Dziewoński)
* ClippableElement: 7 is a better number than 10 (Bartosz Dziewoński)
* FieldLayout: In styles, don't assume that label is given (Bartosz Dziewoński)
* TextInputWidget: Set vertical-align: middle, like buttons (Bartosz Dziewoński)
* FieldLayout: Synchronise PHP with JS (Bartosz Dziewoński)
* FieldLayout: Use <label> for this.$body, not this.$element (Bartosz Dziewoński)
* Account for <html> rather than <body> being the scrollable root in Chrome (Bartosz Dziewoński)
* GridLayout: Don't round to 1% (Bartosz Dziewoński)
* README.md: Drop localisation update auto-commits from release notes (James D. Forrester)
* README.md: Point to Phabricator, not Bugzilla (James D. Forrester)

## v0.4.0 / 2014-12-05
* [BREAKING CHANGE] Remove deprecated Element#onDOMEvent and #offDOMEvent (Bartosz Dziewoński)
* [BREAKING CHANGE] Make a number of Element getters static (Bartosz Dziewoński)
* [BREAKING CHANGE] Rename BookletLayout#getPageName → #getCurrentPageName (Bartosz Dziewoński)
* demo: Don't put buttons in a FieldsetLayout without FieldLayouts around them (Bartosz Dziewoński)
* IconElement: Add missing #getIconTitle (Bartosz Dziewoński)
* SelectWidget: Rewrite #getRelativeSelectableItem (Bartosz Dziewoński)
* Follow-up I859ff276e: Add cursor files to repo (Trevor Parscal)

## v0.3.0 / 2014-12-04
* [BREAKING CHANGE] ButtonWidget: Don't default 'target' to 'blank' (Bartosz Dziewoński)
* InputWidget: Update DOM value before firing 'change' event (Bartosz Dziewoński)
* TextInputWidget: Reuse a single clone instead of appending and removing new ones (Prateek Saxena)
* build: Have grunt watch run 'quick-build' instead of 'build' (Prateek Saxena)
* MediaWiki Theme: Reduce indentation in theme-oo-ui-checkboxInputWidget (Prateek Saxena)
* Adding DraggableGroupElement and DraggableElement mixins (Moriel Schottlender)
* Remove window even if closing promise rejects (Ed Sanders)
* Fix lies in documentation (Trevor Parscal)

## v0.2.4 / 2014-12-02
* TextInputWidget: Use .css( propertyName, value ) instead of .css( properties) for single property (Prateek Saxena)
* TextInputWidget: Stop adjustSize if the value of the textarea is the same (Prateek Saxena)
* Window: Avoid height flickering when resizing dialogs (Bartosz Dziewoński)
* MessageDialog: Fit actions again when the dialog is resized (Bartosz Dziewoński)

## v0.2.3 / 2014-11-26
* Dialog: Only handle escape events when open (Alex Monk)
* Pass original event with TextInputWidget#enter (Ed Sanders)
* Add missing documentation to ToolFactory (Ed Sanders)
* BookletLayout: Make #focus not crash when there are zero pages or when there is no outline (Roan Kattouw)
* Window: Disable transitions when changing window height to calculate content height (Bartosz Dziewoński)
* MessageDialog: Add Firefox hack for scrollbars when sizing dialogs (Bartosz Dziewoński)
* Fix RadioOptionWidget demos (Trevor Parscal)
* RadioOptionWidget: Remove lies from documentation (Trevor Parscal)
* RadioOptionWidget: Increase rule specificity to match OptionWidget (Bartosz Dziewoński)
* MessageDialog: Actually correctly calculate and set height (Bartosz Dziewoński)

## v0.2.2 / 2014-11-25
* LabelWidget: Add missing documentation for input configuration option (Ed Sanders)
* MessageDialog: Fit actions after updating window size, not before (Bartosz Dziewoński)
* MessageDialog: Use the right superclass (Bartosz Dziewoński)
* ProcessDialog, MessageDialog: Support iconed actions (Bartosz Dziewoński)
* Remove padding from undecorated option widgets (Ed Sanders)
* build: Add .npmignore (Timo Tijhof)

## v0.2.1 / 2014-11-24
* Start the window opening transition before ready, not after (Roan Kattouw)
* Add focus method to BookletLayout (Roan Kattouw)
* Add missing History.md file now we're a proper repo (James D. Forrester)
* README.md: Update introduction, badges, advice (James D. Forrester)
* LabelElement: Kill inline styles (Bartosz Dziewoński)
* composer: Rename package to 'oojs-ui' and require php 5.3.3 (Timo Tijhof)

## v0.2.0 / 2014-11-17
* First versioned release

## v0.1.0 / 2013-11-13
* Initial export of repo
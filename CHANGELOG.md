# 0.1.12

* Announce the split of this package.

# 0.1.11
* Fix exports of `FeatureDiscovery` and `MaterialResponsiveUiData`
  ([issue #63](https://github.com/google/flutter.widgets/issues/63)).

* `VisibilityDetector`:

  * Style and comment adjustments.

  * Fix a potential infinite loop in the demo app and add tests for it.

# 0.1.10
* `LinkedScrollControllerGroup`:

  * Add `LinkedScrollControllerGroup.animateTo` and
    `LinkedScrollControllerGroup.jumpTo` methods that control the scroll
    position of the group.

# 0.1.9

* `ScrollablePositionedList`:

  * Store scroll state in page storage to fix
    [issue #43](https://github.com/google/flutter.widgets/issues/43).

* `LinkedScrollControllerGroup`:

  * Add `LinkedScrollControllerGroup.addOffsetChangedListener` method that calls
    the provided callback when the scroll offset of the group changes.

# 0.1.8

* `ScrollablePositionedList`:

  * Fix padding for horizontal lists.

  * Add `ScrollablePositionedList.separated` constructor to complete
    [issue #34](https://github.com/google/flutter.widgets/issues/34).

  * Add `isAttached` method to `ItemScrollController`.

* `LinkedScrollControllerGroup`:

  * Add getter `offset` that returns the current scroll offset for the group.

# 0.1.7

* Added the `FeatureDiscovery` widget.

* Added the `MaterialResponsiveUiData` class.

* Removed the Gallery app.

* `ScrollablePositionedList`:

  * Properly bound `ScrollablePositionedList` to fix
    [issue #23](https://github.com/google/flutter.widgets/issues/23).

  * Allow `ScrollablePositionedList` alignment outside `[0..1]` to fix
    [issue #31](https://github.com/google/flutter.widgets/issues/31).

  * Moved `ScrollablePositionedList` example into `example` subdirectory.

# 0.1.6

* Added `ScrollablePositionedList`.
* Fixed an incompatibility in `VisibilityDetector` with Flutter 1.9.1
  ([issue #20](https://github.com/google/flutter.widgets/issues/20)).
* Removed dependency on package:intl.

# 0.1.5

* Clarified authors in pubspec.yaml.

* Fixed lint violations of prefer_collection_literals.

* Adjust the minimum versions of dependencies.

# 0.1.4

* `VisibilityDetector`:

  * Fixed positioning of text selection handles for `EditableText`-based
    widgets (e.g. `TextField`, `CupertinoTextField`) when used within a
    `VisibilityDetector`.

  * Added `VisibilityDetectorController.widgetBoundsFor`.

# 0.1.3

* Compatibility fixes for Flutter 1.3.0.

# 0.1.2

* Added `VisibilityDetectorController.forget`.

# 0.1.1

* Add `LinkedScrollContainer` and `VisibilityDetector` widgets.

# 0.1.0

Initial release featuring:

* `html_widget`: Limited support for rendering HTML as flutter widgets.
  currently supports the following tags:
  `div`, `br`, `table`, `b`, `u`, `a`, `font`, `hr`, `text`

* `tagged_text`: Support for styling text using custom HTML-like tags. This is
  particularly useful for styling text within a translated string.

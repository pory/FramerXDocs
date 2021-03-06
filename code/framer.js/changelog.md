# Changelog

## 0.7.7
2018-08-28

### Fixed
- Bug in animation / interpolation API

## 0.7.6
2018-08-28

### Added
- Animation of colors

### Improved
- Importing Design Components in Code
- Animation API has more consistent option handling

### Fixed
- Empty state of Stack component
- Off-pixel rendering of Frame in some cases

## 0.7.5
2018-08-21

### Improved

-   Generic types of `Override`

### Fixed

-   Sorting UI of Stacks

## 0.7.4
2018-08-21

### Added

-   Bezier curve animations

## 0.7.3
2018-08-20

### Added

-   Support for OverrideFunctions for Design Components used in code

### Improved

-   Skip invisible stack items during layout
-   Renamed FusedNumber option splitKey to toggleKey

### Fixed

-   Handling of Animatable properties in Stack
-   Rerun OverrideFunction on rerender

## 0.7.2
2018-08-20

### Improved

-   Fix FrameProperties type of Default Override type

## 0.7.1
2018-08-20

### Improved

-   Made Animatable.set() also accepts Animitable values
-   Default Override type to FrameProperties

## 0.7.0

2018-08-20

### Improved

-   Rename FramerFunction to Override

## 0.6.1

2018-08-16

### Added

* onClick, onMouseDown and onMouseUp as event handlers

### Fixed

* Setting default stack properties in package.json

## 0.6.0

2018-08-16

Bump version to 0.6 to avoid nmp registry conflicts in the future

### Fixed

* Make Stack background transparent by default

## 0.2.0

2018-08-15

### Improved

* Better typing of Data function

## 0.1.34

2018-08-15

### Added

* Added private API for CSS exporting from a component

### Improved

* Cleaned up CSS generation

## 0.1.33

2018-08-15

### Improved

* Made a deprecated PropertyStore available again

## 0.1.32

2018-08-15

### Fixed

* Bug where Animatable transactions would not work well together with ObservableObjects

## 0.1.31

2018-08-14

### Added

* Support for importing Design Components in code

## 0.1.30

2018-08-13

### Improved

* Change boolean control titles `enabled` and `disabled` to `enabledTitle` and `disabledTitle`

## 0.1.29

2018-08-13

### Property Controls

* `unit` type for number inputs \(e.g. %\)
* `step` allows numbers to be floats
* `placeholder` for string inputs
* `hidden` function allows controls to be hidden

## 0.1.28

2018-08-09

### Added

* `Data` function to create observable object that rerenders

### Fixed

* `animate()` function updates objects with multiple Animatable values only once per animation tick

## 0.1.27

2018-08-1

Initial Beta 1 release


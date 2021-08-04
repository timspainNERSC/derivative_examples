# derivative_examples
How to get ElementData to calculate gradients cleanly?

## Purpose
ElementData (see https://github.com/timspainNERSC/shallowwater) needs to be able to calculate gradients in a clean way. The algorithm needs to be as DRY as possible, clear to future maintainers and not use too much advanced C++ black magick.

## License
If any of the examples here are of any use to anyone, anywhere, they are free to use the code in any conceivable way.

## Implementations
1. Three objects enter, one derivative leaves.
2. Indirection and enumeration.

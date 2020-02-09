# StepValidator

Validate recipe steps.

``` swift
public struct StepValidator: ValidatorHelper
```

Tests:

  - Non-unique sort order: each step should have a unique sort-order
    integer.

<!-- end list -->

  - No text: need to add step text.

<!-- end list -->

  - Incorrect spelling: checks for British spelling of some common
    words.

## Inheritance

[`ValidatorHelper`](ValidatorHelper)

## Nested Types

[`StepValidator.Error`](StepValidator_Error)

# RecipeValidator

Validate recipes.

``` swift
public struct RecipeValidator: ValidatorHelper
```

Tests:

  - Invalid prep time: should be multiple of 5.

<!-- end list -->

  - No courses: a recipe should have at least one course record.

<!-- end list -->

  - Incorrect spelling: checks for British spelling of some common
    words.

## Inheritance

[`ValidatorHelper`](ValidatorHelper)

## Nested Types

[`RecipeValidator.Error`](RecipeValidator_Error)

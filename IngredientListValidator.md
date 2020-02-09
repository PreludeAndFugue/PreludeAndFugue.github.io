# IngredientListValidator

Validate recipe ingredient lists.

``` swift
public struct IngredientListValidator: ValidatorHelper
```

Tests:

  - Non-unique sort order: each ingredient list should have a unique
    sort-order integer value.

<!-- end list -->

  - No ingredient lists in recipe: a recipe should have at least one
    ingredient list.

## Inheritance

[`ValidatorHelper`](ValidatorHelper)

## Nested Types

[`IngredientListValidator.Error`](IngredientListValidator_Error)

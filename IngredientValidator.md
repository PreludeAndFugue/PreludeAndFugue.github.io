# IngredientValidator

Validate recipe ingredients.

``` swift
public struct IngredientValidator: ValidatorHelper
```

Tests:

  - Missing prep instruction: have used a prep instruction for this recipe
    ingredient, but the common ingredient doesn't have a record for this
    prep ingredient.

<!-- end list -->

  - Invalid ingredient unit: the ingredient unit must match the common
    ingredient nutrition unit so that the recipe macros can be calculated
    correctly.

## Inheritance

[`ValidatorHelper`](ValidatorHelper)

## Nested Types

[`IngredientValidator.Error`](IngredientValidator_Error)

# CommonIngredientValidator

Validate common ingredients.

``` swift
public struct CommonIngredientValidator: ValidatorHelper
```

Tests:

  - Invalid category: make sure category 0 is not used.

<!-- end list -->

  - Invalid shopping aggregate unit: should be gram, ml, item, clove,
    spear, stick, slice, or piece.

<!-- end list -->

  - Invalid conversion pair: both quantity and unit should be either
    empty or non-empty.

<!-- end list -->

  - Invalid nutrition quantity: both quantity and unit should be
    non-empty.

<!-- end list -->

  - Matching allergen: an allergen cannot be both *major* and *minor*.

<!-- end list -->

  - Unused: the common ingredient is not used in any recipes.

<!-- end list -->

  - Invalid macros: 4\*(netCarbs + Protein) + 9\*Fat is more than 5%
    different to the calories value.

## Inheritance

[`ValidatorHelper`](ValidatorHelper)

## Nested Types

[`CommonIngredientValidator.Error`](CommonIngredientValidator_Error)

## Properties

## validShoppingAggregateUnitIds

``` swift
let validShoppingAggregateUnitIds: Set<Int> = [
        // gram
        13,
        // ml
        12,
        // item
        30,
        // clove
        17,
        // spear
        25,
        // stick
        9,
        // slice
        4,
        // piece
        33
    ]
```

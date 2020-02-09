# Validator

The main validator.

``` swift
public struct Validator
```

## Nested Types

[`Validator.Recipe`](Validator_Recipe)

## Properties

## debugDescription

``` swift
var debugDescription: String
```

## debugDescription

``` swift
var debugDescription: String
```

## debugDescription

``` swift
var debugDescription: String
```

## debugDescription

``` swift
var debugDescription: String
```

## Methods

## makeRecipes(data:)

``` swift
func makeRecipes(data: CSVModel) -> [Recipe]
```

## makeCommonIngredients(data:)

``` swift
func makeCommonIngredients(data: CSVModel) -> [CommonIngredient]
```

## validate(data:)

``` swift
private func validate(data: CSVModel) -> [ValidatorError]
```

## errorSort(lhs:rhs:)

``` swift
func errorSort(lhs: ValidatorError, rhs: ValidatorError) -> Bool
```

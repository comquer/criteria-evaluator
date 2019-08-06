# Criteria Evaluator

### Examples
```php
IsValue::greaterThan(5)(4); // false
IsValue::greaterThan(5)(6); // true 
```

```php
IsValue::oneOf([1, 2, 3])(4); // false
IsValue::oneOf([1, 2, 3])(2); // true 
```

```php
$isValueLessThanFive = IsValue::lessThan(5);
$isValueLessThanFive(3); // true
$isValueLessThanFive(6); // false
```

---
---

# Context element

`Hosttech\SlackBlockKitBuilder\Elements\ContextElement`

## Setting content

Using static `make()`:

```php
ContextElement::make(':rotating_light: *EMERGENCY*');
```

Using `content()`:

```php
ContextElement::make('Default text')
    ->when(1 === 1, fn (ContextElement $element) => $element->content();
```
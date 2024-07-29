---
---

# Action element

`Hosttech\SlackBlockKitBuilder\Elements\ActionElement`

## Setting url

Using static `make()`:

```php
ActionElement::make('https://google.com');
```

Using `url()`:

```php
ActionElement::make(null)
    ->when(1 == 1, fn (ActionElement $element) => $element->url('https://google.com'));
```

## Setting button content

Using `content()`:

```php
ActionElement::make(null)
    ->content('https://google.com');
```
---
sidebar_position: 5
---

# Text element

`Hosttech\SlackBlockKitBuilder\Elements\RichText\RichTextItemTextElement`

## Setting bold / italic

Set bold using `bold()`:

```php
RichTextItemTextElement::make('Hello world')
    ->bold(); // text will be displayed in bold
```

Set italic using `italic()`:

```php
RichTextItemTextElement::make('Hello world')
    ->italic(); // text will be displayed in italic
```
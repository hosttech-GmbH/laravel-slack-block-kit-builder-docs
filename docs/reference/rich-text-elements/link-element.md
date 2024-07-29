---
sidebar_position: 6
---

# Link element

`Hosttech\SlackBlockKitBuilder\Elements\RichText\RichTextItemLinkElement`

## Setting bold / italic

Set bold using `bold()`:

```php
RichTextItemLinkElement::make('https://google.com')
    ->content('Hello world')
    ->bold(); // text will be displayed in bold
```

Set italic using `italic()`:

```php
RichTextItemLinkElement::make('https://google.com')
    ->content('Hello world')
    ->italic(); // text will be displayed in italic
```
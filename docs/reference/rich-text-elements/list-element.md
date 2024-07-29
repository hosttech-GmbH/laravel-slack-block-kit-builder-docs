---
sidebar_position: 2
---

# List element

`Hosttech\SlackBlockKitBuilder\Elements\RichText\RichTextListElement`

## Allowed elements

- [Section element](/docs/reference/rich-text-elements/section-element.md)

## Setting indent / border / offset

Set indent using `indent()`:

```php
RichTextListElement::make()
    ->indent(5); // fifth level indentation
```

Set border width using `border()`:

```php
RichTextListElement::make()
    ->border(5); // border will be 5px wide
```

Set offset using `offset()`:

```php
RichTextListElement::make()
    ->offset(5); // list items will be offset by 5px
```
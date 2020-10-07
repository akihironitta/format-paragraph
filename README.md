# format-paragraph: A Japanese Paragraph Formatter

## Example
Original text:
```txt
これはtestです。format-paragraphはこのようなテキストを読みやすくします。英数字(0, 1, 2, ...)や記号の間にはスペースが挿入されます。また一行に長い場合は改行が挿入されます。
```

Formatted text:
```txt
これは test です。 format-paragraph はこのようなテキストを
読みやすくします。英数字 (0, 1, 2, ...) や記号の間にはスペースが
挿入されます。また一行に長い場合は改行が挿入されます。
```

## Functions
### `format-region-as-paragraph`
Format Japanese paragraph in the selected region.

### `format-paragraph`
Format Japanese paragraph around the current point by using `format-region-as-paragraph`.

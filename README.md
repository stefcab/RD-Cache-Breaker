# RD Cache Breaker

![supports ExpressionEngine 3](https://img.shields.io/badge/ExpressionEngine-3-3784B0.svg) ![supports ExpressionEngine 4](https://img.shields.io/badge/ExpressionEngine-4-3784B0.svg)

ExpressionEngine 3 and 4 compatible. Appends the last modified time (unix timestamp) to the specified file:

```html
<link href="{exp:rd_cache_breaker file='/path/to/file' separator='?'}" rel="stylesheet" />
```

This plugin will determine the time that the file was last modified and append that unix timestamp to the file path using the separator, like so:

```html
<link href="/path/to/file?1234567890" rel="stylesheet" />
```
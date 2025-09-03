# Anonymous Redirect / Referrer

Very simple HTML page that is used for anonymous redirect.

Thanks to [Referrer-Policy](https://www.w3.org/TR/referrer-policy/), redirected request will have no referrer at all.
Please note, that Referrer-Policy [is not supported](caniuse.com/#feat=referrer-policy) by IE11.

## Usage

```
https://redirect.trace.rip/?url=[PUT URL HERE]
```

## Examples

https://redirect.trace.rip/?url=https://whatsmyreferer.com/

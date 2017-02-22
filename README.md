# slimerjs-render-stream

This is fork of famous @sorribas lib https://github.com/sorribas/phantom-render-stream.

The only difference, it uses slimerjs instead of phantomjs, to handle problems with webgl renders.
So if you don't intend to render heavy graphics, skip this module and use original module.

Headless version runs only on linux with firefox =< 50 installed.
See slimerjs.org for details

slimerjs should be installed globally

```
npm install -g slimerjs
```
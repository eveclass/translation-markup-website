---
home: true
heroImage: /assets/translation-markup.png
actionLink: /sobre/introducao
features:
  - title: Scalable (and faster)
    details: Type each translation key only once. No more searching and scrolling across files for the right spot and keys.
  - title: Cleaner (and faster)
    details: No more braces and quotes, type faster and keep the file clearner with YAML.
  - title: Keep it Simple
    details: Stop organizing translation files by language and start organizing them by feature, module or the way you see fit.
footer: MIT Licensed | Copyright © 2019 Shift Code
---

<!-- <div style="margin-top:15px;margin-bottom:15px;border-bottom: 1px solid #eaecef;"></div> -->

## What is?

Writing JSON based translations? Managing multiple files, adding keys everywhere, that’s boring.. that’s harsh! You shouldn’t have to do that. You won’t, not anymore!

Translation Markup is a markup language which is intended to have it's translations compiled to `JSON` or `JS` files, with the same structure most `i18n` libs require.

## How it works?

It works through a compiler that takes `translation-markup` files as input and outputs `JSON` or `JS` files that can be read by mosts `i18n` libraries out there in the wild.

## Why should I use it?

Question is, why wouldn't you? The benefits are mostly two: translations become faster to write and much more maintainable. But the latter reason is the greatest.

If you ever worked on a medium sized application with `JSON` translations files, I'm sure you're familiar with the pain of hunting the keys you want to edit across files with innumerous lines. With Translation Markup that's past. All translations goes in the same key. The key is written only once.

Besides that, there is no more `JSON` boilerplate. You get to write translations in `YAML` language. If your not familiar with it, that's actually no problem at all, it's really simple to understand and it's usage for `translation-markup` is really on the basics level.

## Give me some code!

The example bellow takes as input a `translations.lang.yaml` file which we've written, containing our app's translations. Running the compiler will output 3 `JSON` files: `en.json`, `pt.json` and `es.json`, each one with it's own translations in the default "key-value" structure. Having those files, just read them with whichever `i18n` library you want!

![Translation Markup Example](/assets/tm-example.png)

## More examples?

Sure, [click here](/examples/input-output-examples.html) to have a glimpse of what you can achieve.

## Great! So how do I use it?

You can use the compiler with `Node`, in the terminal with the `CLI`, or with the `webpack-loader`.

| Library                   | Usage                     | Github Link                                                                                                        |
| ------------------------- | ------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| Compiler - Node & CLI     | Use with `Node` or `CLI`. | [https://github.com/shift-code/translation-markup](https://github.com/shift-code/translation-markup)               |
| Compiler - Webpack Loader | Use with `Webpack`.       | [https://github.com/shift-code/translation-markup-loader](https://github.com/shift-code/translation-markup-loader) |

# Bulgarian Phonetic macOS keyboard layout with a sprinkle of Ukranian

The keyboard is an exact copy of the Bulgarian Phonetic layout with a couple of modifier key additions.

* [alt/option + i] = і
* [alt/option + y] = ї
* [alt/option + e] = є
* [alt/option + g] = ґ

## Installation

You need [kbdgen](https://github.com/divvun/kbdgen) in order to generate the macOS layout installer.

When you have installed `kbdgen` just run the following line (it will run *only on macOS*):

```sh
kbdgen target -b <path_to_bg-ua.kbdgen> -o <output_path_for_layout> macos generate
```

In the ouput path specified by you, you would find a `.bundle` file that you can copy to `~/Library/Keyboard Layouts`.

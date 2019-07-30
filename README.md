# Bulgarian Phonetic macOS keyboard layout with a sprinkle of Ukranian

The keyboard is an exact copy of the Bulgarian Phonetic layout with a couple of modifier key additions.

* [alt/option + i] = і
* [alt/option + y] = ї
* [alt/option + e] = є

## Installation

You need [kbdgen](https://github.com/divvun/kbdgen) in order to generate the macOS layout installer. 

When you have installed `kbdgen` just run the following line (it will run *only on macOS*):

```sh
kbdgen -t osx -o <installer_output_path> <path_to_kbdgen-project.yaml>
```

In the specified `<installer_output_path>` you'll see an unsigned pkg file, which is basically your installer for the macOS layout. Just run that and follow the installation steps.

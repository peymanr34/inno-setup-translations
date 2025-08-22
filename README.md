# Inno Setup Translations

A collection of Farsi (Persian) translations for Inno Setup 6.1.0+

## Available Versions

| Inno Setup Version          | Encoding       | Translator                                       |
| --------------------------- | -------------- | ------------------------------------------------ |
| [v6.1.0](v6.1.0/Farsi.isl)  | UTF-8 with BOM | [Peyman Mohammadi](https://github.com/peymanr34) |
| [v6.4.0](v6.4.0/Farsi.isl)  | UTF-8          | [Peyman Mohammadi](https://github.com/peymanr34) |
| [v6.5.0](v6.5.0/Farsi.isl)  | UTF-8          | [Peyman Mohammadi](https://github.com/peymanr34) |

## Downloading

You can download the latest translations via the official [Inno Setup Translations][official-translations] page.

## Using the Translations

- Download the `Farsi.isl` file from the [official website][official-translations] or this repository.
- Copy the `Farsi.isl` to the same directory as your script file.
- Then add the following lines to your script.

```
[Languages]
Name: en; MessagesFile: "compiler:Default.isl"
Name: fa; MessagesFile: "Farsi.isl"
```

## License

This project is licensed under the [MIT License](LICENSE).

[official-translations]: https://jrsoftware.org/files/istrans
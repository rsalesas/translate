# translate.swift

`translate.swift` is a command-line utility for translating XCode localization strings files using OpenAI's ChatGPT. The script takes an input strings file, translates the text inside the quotes before the equal sign, and outputs the translated strings file with the same format.

This tool is useful for developers looking to quickly generate localized versions of their iOS/Mac apps in different languages using a powerful AI model. The translations provided by ChatGPT are often more accurate and natural-sounding than traditional machine translation systems.

## Features

- Translates XCode localization strings files using ChatGPT
- Supports any language supported by ChatGPT
- Preserves the original format of the input strings file

## Prerequisites

- Swift programming language installed on your system
- An OpenAI API key with access to ChatGPT

## Usage

1. Clone this repository or download the `translate.swift` script to your local machine.
2. Make sure the script is executable by running `chmod +x translate.swift` in your terminal.
3. Execute the script by providing the required arguments:

```bash
./translate.swift <api_key> <language_code> <input_file> <output_file>
```

- `<api_key>`: Your OpenAI API key for accessing ChatGPT
- `<language_code>`: The two-character language code for the target language (e.g., "es" for Spanish, "fr" for French)
- `<input_file>`: The path to the input strings file you want to translate
- `<output_file>`: The path to the output file where the translated strings will be saved

Example:

```bash
./translate.swift abcd1234xyz es Localizable.strings Localizable_es.strings
```

This command will translate the contents of `Localizable.strings` to Spanish and save the translated strings in `Localizable_es.strings`.

## Important Notes

- The quality of the translations may vary depending on the target language and the specific text being translated. Always review the translated strings to ensure accuracy and proper context.
- Be aware of any API usage limits or costs associated with your OpenAI API key.

## Contributing

If you have any suggestions, bug reports, or feature requests, feel free to open an issue or submit a pull request.

## License

This project is open-source and available under the MIT License.


## Notes

Please let me know if you need any adjustments or further information added to the README.

It's not the cleanest code. You can no doubt guess why.

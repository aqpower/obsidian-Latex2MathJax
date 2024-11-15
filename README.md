# Latex2MathJax Plugin for Obsidian

When you copy math content from large language models (like ChatGPT), the formulas are typically provided in LaTeX format. However, Obsidian supports MathJax, and this plugin will **automatically convert the LaTeX formulas into MathJax format** when pasted into your notes.


## Features

- **Automatic Replacement on Paste:**  
  Automatically replaces LaTeX math delimiters when content is pasted into the editor.
  
- **Manual Replacement:**  
  Use commands to replace LaTeX math delimiters in selected text or the entire document.


## Installation

1. Go to the Release page ([https://github.com/aqpower/obsidian-Latex2MathJax/releases](https://github.com/aqpower/obsidian-Latex2MathJax/releases)) and download the latest version of the plugin in `zip` format.
2. Extract the downloaded plugin files and place them into Obsidian's plugin folder `.obsidian/plugins`.
3. Reload Obsidian, then enable the plugin in the Third-party Plugins section.

## Example

- **LaTeX input**:  
  `\(\frac{a}{b}\)`
  
- **MathJax output**:  
  `$\frac{a}{b}$`

## Configuration

You can configure the plugin from the settings panel in Obsidian.

1. Open **Settings** in Obsidian.
2. Go to **Latex2MathJax Plugin**.
3. Toggle the option **Enable automatic replacement** to turn the feature on or off.

## License

This plugin is open-source and available under the [MIT License](LICENSE).


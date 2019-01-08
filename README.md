# Moodle - snippets & autocomplete

This extension for Visual Studio Code adds Moodle v. 3.4.6 snippets and autocompletion of functions, classes.

## Features

Snippets for all methods for GLOBAL variables:

- `$OUTPUT`

Snippets for all methods from:

- `lib/moodlelib.php`

Also there are some snippets for file comments.

## Usage

Type part of snippet, press `Tab` or `Enter`, and the snippet unfolds. Below is a list of the most important shortcuts.

### Comments Snippets

| Snippet | Purpose                                           |
| ------- | ------------------------------------------------- |
| `cfa`   | Comment block with author of this file for Moodle |
| `cfm`   | Moodle file comment block                         |

### `$OUTPUT` Snippets

| Snippet | Purpose                               |
| ------- | ------------------------------------- |
| `$Of`   | `$OUTPUT->footer();`                  |
| `$Oh`   | `$OUTPUT->header();`                  |
| `$Opi`  | `$OUTPUT->pix_icon(...);`             |
| `$Opu`  | `$OUTPUT->pix_url(...);`              |
| `$Orft` | `$OUTPUT->render_from_template(...);` |

### `moodlelib.php` Snippets

| Snippet | Purpose                  |
| ------- | ------------------------ |
| `cl`    | `current_language(...);` |
| `gs`    | `get_string(...);`       |
| `op`    | `optional_param(...);`   |
| `rl`    | `require_login(...)`     |
| `rp`    | `required_param(...);`   |

## Requirements

VSCode 1.30.0

## Release Notes

### 1.0.0

- Initial release

## License

[GPLv3](./LICENSE)

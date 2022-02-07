# docums-plugin-template

This is a template for a Docums plugin.

## Setup

Install the plugin using pip:

`pip install docums-your-plugin-name`

Activate the plugin in `docums.yml`:
```yaml
plugins:
  - search
  - your-plugin-name
```

> **Note:** If you have no `plugins` entry in your config file yet, you'll likely also want to add the `search` plugin. Docums enables it by default if there is no `plugins` entry set, but now you have to enable it explicitly.

More information about plugins in the [Docums documentation][docums-plugins].

## Config

* `param` - This does something

## Usage

## See Also

More information about templates [here][docums-template].

More information about blocks [here][docums-block].

[docums-plugins]: http://khanhduy1407.github.io/docums/user-guide/plugins/
[docums-template]: https://khanhduy1407.github.io/docums/user-guide/custom-themes/#template-variables
[docums-block]: https://khanhduy1407.github.io/docums/user-guide/styling-your-docs/#overriding-template-blocks

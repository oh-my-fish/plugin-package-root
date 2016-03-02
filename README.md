<img src="https://cdn.rawgit.com/oh-my-fish/oh-my-fish/e4f1c2e0219a17e2c748b824004c8d0b38055c16/docs/logo.svg" align="left" width="144px" height="144px"/>

#### package-root
> Autoload package root directoryies.

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE)
[![Fish Shell Version](https://img.shields.io/badge/fish-v2.2.0-007EC7.svg?style=flat-square)](http://fishshell.com)
[![Oh My Fish Framework](https://img.shields.io/badge/Oh%20My%20Fish-Framework-007EC7.svg?style=flat-square)](https://www.github.com/oh-my-fish/oh-my-fish)

<br/>

Oh My Fish package directory structure works as follows:

    - package-name
      + functions
      + completions
      + init.fish

By default Oh My Fish adds only `package-name/functions` directory to `fish_function_path`. This plugin allows you to also add packages root directories into `fish_function_path`.

## Install

```fish
$ omf install package-root
```

# License

[MIT][mit] © [Derek Stavis][author] et [al][contributors]


[mit]:            http://opensource.org/licenses/MIT
[author]:         http://github.com/derekstavis
[contributors]:   https://github.com/oh-my-fish/plugin-package-root/graphs/contributors
[omf-link]:       https://www.github.com/oh-my-fish/oh-my-fish

[license-badge]:  https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square

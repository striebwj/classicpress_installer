
# ClassicPress Installer

Installing [ClassicPress](https://www.classicpress.net) using [Composer](https://getcomposer.org/).

## Usage/Installation
First, download the ClassicPress installer using Composer:
```
composer global require striebwj/installer
```

Make sure to place Composer's system-wide vendor bin directory in your $PATH so the laravel executable can be located by your system. This directory exists in different locations based on your operating system; however, some common locations include:

- macOS and GNU / Linux Distributions: `$HOME/.config/composer/vendor/bin`
- Windows: `%USERPROFILE%\AppData\Roaming\Composer\vendor\bin`

Once installed, the `classicpress new` command will create a fresh ClassicPress installation in the directory you specify.

For instance, `classicpress new blog` will create a directory named blog containing a fresh ClassicPress installation:

```
classicpress new blog
```


### To Do
 - [ ] Dynamically get the latest version of ClassicPress
 - [ ] Make use of the `-dev` flag to install the latest nightly release

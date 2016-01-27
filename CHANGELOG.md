Northem Dark Atom Syntax
========================

## 0.13.0 (2016-01-27)
### Features
  - Implemented language support for [SQL](https://atom.io/packages/language-sql)

## 0.12.0 (2016-01-24)
### Features
  - Implemented language support for [C++](https://atom.io/packages/language-c) (Related external issues: [northem-light-atom-syntax](https://github.com/arcticicestudio/northem-light-atom-syntax) [#2](https://github.com/arcticicestudio/northem-light-atom-syntax/issues/2))

## 0.11.2 (2015-10-04)
### Bug Fixes
#### Package Support
  * Fixed background color for `markdown-preview` codeblocks

## 0.11.1 (2015-10-01)
### Bug Fixes
#### Package Support
  * Fixed deprecation warning of outdated `.editor` class

## 0.11.0 (2015-09-27)
### Added
#### Package Support
  * Implemented support for [color-picker](https://atom.io/packages/color-picker)

### Updated
#### Documentation
  * Added a list of supported packages and the corresponding version range

### Changed
#### Package Support
  * Code elements are now colored `light-blue` in the preview of the [markdown-preview](https://atom.io/packages/markdown-preview) package

### Bug Fixes
#### Package Support
  * Fixed the background color for code blocks of the [markdown-preview](https://atom.io/packages/markdown-preview) package

## 0.10.1 (2015-09-24)
### Bug Fixes
  * Fixed basic color variable names caused a crash on theme loading

## 0.10.0 (2015-09-24)
### Added
#### Languages
  * Implemented support for language [Generic Config (dotfiles)](https://atom.io/packages/language-generic-config)
    All files containing comments and/or non-comments without a particular structure like
      * .gitignore
      * .env
  * Implemented support for language [git](https://atom.io/packages/language-git)
    This includes:
      * Git Commit Messages (`COMMIT_EDITMSG`,`MERGE_MSG`)
      * Git Configuration `.gitconfig`,`.gitmodules`,`.git/config`,`/etc/gitconfig`)
      * Git Rebase Messages
  * Implemented support for language [PropertyList](https://atom.io/packages/language-property-list)
    Formats:
      * _ASCII_ (Old-Style)
      * _XML_

## 0.9.1 (2015-09-13)
### Updated
#### Languages
  * `Jade` changes to better distinguish from `HTML` tags:
    * Control Keywords (`if`, `each`, `unless` etc.) now highlighted in `dark-blue` instead of `blue`
    * Embedded JavaScript block & line indicators (`- var`, `script.` etc.) now highlighted in `dark-blue` instead of `blue`
    * Inline-Tags & Control-Flows (`#[]`, `#{}`) now highlighted in `dark-blue` instead of `blue`
    * Preprocessor Keywords (`block`, `append`, `prepend`, `include` etc.) now highlighted in bolded `dark-blue` instead of `blue`

## 0.9.0 (2015-08-29)
### Added
#### Languages
  * Implemented support for language [`C`](https://atom.io/packages/language-c)
  * Implemented support for language [`Clojure`](https://atom.io/packages/language-clojure)
  * Implemented support for language [`CS` (`C#`)](https://atom.io/packages/language-csharp)

### Updated
#### Languages
  * `language-haskell`@`1.4.0`:
    * Now supports highlighting for _tags_ and `runhaskell`-shebang

## 0.8.0 (2015-08-16)
### Added
#### Languages
  * Implemented support for language [`D`](https://atom.io/packages/language-d)

## 0.7.0 (2015-08-16)
### Added
#### Languages
  * Implemented support for language [`GLSL`](https://atom.io/packages/language-glsl)
  * Implemented support for language [R](https://atom.io/packages/language-r)

### Bug Fixes
### Documentation
  * Fixed hyperlink of the Northem logo in `README.md`

## 0.6.0 (2015-08-12)
### Added
#### Languages
  * Implemented support for language [`HAML`](https://atom.io/packages/language-haml)

## 0.5.0 (2015-08-08)
### Added
#### Languages
  * Implemented support for language [`Java`](https://atom.io/packages/language-java)

## 0.4.0 (2015-08-02)
### Added
#### Languages
  * Implemented support for language `Haskell`
#### Essentials
  * Now using `Apache Ant` for build automation and deploying
### Bug Fixes
#### Documentation
  * Fixed favicon sizes in `README.md`
  * Fixed missing notice for [`file-icons`](https://atom.io/packages/file-icons) package in [`README.md`](README.md)
### Changed
#### Dependencies
  * Bumped `arcver`@`0.5.0`

## 0.3.1 (2015-06-05)
### Bug Fixes
  * Fixed missing `@color-syntax-type` (thanks to @xiaokekeT) and `@color-syntax-macro`
  * Fixed missing changelog for version 0.3.0

## 0.3.0 (2015-06-05)
### Added
  * Support for:  
    * [Julia](https://atom.io/packages/language-julia)
    * [Shell](https://atom.io/packages/language-shellscript)

### Incidental
  * Added link to recently released 'Northem Light Atom Syntax'

## 0.2.1 (2015-05-24)
* Fix some cosmetics for package description on atom.io registry

## 0.2.0 (2015-05-24) - APM Release
* apm package release

## 0.1.0 (2015-05-23) - First Release
* Initial release

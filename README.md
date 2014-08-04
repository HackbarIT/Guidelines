# Organization Guidelines

## Table of Contents
* [Common Files in Repositories](#commonfilesinrepositories)
    * [LICENSE](#license)
    * [README.md](#readmemd)
    * [CONTRIBUTORS](#contributors)
    * [.editorconfig](#editorconfig)
* [Code-Formatting](#code-formatting)
    * [language-specific formatting](language-specific/README.md)
* [Folderstructur (proposal)](#folderstructur-proposal)


---


### Common Files in Repositories
* required:
    * [LICENSE](#license)
* recommended:
    * [README.md](#readmemd)
    * [CONTRIBUTORS](#contributors)
    * [.editorconfig](#editorconfig)

#### LICENSE
* the complete license of the project
* every file that should be licensed with this must contain a reference to the LICENSE-file AND/OR the README.md must have licensing information
* we recommend our customized ISC-license (see [example](examples/LICENSE))

#### README.md
* what the project is about
* how the project should be used
* who is the maintainer of the project
* how the whole project/certain files/etc. is licensed
* formatted with Markdown

#### CONTRIBUTORS
* containing these things:
    * required:
        * contributor name(s)
        * date(s) of contribution(s)
        * summary of contribution(s)
    * optional:
        * email address
        * comment from contributor
* see [example](examples/CONTRIBUTORS)

#### .editorconfig
* contains formatting instructions for editors
* see [EditorConfig](http://editorconfig.org/)

---

### Code-Formatting
* use [Semantic Versioning](http://semver.org/)
* unix-style line-endings
* charset: UTF-8
* new line at the end of files
* indentation: tabs if possible, 4 spaces if not
* single-quotes
* no trailing whitespace
* no break before braces:
```cpp
int main() {
    if (3 > 2) {
            // many code. such quality. wow
    }
}
```

see [language-specific formatting](language-specific/README.md) for details

---

### Folderstructur (proposal)
* libs - contains library dependencies
* deps - contains other dependencies
* doc - contains documentation
* build - empty directory for (temporary) files created during buildprocess, etc.
* src - contains the source of this project

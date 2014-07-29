# Organization Guidelines

## Content
* [Common Files in Repositories](#commonfilesinrepositories)
* [Code-Formatting](#code-formatting)
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
* every file that should be licensed with this must contain a reference to the LICENSE-file
* we recommend our [customized ISC-license](https://github.com/HackbarIT/Guidelines/blob/master/LICENSE.md)
* see [example](https://github.com/HackbarIT/Guidelines/blob/master/examples/LICENSE)

#### README.md
* what the project is about
* how the project should be used
* who is the maintainer of the project
* formatted with Markdown

#### CONTRIBUTORS
* containing these things:
    * required:
        * contributor name(s)
        * date(s) of contribution(s)
        * summary of contribution(s)
    * optional:
        * comment from contributor
* see [example](https://github.com/HackbarIT/Guidelines/blob/master/examples/CONTRIBUTORS)

#### .editorconfig
* contains formatting instructions for editors
* see [EditorConfig](http://editorconfig.org/)



### Code-Formatting
* unix-style line-endings
* charset: UTF-8
* new line at the end of files
* indentation: 4 spaces
* no trailing whitespace



### Folderstructur (proposal)
* libs - contains binary dependencies
* deps - contains source dependencies
* doc - contains documentation
* build - empty directory for (temporary) files created during buildprocess, etc.

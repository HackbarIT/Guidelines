# Guidelines for all projects of this organization


## Contents of Repositories
* required:
    * [LICENSE](#license)
* recommended:
    * [README.md](#readmemd)
    * [CONTRIBUTORS](#contributors)
    * [.editorconfig](#editorconfig)

#### LICENSE
* the complete license of the project
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


## Code-Formatting
* unix-style line-endings
* charset: UTF-8
* new line at the end of files
* indentation: 4 spaces
* no trailing whitespace

## folderstructur (proposal)
* libs - contains binary dependencies
* deps - contains source dependencies
* doc - contains documentation
* build - empty directory for (temporary) files created during buildprocess, etc.

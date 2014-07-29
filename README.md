# Guidelines for all projects of this organization

## Contents of Repositories
* required:
    * [LICENSE](#license)
* recommended:
    * [README.md](#readmemd)
    * [CONTRIBUTORS](#contributors)
    * [.editorconfig](#editorconfig)

#### LICENSE
* the complete license of the project in this format:
Copyright (c) {year} {author} {mail}
{license text}
* we recommend our [customized ISC-license](https://github.com/HackbarIT/Guidelines/blob/master/LICENSE.md)

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
* formated like this:
    * single contribution:
        > John Doe
        >     Date: 17.05.2014
        >     Summary: changed the README.md
        >     Comment: greetings to my mother \o

    * multiple contributions:
        > Jane Doe
        >     Date: 23.08.2014
        >     Summary: added example #1
        >
        >     Date: 24.08.2014
        >     Summary: added example #2
        >     Comment: 2 examples are better then 1

#### .editorconfig
* contains formatting instructions for editors
* see [EditorConfig](http://editorconfig.org/)


## Code-Formatting
* unix-style line-endings
* charset: UTF-8
* new line at the end of files
* indentation: 4 spaces
* no trailing whitespace

## folderstructur ()
* libs - contains binary dependencies
* deps - contains source dependencies
* doc - contains documentation
* build - empty directory for (temporary) files created during buildprocess, etc.
*

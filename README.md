# GantSign Code Style Configuration

[![Build Status](https://travis-ci.org/gantsign/code-style-intellij.svg?branch=master)](https://travis-ci.org/gantsign/code-style-intellij)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/gantsign/code-style-intellij/master/LICENSE)

Code Style Configuration for code written by GantSign using
[IntelliJ IDEA](https://www.jetbrains.com/idea/).

# About

This project contains two code styles:

* GantSign.xml

    The original GantSign IntelliJ Code Style; custom code style focusing on
    readability and minimizing version control changes.

    The indent is 2 spaces (rather than 4) to make functional style code more
    readable (functional code often has deeper levels of nesting).

    Mandatory line wrapping for enum/array values and implements/extends/throws
    lists both aids readability and minimizes the scope of version control
    changes.

    Continuation indents are fixed rather than aligned with parentheses to
    eliminate unnecessary version control changes.

    Line wrapping by the developer is preserved so the developer can manually
    layout the code for better readability.

* GantSign2.xml

    The goals of `GantSign2.xml` are to avoid bikeshedding and to enable
    automated code reformatting as part of the build.

    * Java

        * based on the [Google Code Style](https://raw.githubusercontent.com/google/styleguide/gh-pages/intellij-java-google-style.xml)
        * compatible with the [fmt-maven-plugin](https://github.com/coveo/fmt-maven-plugin)
          code formatter

    * Kotlin

        * based on the [Kotlin Style Guide](https://kotlinlang.org/docs/reference/coding-conventions.html)
          with some additions from [ktlint](https://github.com/shyiko/ktlint)
        * compatible with the [ktlint](https://github.com/shyiko/ktlint)
          code formatter

    * JavaScript

        * based on the [JavaScript Standard Style](https://standardjs.com/)
        * compatible with the [standard --fix](https://standardjs.com/)
          code formatter

    * Other files

        * based on the [Google Code Style](https://raw.githubusercontent.com/google/styleguide/gh-pages/intellij-java-google-style.xml)

## License

This software is licensed under the terms in the file named "[LICENSE](LICENSE)"
in the root directory of this project.

## Author Information

John Freeman

GantSign Ltd.
Company No. 06109112 (registered in England)

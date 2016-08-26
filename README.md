# iOS Snippets

Collection of snippets for iOS/macOS development. To install this extension, launch VS Code Quick Open (⌘+P), paste ``ext install ios-snippets`` and press enter.

## Swift

* Classes, Protocols, Enums, and Structs
  * ``class`` - Swift Class
  * ``class-subclass`` - Swift Subclass
  * ``protocol`` - Swift Protocol
  * ``struct`` - Swift Struct
  * ``extension`` - Swift Extension
  * ``enum`` - Swift Enumerated Type Declaration

* Misc
  * ``func`` - Swift Function Statement
  * ``mark`` - Mark (``// MARK: - ...``)
  * ``todo`` - To Do (``// TODO: ...``)
  * ``fixme`` - Fix Me (``// FIXME: ...``)
  * ``singleton`` - Swift Singleton (``static let sharedInstance...``)

* TDD/BDD
  * ``describe`` - Describe block for tests in Swift
  * ``context`` - Context block for tests in Swift
  * ``it`` - It block for tests in Swift
  * ``beforeEach`` - Before Each block for tests in Swift
  * ``afterEach`` - After Each block for tests in Swift

## Objective-C

* Classes and Protocols
  * ``@interface`` - Objective-C Class Declaration
  * ``@interface-extension`` - Objective-C Class Extension
  * ``@interface-category`` - Objective-C Category
  * ``@implementation`` - Objective-C Class Implementation
  * ``@implementation-category`` - Objective-C Category Definition
  * ``@protocol`` - Objective-C Protocol Definition

* Misc
  * ``@property`` - Objective-C Property
  * ``#import-local`` - Import Local Header File
  * ``#import-framework`` - Import Framework Header File
  * ``#pragma`` - Pragma Mark
  * ``do`` - Do-While Statement
  * ``for`` - For Statement
  * ``if`` - If Statement
  * ``if-else`` - If-Else Statement
  * ``switch`` - Switch Statement
  * ``enum`` - Enumerated Type Declaration (``NS_ENUM``)
  * ``options`` - Enumerated Type Declaration (``NS_OPTIONS``)

* TDD/BDD - Quick/Specta/Cedar
  * ``describe`` - Describe block for tests in Objective-C
  * ``context`` - Context block for tests in Objective-C
  * ``it`` - It block for tests in Objective-C
  * ``beforeEach`` - Before Each block for tests in Objective-C
  * ``afterEach`` - After Each block for tests in Objective-C

* F*block syntax
  * ``block-as-local-variable`` - Block as a local variable
  * ``block-as-method-parameter`` - Block as a method parameter
  * ``block-as-property`` - Block as a property
  * ``block-as-typedef`` - Block as a typedef
  * ``block-as-argument-to-method-call`` - Block as an argument to a method call

## Ruby. Ruby?

* CocoaPods
  * ``pod`` - Pod Declaration
  * ``pod-git-commit`` - Pod from Git Commit (SHA)
  * ``pod-git-tag`` - Pod from Git Tag
  * ``pod-local-disk`` - Pod from Local Disk
  * ``target`` - Target
  * ``post_install`` - Post Install

In order to make these snippets to work, please edit your Visual Studio Code settings to load ``Podfiles`` are Ruby.

```json
    "files.associations": {
        "Podfile": "ruby"
    }
```

# Contributing

Want to contribute? Sweet!

1. Fork it on [GitHub](https://github.com/ornithocoder/vscode-ios-snippets)
1. Create a branch (`git checkout -b my_awesome_feature`)
1. Commit your changes (`git commit -am "Add new awesome feature"`)
1. Push to the branch (`git push origin my_awesome_feature`)
1. Open a Pull Request

# License

Copyright (c) 2016 Ornithologist Coder. All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
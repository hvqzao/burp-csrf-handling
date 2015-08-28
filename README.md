# BurpSuite csrf-handling Extension

This extension aims to allow extremally simple handling of CSRF tokens for applications testing. 
There is no GUI. All configuration is to be done per given application test. By that, configuration
is very portable - if one tester decides to hand his result to another tester, the other will have
the extension already configured and ready to use in his tests. The same way, once configured and
stored in project folder, extension can wait for new application release to be tested.

Extension handles multiple tokens, use multiple search sequences, you can use specific status codes
etc. Additionally, it is possible to define search and replace modifications for requests and
responses.

This extension is also included in Wildcard Burp extension. http://github.com/hvqzao/wildcard.git

## Usage

- Copy extension to given working directory
- Edit extension in any text editor
- Modify parameters in SETTINGS sections
- Load extension to Burp
- When test is over - unload it from Burp

## License

[MIT License](https://github.com/twbs/bootstrap/blob/master/LICENSE)

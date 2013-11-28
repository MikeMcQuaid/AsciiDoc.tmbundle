# AsciiDoc.tmbundle
TextMate support for AsciiDoc.

## Installation
### TextMate 2
```bash
mkdir -p ~/Library/Application\ Support/Avian/Bundles
cd ~/Library/Application\ Support/Avian/Bundles
git clone git://github.com/mikemcquaid/AsciiDoc.tmbundle
```

### TextMate 1
```bash
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone git://github.com/mikemcquaid/AsciiDoc.tmbundle
osascript -e 'tell app "TextMate" to reload bundles'
```

## Status
Only basic language syntax is supported currently. Still, this seemed to give
better results than other AsciiDoc bundles I tried.

Tested using TextMate 2. May work in TextMate 1 or Sublime Text; I've no idea.

[Patches welcome](https://github.com/mikemcquaid/AsciiDoc.tmbundle/pulls).

## Contact
[Mike McQuaid](mailto:mike@mikemcquaid.com)

## License
AsciiDoc.tmbundle is licensed under the [MIT
License](http://en.wikipedia.org/wiki/MIT_License). The full license text is
available in
[LICENSE.txt](https://github.com/mikemcquaid/AsciiDoc.tmbundle/blob/master/LICEN
SE.txt).

Ideam
================


Introducing
----------------

Ideam is an IDE for [Haiku](https://www.haiku-os.org).
The editor is based on [Scintilla for Haiku](https://sourceforge.net/p/scintilla/haiku/ci/default/tree/).
It is developed and tested on a x86_64 build.


Compiling
----------------

* Download [Scintilla](http://www.scintilla.org) sources
* Download [Scintilla for Haiku](https://sourceforge.net/p/scintilla/haiku/ci/default/tree/) sources
* Follow instructions there and Build it
* Place libscintilla.a in:
  `/boot/home/config/non-packaged/develop/lib`
* Place Sci_Position.h, SciLexer.h, Scintilla.h, ScintillaView.h in:
  `/boot/home/config/non-packaged/develop/headers`
* Download Ideam sources
* Execute `make` in Ideam's top directory

The executable is created in app subdirectory.

License
----------------

Ideam is available under the MIT license. See [License.md](License.md).

i18n-howto
==========

Internationalization (i18n) and Localization (l10n) in Rails How-To

[Download the slides](https://github.com/consti/i18n-howto/blob/master/i18n-howto.pdf)

Content
=======

* Definitions
  * i18n, l10n
* Preparations
  * Raise an exception on missing translations
  * Instead of I18n.t() use t() shortcut in tests
* Best practices
  * Make sure things look pretty with a different text length
  * Internationalize user interface
  * Use correct ISO code for locale
  * Pluralization
  * Interpolation
* i18n: Front end
  * Regular views
  * Static javascript / coffeescript
* i18n: Database
  * ActiveRecord models
* Tools
  * i18n-tasks
  * l10n: webservices
* Application Logic
  * `before_action`
  * store prefered locale in `User` model
* Application Gotchas
  * Fragment Caching
* SEO Gotchas
  * Determine the locale (URL structure)
  * Duplicate content?
  * Sitemaps
  * `hreflang` link tags
  * TLDs, gTLDs, ccTLDs
  * Analytics


License
==========

The MIT License (MIT)

Copyright (c) 2014 Constantin Hofstetter

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

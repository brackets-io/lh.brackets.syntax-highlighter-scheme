Syntax highlighting support for Scheme language in Brackets editor (http://brackets.io/)
(Should work with Racket and other variants too.)

Brackets for some reason only support these languages:
https://github.com/adobe/brackets/blob/master/src/language/languages.json
despite CodeMirror that Brackets use is supporting many more.

Fortunately, it's easy to add support for those through an extension:
https://github.com/adobe/brackets/wiki/Language-Support#defining-a-new-language
and that's why and how this extension has been created.

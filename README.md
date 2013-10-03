#Yasnippets for yang-mode
###What is Yasnippet?
[Yasnippet](https://github.com/capitaomorte/yasnippet)

###What is Yang?
[Yang](http://www.yang-central.org/)

###What is Yang-mode?
[yang-mode](http://www.emacswiki.org/emacs/YangMode)

###Experimental features
Import-snippet and module snippet is now fetching data from .yangsnippetrc, which
must be located in the home-dir, with the following json structure:
```
{
  "namespace": "http://example.com/ns/",
  "import-modules": ["iana-if-type",
                     "ietf-inet-types",
                     "ietf-yang-types",
                     "tailf-common",
                     "tailf-webui",
                     "tailf-xsd-types"]
}
```
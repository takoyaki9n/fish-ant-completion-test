# fish-ant-completion-test
## Install
```
$ cd fish-ant-completion-test
$ cp tmp.xml /tmp
$ cp tmp-another.xml /tmp
```
## Test
Start fish-shell and confirm that following targets are shown.
```
$ fish
$ ant [Tab]
$ ant has\>gt                                                                 from-another-buildfile      has\'single\'quote  with-content
from-buildfile-under-tmp    has\>gt             with-description  (A target with description)
from-yet-another-buildfile  simple-target       with-newline-in-start-tag
has\"double\"quote          single-quote
```

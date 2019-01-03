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
from-another-buildfile      has\"double\"quote  simple-target     with-description  (A target with description)
from-buildfile-under-tmp    has\'single\'quote  single-quote      with-newline-in-start-tag
from-yet-another-buildfile  has\>gt             with-conamentent
```

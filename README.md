# magic-fork

Python 3 and 2 version of Jason Petrone's magic.py

Pure python implemenation of file magic identification using Unix standard metadata https://www.freebsd.org/cgi/man.cgi?query=magic&sektion=5 

https://pypi.org/project/magic/ (as of 2020-04) has dead links and has not been updated.

Alternatives to this pure python file magic implementation are the various libmagic wrappers and file wrapper. See https://bbs.archlinux.org/viewtopic.php?id=240109 for some background.

There are other forks of magic.py but they are Python 2 only and are part of a larger tool and can not be used standalone:

  * https://github.com/autotest/autotest/blob/master/client/shared/magic.py
      * https://chromium.googlesource.com/chromiumos/third_party/autotest/+/master/client/common_lib/magic.py (fork of the above)


There is a similar but different metadata system at https://github.com/floyernick/fleep-py - its Python 3 only and more information is available at https://hackernoon.com/determining-file-format-using-python-c4e7b18d4fc4

Alternative metadata systems (no Python implementations):

  * https://www.nationalarchives.gov.uk/information-management/manage-information/preserving-digital-records/droid/
  * https://www.garykessler.net/library/file_sigs.html
      * https://www.garykessler.net/software/index.html#filesigs
  * https://en.wikipedia.org/wiki/List_of_file_signatures
  * https://filesignatures.net/
      * https://cysecguide.blogspot.com/2017/12/file-signature-and-file-magic-number.html

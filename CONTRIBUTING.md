# Contributing to diff-match-patch

## Setup

Once in your development environment, create a virtualenv
and install the appropriate linting tools and dependencies:

    $ cd <path/to/diff-match-patch>
    $ make venv
    $ source .venv/bin/activate


## Notes

This is a partial fork of [diff-match-patch][],
with extra bits to make this a modern, friendly
member of the Python packaging ecosystem. The
library will be periodically updated with changes
from the upstream project. 

Since August 2024, Google's diff_match_patch 
library is archived, but there is a 
[maintained][diff-match-patch-maintained] fork.

If you would like to contribute fixes or 
improvements to the library itself, and not the 
packaging code, please submit them to the upstream 
maintained fork library directly.

[diff-match-patch]: https://github.com/google/diff-match-patch
[diff-match-patch-maintained]: https://github.com/dmsnell/diff-match-patch
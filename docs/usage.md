# Usage

```bash
msee README.md          # render a file
cat README.md | msee     # render stdin
msee --no-color README.md
```

The exit code is 0 when the file was rendered and 1 when the path cannot be read.

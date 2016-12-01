Copyright (C) 2016 Keith Thompson

`gpg-tmp` is released under GPL version 2 or later.  See the
header comments in `gpg-tmp` and the file `COPYING`.

Invoke `gpg` with a temporary keyring, initialized with a specified key

Usage: `gpg-tmp [key-id] gpg argument(s)`

where "key-id" is an 8- or 16-digit hexadecimal key id.

If the first argument is not an 8- or 16-digit hexadecimal value,
`gpg-tmp` will attempt to extract the key from the file named by the
*last* argument.

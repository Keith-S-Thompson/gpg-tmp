gpg-tmp

Invoke `gpg` with a temporary keyring, initialized with a specified key

Usage: `gpg-tmp [key-id] gpg argument(s)`

where "key-id" is an 8-digit hexadecimal key id.

If the first argument is not an 8-digit hexadecimal value, `gpg-tmp` it will attempt to
extract the key from the file named by the *last* argument.

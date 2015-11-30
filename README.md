# alpine
a fork of the docker alpine linux image

This fork is just the alpine image with the following changes:

1) patched `env` command to also have the `--null` argument. (useful for CI's that do `env --null`)
1) patched the dns so the container links work correctly

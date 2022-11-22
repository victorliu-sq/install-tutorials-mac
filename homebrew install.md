Path error

```shell
error: RPC failed; curl 56 LibreSSL SSL_read: error:02FFF036:system library:func(4095):Connection reset by peer, errno 54

error: 2151 bytes of body are still expected

fetch-pack: unexpected disconnect while reading sideband packet

fatal: early EOF

fatal: fetch-pack: invalid index-pack output

Failed during: git fetch --force origin
```



Installation steps

```shell
# To deleting homebrew and trying a fresh install like this
sudo rm -fr /opt/homebrew

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Run these three commands in your terminal to add Homebrew to your PATH
echo '# Set PATH, MANPATH, etc., for Homebrew.'

echo 'eval "$(/opt/homebrew/bin/brew shellenv)"'

eval "$(/opt/homebrew/bin/brew shellenv)"

# get start
brew help
```


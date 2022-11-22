delete go of old version

```shell
rm -r /usr/bin/go
```



download go **pkg ** from https://go.dev/dl/

```shell
brew install wget

wget https://go.dev/dl/go1.19.3.darwin-arm64.tar.gz
```



unzip the go pkg

```shell
tar -xzvf go1.19.3.darwin-arm64.tar.gz
```



move go pkg of newest version to /usr/bin

```shell
sudo mv -v go /usr/local
```



edit the ~./bash_profile

```shell
vim ~/.bash_profile
```



Append the following 2 lines to set up GOPATH

```shell
# set up golang path
export GOPATH=$HOME/go
export PATH=$PATH:/usr/local/go/bin:$GOPATH/bin
```



Save and close the file when using vim

shift + z + z



run the source command into current bash.shell to load environment variables on ubuntu

```shell
source ~/.bash_profile
go version	
```


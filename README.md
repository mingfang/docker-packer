# docker-packer
Run Packer Inside Docker

## Build
```
./build
```

## Alias
```
alias packer='docker run -v `pwd`:/docker -w /docker --rm -it packer packer'
```

## Run
```
packer version
```

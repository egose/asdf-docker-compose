# asdf-docker-compose

[docker-compose](https://github.com/docker/compose) binary plugin for [asdf](https://github.com/asdf-vm/asdf)

## Install

### Plugin

```sh
asdf plugin add docker-compose
# or
asdf plugin add docker-compose https://github.com/egose/asdf-docker-compose.git
```

### docker-compose

```sh
# List all versions of a package
asdf list all docker-compose

# Install a specific version of a package
asdf install docker-compose <version>

# Install the latest stable version
asdf install docker-compose latest

# Set the package global version
asdf global docker-compose <version>

# Check the version
docker-compose version
```

Please check [asdf](https://github.com/asdf-vm/asdf) for more details.

# License

See [LICENSE](LICENSE) ©[Junmin Ahn](https://github.com/junminahn/)

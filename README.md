# @soramitsukhmer/setup

An automated platform setup and provisioning scripts for @soramitsukhmer.

> Requested by @phuylai-oeung and @phyrumsk

## Supported platforms

- [x] macOS
- [ ] Linux
- [ ] Windows 10/11

### Install & Update Script

```sh
curl -o- https://raw.githubusercontent.com/soramitsukhmer/setup/main/install | sh
```

#### Environments

**Dry run**:

To test drive the installer set `SETUP_DRY_RUN=1`

```sh
curl -o- <url-to-installer> | SETUP_DRY_RUN=1 sh
```

**Verbose mode**:

Set the `CI=1` to run in verbose mode.


```sh
curl -o- <url-to-installer> | CI=1 sh
```

## References

- https://github.com/socheatsok78/setup-macos

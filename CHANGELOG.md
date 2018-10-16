## 0.2.1

- Fixed error with joblib 0.12

## 0.2.0

- Scan default encryption by default
- More greppable output
- Performance optimization for single objects

## 0.1.8

- Added `delete-unencrypted-versions` command
- Added `--acl` option to `reset-object-acl` command
- Added check for existing object ACL before reset
- Fixed issue with unicode keys in Python 2

## 0.1.7

- Added `enable-default-encryption` command
- Added `--dry-run` and `public-uploads` options to `set-policy` command
- Added summary to `scan-object-acl` and `encrypt` commands
- Added `--default-encryption` and `--sns-topic` to `scan` command

## 0.1.6

- Added `scan-dns` command
- Added `set-policy` command
- Added `delete-policy` command
- Added `--named` option to `list-policy` command
- 2x performance for object commands

## 0.1.5

- Fixed error with `enable-logging`

## 0.1.4

- Added `scan-object-acl` command
- Added `--only` and `--except` options
- Added `--log-bucket` and `--log-prefix` options to `scan` command
- Added `--log-prefix` option to `enable-logging` command

## 0.1.3

- Fixed policy check
- Added `list-policy` command
- Added `reset-object-acl` command
- Added support for wildcards
- Added support for customer-provided encryption key
- Added `--version` option
- Parallelize encryption

## 0.1.2

- Fixed issue with packaging

## 0.1.1

- Fixed json error
- Better message for missing credentials

## 0.1.0

- First release

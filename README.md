# openssh

This container image contains an OpenSSH server and provides the means for dynamic user provisioning.

## Usage

All environment variables prefixed by `PASSWORD_` lead to the creation of corresponding users.

For example, when specifying the environment variable `PASSWORD_USER`, the user `user` will be created and its password will be set to the value of `PASSWORD_USER`.

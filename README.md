# RSync deployment step
Deploy your code to any server over ssh using rsync. By default it will upload the whole directory to the target.

[![wercker status](https://app.wercker.com/status/499b8fe35ef7e486ec68e7b66a4a82bd/m "wercker status")](https://app.wercker.com/project/bykey/499b8fe35ef7e486ec68e7b66a4a82bd)

# Options

* `host` the hostname to connect to
* `directory` the remote directory to upload to
* `user` (optional) the username used for the connection, default is `ubuntu`
* `sshkey` the private key file to use for authentication

# Example

    - rsync-deploy:
        host: example.org
        directory: /var/www
        sshkey: $PRIVATEKEY_FILE
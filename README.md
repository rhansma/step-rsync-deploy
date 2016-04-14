# RSync deployment step
Deploy your code to any server over ssh using rsync. By default it will upload the whole directory to the target.


# Options

* `host` the hostname to connect to
* `directory` the remote directory to upload to
* `sshkey` the private key file to use for authentication
* `user` (optional) the username used for the connection, default is `ubuntu`
* `sshport` (optional) the port that ssh uses for the connection, default is `22`
* `source` (optional) specify which source directory to upload, default is `./`

# Example

    - rsync-deploy:
        host: example.org
        directory: /var/www
        sshkey: $PRIVATEKEY_FILE

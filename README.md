# RSync deployment step
Deploy your code to any server over ssh using rsync. By default it will upload the whole directory to the target.

[![wercker status](https://app.wercker.com/status/499b8fe35ef7e486ec68e7b66a4a82bd/m "wercker status")](https://app.wercker.com/project/bykey/499b8fe35ef7e486ec68e7b66a4a82bd)

# What's new

# Options

* `host` the hostname to connect to
* `directory` the remote directory to upload to
* `user` the username to use to connect (optional, default is `ubuntu`)
* `sshkey` the private key to use for authentication

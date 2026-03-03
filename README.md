# QoL Files

## VS-Code

## rclone

Example SFTP remote using an SSH key:

```bash
# one-time: create a remote that uses a private key
rclone config create myserver sftp host example.com user alice key_file ~/.ssh/id_ed25519

# use the remote
rclone ls myserver:/remote/path
rclone copy /path/to/local myserver:/remote/path
```

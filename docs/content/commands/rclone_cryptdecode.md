---
date: 2019-05-10T23:12:21+01:00
title: "rclone cryptdecode"
slug: rclone_cryptdecode
url: /commands/rclone_cryptdecode/
---
## rclone cryptdecode

Cryptdecode returns unencrypted file names.

### Synopsis


rclone cryptdecode returns unencrypted file names when provided with
a list of encrypted file names. List limit is 10 items.

If you supply the --reverse flag, it will return encrypted file names.

use it like this

	rclone cryptdecode encryptedremote: encryptedfilename1 encryptedfilename2

	rclone cryptdecode --reverse encryptedremote: filename1 filename2


```
rclone cryptdecode encryptedremote: encryptedfilename [flags]
```

### Options

```
  -h, --help      help for cryptdecode
      --reverse   Reverse cryptdecode, encrypts filenames
```

### SEE ALSO

* [rclone](/commands/rclone/)	 - Show help for rclone commands, flags and backends.

###### Auto generated by spf13/cobra on 10-May-2019

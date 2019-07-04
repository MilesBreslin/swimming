# Swimming

This shell script is capable of managing encryption for multiple block devices. It is intended for encryption before RAID gets applied. It converts a block device to a luks encrypted block device and encrypts each added device with a common key that is stored on the filesystem and encrypted with a single password. This repository is no longer actively maintained as I no longer use this myself.

#### Running

This script is an executable script. Ensure it has been marked as executable and run it.

```
usage: swimming <pool> <command> [command arguments]

commands:
	create_config <devices>
	create_pool <devices>
	open
	add <devices>
	keygen
```

#### License

This repository is licenced under the MIT License. See the `LICENSE` for details.

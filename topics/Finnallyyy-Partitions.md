# Finnallyyy: Partitions

## For this we will be using a pretty simple partition map.

| Name | Type       | Mount     | Size           |
|------|------------|-----------|----------------|
| EFI  | EFI        | /boot/efi | 1GB            |
| SWAP | Linux SWAP | [SWAP]    | 8GB (or more)  |
| ROOT | EXT4       | /mnt      | 30GB           |
| HOME | EXT4       | /mnt/home | REMAINING DISK |

Your very **smart**, so just use <code>cfdisk</code> and partition it smh.

```Shell
# EXT4
mkfs.ext4 /dev/part

# SWAP
mkswap /dev/part
swapon /dev/part

# EFI
mkfs.fat -F 32 /dev/part
```

WIP :)
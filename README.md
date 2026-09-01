# ritasboots
expimental film and video archive


# Backup to Maxine

 ```tmbackup.sh --ssh-opt "-p 13084" backup /media/cooper/media-served/media-rita "maxine@192.168.1.40:/volume1/Maxine-shared/media-ritasboots-backup"```



# find all DVD forders
```find "$(pwd)" -type f -iname "*.vob" -printf '%h\n' | sort -u```

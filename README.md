# rsyncignore

Maybe you are syncing two backup drives. Maybe you don't care about the system files like OS X Trash files or Windows temporary files. Maybe you encounter permission issues when rsync tries to copy these files?

If so, you might find this list of exclusion patterns handy.

## Usage

Copy the [rsyncignore.txt](rsyncignore.txt) file and include it in your command using ```--exclude-from```. 

Example:
```bash
rsync -rtv --exclude-from 'rsyncignore.txt' source/ destination/
```

## What are these files?

I planned to explain what each of these files is for, however, unfortunately, I don't have enough time now.

Partial explanation about OS X files can be found [here](http://blog.hostilefork.com/trashes-fseventsd-and-spotlight-v100/).

## Your contribution

If you find any issues with this ignore file or think that it should be improved in any way let me know.
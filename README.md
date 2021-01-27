# cleanly-zip-folder-mac

## Shell script to compress folders on a mac without DS_Store files

To make this script globally accessible:

1. Move it to a custom path
2. Add the path to your shell's config
3. Make it executable by running `chmod +x zipit.sh`

Now you should be able to cleanly zip files using a simple command:

```
zipit my-folder
```

Do not forget that you need to be inside the target folder’s parent directory for it to work.

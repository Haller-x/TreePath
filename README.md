# TreePath
Directory mapping script

# Exemple
```
exemple/
├── sample/
│   └── subsample/
│       └── subsample.txt
└── test/
    └── exemple_test1.txt
```

# Flags
Usage:
```
python treepath.py --root exemple/ --filename TreeDirectories.txt --print True
```
- root: Folder to map

- filename: txt filename (can be in other folder also)

- print: print on kernel? Default False

**Default filename will be tree.txt**

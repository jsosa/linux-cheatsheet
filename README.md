# linux-cheatsheet
Simple linux cheat sheet

#### Find files per extension including folder depth
```
find . -maxdepth 3 -iname \*.zip
```

#### Remove lines in text file containing a keyword
```
sed -i /-9999/d textfile.txt
```

#### Concatenate several text files in one
```
cat *.csv > out.csv
```

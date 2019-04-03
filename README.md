# linux-cheatsheet
Simple linux cheat sheet

#### Find files per extension including finding folder depth
```
find . -maxdepth 3 -iname \*.zip
```

#### Remove lines in text file containing a keyword
```
sed -i /-9999/d textfile.txt
```

#### Concatenate several .csv files
```
cat *.csv > out.csv
```

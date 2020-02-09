2. `cat words | egrep 'a{1,}.*[^s]$' | grep -o '..$' | sort | uniq -c | sort | tail -n10`

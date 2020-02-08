1. `ls -lhat`
2. ```bash
	marco() {
		dir=$(pwd)
	
		cd ~
	}```
	
	```bash
	polo(){
		cd $dir
	}```
3. `find ~/random/ | grep -i "[.]html$" | zip -r html.zip -@`
4. ```bash
x=0
while true; do
	x=$((x+1))
	#echo "Case $x"
	./answer.sh 1>/dev/null
	if [[ "$?" == 1 ]]; then
		echo "Done $x"
		exit
	fi
done
```

	
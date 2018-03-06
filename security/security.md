Made using SSA easier than usernane/password for github by improving my "mgit" function in ~/.bashrc.  Better github secruity against key loggers. 
```
mgit() {
    regex=".+?/([^.]+)(\.git)?$"
    package_json="./package.json"
    if [[ $1 =~ $regex ]]; then
        if [[ 2 -le ${#BASH_REMATCH[*]} ]]; then
            dir=${BASH_REMATCH[1]}
            echo "dir:" $dir 
            git clone $1
            cd $dir
	    if [ -f $package_json ]; then
	    	yarn install
	    fi
	    git remote set-url origin "git@github.com:invegat/"$dir".git"	
        fi
    fi 
}
```
Gethub repository signing with GPG2 - used it to sign this.   Anybody who steals my Github login wouldn't be able to make any signed posts unless they can also steal my GPG2 secret key.

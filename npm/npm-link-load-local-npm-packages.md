#npm #local #library
# Linking
1. in library/node module terminal run: `npm link`
2. in app terminal run : `npm link <name of package>`
	1. ex. `npm link exchange-ui-core`
	- if error occurs, most likely because node versions are diffrent between package and app
		- `node --version` to check
		- to fix
			- create .nvmc in app folder and put in version of package at text
				- ![[Pasted image 20240606100604.png]]
3. remove node_modules and package.lock.json and run `npm i`
### how to unlink
1. in local npm package run : `npm unlink <name of package>`
	- ex: `exchange-ui-core`
2. in app run the same thing `npm unlink <name of package>



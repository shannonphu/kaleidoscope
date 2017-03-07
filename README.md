# flatpage generator

### Steps to install dev environment:
1. [*Mac OSX only*] Install Homebrew at https://brew.sh/
2. Install NPM and node.js 
	* Options
		1. `curl -L https://www.npmjs.com/install.sh | sh`
		2. With Homebrew:
			* `brew install npm`
			* `brew install node`
		3. https://docs.npmjs.com/getting-started/installing-node
3. Install MongoDB
	* Options:
		1. With Homebrew: `brew install mongodb`
		2. https://docs.mongodb.com/manual/administration/install-community/
4. Install nodemon: `npm install -g nodemon`
	
### Starting the dev environment
1. `npm run mongo`
2. `nodemon` [note: if nodemon not installed, run `npm start`]
3. `npm run webpack`

### How to Use the MongoDB Shell
* To start database command shell: `mongo`
* `use flatpage`
* To show all currently existing tables: `show tables`
* To show all stored pages: `db.pages.find()`
* To clear all database content: `db.dropDatabase()`
* To leave the db shell: `quit()`

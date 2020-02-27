This project is currently under construction.

# My First Database

### Installation
1. Begin by downloading and installing the [MySQL Command Line Client](http://dev.mysql.com/downloads/shell/).
	* http://dev.mysql.com/downloads/shell/
2. Or install it directly on `OSX` by executing the following command.
	* `brew cask install mysql-shell`
3. To launch `MySQL` shell, execute the following command in terminal
	* `mysqlsh`


### Creating `Session` Object
* To create a `MySQL` session execute the following command from `MySQL` shell
	* `shell.connect('mysqlx://root@localhost:33060')`


* To Enter a `MySQL` session `mysql` execute the following command from `MySQL` shell
	* `mysqlsh --uri mysql://root@localhost:33060`

	

### Submitting Assignment
* Export database
* Echo the CLI history to a text file.
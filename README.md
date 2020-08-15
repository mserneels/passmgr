dead simple bash password manager using gpg-encrypted database

Will generate individual random password based on username/service pair, and store it in some gpg-encrypted database


	usage:
	passmgr -a|--add    	create a new entry (default action)
	passmgr -d|--delete 	delete some entry
	passmgr -h|--help   	show this message
	passmgr -l|--list   	list item(s) in db
	passmgr -s|--set    	create a new static entry

	optional:
	-D|--database path		password database to use
	-S|--services str 		pre-define service
	-U|--username str 		pre-define username
	-W|--wordfile path 		wordfile to use


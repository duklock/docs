# r/Duklock ban bot documentation
# NO LONGER SUPPORTED

## Discord module
### Commands
------------
*prefix =* `.`




**fetchall**/**fa** [val]

*prints every line of database limited by val*

		example: .fetchall 10

------------


**fetch**/**f** [user] 

*prints user values*
	
		example: .fetch mirandanielcz

------------


**insert**/**i** [user, removed_posts, bans] 

*adds a line (new user)*
	
		example: .insert mirandanielcz 0 0

------------


**setter**/**set** [username] [+/-{val}] 

*changes the value of rem_posts for a user*
	
		example: .setter mirandaniel +5

------------


**exe** [command] 

*executes SQL commands*
	
		example: .exe UPDATE public.ban SET rem_posts=rem_posts+5 WHERE u='mirandanielcz'
------------


**info**

*prints system info*
	
		example: info

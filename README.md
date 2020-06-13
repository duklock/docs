# Duklock ban bot documentation


## Discord module
### Commands
------------

**fetchall**

*prints every line of database*

		example: .fetchall

------------


**fetch** [user] 

*prints user values*
	
		example: .fetch mirandanielcz

------------


**insert** [user, removed_posts, bans] 

*adds a line (new user)*
	
		example: .insert mirandanielcz 0 0

------------


**setter** [username] [+/-{val}] 

*changes the value of rem_posts for a user*
	
		example: .setter mirandaniel +5

------------


**exe** [command] 

*executes SQL commands*
	
		example: .setter UPDATE public.ban SET rem_posts=rem_posts+5 WHERE u='mirandanielcz'

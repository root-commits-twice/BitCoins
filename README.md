# readme.txt (For experimental 0.9.0)  
  
## This text file explains a bit about modding and such. 
You can't delete this file!  
If you do modding will stop working  
  
  
## How to add miners: (.txt file needs to be called miners.txt)  
  
  
___
```
<head> 				#Starts the script (Must be first word)
<body>
	Name=Antpicker X1 	#The name of the product
	
	Speed=2 		#Speed of the miner. Higher is better	
	Power=2 		#How much power the miner uses
	Price=2 		#The price of the miner
	UnlockYear=2012 	#When the miner is available
	
	CurrencyCost=USD 	#The currency it costs
	CurrencyEarned=BTC 	#The currency it mines
	CurrencyLocked=True 	#If you can change what currency it mines

	PrefixPower= 		#Prefix of power value
	PrefixSpeed= 		#Prefix of speed value
	PrefixPrice=$ 		#Prefix of price value
	PostfixPower=w 		#Postfix of power value
	PostfixSpeed=/s 	#Postfix of speed value
	PostfixPrice= 		#Postfix of price value
</body>
<body>
	Name=X 			#The name of the product
</body>
</head> 			#Stops the script
```

___

 `<head>` and `</head>` are needed to start and end the mod.

  
## How to add currencies: (.txt file needs to be called currencies.txt)  

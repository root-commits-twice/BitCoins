# readme.txt (For experimental 0.9.0)  
  
## This text file explains a bit about modding and such. 
You can't delete this file!  
If you do modding will stop working  
  
  
## How to add miners: (.txt file needs to be called miners.txt)  
  
  
___
```
<0>
Miner:
	Basic:
		Name=Antpicker X1 	#The name of the product
		Speed=2 		#Speed of the miner. Higher is better	
		Power=2 		#How much power the miner uses
		Price=2 		#The price of the miner
		UnlockYear=2012 	#When the miner is available
	Currencies:
		Cost=USD 	#The currency it costs
		Earned=BTC 	#The currency it mines
		PowerCost=BTC	#The power costs currency
		Locked=True 	#If you can change what currency it mines
	Prefixes:
		Power= 		#Prefix of power value
		Speed= 		#Prefix of speed value
		Price=$ 		#Prefix of price value
	Suffixes:
		Power=w 		#Postfix of power value
		Speed=/s 	#Postfix of speed value
		Price= 		#Postfix of price value
Miner:
	etc.
<1>
```

___

 `<head>` and `</head>` are needed to start and end the mod.

  
## How to add currencies: (.txt file needs to be called currencies.txt)  

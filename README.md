# readme.txt (For experimental 0.9.0)  
  
## Content
* [Adding Miners](#Adding-Miners)
* [Adding Currencies](#Adding-Currencies)
* [Adding Themes](#Adding-Themes)
  
## This text file explains a bit about modding and such. 
You can't delete this file!  
If you do modding will stop working  
  
  
## Adding Miners
  
  
___
```
<0>
- 	Miner
		String-Name: minertest

		Float-Speed: 1
		Float-Price: 1
		Float-Power: 1
		Float-UnlockYear: 2005

		String-CurrencyCost: USD
		String-CurrencyEarning: BTC
		String-CurrencyPower: USD

		String-PowerPrefix:
		String-SpeedPrefix:
		String-PricePrefix: $

		String-PowerSuffix: w
		String-SpeedSuffix: /s
		String-PriceSuffix:
- 	Miner
		String-Name: minertest2

		Float-Speed: 1
		Float-Price: 1
		Float-Power: 1
		Float-UnlockYear: 2005

		String-CurrencyCost: USD
		String-CurrencyEarning: BTC
		String-CurrencyPower: USD

		String-PowerPrefix:
		String-SpeedPrefix:
		String-PricePrefix: $

		String-PowerSuffix: w
		String-SpeedSuffix: /s
		String-PriceSuffix:
<1>
```

___

 ! `<0>` and `<1>` are needed to start, and end mods  
   
 To add more copy from `- 	Miner` to the end and paste  

  
## Adding Currencies
___
```
<0>
- 	Currency
		String-Name: USD
		String-NameWorth: USDworth
		Float-StartingValue: 1

		Float-DelayS: 2
		Float-EventDelayS: 300

		Float-MaxChange: 0
		Float-MaxChangeEvent: 0

		Float-MinChange: 0
		Float-MinChangeEvent: 0
<1>
```
___

 ! `<0>` and `<1>` are needed to start, and end mods  
   
 To add more copy from `- 	Currency` to the end and paste  
 
 
## Adding Themes  
___
```
<0>
- 	Theme
		Dark-Red: 85
		Dark-Green: 55
		Dark-Blue: 134
		
		Light-Red: 103
		Light-Green: 70
		Light-Blue: 156
		
		Middle-Red: 0.1
		Middle-Green: 0.1
		Middle-Blue: 0.1
<1>
```
___

 ! `<0>` and `<1>` are needed to start, and end mods  
   
 To add multiple themes copy-paste the file and rename it  

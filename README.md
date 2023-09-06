# esx_banking
Modified version of esx_banking that allows user to have an MasterCard item for ATM

This only supports ox_inventory
Put this on your @ox_inventory/data/items
```
['mastercard'] = {
		label = 'Mastercard',
		stack = false,
		close = true,
		weight = 10,
		client = {
			anim ={dict = 'amb@prop_human_atm@male@enter', clip = 'enter'},
			event = "esx_banking:usecard",
			usetime = 3500
		}
	},
```

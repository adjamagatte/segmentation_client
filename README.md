# SegmentationClients
This repository content all code and reflexion about customers segmentation

 Recency
for that, we will have to weight so as not to penalize the customers who buy everything at the same time and at the beginning of seasons ( for example multiply by 1/3 )


Frequency
Because of some customers who buy their C02 directly from other stores, we will use “leurre” as consumable in this case. ( 18 consumable / 1 device/3years )

Amount
cost = consumable unit price for 1 month 
d = expense = amount of the invoice / number of customer’s devices
Here we divide by the number of customer’s devices to normalize. If the customer has 2 terminals and buys consumables for only one device, his score for the amount will be low.

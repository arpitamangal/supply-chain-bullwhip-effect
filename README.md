# supply-chain-bullwhip-effect

### Why does the bullwhip effect occur?
The bullwhip effect occurs due to factors such as demand forecast inaccuracies, order batching, inventory management practices, lead time variability, lack of information sharing, and behavioral factors. As a retailer, we saw that the demand from the consumer end increased initially. We assumed that it was gonna increase further and we ordered extra beers. However, the demand remained constant from the consumer end. Moreover, our orders were not being fulfilled by the wholesaler. Due to lack of communication or having no channel to share information we were confused why the orders were not being fulfilled. We were not sure if they were gonna clear all the backlog orders or not and we ended up placing a high quantity order. This resulted in a high inventory for us later and we resumed from placing any orders. These factors lead to amplified fluctuations in demand as they move upstream in the supply chain.

### How can the bullwhip effect be controlled ?
Strategies to control the bullwhip effect:
Improve demand forecasting and share information.
Implement inventory smoothing and replenishment policies.
Foster collaborative planning and coordination among supply chain partners.
Reduce lead times through process optimization.
Adopt vendor-managed inventory (VMI) approaches.
Implement order batching and smoothing techniques.
Build a flexible and responsive supply chain.
By employing these strategies, companies can minimize the bullwhip effect and achieve greater supply chain efficiency.

### What would be a good metric to characterize the bullwhip effect?
Coefficient of Variation (CV), could be a good metric to characterize the bullwhip effect. CV measures the relative variability of orders or demand at different stages of the supply chain. It is calculated as the ratio of the standard deviation to the mean demand or order quantity. A higher CV indicates higher variability and potential bullwhip effect.

### How is perceived demand compared to the actual demand?
In the beer simulation game, the presence of the bullwhip effect is observed when comparing perceived demand and actual demand data. Our individual estimations of demand frequently deviate from the true market demand, causing fluctuations in inventory levels and suboptimal decision-making.
Initially, the perceived and actual demand closely align with each other. However, as the simulation progresses, discrepancies emerge. We tend to overestimate or underestimate the actual demand, leading to inflated or understated perceived demand. These differences can result in stockouts, missed sales opportunities, and excessive production or inventory buildup.
One of the primary reasons behind the shot up demand is due to lack of supply from wholesale at one instance, where we received just 0 units. With an increasing backlog, we had to place larger orders not knowing whether the previous outstanding ones would be fulfilled or not.
5. How did the costs, backlog, inventory progress over time ?
As a retailer, we saw that the demand from the consumer end increased initially. We assumed that it was gonna increase further and we ordered extra anticipating an increasing demand. However, the demand remained constant from the consumer end. Moreover, our orders were not being fulfilled by the wholesaler. We were not sure if they were gonna clear all the backlog orders or not and we ended up placing a high quantity order. The order was still not being fulfilled and we had a very high backlog. We had no inventory. Then at one point we received around 1M quantity. This did clear our backlog but resulted in a high inventory for us and we stopped placing any orders for the next 10 weeks. With our backlog constantly increasing from week 7 until week 20, our cost due to missed opportunities increased as well. Following which once we received a huge order of over 1Mn units, our backlog did clear out but the inventory costs kept increasing. 

### Explain what was the strategy/algorithm used in placing the orders? Did the parameters of holding, backorder cost, lead time affect your decisions? Yes/ no
Yes, when we saw we were incurring holding costs, we placed less orders. But then the orders were not being fulfilled, we had a lot of back orders and we placed too many orders. When the order was fulfilled we started incurring a high holding cost and resumed placing new orders.

### How would your strategy change if the lead time was increased ?
If the lead time was increased, we would have ended up ordering more initially thinking that it is gonna take time to receive the order. After a few weeks we might end up having inventory and would have preferred to have inventory rather than back order. With lead time just 2 weeks we tried to just meet  demand. However, this would not have been the case if lead time was higher, we would have preferred to always have holdings to meet the uncertainty in demand.

### How would your strategy change if the lead time was decreased ?
If the lead time was decreased, we would have ended up ordering just to meet the demand. After a few weeks we might have ended up having backorders if the demand increased unexpectedly. With lead time just 2 weeks we tried to just meet demand but still plan for the coming 2 weeks. However, this would not have been the case if lead time was decreased.


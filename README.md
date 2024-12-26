# Optimization algorithm to support transportation companies
A transportation company needs to solve the problem of dividing customers into transportation hubs with the aim of serving customers faster and more efficiently. This problem is stated as follows. The shipping company has,

 - A set of n transport hubs H = {1,...,n}, each transport hub ∈ H is located at the position (xh,yh) on the 2-dimensional coordinate plane Oxygen and has the maximum capacity to process h orders in one month;
 - A set of regular customers C = {1,...,m}, each client c ∈ C has a position on the Oxygen coordinate axis of (xc,yc) and has the number of orders that need to be shipped vc in a month.

The Company needs to assign customers to hubs so that the total distance from the customer to the assigned hub is minimal, so that each customer is assigned to 1 of the last 5 hubs and the total number of orders placed by customers assigned to the hubs in a month is less than or equal to the maximum processing capacity of those hubs in a month. Notice, the distance here is the Euclidean distance. 

You are asked to develop optimal algorithms to support the delivery company to solve the above problem. Analyze, evaluate, and compare developed algorithms.

References:
- Slide: https://docs.google.com/presentation/d/1KR5fIEUiR5Ht_djiN28Cglcjg4MvUEXZ/edit?fbclid=IwY2xjawHZEitleHRuA2FlbQIxMAABHdJxVFAG_GrDqZatXO_61ziEQ8fO18UCYdKfWO-uzanepfBOdvELKBkZlA_aem_xLvdOZDZsXdlOptk8oWLcQ#slide=id.p1

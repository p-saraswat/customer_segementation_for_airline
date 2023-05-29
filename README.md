# Customer Segementation for a leading Airline
Analyzed customer travel patterns, and segmented more than 3.5M customers into 4 groups via K-prototype, and 180+ routes into 3 clusters via Density-Based clustering, boosting vacation package promotions and driving airline loyalty program.

### Business Goal:
Data Analytics plays a vital role in the aviation industry and it can aid business growth by looking into customer flying patterns. This report aims to provide XYZ Airlines with the following:
Robust understanding of their customers by doing customer segmentation, customer profiling, and identification of meaningful travel patterns
Strategic Recommendations to better meet their customer's needs and devise effective marketing plans to generate more revenue
Insights to increase customer enrollment in the Ufly Rewards loyalty program

### Key Findings:
The given data is transformed and aggregated such that each row represents a unique customer. Customer-level data is analyzed by leveraging various clustering techniques. K-means clustering analysis and Gaussian Mixture model (GMM) clustering analysis were performed on this dataset. After feature level comparison of each cluster between K-means and GMM models, it is clear that K-means clusters are interpretable and distinct. Whereas GMM clusters have the least varied features among several features making them less interpretable. K-Means clusters serve the primary purpose of drawing critical insights which are actionable by XYZ airlines. As a result of K-means clustering analysis, XYZ's customers are grouped into four clusters. We create four personas to describe customers in each cluster based on the features highlighted, as shown in the diagram below: 


                                                                                                                                                                                       
                                                                                                     
**Need-based Travelers**

This segment contains the majority of the customers (55%), but they are cost-sensitive and spend the least per ticket, as their average ticket cost is $200. Moreover, since the frequency of travel for these customers is about once a year and on average they book 37 days prior and travel in case of ‘need’. Also, these customers have a majority of young population, between 20 to 30 years of age. The dominant population in this cluster (93%) did not enroll in a Ufly membership. These customers also have a tendency to book return tickets back to their origin 35% of the time.




**Figure 1: Percentage of Revenue generated per customer segment**

**Leisure Long-Distance Travellers**
This cluster consists of 29% of the customers who contribute the most to XYZ in revenue (44%) (Figure 1). Customers in this cluster are leisure travelers because their average per-ticket cost is $409, and they don't hesitate to pay extra for supplementary services. They travel long distances (1450 miles on average) for leisure. And out of the most common routes from our route-based analysis, these customers travel to vacation places such as Cancun, Los Angeles, San Diego, etc. They are also traveling highly in quarter 1 and quarter 4 of the year. They travel once a year on average and have a low number (24%) of Ufly enrolled members. These customers prefer to plan their trip way early in time, 102 days in advance, and only 8% of them book a round trip with XYZ. These customers are the most valuable group for XYZ based on revenue generated.

**Cost-Sensitive Frequent Flyers**

Customers in this cluster comprise 15% of the total customers of XYZ, who contribute 16% of the total revenue. They prefer relatively low-cost travel, as their average ticket price is $295. These customers are frequent flyers with XYZ Airlines who travel about 3 times a year on average, and 35% of the members in this cluster have a Ufly Membership. They book their tickets with round trips 14% of the time and belong to an average age group of 42 years. The customers plan their trips with sufficient planning (58 days in advance) and travel to 4 different locations over 2 years on average. These customers already have a brand engagement with SCA.

**Premium Frequent Travelers**

Customers in this category are generally considered the most valuable to any airline. They are small in percentage, 1% of all customers, but they only cover 2% of the total revenue of XYZ. They travel first class (0% of the time) with an average cost per ticket of $327, and they travel frequently (seven times a year) with XYZ. 60% of the 1155 Elite customers belong to this segment and they book around 53 days in advance.

### Route-based Analysis findings:
A route-based segmentation analysis was performed to supplement our clustering results. The results from this analysis are listed below:
It is found that 80% of the customer base travel to and fro from Minneapolis to only 13 different cities (Boston, Cancun, Washington DC, New York City, Dallas, Las Vegas, Orlando, Los Angeles, Orlando, Los Angeles, Phoenix, Lee County, San Diego, San Francisco and Seattle). 
Out of these 13 cities, 4 cities (Cancun, Los Angeles, San Diego, and San Francisco) have a distance from Minneapolis greater than 1400 miles.

### Recommendations:
With the identification of four distinct customer profiles, we recommend approaching each profile with a different marketing strategy to target and cater to each one of their needs.

**Leisure Long-Distance Travellers**

Customers in this segment travel longer distances (1450 miles on average) with good planning in advance (102 days earlier) and consist of all age groups ranging from kids to old-aged. We also checked the routes most likely to be traveled by these customers. From our route-based analysis, we know that more than 80% of customers travel to 22 locations from Minneapolis, from which some common destinations with miles close to 1450 are Cancun, Los Angeles, San Francisco, and San Diego. And customers in these routes mostly travel during Q1 and Q4, so we can say these customers travel for leisure in warmer regions. So we have the following recommendations based on these findings:
To increase further engagement of these customers with XYZ, we should encourage them to enroll in Ufly Membership by offering ancillary services, such as stay recommendations, premium flight entertainment, kids' entertainment, free wifi, flight upgrade options, and priority check-in after UFly Membership signup
Since only 8% of the customers in this segment are booking return flights, so to further increase bookings, XYZ can offer in-house vacation packages with cheaper round trips. 

**Need-based travelers**

We identified this segment as the largest customer base of XYZ with 55% of total customers, but they currently have only 7% of customers in this segment have standard membership. Hence, we suggest the following strategies to improve UFly Membership and improve overall revenue:
Provide free cancellation on the first booking after UFly Membership signup,  especially on the busier routes as customers in this segment are relatively late planners, booking tickets 37 days prior to travel on average.
With the majority of consumers falling into the age bracket of 20-30 years and also returning to the origin airport 35% of the time, these customers can be considered Students. Students can be provided additional baggage allowance on the first flight after signing up for UFly Membership program.
Additionally, XYZ could also start a referral system that offers additional points both to the referee and referrer as an incentive to join the Ufly membership program as referral programs are more successful amongst the younger population.
Cost-Sensitive Frequent Flyers
This segment contributes 15% of the total customer base, and only 35% of the members in this segment have Ufly Membership. The remaining 65% of the customers within this cluster can be the first to be targeted amongst all the clusters with respect to running marketing campaigns as they have the highest percentage of Standard Members and are already frequent flyers (averaging 3 trips over a year) with XYZ.
Customers who have not yet signed up for the Standard Membership within this segment can be given a provision to claim past travel points based on PNR and Ticket Number as an incentive to join Ufly Membership.
For these customers, the web app can generate notifications that indicate the past reward points the user can claim for redeeming services in their upcoming travel if they join Ufly Membership.

**Premium Frequent Travelers**
We recommend prioritizing marketing efforts and resources to other customer profiles. While customers in this segment have the most frequent travels and majorly hold Elite UflyMembership, they comprise only 1% of the total customer base of XYZ contributing to only 2% of revenue. Hence, more time could be concentrated on other groups while maintaining the quality of services to these customers.

### Long-Term Recommendation

Based on our additional analysis, we would like to draw the attention of the management to the contribution of First Class to overall revenue for SCA.

Table 1: Percentage distribution of tickets and revenue for Booked Class of Travel

From the table above, it is seen that First-Class tickets are only 2.7% of the total booked tickets contributing to only 5.66% of the revenue. A cost-benefit analysis can be conducted with respect to replacing the First Class seats with more Economy or Premium Economy seats to analyze per sq. inch return with respect to overall profit. Based on a simulated cost-benefit study, an appropriate operational design change can be undertaken in the long run.


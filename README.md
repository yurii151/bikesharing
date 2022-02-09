# bikesharing

## Overview

The purpose of this analysis is to understand the users trends of renting bikes for a New York City bike sharing service. Before I could convert the data needed for the analysis into Tableau, I had to use python to convert the type of the tripduration column to make the analysis work. This description starts after the data was ready for use, but my .ipynb can be found in the repository.

## Results

The results below can be found at this  [link to dashboard](https://public.tableau.com/shared/6Q84RJSQ4?:display_count=n&:origin=viz_share_link)

### Bike Usage Per Hour

The first thing analyzed was what time were the least amount of being rented:


<img width="1436" alt="Screen Shot 2022-02-08 at 4 12 09 PM" src="https://user-images.githubusercontent.com/92888170/153097880-0d1396c0-7e35-480c-a571-14f126e88207.png">

We found that there is a severe drop in bike usages in the hours of 12-2 in the morning. This is when we would likely want to do repairs to minimize the amount of bikes being unavailabe. 

### Bike Usage Per Hour by Gender

Analyzing the first chart we can break the users down by gender:

<img width="1436" alt="Screen Shot 2022-02-08 at 4 22 55 PM" src="https://user-images.githubusercontent.com/92888170/153098329-1d3c0224-5971-4636-b80a-d9fa978fb2e5.png">

We find that while there is a steep drop in users from the times 12-2 AM, men are dominating the bike usage in those times.

### Trips by Weekday Per Hour

The next thing I analyzed was how the number bike rides broke down per day by each hour:

<img width="1010" alt="Screen Shot 2022-02-08 at 4 27 18 PM" src="https://user-images.githubusercontent.com/92888170/153098663-92a3a400-f3f1-4dec-93ef-0379d2e8ad23.png">


8-9 AM and 5-6 PM seem to be the times in the day where most bikes are being use. And, as we suspected above, 12-2 AM is the least busy time for bike rides.

### Trips by Gender Per Hour

I then broke down the chart above the see how gender and time were related:


<img width="1041" alt="Screen Shot 2022-02-08 at 4 30 10 PM" src="https://user-images.githubusercontent.com/92888170/153099036-b3100a6b-7ab7-45e2-807a-3235d39472ba.png">

Men and Women seem to bike at the same times, with more men using bikes overall. 

### User Trips by Gender

The next thing I analyzed was how the type of user-customer or subsriber broke down in the riding trends from above:

<img width="1077" alt="Screen Shot 2022-02-08 at 4 33 49 PM" src="https://user-images.githubusercontent.com/92888170/153099286-b6e4ba21-7a23-4e7c-b7e4-dae712f9668a.png">

We have more subsribers than users, and our subsribers use the bikes more frequently.

## Starting Stations

The next thing I analyzed was where most of the trips were starting from:



<img width="1077" alt="Screen Shot 2022-02-08 at 4 36 38 PM" src="https://user-images.githubusercontent.com/92888170/153099643-36ade228-8458-4fc5-afee-b17f53bc6879.png">

Two of the busier starting stations were at West st and Chambers st, and East 17th St and Broadway.

## Ending Stations

The last thing I analyzed was where most of the trips were ending at:

<img width="1077" alt="Screen Shot 2022-02-08 at 4 40 03 PM" src="https://user-images.githubusercontent.com/92888170/153099954-e118525b-0d19-4741-a555-0a7cae6cc98f.png">

The most common ending point for the bike rides were on the island off the tip of the city at Picnic Point and Central Park.



Summary:

The data gives alot of things to work with. For exampole, as I stated before, we could do repairs on the bikes from 12-2 AM at nights on the weekends because that is when the bikes are being rented. Another thing that we learned is that men use this service a lot more than women, so we could create a promotion aimed at getting more women to use the bikes. We could also incentivize current riders to reccomend thier friends by offering discounted rides to people who convert their freinds to subscribers. This will capitilize on the discovery that subsribers are our most profitable users. One thing I would want to visualize would be the cost of trips per user to see whos spending more money on rides. Another thing I would try to figure out is what are the most common routes between stations. 

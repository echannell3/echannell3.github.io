# Warehouse Distribution Center Labor Cost Saving Strategies
*** Disclaimer this is currently in the process of being rewritten***
This project was completed for the Senior Design Competition at Georgia Tech for Industrial Engineers. This is a year long competition where a team of students connect with a company as a client and completes a project for them using the skills learned from the Industrial Engineering curriculum. You can read more specific details about the competition in general here: https://www.isye.gatech.edu/academics/bachelors/current-students/senior-design.

# Introduction
For this project, our team worked with NAPA Autoparts as our client with a specific focus on analyzing their newly built Nashville Distribution Center to see how we could improve operations. I was responsible for creating a tool that could be used by NAPA Autoparts that would lead to reduce labor cost from their putwall within the warehouse. The putwall for NAPA was a term used to describe their sorting system. Essentially, stores are assigned groups on the putwall and the pick and sorting for them would be done in waves. With NAPA's current system the putwall assignments were static where the store groups wouldn't be evaulated until months at a time passed. The tool I ended up creating allowed for a dynamic system instead where the putwall assignments would change daily to save on labor cost.

# The Dynamic Putwall Tool
The tool I created for the putwall was created in python and can be seen below.

![image](https://user-images.githubusercontent.com/42851869/148291358-415ebeba-0b6f-4160-94a8-07a77799edd6.png)


***OLD***

For this project, our team worked with NAPA Autoparts as our client with a specific focus on analyzing their newly built Nashville Distribution Center to see how we could improve operations. We focused on 3 key solutions to further improve their operations and save them money on their day to day operations. These 3 solutions were (1) implementing a dynamic store-to-putwall assignmet, (2) create a fast pick zone, and (3) modify putaway locations. I was in charge of creating the dynamic store-to-putwall delivarable and will go into detail about what I did to complete this part of the project. The work our team did for this project led to us winning the competition and make a lasting impact on the company!

# Introduction
I was in charge of creating a deliverable that would lead to more efficient putwall operations. At a highlevel, the putwall is the sorting system the warehouse uses to pick items for stores in waves and create bins to be shipped to the different NAPA stores. The putwall influences cost of warehouse operations through 2 key metrics. 

The first is how many putwalls are being used on a given day. Each putwall that is active requires that a picker go through the warehouse and pick for the required material for the stores on that putwall. So reducing the number of putwalls being used allows for less distance to be traveled for the workers in the warehouse which leads to labor cost reduction. However, there are so key constraints that have to be considered when reducing the number of putwalls being used. These constraints revolve around the amount of product that needs to be sorted for the stores on the putwall and the limited number of slots for stores.

The second is the stores on specific putwalls. Stores that share similiar order profiles being placed on the same putwall would reduce the distance that workers would need to travel since they would reduce the need to revisit the same aisle for each putwall thus saving time and reducing labor cost.

# Offering a Solution
In its current state, NAPA Autoparts used a static putwall where stores assignments to each of their putwalls would be assigned and not be reevaluated for months at a time. However for the reasons mentioned earlier, moving to a dynamic system where the store assignments to a putwall changed day to day would offer a great opportunity to reduce the labor cost. To be able to change to a dynamic system there would need to be data on what parts each store needed before picking operations started in the morning and time to make the putwall changes. Luckily, both of these requirements could be met for their operations and led to the development of a program that....




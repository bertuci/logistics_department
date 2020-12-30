# logistics_department
## To optimize the cargo so that the company has more profitability.

![logistica](https://user-images.githubusercontent.com/55574172/102757943-c9fa4980-4350-11eb-868e-2cbf66b1c9b5.jpg)


# UNDERSTANDING THE CUSTOMER'S PROBLEM


The tropical airline uses the hold of its planes to transport cargo and optimize the company's profit from cargo, the person in charge of the sector approached us to create an solution to solve this problem.

The cargo needs to be optimized to get the maximum profit possible on a trip.
so far it seems easy, doesn't it?

However, we must take into account some factors, such as:
Live loads are the most expensive to transport, then come dangerous products and then electronics and asism onwards and it is also charged for size and weight. so it is necessary to take into account the size and price, because instead of an expensive order there would be 10 smaller ones, which would be worth a lot more money for the company.


## How to solve

To solve this problem we will use genetic algorithms and shainy to create an solution


# DEMONSTRATING THE SOLUTION

This is the first screen where the user will load the table with the loads
![Screenshot_73](https://user-images.githubusercontent.com/55574172/102760570-77229100-4354-11eb-8fe7-0ff2d01bd3af.png)



after the database is loaded
![Screenshot_75](https://user-images.githubusercontent.com/55574172/102760903-f1531580-4354-11eb-88e1-378a55f15be3.png)


Some information will be presented such as the number of items, the total weight, the total volume and the total value
![Screenshot_76](https://user-images.githubusercontent.com/55574172/102761100-35461a80-4355-11eb-8f75-4267b974869c.png)


Next we go to the processing tab there, we will inform how much weight and volume is still available on the plane to place the loads and then we choose the number of iterations for the algorithm to bring the result.
After choosing all the options and clicking on process, the application shows which loads should be sent

![Screenshot_78](https://user-images.githubusercontent.com/55574172/102761806-2ca21400-4356-11eb-8c7b-9fa311776ace.png)


# HOW TO USE

To use, just have a CSV file with the same structure as the file located in the 'DATA' folder, it contains 4 columns which are: ID, WEIGHT, VALUE AND VOLUME. then just load the file, click on load totals then go to the processing tab, choose the desired parameters and click on calculate totals.

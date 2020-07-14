# Pizza-Ordering
Pizza Project

## Final Project
Imagine that you are starting a new pizza restaurant franchise, and you'd like to be able to take online orders. Create specified classes with following requirements.

## Requirements
### A- Class PizzaOrder
        - Ability to add/remove pizza(s)
        - An order can have more than one pizza.
        - Ability to specify the store for which the order is made
        - Ability to apply special promotion code
        - Ability to check the order status
              Possible statuses are ORDER_CREATED, ORDER_CANCELED,
              ORDER_READY, ORDER_ON_DELIVERY, ORDER_COMPLETE
        - Has customer information
### B- Class Pizza
        - Ability to specify toppings
        - Ability to add/remove toppings
        - Ability to specify price
        - Ability to specify crust type (thin/thick)
### C- Class Store
        - Ability to hold a list of employees
        - Ability to add/remove employees
        - Needs to have address including zip code
        - Needs to have phone number
        - Needs to be able to show monthly pizza sales
### D- Class Employee
        - Has first name, last name
### E- Class Customer
        - Has first name, last name, phone number, zip code, frequent mileage number
### Notes:
- You need to be able to sort PizzaOrder by order date and total order amount
- You need to be able to search PizzaOrder by customer
- You need to be able to search PizzaOrder by order date
- You need to be able to pull a list of PizzaOrder prior to a certain date in sorted order by date
- You need to be able to pull a list of PizzaOrder after a certain date in sorted order by date
- A customer must be able to find one of your stores in the same zip code
- For searching and sorting above, explain time/space computation complexity using Big O Notation.
- You are allowed to add any private attributes (properties/variables) and methods as necessary

### Using Big O Notation to explain searching and sorting, and time/sapce computational complexitity.
- The Sorting algorithm used for this project is the Python Timsort Algorithm.

Timsort is a hybrid algorithm, derived from merge sort and insertion sort, designed to perform well on many kinds of real-world data. It was invented by Tim Peters in 2002 for use in the Python programming language. The algorithm finds subsets of the data that are already ordered, and uses the subsets to sort the data more efficiently. This is done by merging an identified subset, called a run, with existing runs until certain criteria are fulfilled. Timsort has been Python's standard sorting algorithm since version 2.3. It is now also used to sort arrays in Java SE 7, and on the Android platform.

- The Search methond used in this project is the Linear-Search.

Linear search is one of the simplest searching algorithms, and the easiest to understand. The time complexity of linear search is O(n), meaning that the time taken to execute increases with the number of items in our input list. Although linear search is not often used in practice, because the same efficiency can be achieved by using inbuilt methods or existing operators, and it is not as fast or efficient as other search algorithms, nevertheless linear search is a good fit for this project since we are using an unsorted collection of items. Unlike most other search algorithms, it does not require that a collection be sorted before searching begins.

### Refrences:
https://stackoverflow.com/questions/10948920/what-algorithm-does-pythons-sorted-use https://en.wikipedia.org/wiki/Timsort
https://stackabuse.com/search-algorithms-in-python/
https://github.com/topics/pizza-order
https://github.com/mddemarie/pizza-ordering-system

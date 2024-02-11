Look up Prices
==============

In this chapter you will:
-------------------------

======= ====================================
area    topic
======= ====================================
🚀      write a better receipt assistant
⚙       define a dictionary
⚙       look up values of a dictionary
🔀      iterate through a list of dictionary keys
🐞      fix index errors
======= ====================================

Exercise 1: Look up
-------------------

Consider we would like to look up shopping prices.
In this chapter, we will use a **dictionary**,
a data structure that is good for looking up items.

Execute the following code:

.. code:: python3

   prices = {
      "apple": 0.50,
      "banana": 1.00,
      "orange": 1.50,
      "cherries": 3.00,
   }
   print(prices["banana"])

How does the dictionary differ from a list?


Exercise 2: Explore
-------------------

Find out what each of the expressions does to the dictionary in the center.

.. figure:: dicts.png
   :alt: dict exercise


Exercise 3: Look up
-------------------

Now consider having the list of items in ``fruit``.
You would like to calculate the total price.
For that, the list and dictionary need to work together.

Sort the lines and indent them properly:

   print(total)
   total += prices[item]
   bought = ["banana", "banana", "cherries", "apple", "apple", "banana"]
   for item in bought:
   total = 0
   prices = {
      "apple": 0.50,
      "banana": 1.00,
      "orange": 1.50,
      "cherries": 3.00,
   }

Exercise 4: Receipt assitant 2.0
--------------------------------

Improve the receipt assistant from the previous chapter
so that it uses a dictionary of prices.


Reflection Questions
--------------------

-  How can you create a dictionary?
-  How can you modify values in a dictionary?
-  Is it possible to run a for loop over a dictionary?

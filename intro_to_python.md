# Python homework
## Beginner Python Exercises

### Exercise 1
> Practicing the print function:
> Replace "type here" on line 2 with "Hello World!"
print("Hello World!")

> You can assign "Hello World!" to the variable below on line 3.

my_text="Hello world!"
print(my_text)

### Exercise 2
> Assigning data to variables:
>Type here. Assign a number to the variable: glass_of_water

glass_of_water=3

print("I drank", glass_of_water, "glasses of water today.")

>Fill the print function so it prints glass_of_water

glass_of_water=3

glass_of_water=glass_of_water + 1


print(glass_of_water)

### Exercise 3
> Practicing data types
>Assign an integer to the variable, then print it.

men_stepped_on_the_moon=12
print(men_stepped_on_the_moon)

>Type a couple of words or a short sentence for your variable, then print it.

my_reason_for_coding="is to be cool"
print(my_reason_for_coding)

>Assign a float with 2 decimals to the variable below. If you don't wan't to search the value you can check out Hint 1.

global_mean_sea_level_2018=21

global_mean_sea_level_2018=21.36


print(global_mean_sea_level_2018)

### Exercise 9
> Practicing string operations
>Type your answer here.

str="It's always darkest before dawn."

print(str)

>By using first, second and last characters of the string, create a new string.

str="It's always darkest before dawn."

ans_1=str[0]+str[1]+str[-1]

print(ans_1)

str="It's always darkest before dawn."

>Type your code here.

str=str.replace('.','!')

print(str)

### Exercise 10
> Finding out the length objects by practicing the len function in python
>Using len() function find out how many items are in the list.

lst=[11, 10, 12, 101, 99, 1000, 999]

answer_1=len(lst)


print(answer_1)

>len() function can also tell the length of a string. Find out the length of the string given below.

msg="Be yourself, everyone else is taken."

msg_length=len(msg)

print(msg_length)

>How many keys are there in the dictionary?

dict={"Real Madrid": 13,"AC Milan": 7,"Bayern Munich":5 ,"Barcelona": 5, "Liverpool": 5}

ans_1=len(dict)

print(ans_1)

### Exercise 11
>Practicing the sort method in Beginner Python Exercises
>Sort the list in ascending order with .sort() method.

lst=[11, 100, 99, 1000, 999]

lst.sort()

print(lst)

>This time sort the countries in alphabetic order.
lst=["Ukraine", "Japan", "Canada", "Kazakhstan", "Taiwan", "India", "Belize"]

lst.sort()

print(lst)

>Now sort the list in descending order with .sort() method.

lst=[11, 100, 101, 999, 1001]

lst.sort(reverse=lst)

print(lst)

### Exercise 12
>Practicing the pop method
>Pop the last item of the list below.

lst=[11, 100, 99, 1000, 999]

popped_item=lst.pop(-1)
 
print(popped_item)
print(lst)

>Remove "broccoli" from the list using .pop and .index methods.
lst=["milk", "banana", "eggs", "bread", "broccoli", "lemons"]

item_to_pop=lst.index("broccoli")

item=lst.pop(item_to_pop)

print(lst, item)

>Save Italy's GDP in a separate variable and remove it from the dictionary.
GDP_2018={"US": 21, "China": 16, "Japan": 5, "Germany": 4, "India": 3, "France": 3, "UK": 3, "Italy": 2}

italy_gdp=GDP_2018.pop("Italy")

print(GDP_2018)
print(italy_gdp, "trillion USD")

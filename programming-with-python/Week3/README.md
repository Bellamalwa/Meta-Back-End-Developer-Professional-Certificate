Week 3 of programming with python tasks.

Instructions for comprehensions.py

Step 1: Open the comprehensions.py file

Step 2: Implement the to_mod_list() function by using the map() function to apply mod() to all elements within employee_list. Assign the result of it to a new variable called map_emp. Convert map_emp to a list and return it.

The mod() function returns a string value for example such as “Lisa_Cold Storage” from the dictionary passed to it. 

Step 3: At this point you should have a list of the values such as: “Lisa_Cold Storage” mentioned above. But that is no good for a username with the whitespace present in it. Implement the generate_usernames() method by using list comprehension and the replace()  over mod_list to replace all spaces (" ") with underscores ("_"). Return the resulting list.

Step 4: We want to create a dictionary that stores employees' first initials and IDs. Implement map_id_to_initial() by using dictionary comprehension over the employee_list to create a dictionary where each key is the first letter of an employee's name and the value is the employee's ID.

Step 5: Run the script by opening the terminal and executing the command 

python3 comprehensions.py
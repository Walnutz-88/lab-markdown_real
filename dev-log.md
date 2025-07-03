Paul, 7/3/25

## What I learned today
1. lists
2. how to add/remove things from lists
3. try-except 
4. how to get values from an outside file

## Lab Relfection
>Something that challenged me was getting the list in the stretch to be from outside the main.py file

## Code Snippet
``` Python
if choice == "0":

input_task = input("Enter a task: ")

if input_task == "":

print ("Please don't leave the task empty.")

else:

tasks.append(input_task)

elif choice == "1":

delete_task_num = int(input("Enter a task number to delete: "))

if delete_task_num == "" or delete_task_num > len(tasks):

print ("Invalid task number.")

else:

tasks.remove(tasks[delete_task_num])

```

## Helpful Links
[ChatGPT](https://chatgpt.com/)
[Google](https://google.com )

_yo_! Whats up!
__HI__! how are you?
___hello world__




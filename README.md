tasks = []

task1 = input("Enter a task: ")
tasks.append(task1)

task2 = input("Enter another task: ")
tasks.append(task2)

print("\nYour To-Do List:")
for task in tasks:
    print("-", task)
    

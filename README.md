# Create-a-simple-to-do-list-application-where-users-can-add-update-and-remove-tasks.
class ToDoList:
    def __init__(self):
        self.tasks = []

    def add_task(self, task):
        self.tasks.append(task)

    def remove_task(self, task):
        self.tasks.remove(task)

    def show_tasks(self):
        for task in self.tasks:
            print(task)

todo = ToDoList()
todo.add_task("Buy groceries")
todo.add_task("Do laundry")
todo.show_tasks()

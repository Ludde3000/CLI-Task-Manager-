# CLI-Task-Manager-
My take on a Task manager that is fully controlled from the terminal and uses a json-file
https://roadmap.sh/projects/task-tracker


How to use the task manager:
It is used in the terminal and the input has to be task-cli and then arguments

ID is the number for the task given in output when adding tasks


adding tasks            adding new tasks
task-cli add 'write what you want to add here'

updating tasks          changing name
task-cli update 'ID' 'new_name'   

deleting                removing tasks
task-cli delete 'ID'

marking tasks           changing the status of tasks to a new status
task-cli mark 'ID' 'new status'

list_tasks              listing tasks by status (todo, in progress, done)
task-cli list                for all tasks
task-cli list 'todo'         for tasks that have todo status 
task-cli list 'in progress'  for tasks that are in progress
task-cli list 'done'         for tasks that are done

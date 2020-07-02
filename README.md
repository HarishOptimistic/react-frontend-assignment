# A Todo App

What do we look for:

1.  Problem understanding and solution
    
2.  Approach on modularity and resusable components
    
3.  Coding standards
    
4.  Use of known libraries and packages only as needed
    

## Requirement
 Build a Todo app with functionalities listed with decent UI ( You can use any UI libraries if you prefer). We hope you know what todo app is all about. If you have any doubts or queries feel free to get in touch.


## Task Element

Task element should have following details.

status: open,cancelled,done
title: task title
desc: task description
created_at : time of creation
due_by: ETA
expected_hours: number of planned hours
priority: high,medium,low (dropdown)
spent_hours: number of hours spent on marking completion
 
Please use a UI design that you see fit just to accomplish the task functionalities. Weigh UX more than UI.

### Component expected in page
1.  Add Task button
2.  Add Task Form - as modal
3.  Update Task Form - as modal
4.  Save and Cancel buttons in forms
5.  Task list seperated across 3 tabs - completed, pending, All Tasks
6.  List of tasks with brief details added while creation.
7.  Global Search option - based on title

## Must haves

1.  Add task flow
2.  Edit Task Flow
3.  Delete Task Flow
4.  Mark as complete, reopen a completed task
5.  Add hours used when marking complete

## Good to have
1. Keyboard shortcuts for various actions
3. Bulk edit and mark as complete


# ** Extra points

1. Statistic dashboard of tasks with counts and numbers of hours deviation etc.
2. Confirmation dialogs for reopen and cancellation
3. Optimise API call - i.e validate submissions if update api or update function need to be called. (Add a logic to identify this. If the data of a task has not changed on clicking the save button, do not make the API call. In short, make the API call only if the data of a task has changed.)
4. Unit Testing

# redux-task

A Side Effects manager for redux. The idea is really simple: we give an asynchronous task(such as fetch data from server) a name, then we can use the name to get the state of the task or cancel it if we want. You will no longer need to set state like `isSubmitting` to indicate asynchronous action state.



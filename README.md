# Multiply-Task-Manager
An async Linux commands monitor! 


## Description

The objective of this project is to create a task manager capable of executing multiple Linux commands concurrently (depends on the number of cpu cores) in the background. Users will be able to queue commands and review the outcomes of completed tasks. By facilitating simultaneous execution of multiple tasks without waiting for one command to finish before initiating another, the task manager will enhance user workflow and boost productivity.

This application is not designed for executing simple commands; rather, its purpose is to concurrently run multiple extensive-duration commands in a centralized location, while offering performance monitoring capabilities.

User inputs, results from completed tasks and data transfer are processed in asynchronous ways so that the task manager will never be blocked for I/O or data transfer in the background. And also wrong or bad Linux commands will be discarded automatically to maintain the task manager in a stable condition.

![async structure](/docs/img/async_struct.png)


# Beginner web course

## About 
The objective of this course is to learn to create a simple (or maybe not so simple) web application. By the end of the course, you should have a client-server web-application, with Angular frontend and Java backend.

This course is intended to be used by beginers, who have never implemented a web application before. Knowledge in programming in general is preferable.

## Methodology

You will work with Github for source versioning control. The steps for setting up the repo and a skeleton for the first protoype will be found [here](https://github.com/Ranapop/web-course/blob/master/weeks/week-1/setup.md).

In each week you will implement some functionalities. These will be divided in tasks. For each task, you will do the development on a 'dev' branch and when you are done with the task, you will request a review before merging any changes on the master. Only if changes are approved, can you merge into the master. Github will allow you to do the merge before as well, but you should not. Please take a look at the last two steps from [here](https://github.com/Ranapop/web-course/blob/master/weeks/week-1/setup.md).

In each week you will receive a requirements file, with the tasks, as well as some resources. If you find helpful resources that are not listed, please feel free to suggest them.

The application will be built iteratively, in the first few weeks only with html and javascript (you can consider this a prototype, but it's mostly intended for learning purposes). Then, the frontend will be migrated to Angular. A server in Java will be implemented, first with in-memory data, then with persisted data. Towards the end, more complex features will be added. 

## Weekly plan 

### [Week1](https://github.com/Ranapop/web-course/blob/master/weeks/week-1) Setup workspace and add first tab
### [Week2](https://github.com/Ranapop/web-course/blob/master/weeks/week-2) Add elements interaction
### [Week3](https://github.com/Ranapop/web-course/blob/master/weeks/week-3) Save and update data
### [Week4](https://github.com/Ranapop/web-course/blob/master/weeks/week-4) Migrate to Angular: Part 1
### [Week5](https://github.com/Ranapop/web-course/blob/master/weeks/week-5) Migrate to Angular: Part 2
### [Week6](https://github.com/Ranapop/web-course/blob/master/weeks/week-6) Add server
### [Week7](https://github.com/Ranapop/web-course/blob/master/weeks/week-7) Persist data 
### [Week8](https://github.com/Ranapop/web-course/blob/master/weeks/week-8) Some complex features 


## The application

The application that you will implement will be one for self-management. You can take a look at the already existing [mocks](https://github.com/Ranapop/web-course/blob/master/images/mocks) to get a better idea.

It will allow users to define life-goals, objectives and tasks. Life-goals are (quite self-explanatory) macro-goals that one hopes to achieve in one's life. To achieve a goal, one can set clear objectives - defined sub-goals. Thus, each goal will have several objectives associated. The objectives can be further broken down into tasks, which are supposed to be at sufficiently fine-grained to be planned during the day. Each life-goal will have a color, which will be propagated down to tasks. In this way, when the user plans his/her day, he will have color-coded tasks, knowing why he/she does each task, giving perhaps, a sense of meaning to his/her life.

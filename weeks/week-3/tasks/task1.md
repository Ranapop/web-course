## 1) Construct the life-goals list in Javascript

Until now, you most probably had the list of goals defined directly in the html. As in the following tasks you will have to dynamically
modify the list, it's better to put it in the javascript already and construct it dynamically. You should define a list of objects, 
something like this: 
```
var lifeGoals = [
    { id: 0, name: 'Vulcanus in Japan', description: 'I want to participate in the "Vulcanus in Japan" project when I finish my Master‘s degree', color: 'blue' },
    { id: 1, name: 'PhD in Austria', description: 'I want to start my PhD in Austria when I return from Japan', color: 'red' },
    { id: 2, name: '3 countries a year', description: 'I want to visit at least 3 countries a year', color: 'purple' }
];
```
Then, you should display the names in the list of life goals (no further interaction is needed for now)
For the list above, the ui should look like this:

![javascript_list_ui](https://github.com/Ranapop/web-course/blob/master/images/mocks/week3/week3_1.png)

# Overview:
This week you will add the following functionalities:
* interract with the list (select life goals)
* add new life goals
* edit existing life goals
You are free to use Javascript or jQuery.
# Tasks
## 1) Construct the life-goals list in Javascript
Until now, you most probably had the list of goals defined directly in the html. As in the following tasks you will have to dynamically
modify the list, it's better to put it in the javascript already and construct it dynamically. You should define a list of objects, 
something like this: 
```
var lifeGoals = [
    { name: 'Vulcanus in Japan', description: 'I want to participate in the "Vulcanus in Japan" project when I finish my Master‘s degree', color: 'blue' },
    { name: 'PhD in Austria', description: 'I want to start my PhD in Austria when I return from Japan', color: 'red' },
    { name: '3 countries a year', description: 'I want to visit at least 3 countries a year', color: 'purple' }
];
```
Then, you should display the names in the list of life goals (no further interaction is needed for now)
For the list above, the ui should look like this:

![javascript_list_ui](https://github.com/Ranapop/web-course/blob/master/images/mocks/week3/week3_1.png)

# Tasks
## 1) Interact with the life-goals list
In this task, you have to add the functionality of interacting with the list of life goals.
Initially (when the page loads), the first item in the list is selected.
Then, as you click on the list, the item you click on is selected (blue color). Besides the item being highlighed in the list, the data in the right panel changes to match the selected item in the list.
If the 'Vulcanus in Japan' list item is clicked, then the following data is shown on the right panel:
![vulcanus_selected](https://github.com/Ranapop/web-course/blob/master/images/mocks/week3/vulcanus_selected.png)
For the 'PhD in Austria' list item:
![vulcanus_selected](https://github.com/Ranapop/web-course/blob/master/images/mocks/week3/phd_selected.png)
And for the '3 countries a year' list item:
![vulcanus_selected](https://github.com/Ranapop/web-course/blob/master/images/mocks/week3/3_countries_selected.png)
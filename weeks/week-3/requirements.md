# Overview:
This week you will add the following functionalities:
* interract with the list (select life goals)
* add new life goals
* edit existing life goals
You are free to use Javascript or jQuery.
# Tasks
## 1) [Construct the life-goals list in Javascript](task1.md) 
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

## 2) Interact with the life-goals list
In this task, you have to add the functionality of interacting with the list of life goals.
Initially (when the page loads), the first item in the list is selected.
Then, as you click on the list, the item you click on is selected (blue color). Besides the item being highlighed in the list, the data in the right panel changes to match the selected item in the list. In this task you only care about the readonly view to be updated.
If the 'Vulcanus in Japan' list item is clicked, then the following data is shown on the right panel:
![vulcanus_selected](https://github.com/Ranapop/web-course/blob/master/images/mocks/week3/vulcanus_selected.png)
For the 'PhD in Austria' list item:
![vulcanus_selected](https://github.com/Ranapop/web-course/blob/master/images/mocks/week3/phd_selected.png)
And for the '3 countries a year' list item:
![vulcanus_selected](https://github.com/Ranapop/web-course/blob/master/images/mocks/week3/3_countries_selected.png)

## 3) Interact with the life-goals list (edit mode)
In this task you have to implement a similar behaviour as for the previous task, but in the scope of this task, it should also work in edit mode. That is, if you enter edit mode (click the edit icon) and interact with the list items by selecting them, the values in the form should change accordingly.
For example, this is how it would look like when clicking on the '3 countries a year' list item while in edit mode:
![selected_edit_mode](https://github.com/Ranapop/web-course/blob/master/images/mocks/week3/3_countries_edit_mode.png)
## 3) Add a "Add life goal" button
For this task you have to:
* add a __"Add life goal"__ button underneath the life goals list (first image)
* clear the data in the form on clicking the button (second image)
![add_button](https://github.com/Ranapop/web-course/blob/master/images/mocks/week3/add_button.png)
![clear_form_on_add](https://github.com/Ranapop/web-course/blob/master/images/mocks/week3/clear_form_on_add.png)

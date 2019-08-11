# The tasks for this week are:
## 1) Add 4 tabs: boostrap style
You have to rewrite your html & css to implement the tabs. The tab content should also change on tab clicking, but use no custom javascript for that. See the mocks folder for more images.
You should not have more functionality than that, even if it means removing old code.
This is how the page looks like when first open. The first tab is automatically selected:
![bootstrap tabs](https://github.com/Ranapop/web-course/blob/master/images/mocks/week2/tabs.png)
This is what happens when the __Objectives__ tab is selected:
![bootstrap tabs](https://github.com/Ranapop/web-course/blob/master/images/mocks/week2/tabs_objectives_selected.png)
This is what happens when the __Tasks__ tab is selected:
![bootstrap tabs](https://github.com/Ranapop/web-course/blob/master/images/mocks/week2/tabs_tasks_selected.png)
This is what happens when the __Calendar__ tab is selected:
![bootstrap tabs](https://github.com/Ranapop/web-course/blob/master/images/mocks/week2/tabs_calendar_selected.png)
## 2)  Add life-goals list: boostrap style
For this task you have to add the list of life goals to the page. 
You should make the list look as in the following mock, using as little custom css as possible. It is not in the scope of this task to have the list interactable. The first element is always selected, clicking on the items results in nothing. 
![bootstrap tabs](https://github.com/Ranapop/web-course/blob/master/images/mocks/week2/tabs_list.png)

## 3)  Add life-goal view section: boostrap style
For this task you have to add the view section of a life goal. Unlike the mock from week-1, it doesn't contain the related objectives.
The view section is to be placed in the right of the list, as in the mockup. It should contain:
* an edit icon in the top right, the same color as the unselected tabs
* three fields with labels and content:
  * name
  * description
  * color
  
It is not in the scope of this task to add make the edit icon responsive, or to make the list on the left responsive. The content will for now be hardcoded in html.
You need to write the code in such a way that the list group and the view section occupy the whole screen also when resizing, each taking about half. Please use the [Bootstrap Grid System](https://getbootstrap.com/docs/4.0/layout/grid/) for that.
This is how it should look like on a wide screen:

![wide screen](https://github.com/Ranapop/web-course/blob/master/images/mocks/week2/readonly_section_large.png)
And this is how it should look like on a small screen:

![small screen](https://github.com/Ranapop/web-course/blob/master/images/mocks/week2/readonly_section_small.png)

## 4) Interact with the edit button: javascript time
For this task you have to add a view-edit section to the page. When our user clicks on the edit button, he/she should be able to edit the data, and go back to the readonly view once he clicks submit. 
In this task you must:
* add styling to the edit button on hover
* load an editable form on clicking edit
* go back to the readonly view when clicking submit
It is not in the scope of this task to:
* save the data when submiting. If something is modified, the old data will be visible on submit (basically hardcoded in the html for now)
This is how the edit button should look on hover:
![edit_hover](https://github.com/Ranapop/web-course/blob/master/images/mocks/week2/edit_button_hover.png)
This is the form that appears on clicking the edit button:
![edit_click](https://github.com/Ranapop/web-course/blob/master/images/mocks/week2/edit_button_click.png)
This is how a color can be selected:
![edit_select_box](https://github.com/Ranapop/web-course/blob/master/images/mocks/week2/edit_button_click_select_box.png)



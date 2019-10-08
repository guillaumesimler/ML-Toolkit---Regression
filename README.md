# Machine Learning Toolkit - Templates for Regression

## Aims and origin

### Aims
_Why reinvent the wheel?_
 
The following templates can be used to jump start Machine Learning projects by using predefined templates.

### Origin 

These templates were adapted from the Udemy course, **[Machine Learning A-Z™: Hands-On Python & R In Data Science](https://www.udemy.com/course/machinelearning/)**.

I added the following changes:
- migration to _Jupyter Notebook_, my preferred data science interface, from _Spyder_, used in the course
- higher use of variables

## Structures

### Pycharm project 

I used Pycharm for editing this repository. Consequently, pycharm project settings are included in

```
~/.idea
``` 

This simplifies my commits. Feel free to delete the folder if you fork or clone the repo. 

### Conda env

Lesson learnt from previous developments, **pip** & **virtual env** might be great for productive use. 

However, it is painful in data science development. A conda distribution, **Anaconda** or **Miniconda**, is far more 
helpful. 

The config file (.yml) is attached to the repo.

## Generic approach

Contrary to the usual data _scientist_ approach, the module are imported on top of the file and not in the specific cells.

## License

The files are licensed under an **MIT License**. Please have a look at the attached file.
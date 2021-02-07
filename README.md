1. Install python (I used 3.7).
2. pip is a package-management system used to install and manage software packages written in Python (similar like npm).pip is inside of python folder.
3. Set 2 environment variables. .\Python\python37-32\  and .\Python\python37-32\Scripts.
4. Verify in cmd: python --version; pip --version.
5. Create Virtual Environments:A virtual environment is a tool that helps to keep dependencies required by different projects separate by creating isolated python virtual environments for them.
> pip install virtualenv

> pip install virtualenvwrapper-win

> python -m virtualenv <nameOfEnv>  [command we will create a virtual environment, then create project directory and then finally bind the environment to the project directory.]

> cd amazon

> setprojectdir .

6. We can deactivate the environment by typing in command deactivate or exiting the command prompt. However, if we want to work more on our project using this environment, we simply need to type virtualenv activate.
> pip install selenium

> pip check selenium

> pip show selenium

7.Installing ChromeDriver, under name ‘Drivers’ in project folder

8. Create __init__.py file in each folder, so that python will consider these folders as standard package.

9. If the unittest html report not generated then deactivate and reactivate virtual env as mentioned # 6.

10. __init__() in python like constructor in Java and self like this keyword in Java.

11. if __name__ == '__main__': __name__ is a built-in variable in python that stores the name of the current module/script being executed. If the current module is executing then the __name__ variable is assigned the value __main__ otherwise it simply contains the name of the imported module or script.

12. Execute script: python tests/AllTests.py -v Test_AMZN_Search

##### Reference:

https://medium.com/@asheeshmisra29/web-automation-selenium-webdriver-and-python-getting-started-part-3-a9c07143d36d




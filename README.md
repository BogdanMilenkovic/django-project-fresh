# django-project-fresh
Just creating a new project of Django


1] After opening the Windows powershell, we need to install virtualenvwrapper.

pip install virtualenvwrapper-win

2] Now, we'll create a virtual environment for a project

mkvirtualenv mywebsite

3] To activate the environment mywebsite we have to run the following command.

workon mywebsite

4] Next, we are going to install Django with the pip command

pip install django

5] You can check the django version by executing the following command.

python -m django --version

6] We'll set the current directory to C drive.

cd \

7] The next step is to create a new directory to store the new project that we are going to work on. In this case it will be webdesign.

mkdir newdir

Once you create the directory, set it as the current directory.

cd newdir

8] Now, we need to startproject with the django-admin startproject projectname where we will replace the projectname with a name of the project.

As I have mentioned already it this case it will be webdesign.

django-admin startproject webdesign

9] Set the current directory to the project directory i.e webdesign.

cd webdesign

10] After that is done simply run the

python manage.py runserver
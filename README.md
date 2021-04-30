# EmployeeHRMS

git clone https://github.com/sky98199/EmployeeHRMS.git

pip install requirements.txt

python manage.py migrate

python manage.py runserver



## Beanstalk

upload the zip to beanstalk environment. 

requirements.txt folder will install all the required module 
.ebextensions folder will take care of WSGI path

## CodeBuild Stage

Use buildspec.yml file for CodeBuild stage

Note: you can add any more test cases if required.

# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:

Created table and inserted values to it in the django applications
### STEP 2:
Implementation of python code in README.md file

### STEP 3:

Uploading the necessary files

## PROGRAM
```python
from django.db import models
from django.contrib import admin

class Bikesinfo(models.Model):
    registrationno = models.CharField(max_length=10,primary_key=True)
    brandname = models.CharField(max_length=100)
    mileage = models.IntegerField()
    dateofmanufacture = models.DateField()
    modelname = models.CharField(max_length=100)

class BikesinfoAdmin(admin.ModelAdmin):
    list_display = ('registrationno','brandname','mileage','dateofmanufacture','modelname')

```


## OUTPUT




## RESULT 
The program was executed successfully.


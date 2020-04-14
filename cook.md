# mkpycode

import calendar
import datetime
import time
from turtle import *

forward(100)
right(120)
forward(100)
left(100)
forward(100)

current_time = datetime.datetime.now()

print("COOKING...")
print()
print()



def cook(chicken):
    if chicken > 0:
        print("Cooking..")
        cut(onion)
        ready = fry(onion)
        if ready == True:
            print("Finished cooking")
            return ready


def fry(item):
    minutes = 8
    if item > 0 and minutes > 0:
        #add(oil)
        print(current_time)
        i = 1
        print("Frying...")
        for i in range (9):
            print("Frying...")
            print( "Minutes remaining...", '[' + str(minutes)+ ']')
            print("Year : ", end= "")
            print(current_time.year)
            print("Month : ", end="")
            print(current_time.month)
            print("Day : ", end="")
            print(current_time.day)
            print("mHour : ", end="")
            print(current_time.hour)
            print("Minute : ", end="")
            print(current_time.minute)
            print("Second : ", end="")
            print(current_time.second)
            minutes = minutes - 1
            if minutes == 4:
                #add(salt)
               if minutes <= 0:
                  ready = True
               else:
                  ready = False
    return ready


def cut(item):





#def add(Item)
    pass


#def server(food)
    pass

salt = 5 #grams
oil = 500 #mililiters
onion = 5
chicken = 1


print("Something added at the end")

fry(onion)

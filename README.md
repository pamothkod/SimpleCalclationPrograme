# SimpleCalclationPrograme
# This python groramme
import math
# simple calculater
def mycal(num1,num2,operater):
    if operater == 'a':
            print ("output:", num1+num2)
    elif operater == 's':
        if num1<num2:
               print ("output:", num2-num1)
        else:
               print ("output:", num1-num2)
    elif operater == 'm':
            print ("output:", num1*num2)
    elif operater == 'd':
            print ("output:" ,num1/num2)
    else:                                                                                                         
            print ( "Invalid input")
# Run function for division, when num1=2 and num2=5 
mycal(2,5,'d')program is write for addition, substraction, devition and multiplication 

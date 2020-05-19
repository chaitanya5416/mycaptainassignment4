# mycaptainassignment4
#assigning elements to different lists

#creating a list
list=[]
print("initial blank list:")
print(list)
list.append(1)
list.append(2)
list.append(3)
print("\n list after assigning elements:")
print(list) #list after assigning elements


#accessing elements from a tuple
tuple1 = (0 ,1, 2, 3)
print("accessing elements from a tuple")
print(tuple1[1:])  
print(tuple1[2:4])
#deleting elements from a dictionary
# Initializing dictionary 
test_dict = {"Arushi" : 22, "Anuradha" : 21, "Mani" : 21, "Haritha" : 21} 
  
# Printing dictionary before removal 
print ("The dictionary before performing remove is : " + str(test_dict)) 
  
# Using del to remove a dict 
# removes Mani 
del test_dict['Mani'] 
  
# Printing dictionary after removal 
print ("The dictionary after remove is : " + str(test_dict)) 
  
     

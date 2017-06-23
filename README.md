# Python-3-tricks

for i in range(len(list)): 
  print(list[i])           #This uses indexes to loop through the list, allowing us to modify the list.
  
  #you can add lists. e.g., 
  a = [1,2,3] b= [4, 5, 6]
  x = a + b
  print(x) # gives 1, 2, 3, 4, 5, 6
  #function would look like:
    def join(a, b):
      x = a +b
      return x
  
  #you can add to a string like this:
  empty_string = ""
  for whatever is whatevs:
    empty_string += whatever

list_with_lists = [[1, 2, 3], [4, 5, 6]]
for a_list in list_with_lists:
  for x in a_list:
    print(x) # this prints each number. ikr.
    
# how to get a key's value from a dictionary
d = {'x': 9, 'y': 10, 'z': 20}
for key in d:
  if d[key] == 10 #use list[key]

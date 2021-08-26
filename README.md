# working-with-data-structure
#Union
def union(set1, set2):
    return set(set1).union(set2)
#Driver code
set1 ={0, 2, 3, 4, 5, 6, 8}
set2 ={1, 2, 3, 4, 5}
print(union(set1, set2))


#intersection
def intersection(set1, set2): 
    return set(set1)&(set2)
# Driver Code 
set1 ={0, 2, 4, 6, 8}
set2 ={1, 2, 3, 4, 5}
print(intersection(set1, set2))


#Difference
set1 = {0, 2, 3, 4, 5, 6, 8}
set2 = {1, 2, 3, 4, 5}
set_difference = (set1) - (set2)
set_difference = set(set_difference)
print(set_difference)


# Python code to find the symmetric_difference 
# Use of symmetric_difference() method 
set_A = {0, 2, 4, 6, 8} 
set_B = {1, 2, 3, 4, 5, } 
print(set_A.symmetric_difference(set_B)) 

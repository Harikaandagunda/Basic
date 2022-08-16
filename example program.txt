# Import sample() function from the random module using the import keyword.
from random import sample
# Give the list as static input and store it in a variable.
gvn_lst = [24, 4, 5, 9, 2, 1]
# Give the length of the sample as static input and store it in another variable.
len_sampl = 3
# Pass the given list, sample length as the arguments to the sample() method
# to get given length(len_sampl) of random sample items from the list
# Store it in another variable.
rslt = sample(gvn_lst, len_sampl)
# Print the above result.
print("The", len_sampl, "random items from the given list are:")
print(rslt)
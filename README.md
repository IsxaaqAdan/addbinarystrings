# addbinarystrings
given two binary strings a and b, return their sum as a binary string.
class Solution(object):
    def addBinary(self, a, b):
        # Convert the binary strings to integers
        num_a = int(a, 2)
        num_b = int(b, 2)
        
        # Add the integers
        sum_ab = num_a + num_b
        
        # Convert the sum to a binary string and return it
        return bin(sum_ab)[2:]

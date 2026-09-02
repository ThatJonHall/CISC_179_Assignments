var1 = 10
print(hex(id(var1)))
# 0x10411cd50 - output 

var1 = 100
print(hex(id(var1)))
#0x102d94d50 - output

#There are two different address because each time it creates a new variable it's like making it from 
#scratch, so it also has a new location in volatile memory. 

var2 = 100 
print(hex(id(var2)))

#No, my hex memory address was the same for both variables....

#Address in hexadecimal 	Char
# 	0x104e45c30
# 	0x104d39130 
# 	0x104d33c70
# 	0x104d33c70
# 	0x104cb21b0
# 	0x104d33e70
# 	0x104cb21b0
# 	0x104bf38b0
# 	0x104d33c70
#.  0x104cb2070

# x + y                             |     godcat
# "the " + x + "chases the " + y.   |.    the dog chases the cat
# X * 4                             |.    dogdogdogdog

X = 50
X = 50+1

# Troubleshooting
#A seems okay to me. It's putting the string hello into the variable hello. 
#B Also seems okay, _ are awesome I use them all the time
#C Can't start with a !
# I think this would work, print is a function, you are just breaking it to also print "print me" This would ruin all your other prints statements 
# False is one of the those reserved python words. You're gonna have a bad time.

# The biggest challeges was the last toubleshooting exercise. I remembered some, like the print = "print me" from another coding thing awhile back, but I had to do some goolging for the others. 

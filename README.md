#String Creation
Creating strings using single quotes, double quotes, and triple quotes(multiline)
#single_quote = 'Hello World'
#Double_quote = "Hello World"
#Multiline = '''Follow \nBradnexttdoor.instagram''' 

#String Indexing
S = "Python"
#Accesing characters using indexing
print(s[O]) #First character

#String Slicing
string sublicing
print(s[1:4])   #Substring from index 1 to 3
print(s[:5]).   #Substring from start to index 4
print(s[::2])   # Every other character

#Concatenation and Repetition
# Concatenating string using + and repeating strings using *
concatenated = ' Follow'+ ' ' + 'Pycode.hub'
repeated = 'Hi!' * 3

# Printing the results 
print(concatenated)  # Concatenated String
print(repeated). # Repeated string

OUTPUT
Follow pycode.hub
Hi! Hi! Hi!

strip() method
# strip loading and trailing spaces
print(s.strip()) # Remove loading/trailing spaces

OUTPUT
Follow Pycode.Hub!

replace() method
# Replace substring
print(s.replace('Follow', 'subscribe')) # Replace 'Follow' with 'subscribe'

OUTPUT
subscribe pycode.Hub!

split() method
#split string by spaces
print(s.split()) # Split sytring by spaces

OUTPUT
['Follow', subscribe, pycode.hub'!] ****

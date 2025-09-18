#Exercise 3.25

#penggunaan_finding 
message = "Aku suka alogoritma dan pemograman."
pemograman_present = 'pemograman' in message
print(pemograman_present)

#penggunaan_replace
message = "Aku suka algoritma dan pemograman, tapi aku lebih suka membuat coding."
message = message.replace('pemograman', 'membuat coding')
print(message)
 
#penggunaan_count 
number_membuatcoding = message.count("Aku suka algoritma dan pemograman, tapi aku lebih suka membuat coding.")
print(number_membuatcoding)

#penggunaan_split
message = ("Aku suka algoritma dan pemograman, tapi aku lebih suka membuat coding.")
words = message.split(' ')
print(words)

#penggunaan_rfind
message = ("Aku suka algoritma dan pemograman, tapi aku lebih suka membuat coding.")
last_membuat_coding_index = message.rfind('membuat coding')
print(last_membuat_coding_index)

#Exercise 4.2

#penggunaan_if statement
people = ['valen', 'dela', 'cia','andre']
if len(people) > 3:
    print("Ruangan terlalu ramai")

people = ['valen', 'dela']
if len(people) >3:
    print("Ruangan terlalu ramai")
else:
    print("Ruangan hanya cukup untuk satu orang")
    
#Exercise 4.3
people = ['valen', 'dela', 'cia','andre','anin',]
if len(people) >5:
    print("Ruangan terlalu ramai")
if len(people) >2:
    print("Ruangan tidak terlalu ramai")
else:
    print("Ruangan tidak ramai")
    
#Exercise 4.4
people = ['valen', 'dela', 'cia','andre','anin','raye']
if len(people) >5:
    print("Terdapat kerumunan di dalam ruangan")
if len(people) >3:
  print("Ruangan terlalu ramai")
if len(people) >2:
    print("Ruangan tidak ramai")
else:
    print("Ruangan sepi")
    

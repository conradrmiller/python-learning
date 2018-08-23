# python-learning
Basic python experiments for learning 

import random
correct = 0
for iteration in range(0,10):
    k = random.randint(10000, 10000000)
print("Prime or Not: Is the number ",k," prime? (yes or no)")
answer = input()
isprime = "yes"
isprime = True
for n in range(1, int(k/2)):
    if k%n == 0:
        isprime = "no"
if isprime==answer:
    print("You are correct!")
    correct = correct + 1
else:
    print ("You are incorrect.")
print ("You gave ",correct," right answers out of 10.")

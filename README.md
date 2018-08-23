# python-learning
Basic python experiments for learning 

choice = "scissors"
print("rock-paper-scissors: type in your choice:   ")
player = input()
if player == choice:
    print("Game is a tie. Please try again.")
else:
    if player == "rock":
        if choice == "scissors":
            print("Congratulations. You win.")
        else:
            print("Sorry - computer wins.")
    if player == "paper":
        if choice == "scissors":
            print("Sorry - computer wins.")
        else:
            print("Congratulations. You win.")
    if player == "scissors":
        if choice == "rock":
            print("Sorry - computer wins.")
        else:
            print("Congratulations. You win.")


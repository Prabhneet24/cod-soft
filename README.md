import random
user_choice=int(input("Enter your choice: Type 0 for Rock, 1 for Paper, 2 for Scissor: "))
computer_choice=random.randint(0,2)
print("Computer Chose:")
print(computer_choice)

if computer_choice == user_choice:
  print("It's a draw.")
elif computer_choice > user_choice:
  print("You loose")
elif computer_choice < user_choice:
  print("You win.")
elif computer_choice == 0 and user_choice == 2:
    print("You loose")
elif user_choice == 0 and computer_choice ==2:
  print("You win")

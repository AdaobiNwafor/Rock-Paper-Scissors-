import random

print('The rules for this game are as follows') 
print('If you win, you gain (1) point and if you tie, you gain (0.5) points.')
print('However if you lose, you lose (2) points. When you are ready to proceed, follow the instructions.')
print('The input is case - sensitive.')
intro = input('Are you ready to Proceed? (y/n): ')
if intro != 'y':
    pass
    
score = 0
total = 0
        
while True:
    
    user = input('Choose Rock, Paper or Scissors: ')
    actions = ['Rock', 'Paper', 'Scissors']
    c_actions = random.choice(actions)
    
    
    if user == c_actions:
        score += 0.5
        print(f'You and the computer chose {user}, It"s a TIE!')
        print(f'Your score for this round is {score}!')
    elif user == 'Rock':
        if c_actions == 'Scissors':
            score += 1
            print(f'You chose {user} and computer chose {c_actions}. You WIN!')
            print(f'Your score for this round is {score}!')
        else:
            score -= 2
            print(f'You chose {user} and computer chose {c_actions}, You LOSE!')
            print(f'Your score for this round is {score}!')
    elif user == 'Paper':
        if c_actions == 'Rock':
            score += 1
            print(f'You chose {user} and computer chose {c_actions}, You WIN!')
            print(f'Your score for this round is {score}!')
        else:
            score -= 2
            print(f'You chose {user} and computer chose {c_actions}, You LOSE!')
            print(f'Your score for this round is {score}!')
    elif user == 'Scissors':
        if c_actions == 'Rock':
            score -= 2
            print(f'You chose {user} and computer chose {c_actions}, You LOSE!')
            print(f'Your score for this round is {score}!')
        else:
            score += 1
            print(f'You chose {user} and computer chose {c_actions}, You WIN!')
            print(f'Your score for this round is {score}!')
            
    
  
    total =+ score
    
    play_again = input('Do you want to play again? (y/n): ')
    if play_again.lower() != 'y':
        know_score = input('Do you want to know your final score? (y/n): ')
        if know_score.lower() == 'y':
            print(f'Your Total score is {total}')
            print('Hope to see you again')
            break

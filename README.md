import random

def draw_marble():
    # Representing marbles as numbers: 1, 2, 3 for success and 4, 5, 6 for failure
    marble = random.randint(1, 6)
    
    # Check if the drawn marble is a success (1, 2, 3)
    if marble <= 3:
        return True
    else:
        return False

# Example usage
if draw_marble():
    print("Success! You drew a marble.")
else:
    print("Failure. Better luck next time.")

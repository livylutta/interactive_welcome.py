# An interactive Python script for the GitHub assignment

def interactive_greeting():
    """
    This function asks the user for their name and prints a
    personalized greeting.
    """
    project_title = "Interactive Welcome Project"
    
    print("-------------------------------------------")
    print(f"🚀 Welcome to the {project_title}!")
    print("-------------------------------------------")

    # Ask the user for their name and store it in a variable
    name = input("Please enter your name: ")
    
    # Print a personalized message
    print(f"\nHello, {name}! Welcome to the assignment.")
    print("This script demonstrates how to handle user input in Python.")

# This is the standard way to make a Python script runnable
if __name__ == "__main__":
    interactive_greeting()

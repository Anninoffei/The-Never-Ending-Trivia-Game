import requests

url = "https://opentdb.com/api.php?amount=1&category=12&difficulty=easy&type=multiple"

play_again = True
while play_again:
    response = requests.get(url)
    data = response.json()
    
    question = data["results"][0]["question"]
    correct_answer = data["results"][0]["correct_answer"]
    
    print(question)
    user_answer = input("Your answer: ")
    
    if user_answer.lower() == correct_answer.lower():
        print("Correct!")
    else:
        print(f"Wrong. The correct answer is {correct_answer}")
        
    play_again_input = input("Play again (y/n)? ")
    if play_again_input.lower() != "y":
        play_again = False
        print("Thank you for playing!")

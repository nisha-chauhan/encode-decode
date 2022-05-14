from operator import truediv
from art import logo
print(logo)
alphabet = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z','a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z']

def caesar(start_text,shift_amt,chipher_direction):
    end_text=""
    if chipher_direction=="decode":
        shift_amt*= -1
        
    for letter in start_text:
        if letter in alphabet:
            position=alphabet.index(letter)
            new_position=position+shift_amt
            # new_letter=alphabet[new_position]
            end_text+=alphabet[new_position]
        else:
            end_text+=letter
    print(end_text)

run=True
while run:
    direction=input("Type 'Encode'to Encypt and 'Decode' to Decrypt the message:\n").lower()
    text= input("enter your text:\n").lower()
    shift=int(input("Enter the shift ammount:\n"))
    shift=shift%26
    caesar(start_text=text,shift_amt=shift,chipher_direction=direction)
    user= input("type'yes' if you want to continue and 'no' if you want to exit:\n")
    if user=='no':
        run=False
        print("you choose 'NO' so your programme terminates here\n GoodBye")

        
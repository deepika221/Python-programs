def missing_characters_to_pangram(input_string):
    # Define the full alphabet
    alphabet = set('abcdefghijklmnopqrstuvwxyz')
    
    input_chars = set(input_string.lower())
    
    missing_chars = alphabet - input_chars
    
    sorted_missing_chars = sorted(missing_chars)
    
    return ''.join(sorted_missing_chars)

# Input reading
input_string = input()
result = missing_characters_to_pangram(input_string)
print(result)

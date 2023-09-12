Refer .capitalize() and Replicate .upper() and .lower() Functions:
text = "hello world"

capitalized_text = text.capitalize()
upper_text = text.upper()
lower_text = text.lower()

print("Original Text:", text)
print("Capitalized:", capitalized_text)
print("Upper Case:", upper_text)
print("Lower Case:", lower_text)

Create an Odd Sequence:
sequence = [1, 2, 34, 65, 1, 2, 65, 66, 44, 33, 22, 87, 123412, 9, 78, 76]

odd_sequence = [num for num in sequence if num % 2 != 0]
print("Odd Sequence:", odd_sequence)

Filter Fruits with More Than 20:
fruits = {'apple': 10, 'mango': 20, 'pineapple': 25, 'orange': 30, 'strawberry': 50, 'jackfruit': 10}

fruits_more_than_20 = {fruit: quantity for fruit, quantity in fruits.items() if quantity > 20}
print("Fruits with More Than 20:", fruits_more_than_20)
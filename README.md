def count_odd_even_numbers(numbers):
    odd_count = 0
    even_count = 0

    for num in numbers:
        if num % 2 == 0:
            even_count += 1
        else:
            odd_count += 1

    return odd_count, even_count


# Test the function with the given list
numbers = [2, 3, 4, 55, 56, 78, 75, 69, 66, 101, 100]
odd_count, even_count = count_odd_even_numbers(numbers)

print("Number of odd numbers:", odd_count)
print("Number of even numbers:", even_count)

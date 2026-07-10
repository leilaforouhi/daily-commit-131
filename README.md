def filter_positive_numbers(numbers):
    return [number for number in numbers if number > 0]

if __name__ == "__main__":
    values = [-5, 10, -3, 8, 0, 15, -1]

    print(f"Numbers: {values}")
    print(f"Positive numbers: {filter_positive_numbers(values)}")

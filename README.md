# rate
def calculate_refinancing_rate(old_rate, new_rate):
    return old_rate - new_rate

# Example usage
if __name__ == "__main__":
    old_rate = 5.0  # Old refinancing rate
    new_rate = 4.5  # New refinancing rate

    refinancing_difference = calculate_refinancing_rate(old_rate, new_rate)
    print(f"The difference in refinancing rates is: {refinancing_difference} percentage points")

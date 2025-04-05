# speed-formula
def calculate_speed(distance, time):
    """Calculate speed given distance and time."""
    if time <= 0:
        return "Time must be greater than zero!"
    return distance / time

# Example usage
distance = 100  # meters
time = 10  # seconds
speed = calculate_speed(distance, time)
print(f"Speed: {speed} m/s")
rare

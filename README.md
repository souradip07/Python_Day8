# Python_Day8
#Project: Develop a Program to Average Signal Data from an Array of Readings
def average_signal_readings(readings):
    """
    Calculate the average of signal readings.

    Parameters:
    readings (list): A list of signal readings.

    Returns:
    float: The average of the signal readings.
    """
    if not readings:
        return 0
    
    total = sum(readings)
    count = len(readings)
    average = total / count
    return average

# Example usage:
signal_readings = [10, 12, 15, 14, 11, 13, 12, 14]
average = average_signal_readings(signal_readings)
print(f"The average signal reading is {average:.2f}")

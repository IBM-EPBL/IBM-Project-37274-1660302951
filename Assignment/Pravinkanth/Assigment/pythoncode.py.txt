#importing random function
import random  

# Generating random Temperature data.
Temperature = random.sample(range(0, 120), 10)
print("Temperature data = ", Temperature)

# Generating random Humidity data.
Humidity = random.sample(range(40, 90), 10)
print("Humidity data = ", Humidity)

#Condition to Detect Alarm.
for i in Temperature:
    if(i>80):
        print(f"{i} Exceeds Normal temperature. Alarm Detected")
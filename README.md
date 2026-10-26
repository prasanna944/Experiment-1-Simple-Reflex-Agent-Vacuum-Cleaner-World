# Experiment-1-Simple-Reflex-Agent-Vacuum-Cleaner-World
print("Vacuum Cleaner World")

location = input("Enter current location (A/B): ").upper()
status = input("Enter room status (Clean/Dirty): ").capitalize()

if status == "Dirty":
    action = "Suck"
elif location == "A":
    action = "Move Right"
elif location == "B":
    action = "Move Left"
else:
    action = "Invalid location"

print("\nCurrent Location:", location)
print("Room Status:", status)
print("Action Performed:", action)

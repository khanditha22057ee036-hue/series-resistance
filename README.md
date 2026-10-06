# Series Resistance Calculation
# Formula: R_total = R1 + R2 + R3 + ... + Rn

n = int(input("Enter the number of resistors: "))

total_resistance = 0

for i in range(1, n + 1):
    resistance = float(input(f"Enter resistance R{i} (Ohms): "))
    total_resistance += resistance

print("Total Series Resistance =", total_resistance, "Ohms")
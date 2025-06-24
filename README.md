# Kirthi-date-time-
from datetime import datetime, date

# 1. Get current date and time
current_dt = datetime.now()
print("✅ Current Date and Time:")
print(current_dt)
print("-" * 40)

# 2. Calculate difference between two dates
date1 = date(2025, 6, 24)
date2 = date(2025, 7, 15)
difference = date2 - date1
print("✅ Difference between two dates:")
print(f"From {date1} to {date2} = {difference.days} days")
print("-" * 40)

# 3. Convert timestamp to datetime
timestamp = 1750750800  # Example: 2025-07-24 10:00:00
dt_object = datetime.fromtimestamp(timestamp)
print("✅ Convert Timestamp to Datetime:")
print(f"Timestamp {timestamp} = {dt_object}")

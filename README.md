# fluffy-waffle
import time

def simulate_traffic():
    timestamps = []
    for i in range(5):
        timestamps.append(time.time())
        time.sleep(0.5)
    return timestamps

print(simulate_traffic())

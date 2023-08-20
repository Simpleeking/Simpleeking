import time

def traffic_light():
    while True:
        print("Red light - Stop")
        time.sleep(5)
        
        print("Green light - Go")
        time.sleep(5)
        
        print("Yellow light - Prepare to stop")
        time.sleep(2)

traffic_light()

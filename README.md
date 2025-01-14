...
# Vicinity
## Purpose:
 To track the presence of a laptop user and lock the system when the user is absent
 
## Features:
 #### 1. Face Recognition:
- Use OpenCV to detect the presence of a user in front of the laptop.
- Use a machine learning model to identify the user using the laptop's built-in webcam.
#### 2. Auto-locking:
- Automatically lock the system after a certain amount of time.
- Create a timer-based feature to automatically lock the system after a certain amount of time of inactivity.
#### 3. Locking:
- Pause all open applications and lock the system when the user is absent.
- Use OpenCV's face recognition capabilities combined with a machine learning model trained to recognize the user's face to detect if another person is attempting to use the laptop.
#### 4. Notification system:
- Alert the user when the program is about to lock the system, giving them a chance to save any unsaved work before the system locks.
 Outputs:
- Record video or take snapshot of interloper.
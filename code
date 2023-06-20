# lock_system.py

class LockSystem:
    def __init__(self, password):
        self.password = password
        self.locked = True

    def unlock(self, password_attempt):
        if password_attempt == self.password:
            self.locked = False
            print("Lock system unlocked")
        else:
            print("Incorrect password")

    def lock(self):
        self.locked = True
        print("Lock system locked")

    def is_locked(self):
        return self.locked

# Example usage
lock = LockSystem("1234")

lock.unlock("4321")  # Incorrect password
lock.unlock("1234")  # Correct password

if not lock.is_locked():
    print("Access granted")
else:
    print("Access denied")

lock.lock()

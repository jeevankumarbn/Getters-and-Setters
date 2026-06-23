class BankAccount:
    def __init__(self , balance):
        self.__balance = balance

    def get_balance(self):
        return self.__balance
    
    def set_balance(self , balance):
        self.__balance = balance
    
b = BankAccount(1000)
print(b.get_balance())

b.set_balance(2000)
print(b.get_balance())

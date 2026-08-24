def calculate_balance(transactions):
    balance = 0

    for transaction in transactions:
        balance += transaction

    return balance


if __name__ == "__main__":
    transactions = [150, -40, 75, -25, 100]

    print(f"Transactions: {transactions}")
    print(f"Final balance: {calculate_balance(transactions)}")

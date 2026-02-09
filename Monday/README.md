# 📅 Monday: The "Payment Gateway" 
## Part 1A: Create an interface PaymentMethod with:
- void authorize(double amount)
- boolean isFlaggedForFraud()

Then, create an Abstract Class called DigitalWallet that implements PaymentMethod.

- Why might this class be Abstract? ❗Please write your answer as a comment
- Add a protected method void deductBalance(double amount) that subclasses can use.
## Part 1B: Create two concrete classes:
- CreditCard (Directly implements PaymentMethod): Needs a limit and currentDebt. The authorize method should fail if the amount exceeds the limit.
- CryptoWallet (Extends DigitalWallet): Needs a walletAddress. The authorize method must check if the balance is sufficient and then call deductBalance.

The Challenge: In your main method, create a List<PaymentMethod> checkoutCart. Add one Credit Card and two different Crypto Wallets. Loop through them and call authorize(100.0).

## Part 1C: Write a method called processRefunds(List<PaymentMethod> methods).
- If the method is a DigitalWallet, cast it and print "Refunding to email: [email]".
- If it is a CreditCard, print "Adjusting debt for cardholder."
- Hint: Use instanceof and Type Casting correctly to access the email/debt fields that aren't in the base interface.


See you tomorrow! 

![Describe the GIF here](https://media0.giphy.com/media/v1.Y2lkPTZjMDliOTUyZW1rbnhoOW4wNnFqZ2c5cjFzbnJrenpyYzFhd2g5NTNiazJseWNyciZlcD12MV9naWZzX3NlYXJjaCZjdD1n/3ov9jIYPU7NMT6TS7K/200w.gif)


# Coffee Delivery — Test Cases

## Module: Checkout & Payment

### TC-01: Successful checkout with valid payment details
Precondition: Products are added to the shopping cart.

Steps:
1. Open the shopping cart.
2. Proceed to checkout.
3. Enter a valid delivery address.
4. Enter valid payment details.
5. Confirm the order.

Expected result: The order is successfully placed.

### TC-02: Checkout with an empty required address field
Precondition: Products are added to the shopping cart.

Steps:
1. Open the shopping cart.
2. Proceed to checkout.
3. Leave the delivery address field empty.
4. Fill in the remaining required fields.
5. Confirm the order.

Expected result: The system displays a validation error and does not place the order.

### TC-03: Payment with an invalid card number
Precondition: Products are added to the shopping cart.

Steps:
1. Open the shopping cart.
2. Proceed to checkout.
3. Enter a valid delivery address.
4. Enter an invalid card number.
5. Confirm the payment.

Expected result: The system displays a validation error and does not complete the payment.
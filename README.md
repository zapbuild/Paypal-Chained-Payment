Paypal-Chained-Payment
======================

This Repository contain a component to perform chained payment in paypal.

What is Chained Payment?

Chained Payments

A chained payment is a payment from a sender that is indirectly split among multiple receivers. It is an extension of a typical payment from a sender to a receiver, in which a receiver, known as the primary receiver, passes part of the payment to other receivers, who are called secondary receivers.

Note: The API caller must get permission from PayPal to use chained payments.

You can have at most one primary receiver and 1-9 secondary receivers. Chained payments are useful in cases when the primary receiver acts as an agent for other receivers. The sender deals only with the primary receiver and does not know about the secondary receivers, including how a payment is split among receivers.

For further information on how a Chained payment work step by step you can follow below link:

https://developer.paypal.com/docs/classic/adaptive-payments/ht_ap-basicChainedPayment-curl-etc/

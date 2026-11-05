# Campus Bites — PhonePe QR payment update

## Included
- Cash at counter option.
- PhonePe/UPI QR option (scan using PhonePe, Google Pay, Paytm or another UPI app).
- Optional UTR/reference field for the student.
- QR orders are recorded as **Pending verification**.
- Payment method, reference and payment status appear in student order history and admin order management.

## Important payment notes
- The QR image is the one supplied by the project owner and is included as `phonepe-qr.jpeg`.
- The student must enter the exact order total in their UPI app before paying.
- This static QR does not automatically receive the order amount and the website cannot confirm that money was received.
- The canteen admin must independently check the PhonePe/bank transaction before treating an order as paid.
- Do not mark an order as paid based only on a screenshot or an unverified reference.
- This is a front-end demo using browser local storage; orders are not shared across devices until a trusted backend/database is connected.
- The GitHub repository is public. Anyone who can access the site can view and scan this QR. Only publish it if you intend this payment QR to be public.

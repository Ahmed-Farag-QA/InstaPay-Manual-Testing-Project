# User Stories - InstaPay Manual Testing Project

---

## US-01: User Registration
As a new user,
I want to register using my mobile number,
so that I can create an InstaPay account.

### Acceptance Criteria:
- User can enter a valid mobile number.
- System validates mobile number format.
- System does not allow empty fields.
- OTP is sent after successful registration request.
- Duplicate mobile numbers are not allowed.

---

## US-02: OTP Verification
As a user,
I want to verify my mobile number using OTP,
so that my account becomes activated.

### Acceptance Criteria:
- User can enter valid OTP.
- System rejects invalid OTP.
- OTP expires after a defined time.
- User can request to resend OTP.
- Account is activated after successful OTP verification.

---

## US-03: Login
As a registered user,
I want to login using my mobile number and PIN,
so that I can access my account securely.

### Acceptance Criteria:
- User can login with valid credentials.
- System rejects invalid PIN or mobile number.
- System shows error for empty fields.
- Account may be locked after multiple failed attempts.
- User is redirected to home page after successful login.

---

## US-04: Link Bank Account
As a user,
I want to link my bank account,
so that I can perform transactions.

### Acceptance Criteria:
- User can add valid bank account details.
- System validates account number format.
- Duplicate bank accounts are not allowed.
- Unsupported banks are rejected.
- Successful linking shows confirmation message.

---

## US-05: Balance Inquiry
As a user,
I want to view my account balance,
so that I can track my funds.

### Acceptance Criteria:
- User can view current balance.
- Balance is updated after transactions.
- System shows correct and real-time data.

---

## US-06: Send Money
As a user,
I want to send money to another user,
so that I can complete financial transactions.

### Acceptance Criteria:
- User can enter valid recipient.
- System checks sufficient balance.
- Transfer fails if balance is insufficient.
- Self-transfer is not allowed.
- Transaction is recorded after success.

---

## US-07: Request Money
As a user,
I want to request money from another user,
so that I can receive payments.

### Acceptance Criteria:
- User can send money request.
- Recipient can accept or reject request.
- Invalid requests are not allowed.
- Request is visible in notifications/history.

---

## US-08: Beneficiaries Management
As a user,
I want to manage beneficiaries,
so that I can save frequent recipients.

### Acceptance Criteria:
- User can add beneficiary.
- User can delete beneficiary.
- Duplicate beneficiaries are not allowed.
- Only valid accounts can be saved.

---

## US-09: Transaction History
As a user,
I want to view my transaction history,
so that I can track all payments.

### Acceptance Criteria:
- User can view transaction list.
- Each transaction shows correct details.
- Transactions are sorted by date.
- History updates after each transaction.

---

## US-10: Notifications
As a user,
I want to receive notifications,
so that I stay updated.

### Acceptance Criteria:
- System sends notification on successful transactions.
- System sends notification on failed transactions.
- Notifications are delivered in real time.
- User can view notification history.

---

## US-11: Logout
As a user,
I want to logout from the application,
so that my account remains secure.

### Acceptance Criteria:
- User can logout successfully.
- Session is terminated after logout.
- User cannot access app after logout without login again.

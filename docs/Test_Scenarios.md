# Test Scenarios - InstaPay Manual Testing Project

---

## 1. Registration Scenarios
- Verify user can register with valid mobile number
- Verify system prevents registration with invalid mobile format
- Verify system rejects duplicate mobile number
- Verify system sends OTP after successful registration
- Verify system handles empty registration fields

---

## 2. OTP Verification Scenarios
- Verify user can verify OTP successfully
- Verify system rejects invalid OTP
- Verify system handles expired OTP
- Verify user can resend OTP
- Verify account is activated after valid OTP

---

## 3. Login Scenarios
- Verify user can login with valid credentials
- Verify system rejects invalid PIN
- Verify system shows error for empty fields
- Verify account locks after multiple failed attempts
- Verify user is redirected to home page after login

---

## 4. Bank Account Linking Scenarios
- Verify user can link valid bank account
- Verify system rejects invalid account number
- Verify system prevents duplicate bank linking
- Verify system rejects unsupported bank

---

## 5. Balance Inquiry Scenarios
- Verify user can view account balance
- Verify balance reflects latest transactions

---

## 6. Send Money Scenarios
- Verify user can send money successfully
- Verify system blocks transfer with insufficient balance
- Verify system prevents self-transfer
- Verify system validates transfer limits
- Verify transaction is recorded after success

---

## 7. Request Money Scenarios
- Verify user can send money request
- Verify recipient can accept request
- Verify recipient can reject request
- Verify invalid requests are blocked

---

## 8. Beneficiaries Scenarios
- Verify user can add beneficiary
- Verify user can delete beneficiary
- Verify system prevents duplicate beneficiaries

---

## 9. Transaction History Scenarios
- Verify user can view transaction history
- Verify correct transaction details are displayed
- Verify transactions are sorted by date

---

## 10. Notifications Scenarios
- Verify success notification is shown
- Verify failure notification is shown
- Verify notifications are delivered in real time

---

## 11. Logout Scenarios
- Verify user can logout successfully
- Verify session is terminated after logout
- Verify user cannot access app after logout

# Test Scenarios - InstaPay Manual Testing Project

## 1. Registration Scenarios
- Verify user can register with valid mobile number
- Verify system rejects duplicate mobile number
- Verify system validates invalid mobile format
- Verify OTP is sent after registration

---

## 2. OTP Verification Scenarios
- Verify user can verify valid OTP
- Verify system rejects invalid OTP
- Verify system handles expired OTP
- Verify resend OTP functionality

---

## 3. Login Scenarios
- Verify login with valid credentials
- Verify login with invalid PIN
- Verify login with unregistered mobile number
- Verify system handles empty fields

---

## 4. Bank Account Linking Scenarios
- Verify user can link valid bank account
- Verify system rejects invalid account number
- Verify duplicate account linking is prevented

---

## 5. Balance Inquiry Scenarios
- Verify user can view correct balance
- Verify balance updates after transactions

---

## 6. Send Money Scenarios
- Verify successful money transfer
- Verify transfer fails if balance is insufficient
- Verify system prevents self-transfer
- Verify transfer limit validation

---

## 7. Request Money Scenarios
- Verify user can send money request
- Verify user can accept request
- Verify user can reject request

---

## 8. Beneficiaries Scenarios
- Verify user can add beneficiary
- Verify user can delete beneficiary
- Verify duplicate beneficiary handling

---

## 9. Transaction History Scenarios
- Verify user can view transaction history
- Verify correct transaction details are displayed

---

## 10. Notifications Scenarios
- Verify success notification is shown after transfer
- Verify failure notification is shown correctly

---

## 11. Logout Scenarios
- Verify user can logout successfully
- Verify session is terminated after logout

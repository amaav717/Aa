```
// تحديد عناصر الفورم
const usernameInput = document.getElementById('username');
const passwordInput = document.getElementById('password');
const loginButton = document.getElementById('login-button');

// إضافة حدث للزرار
loginButton.addEventListener('click', () => {
  // الحصول على قيم الإدخال
  const username = usernameInput.value;
  const password = passwordInput.value;

  // التحقق من البيانات
  if (username === 'admin' && password === 'password') {
    // chuyển đến trang chủ
    window.location.href = 'index.html';
  } else {
    alert('بيانات الدخول غير صحيحة');
  }
});
```

مثال 2: نظام إيداع الأموال
```
// تحديد عناصر الفورم
const amountInput = document.getElementById('amount');
const depositButton = document.getElementById('deposit-button');

// إضافة حدث للزرار
depositButton.addEventListener('click', () => {
  // الحصول على قيمة الإيداع
  const amount = amountInput.value;

  // التحقق من القيمة
  if (amount > 0) {
    // إضافة القيمة إلى الحساب
    alert(`تم إيداع مبلغ ${amount} بنجاح`);
  } else {
    alert('يجب إدخال قيمة إيجابية');
  }
});
```

مثال 3: نظام وضع المراهنات
```
// تحديد عناصر الفورم
const betAmountInput = document.getElementById('bet-amount');
const betButton = document.getElementById('bet-button');

// إضافة حدث للزرار
betButton.addEventListener('click', () => {
  // الحصول على قيمة المراهنة
  const betAmount = betAmountInput.value;

  // التحقق من القيمة
  if (betAmount > 0) {
    // وضع المراهنة
    alert(`تم وضع المراهنة بمبلغ ${betAmount} بنجاح`);
  } else {
    alert('يجب إدخال قيمة
``# Aa

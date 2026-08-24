<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>بطاقة أيوب فوزي | NFC Card</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- FontAwesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;800&display=swap');
    body {
      font-family: 'Tajawal', sans-serif;
    }
  </style>
</head>
<body class="bg-slate-950 min-h-screen flex flex-col items-center justify-center p-4 text-slate-100">

  <!-- Header / Logo Section - تم وضع اللوݣو في الوسط -->
  <header class="mb-6 flex justify-center w-full">
    <div class="inline-flex items-center gap-3 bg-slate-900/80 backdrop-blur-md px-6 py-3 rounded-full shadow-lg border border-slate-800">
      <img src="logo.png" alt="By Ayoub Logo" class="w-10 h-10 rounded-full object-cover bg-black border border-slate-700">
      <span class="font-bold text-slate-200 text-lg">NFC Smart Card</span>
    </div>
  </header>

  <!-- كادر ليدونتيتي (Identity Card Container) -->
  <main class="w-full max-w-md bg-slate-900 rounded-3xl shadow-2xl overflow-hidden border border-slate-800">
    
    <!-- Cover & Profile Image - اللوݣو موقعه متناسق وفي الوسط -->
    <div class="relative bg-gradient-to-r from-slate-800 via-slate-900 to-black h-36 border-b border-slate-800">
      <div class="absolute -bottom-12 inset-x-0 flex justify-center">
        <div class="relative">
          <img src="logo.png" alt="By Ayoub Logo" class="w-24 h-24 rounded-2xl border-4 border-slate-900 shadow-2xl object-cover bg-black">
          <div class="absolute -top-2 -right-2 bg-blue-600 text-white w-7 h-7 rounded-full flex items-center justify-center border-2 border-slate-900 text-xs shadow">
            <i class="fa-solid fa-nfc-symbol"></i>
          </div>
        </div>
      </div>
    </div>

    <!-- Identity Details -->
    <div class="pt-16 px-6 pb-8">
      
      <!-- User Info -->
      <div class="text-center mb-6">
        <h1 class="text-2xl font-extrabold text-white mb-1">أيوب فوزي</h1>
        <p class="text-sm font-semibold text-blue-400">By Ayoub</p>
      </div>

      <!-- Quick Action Buttons -->
      <div class="grid grid-cols-2 gap-3 mb-6">
        <a href="tel:0687606669" class="flex items-center justify-center gap-2 bg-blue-600 hover:bg-blue-500 text-white font-medium py-3 px-4 rounded-xl shadow-lg transition-all text-sm">
          <i class="fa-solid fa-phone"></i> اتصال
        </a>
        <a href="https://wa.me/212687606669" target="_blank" class="flex items-center justify-center gap-2 bg-emerald-600 hover:bg-emerald-500 text-white font-medium py-3 px-4 rounded-xl shadow-lg transition-all text-sm">
          <i class="fa-brands fa-whatsapp"></i> واتساب
        </a>
      </div>

      <!-- Identity & Contact Information Cards -->
      <div class="space-y-3 mb-6">
        
        <!-- Nr. Phone -->
        <a href="tel:0687606669" class="flex items-center justify-between p-3.5 rounded-2xl bg-slate-800/60 hover:bg-slate-800 border border-slate-700/50 transition-all">
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-xl bg-blue-500/10 text-blue-400 flex items-center justify-center text-lg">
              <i class="fa-solid fa-mobile-screen-button"></i>
            </div>
            <div>
              <p class="text-xs text-slate-400 font-medium">رقم الهاتف</p>
              <p class="text-sm font-bold text-slate-200" dir="ltr">0687606669</p>
            </div>
          </div>
          <i class="fa-solid fa-chevron-left text-xs text-slate-500"></i>
        </a>

        <!-- Instagram -->
        <a href="https://instagram.com/faouzi_901" target="_blank" class="flex items-center justify-between p-3.5 rounded-2xl bg-slate-800/60 hover:bg-slate-800 border border-slate-700/50 transition-all">
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-xl bg-pink-500/10 text-pink-400 flex items-center justify-center text-lg">
              <i class="fa-brands fa-instagram"></i>
            </div>
            <div>
              <p class="text-xs text-slate-400 font-medium">إنستغرام</p>
              <p class="text-sm font-bold text-slate-200" dir="ltr">faouzi_901</p>
            </div>
          </div>
          <i class="fa-solid fa-chevron-left text-xs text-slate-500"></i>
        </a>

        <!-- Facebook -->
        <a href="https://facebook.com" target="_blank" class="flex items-center justify-between p-3.5 rounded-2xl bg-slate-800/60 hover:bg-slate-800 border border-slate-700/50 transition-all">
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-xl bg-blue-600/10 text-blue-500 flex items-center justify-center text-lg">
              <i class="fa-brands fa-facebook-f"></i>
            </div>
            <div>
              <p class="text-xs text-slate-400 font-medium">فيسبوك</p>
              <p class="text-sm font-bold text-slate-200">أيوب فوزي</p>
            </div>
          </div>
          <i class="fa-solid fa-chevron-left text-xs text-slate-500"></i>
        </a>

      </div>

      <!-- Save Contact CTA Button -->
      <div class="pt-2 text-center">
        <button class="w-full py-3.5 bg-gradient-to-r from-blue-600 to-indigo-600 hover:from-blue-500 hover:to-indigo-500 text-white font-bold rounded-2xl text-sm flex items-center justify-center gap-2 shadow-xl transition-all">
          <i class="fa-solid fa-user-plus"></i> حفظ جهة الاتصال (vCard)
        </button>
      </div>

    </div>
  </main>

</body>
</html>
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>بطاقة أيوب فوزي | NFC Card</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- FontAwesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;800&display=swap');
    body {
      font-family: 'Tajawal', sans-serif;
    }
  </style>
</head>
<body class="bg-slate-950 min-h-screen flex flex-col items-center justify-center p-4 text-slate-100">

  <!-- Header / Logo Section - تم وضع اللوݣو في الوسط -->
  <header class="mb-6 flex justify-center w-full">
    <div class="inline-flex items-center gap-3 bg-slate-900/80 backdrop-blur-md px-6 py-3 rounded-full shadow-lg border border-slate-800">
      <img src="logo.png" alt="By Ayoub Logo" class="w-10 h-10 rounded-full object-cover bg-black border border-slate-700">
      <span class="font-bold text-slate-200 text-lg">NFC Smart Card</span>
    </div>
  </header>

  <!-- كادر ليدونتيتي (Identity Card Container) -->
  <main class="w-full max-w-md bg-slate-900 rounded-3xl shadow-2xl overflow-hidden border border-slate-800">
    
    <!-- Cover & Profile Image - اللوݣو موقعه متناسق وفي الوسط -->
    <div class="relative bg-gradient-to-r from-slate-800 via-slate-900 to-black h-36 border-b border-slate-800">
      <div class="absolute -bottom-12 inset-x-0 flex justify-center">
        <div class="relative">
          <img src="logo.png" alt="By Ayoub Logo" class="w-24 h-24 rounded-2xl border-4 border-slate-900 shadow-2xl object-cover bg-black">
          <div class="absolute -top-2 -right-2 bg-blue-600 text-white w-7 h-7 rounded-full flex items-center justify-center border-2 border-slate-900 text-xs shadow">
            <i class="fa-solid fa-nfc-symbol"></i>
          </div>
        </div>
      </div>
    </div>

    <!-- Identity Details -->
    <div class="pt-16 px-6 pb-8">
      
      <!-- User Info -->
      <div class="text-center mb-6">
        <h1 class="text-2xl font-extrabold text-white mb-1">أيوب فوزي</h1>
        <p class="text-sm font-semibold text-blue-400">By Ayoub</p>
      </div>

      <!-- Quick Action Buttons -->
      <div class="grid grid-cols-2 gap-3 mb-6">
        <a href="tel:0687606669" class="flex items-center justify-center gap-2 bg-blue-600 hover:bg-blue-500 text-white font-medium py-3 px-4 rounded-xl shadow-lg transition-all text-sm">
          <i class="fa-solid fa-phone"></i> اتصال
        </a>
        <a href="https://wa.me/212687606669" target="_blank" class="flex items-center justify-center gap-2 bg-emerald-600 hover:bg-emerald-500 text-white font-medium py-3 px-4 rounded-xl shadow-lg transition-all text-sm">
          <i class="fa-brands fa-whatsapp"></i> واتساب
        </a>
      </div>

      <!-- Identity & Contact Information Cards -->
      <div class="space-y-3 mb-6">
        
        <!-- Nr. Phone -->
        <a href="tel:0687606669" class="flex items-center justify-between p-3.5 rounded-2xl bg-slate-800/60 hover:bg-slate-800 border border-slate-700/50 transition-all">
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-xl bg-blue-500/10 text-blue-400 flex items-center justify-center text-lg">
              <i class="fa-solid fa-mobile-screen-button"></i>
            </div>
            <div>
              <p class="text-xs text-slate-400 font-medium">رقم الهاتف</p>
              <p class="text-sm font-bold text-slate-200" dir="ltr">0687606669</p>
            </div>
          </div>
          <i class="fa-solid fa-chevron-left text-xs text-slate-500"></i>
        </a>

        <!-- Instagram -->
        <a href="https://instagram.com/faouzi_901" target="_blank" class="flex items-center justify-between p-3.5 rounded-2xl bg-slate-800/60 hover:bg-slate-800 border border-slate-700/50 transition-all">
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-xl bg-pink-500/10 text-pink-400 flex items-center justify-center text-lg">
              <i class="fa-brands fa-instagram"></i>
            </div>
            <div>
              <p class="text-xs text-slate-400 font-medium">إنستغرام</p>
              <p class="text-sm font-bold text-slate-200" dir="ltr">faouzi_901</p>
            </div>
          </div>
          <i class="fa-solid fa-chevron-left text-xs text-slate-500"></i>
        </a>

        <!-- Facebook -->
        <a href="https://facebook.com" target="_blank" class="flex items-center justify-between p-3.5 rounded-2xl bg-slate-800/60 hover:bg-slate-800 border border-slate-700/50 transition-all">
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-xl bg-blue-600/10 text-blue-500 flex items-center justify-center text-lg">
              <i class="fa-brands fa-facebook-f"></i>
            </div>
            <div>
              <p class="text-xs text-slate-400 font-medium">فيسبوك</p>
              <p class="text-sm font-bold text-slate-200">أيوب فوزي</p>
            </div>
          </div>
          <i class="fa-solid fa-chevron-left text-xs text-slate-500"></i>
        </a>

      </div>

      <!-- Save Contact CTA Button -->
      <div class="pt-2 text-center">
        <button class="w-full py-3.5 bg-gradient-to-r from-blue-600 to-indigo-600 hover:from-blue-500 hover:to-indigo-500 text-white font-bold rounded-2xl text-sm flex items-center justify-center gap-2 shadow-xl transition-all">
          <i class="fa-solid fa-user-plus"></i> حفظ جهة الاتصال (vCard)
        </button>
      </div><img width="720" height="582" alt="1000079256" src="https://github.com/user-attachments/assets/a0525014-4bb2-4e02-babf-8dfcd0f72056" />


    </div>
  </main>

</body>
</html>

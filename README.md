<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TashDrops — Мужской стиль 2026</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body { font-family: 'Inter', system-ui, sans-serif; }
    .hero { background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.8)), url('https://picsum.photos/id/1015/2000/1200') center/cover no-repeat; }
    .card-hover:hover { transform: translateY(-8px); transition: all 0.4s ease; }
  </style>
</head>
<body class="bg-zinc-950 text-zinc-100">

  <!-- Navbar -->
  <nav class="bg-black/90 backdrop-blur-md border-b border-zinc-800 sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-8 py-5 flex items-center justify-between">
      <div class="text-3xl font-bold tracking-tighter">TashDrops</div>
      <div class="flex gap-10 text-sm font-medium">
        <a href="index.html" class="hover:text-white">Главная</a>
        <a href="novinki.html" class="hover:text-white">Новинки</a>
        <a href="obzory.html" class="hover:text-white">Обзоры</a>
        <a href="sravneniya.html" class="hover:text-white">Сравнения</a>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section class="hero h-screen flex items-center">
    <div class="max-w-7xl mx-auto px-8 text-center">
      <h1 class="text-7xl md:text-8xl font-bold leading-none mb-6">Мужской стиль<br>2026</h1>
      <p class="text-2xl text-zinc-300 max-w-2xl mx-auto mb-10">Runway looks из Парижа, Милана и Токио. Только то, что будут носить.</p>
      <a href="novinki.html" class="inline-flex items-center gap-3 px-10 py-5 bg-white text-black rounded-3xl text-xl font-medium hover:bg-amber-300 transition">
        Смотреть новинки <i class="fas fa-arrow-right"></i>
      </a>
    </div>
  </section>

  <!-- Trending Runway -->
  <section class="max-w-7xl mx-auto px-8 py-20">
    <h2 class="text-5xl font-bold mb-12 text-center">С подиума прямо к тебе</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
      <div class="card-hover bg-zinc-900 rounded-3xl overflow-hidden">
        <img src="https://picsum.photos/id/1005/800/1000" alt="Fashion show" class="w-full h-96 object-cover">
        <div class="p-6">
          <p class="text-amber-400 text-sm">Paris Fashion Week</p>
          <p class="font-semibold mt-2">Chanel Men's SS 2026</p>
        </div>
      </div>
      <div class="card-hover bg-zinc-900 rounded-3xl overflow-hidden">
        <img src="https://picsum.photos/id/1016/800/1000" alt="Fashion show" class="w-full h-96 object-cover">
        <div class="p-6">
          <p class="text-amber-400 text-sm">Milan Fashion Week</p>
          <p class="font-semibold mt-2">Prada Men's FW 2026</p>
        </div>
      </div>
      <!-- Добавь ещё карточки по аналогии -->
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-black py-12 border-t border-zinc-800">
    <div class="max-w-7xl mx-auto px-8 text-center text-zinc-500">
      <p>TashDrops — твой гид по мужскому стилю и новинкам моды 2026</p>
    </div>
  </footer>

</body>
</html>

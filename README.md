# TashDrops
Современный мужской стиль и новинки моды
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TashDrops — Мужской стиль и новинки моды</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body { font-family: 'Inter', system-ui, sans-serif; }
    .hero-bg { background: linear-gradient(135deg, #111111, #1a1a1a); }
  </style>
</head>
<body class="bg-zinc-950 text-zinc-100">

  <!-- Navbar -->
  <nav class="bg-black border-b border-zinc-800 sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">
      <div class="text-2xl font-bold tracking-tighter">TashDrops</div>
      <div class="flex gap-8 text-sm font-medium">
        <a href="index.html" class="hover:text-white transition">Главная</a>
        <a href="novinki.html" class="hover:text-white transition">Новинки</a>
        <a href="obzory.html" class="hover:text-white transition">Обзоры</a>
        <a href="sravneniya.html" class="hover:text-white transition">Сравнения</a>
        <a href="o-proekte.html" class="hover:text-white transition">О проекте</a>
      </div>
      <div class="flex items-center gap-4">
        <a href="#" class="text-sm px-6 py-2.5 bg-white text-black rounded-full font-medium hover:bg-zinc-200 transition">Подписаться</a>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section class="hero-bg py-24">
    <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
      <div>
        <h1 class="text-6xl font-bold leading-none mb-6">
          Мужской стиль<br>2026
        </h1>
        <p class="text-xl text-zinc-400 mb-8 max-w-lg">
          Новинки из Европы и мира. Лучшие аксессуары, одежда и тренды. 
          Только то, что реально стоит внимания.
        </p>
        <div class="flex gap-4">
          <a href="novinki.html" class="px-8 py-4 bg-white text-black rounded-2xl font-medium text-lg hover:bg-zinc-200 transition">Смотреть новинки</a>
          <a href="#" class="px-8 py-4 border border-zinc-600 rounded-2xl font-medium text-lg hover:bg-zinc-900 transition">Как это работает</a>
        </div>
      </div>
      <div class="relative">
        <div class="bg-zinc-900 rounded-3xl overflow-hidden aspect-video">
          <!-- Здесь можно поставить фото или видео -->
          <div class="h-full bg-gradient-to-br from-zinc-800 to-black flex items-center justify-center text-4xl font-light text-zinc-500">
            Новинки моды 2026
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Trending -->
  <section class="max-w-7xl mx-auto px-6 py-16">
    <h2 class="text-3xl font-bold mb-8">Новинки и тренды</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
      <!-- Карточки товаров будут здесь -->
      <div class="bg-zinc-900 rounded-3xl overflow-hidden">
        <div class="h-64 bg-zinc-800"></div>
        <div class="p-6">
          <p class="text-sm text-zinc-400">On Cloud • 2026</p>
          <p class="font-medium mt-1">Мужские кроссовки Cloudmonster 2</p>
          <p class="text-emerald-400 mt-4">от 249 000 сум</p>
        </div>
      </div>
      <!-- Повторить карточки по аналогии -->
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-black border-t border-zinc-800 py-12">
    <div class="max-w-7xl mx-auto px-6 text-center text-sm text-zinc-500">
      <p>TashDrops — рекомендации мужского стиля. Мы используем affiliate-ссылки.</p>
      <p class="mt-4">© 2026 Все права защищены.</p>
    </div>
  </footer>

</body>
</html>

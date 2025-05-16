<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TrendWear | Loja Online</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-gray-800">

  <!-- Cabeçalho -->
  <header class="flex justify-between items-center p-4 shadow-md">
    <h1 class="text-2xl font-bold text-pink-600">TrendWear</h1>
    <nav class="space-x-6">
      <a href="#" class="hover:text-pink-600 font-medium">Início</a>
      <a href="#" class="hover:text-pink-600 font-medium">Produtos</a>
      <a href="#" class="hover:text-pink-600 font-medium">Contato</a>
      <a href="#" class="hover:text-pink-600 font-medium">Carrinho</a>
    </nav>
  </header>

  <!-- Banner Principal -->
  <section class="relative h-96 bg-cover bg-center" style="background-image: url('https://source.unsplash.com/featured/?fashion');">
    <div class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center">
      <div class="text-white text-center">
        <h2 class="text-4xl font-extrabold">Nova Coleção Primavera 2025</h2>
        <p class="mt-2 text-lg">Estilo, conforto e personalidade em um só lugar</p>
        <button class="mt-4 px-6 py-2 bg-pink-600 hover:bg-pink-700 text-white font-semibold rounded-full">
          Comprar Agora
        </button>
      </div>
    </div>
  </section>

  <!-- Sessão de Produtos -->
  <section class="p-6">
    <h3 class="text-2xl font-bold mb-4">Destaques</h3>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
      <!-- Produto -->
      <div class="border rounded-lg overflow-hidden shadow hover:shadow-lg transition">
        <img src="https://source.unsplash.com/featured/?shirt" alt="Produto" class="w-full h-56 object-cover">
        <div class="p-4">
          <h4 class="font-semibold text-lg">Camisa Estilosa</h4>
          <p class="text-pink-600 font-bold">R$ 89,90</p>
          <button class="mt-2 w-full bg-pink-600 text-white py-1 rounded hover:bg-pink-700">Adicionar</button>
        </div>
      </div>
      <!-- Mais produtos podem ser adicionados aqui -->
    </div>
  </section>

  <!-- Rodapé -->
  <footer class="bg-gray-100 text-center p-4 mt-8 text-sm text-gray-600">
    © 2025 TrendWear. Todos os direitos reservados.
  </footer>

</body>
</html>

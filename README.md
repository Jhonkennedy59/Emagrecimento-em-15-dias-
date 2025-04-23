<!DOCTYPE html><html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ebook Emagreça com Saúde</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/framer-motion@5.5.5/dist/framer-motion.umd.js"></script>
</head>
<body class="bg-white text-gray-800 font-sans">
  <section class="bg-gradient-to-r from-green-400 to-lime-500 text-white py-20 text-center">
    <div class="max-w-3xl mx-auto px-4">
      <h1 class="text-4xl md:text-5xl font-bold mb-6">Transforme seu Corpo com Saúde</h1>
      <p class="text-xl mb-8">Com nosso ebook exclusivo, você pode emagrecer de forma saudável e prática.</p>
      <a href="https://pay.kiwify.com.br/aohtlBe" class="bg-white text-green-600 font-bold py-3 px-8 rounded-full shadow-md hover:bg-gray-100 transition">Comprar Agora - R$ 20,00</a>
    </div>
  </section>  <section class="py-16 bg-gray-50">
    <div class="max-w-6xl mx-auto px-4 grid md:grid-cols-2 gap-10">
      <div>
        <h2 class="text-3xl font-bold mb-4">O que você vai encontrar no ebook?</h2>
        <ul class="list-disc list-inside text-lg space-y-2">
          <li>Dicas práticas de alimentação saudável</li>
          <li>Receitas simples e saborosas</li>
          <li>Treinos rápidos para fazer em casa</li>
          <li>Plano de metas e motivação</li>
        </ul>
      </div>
      <div>
        <img src="https://images.unsplash.com/photo-1554284126-5c1c7b8b8c15" alt="Comida saudável" class="rounded-xl shadow-lg">
      </div>
    </div>
  </section>  <section class="py-16">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-10">Veja o que dizem nossos clientes</h2>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded-lg shadow">
          <p class="italic">"Perdi 8kg em 2 meses seguindo o ebook. Me sinto renovada!"</p>
          <span class="block mt-4 font-bold text-green-600">- Ana Paula</span>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
          <p class="italic">"Receitas maravilhosas e fáceis de fazer! Super recomendo."</p>
          <span class="block mt-4 font-bold text-green-600">- Marcelo</span>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
          <p class="italic">"Finalmente encontrei um guia simples e eficaz para emagrecer."</p>
          <span class="block mt-4 font-bold text-green-600">- Juliana</span>
        </div>
      </div>
    </div>
  </section>  <section class="py-20 bg-green-500 text-white text-center">
    <h2 class="text-3xl md:text-4xl font-bold mb-6">Garanta o seu por apenas R$ 20,00</h2>
    <a href="https://pay.kiwify.com.br/aohtlBe" class="bg-white text-green-600 font-bold py-3 px-10 rounded-full shadow-lg hover:bg-gray-100 transition">Quero Emagrecer com Saúde!</a>
  </section>  <script>
    // Exemplo básico de animação com Framer Motion (opcional)
    const { motion } = window["framer-motion"];
    document.querySelectorAll("section").forEach((sec, i) => {
      sec.style.opacity = 0;
      sec.style.transform = "translateY(30px)";
      setTimeout(() => {
        sec.animate([
          { opacity: 0, transform: 'translateY(30px)' },
          { opacity: 1, transform: 'translateY(0)' }
        ], {
          duration: 800,
          easing: 'ease-out',
          fill: 'forwards'
        });
      }, i * 300);
    });
  </script></body>
</html>

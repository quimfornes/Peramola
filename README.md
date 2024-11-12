# Peramola
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Casa Rural a Peramola</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.16/dist/tailwind.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" />
</head>
<body>
  <header class="bg-gray-900 text-white py-4">
    <div class="container mx-auto flex justify-between items-center">
      <div class="text-2xl font-bold">Casa Rural a Peramola</div>
      <div class="flex space-x-4">
        <a href="#" class="hover:text-gray-400"><i class="fab fa-facebook-f"></i></a>
        <a href="#" class="hover:text-gray-400"><i class="fab fa-twitter"></i></a>
        <a href="#" class="hover:text-gray-400"><i class="fab fa-instagram"></i></a>
      </div>
    </div>
  </header>

  <main class="container mx-auto py-8">
    <section id="about" class="mb-8">
      <h2 class="text-2xl font-bold mb-4">Qui som</h2>
      <p>Som una família que ha restaurat una antiga casa rural a Peramola, un petit poble del Prepirineu lleidatà a 40 km d'Andorra. Volem compartir la nostra llar amb vosaltres per tal que pugueu gaudir d'unes vacances tranquil·les en contacte amb la natura.</p>
    </section>

    <section id="property" class="mb-8">
      <h2 class="text-2xl font-bold mb-4">Sobre la propietat</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <div>
          <img src="/api/placeholder/400/300" alt="Imatge de l'habitatge" class="w-full rounded">
        </div>
        <div>
          <p>La nostra casa rural disposa de:</p>
          <ul class="list-disc pl-4">
            <li>5 habitacions dobles</li>
            <li>Jardí de 150 m²</li>
            <li>Barbacoa</li>
            <li>Rocòdrom interior</li>
            <li>Garatge per a 2 cotxes</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="blog" class="mb-8">
      <h2 class="text-2xl font-bold mb-4">Novetats i Ofertes</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
        <div class="bg-gray-100 rounded p-4">
          <h3 class="text-xl font-bold mb-2">Nova zona de jocs per als nens</h3>
          <p>Hem instal·lat una nova àrea de jocs per als més petits al jardí.</p>
          <a href="#" class="text-blue-500 hover:underline">Llegir més</a>
        </div>
        <div class="bg-gray-100 rounded p-4">
          <h3 class="text-xl font-bold mb-2">Ofertes d'última hora</h3>
          <p>Consulta les nostres ofertes especials per a reserves a curt termini.</p>
          <a href="#" class="text-blue-500 hover:underline">Veure ofertes</a>
        </div>
        <div class="bg-gray-100 rounded p-4">
          <h3 class="text-xl font-bold mb-2">Nous productes a la botiga</h3>
          <p>Hem afegit nous productes locals a la nostra botiga.</p>
          <a href="#" class="text-blue-500 hover:underline">Visita la botiga</a>
        </div>
      </div>
    </section>

    <section id="contact" class="mb-8">
      <h2 class="text-2xl font-bold mb-4">Contacta amb nosaltres</h2>
      <form class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <input type="text" placeholder="Nom" class="border rounded py-2 px-4">
        <input type="email" placeholder="Email" class="border rounded py-2 px-4">
        <textarea rows="4" placeholder="Missatge" class="border rounded py-2 px-4 col-span-2"></textarea>
        <button type="submit" class="bg-blue-500 text-white rounded py-2 px-4 hover:bg-blue-600">Enviar</button>
      </form>
    </section>

    <section id="faq" class="mb-8">
      <h2 class="text-2xl font-bold mb-4">Preguntes Freqüents</h2>
      <div class="space-y-4">
        <div>
          <h3 class="text-xl font-bold">Quina és la capacitat de la casa?</h3>
          <p>La casa té capacitat per a 10 persones, amb 5 habitacions dobles.</p>
        </div>
        <div>
          <h3 class="text-xl font-bold">Hi ha activitats a la zona?</h3>
          <p>Sí, a prop tenim moltes opcions per fer excursions, visitar pobles, practicar esports d'aventura, etc.</p>
        </div>
        <div>
          <h3 class="text-xl font-bold">Accepteu animals de companyia?</h3>
          <p>Sí, acceptem animals de companyia amb un suplement addicional.</p>
        </div>
      </div>
    </section>
  </main>

  <footer class="bg-gray-900 text-white py-4">
    <div class="container mx-auto flex justify-between items-center">
      <p>&copy; 2023 Casa Rural a Peramola. Tots els drets reservats.</p>
      <div>
        <a href="#" class="hover:text-gray-400"><i class="fas fa-map-marker-alt"></i> Peramola, Lleida</a>
      </div>
    </div>
  </footer>
</body>
</html>

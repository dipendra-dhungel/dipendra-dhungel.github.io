<!DOCTYPE html>
<html lang="en" class="bg-gray-900 text-white">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dark Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="min-h-screen flex flex-col bg-gray-900 text-white">
  <!-- Navigation -->
  <nav class="bg-gray-800 shadow-lg">
    <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-white">Dipendra Dhungel's Portfolio</h1>
      <ul class="flex space-x-6">
        <li><a href="#home" class="hover:text-gray-300">Home</a></li>
        <li><a href="#profile" class="hover:text-gray-300">Profile</a></li>
        <li><a href="#contact" class="hover:text-gray-300">Contact</a></li>
        <li><a href="#download" class="hover:text-gray-300">Download CV</a></li>
      </ul>
    </div>
  </nav>

  <!-- Pages -->
  <main class="flex-grow">
    <!-- Home Page -->
    <section id="home" class="py-20 px-6 text-center">
      <h2 class="text-4xl font-semibold mb-4">Welcome to My Portfolio</h2>
      <p class="text-lg text-gray-300">Explore my work, background, and reach out if you’d like to collaborate!</p>
    </section>

    <!-- Profile Page -->
    <section id="profile" class="py-20 px-6 bg-gray-800">
      <h2 class="text-3xl font-semibold mb-4 text-center">About Me</h2>
      <p class="max-w-3xl mx-auto text-gray-300">
        I'm a dedicated professional with experience in day trading. I specialize in financial analysis and trading strategies, and I'm passionate about building impactful portfolios.
      </p>
    </section>

    <!-- Contact Page -->
    <section id="contact" class="py-20 px-6">
      <h2 class="text-3xl font-semibold mb-4 text-center">Contact Me</h2>
      <div class="text-center text-gray-300">
        <p>Email: dipendradhungel1@gmail.com</p>
        <p>WhatsApp: +358 466310824</p>
        <p>
          <a href="https://twitter.com/dipendradhungel" target="_blank" class="underline hover:text-gray-100">Twitter</a> |
          <a href="https://www.linkedin.com/in/dipendra-dhungel/" target="_blank" class="underline hover:text-gray-100">LinkedIn</a> |
          <a href="https://www.instagram.com/dipendra_dhungel/" target="_blank" class="underline hover:text-gray-100">Instagram</a> |
          <a href="https://x.com/dipendradhungel" target="_blank" class="underline hover:text-gray-100">X</a>
        </p>
      </div>
    </section>

    <!-- Download CV Page -->
    <section id="download" class="py-20 px-6 bg-gray-800 text-center">
      <h2 class="text-3xl font-semibold mb-4">Download My CV</h2>
      <a href="your-cv.pdf" download class="inline-block mt-4 bg-gray-700 text-white px-6 py-3 rounded hover:bg-gray-600">
        Download CV
      </a>
    </section>
  </main>

  <!-- Footer -->
  <footer class="bg-gray-900 text-center py-4 text-gray-400">
    &copy; 2025 Dipendra Dhungel. All rights reserved.
  </footer>
</body>
</html>

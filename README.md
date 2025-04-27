<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dipendra Dhungel | Trader & Gamer</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    body {
      font-family: 'Inter', sans-serif;
    }
    #navbar {
      transition: all 0.3s ease;
    }
    .navbar-hidden {
      transform: translateY(-100%);
    }
    .profile-img {
      transition: transform 0.5s ease;
    }
    .profile-img:hover {
      transform: scale(1.05);
    }
    .explore-btn {
      transition: all 0.3s ease;
    }
    .explore-btn.expanded {
      background-color: #4f46e5 !important;
      transform: scale(1.05);
    }
    .social-icon {
      transition: transform 0.2s ease;
    }
    .social-icon:hover {
      transform: translateY(-3px);
    }
  </style>
</head>
<body class="bg-gray-900 text-gray-100">

  <!-- Navigation -->
  <nav id="navbar" class="bg-gray-800 fixed w-full top-0 z-50 shadow-lg py-3">
    <div class="container mx-auto px-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-green-400">Dipendra Dhungel</h1>
      <ul class="hidden md:flex space-x-8">
        <li><a href="#home" class="hover:text-green-400 transition">Home</a></li>
        <li><a href="#profile" class="hover:text-green-400 transition">Profile</a></li>
        <li><a href="#explore" class="hover:text-green-400 transition">Explore</a></li>
        <li><a href="#contact" class="hover:text-green-400 transition">Contact</a></li>
        <li><a href="#cv" class="hover:text-green-400 transition">CV</a></li>
      </ul>
      <button class="md:hidden text-2xl" onclick="toggleMobileMenu()">☰</button>
    </div>
    <!-- Mobile Menu -->
    <div id="mobileMenu" class="hidden md:hidden bg-gray-700 px-4 py-2">
      <ul class="space-y-2">
        <li><a href="#home" class="block hover:text-green-400" onclick="toggleMobileMenu()">Home</a></li>
        <li><a href="#profile" class="block hover:text-green-400" onclick="toggleMobileMenu()">Profile</a></li>
        <li><a href="#explore" class="block hover:text-green-400" onclick="toggleMobileMenu()">Explore</a></li>
        <li><a href="#contact" class="block hover:text-green-400" onclick="toggleMobileMenu()">Contact</a></li>
        <li><a href="#cv" class="block hover:text-green-400" onclick="toggleMobileMenu()">CV</a></li>
      </ul>
    </div>
  </nav>

  <!-- Main Content -->
  <main class="pt-16">

    <!-- Hero Section -->
    <section id="home" class="min-h-screen flex items-center justify-center bg-gradient-to-br from-gray-800 to-gray-900 px-6 text-center">
      <div class="max-w-4xl">
        <h1 class="text-4xl md:text-6xl font-bold mb-6 text-green-400">Dipendra Dhungel</h1>
        <p class="text-xl md:text-2xl mb-8 text-gray-300">Trader | Gamer | Thinker</p>
        <div class="flex justify-center gap-4">
          <a href="#contact" class="bg-green-600 hover:bg-green-700 text-white px-6 py-3 rounded-lg font-medium transition">Contact Me</a>
          <a href="#explore" class="bg-gray-700 hover:bg-gray-600 text-white px-6 py-3 rounded-lg font-medium transition">Explore More</a>
        </div>
      </div>
    </section>

    <!-- Profile Section -->
    <section id="profile" class="py-20 px-6 bg-gray-800">
      <div class="container mx-auto max-w-4xl">
        <h2 class="text-3xl font-bold text-center mb-12 text-green-400">About Me</h2>
        
        <div class="flex flex-col md:flex-row items-center gap-8">
          <div class="w-full md:w-1/3 flex justify-center">
            <div class="relative">
              <img id="profileImage" src="profile1.jpg" alt="Dipendra Dhungel" 
                   class="profile-img w-48 h-48 md:w-64 md:h-64 rounded-full border-4 border-green-500 object-cover shadow-lg">
              <div class="absolute -bottom-4 left-0 right-0 flex justify-center gap-2">
                <div class="w-12 h-12 bg-gray-700 rounded-full flex items-center justify-center text-xs">1</div>
                <div class="w-12 h-12 bg-gray-700 rounded-full flex items-center justify-center text-xs">2</div>
                <div class="w-12 h-12 bg-gray-700 rounded-full flex items-center justify-center text-xs">3</div>
              </div>
            </div>
          </div>
          
          <div class="w-full md:w-2/3">
            <p class="text-lg mb-6">
              I'm Dipendra Dhungel, a passionate trader dedicated to mastering financial markets and building sustainable wealth. 
              When I'm not analyzing charts, you'll find me exploring virtual worlds or contemplating life's deeper connections.
            </p>
            <div class="grid grid-cols-2 gap-4">
              <div class="bg-gray-700 p-4 rounded-lg">
                <h3 class="font-semibold text-green-400 mb-2">Trading</h3>
                <p class="text-sm">Technical analysis, risk management, portfolio building</p>
              </div>
              <div class="bg-gray-700 p-4 rounded-lg">
                <h3 class="font-semibold text-green-400 mb-2">Gaming</h3>
                <p class="text-sm">Competitive FPS, strategy games, immersive RPGs</p>
              </div>
              <div class="bg-gray-700 p-4 rounded-lg">
                <h3 class="font-semibold text-green-400 mb-2">Mindset</h3>
                <p class="text-sm">Discipline, continuous learning, emotional control</p>
              </div>
              <div class="bg-gray-700 p-4 rounded-lg">
                <h3 class="font-semibold text-green-400 mb-2">Connections</h3>
                <p class="text-sm">Building meaningful relationships, personal growth</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Explore Section -->
    <section id="explore" class="py-20 px-6 bg-gray-900">
      <div class="container mx-auto max-w-4xl">
        <h2 class="text-3xl font-bold text-center mb-12 text-green-400">Explore My World</h2>
        
        <div class="flex justify-center mb-8">
          <button onclick="toggleExplore()" 
                  class="bg-gray-700 hover:bg-gray-600 text-white px-8 py-3 rounded-lg font-medium transition">
            Toggle Explore Sections
          </button>
        </div>

        <div id="exploreButtons" class="hidden md:flex justify-center gap-4 mb-12">
          <button onclick="expandTopic('love')" id="btn-love" 
                  class="explore-btn bg-gray-700 hover:bg-gray-600 text-white px-6 py-2 rounded-lg">
            Love & Relationships
          </button>
          <button onclick="expandTopic('trade')" id="btn-trade" 
                  class="explore-btn bg-gray-700 hover:bg-gray-600 text-white px-6 py-2 rounded-lg">
            Trading Journey
          </button>
          <button onclick="expandTopic('game')" id="btn-game" 
                  class="explore-btn bg-gray-700 hover:bg-gray-600 text-white px-6 py-2 rounded-lg">
            Gaming Passion
          </button>
        </div>

        <div id="mobileExploreButtons" class="flex flex-col gap-2 md:hidden mb-8">
          <button onclick="expandTopic('love')" id="mobile-btn-love" 
                  class="explore-btn bg-gray-700 hover:bg-gray-600 text-white px-4 py-2 rounded-lg text-sm">
            Love
          </button>
          <button onclick="expandTopic('trade')" id="mobile-btn-trade" 
                  class="explore-btn bg-gray-700 hover:bg-gray-600 text-white px-4 py-2 rounded-lg text-sm">
            Trading
          </button>
          <button onclick="expandTopic('game')" id="mobile-btn-game" 
                  class="explore-btn bg-gray-700 hover:bg-gray-600 text-white px-4 py-2 rounded-lg text-sm">
            Gaming
          </button>
        </div>

        <!-- Explore Content -->
        <div class="space-y-8">
          <div id="love" class="explore-content hidden bg-gray-800 p-6 rounded-xl">
            <div class="flex flex-col md:flex-row gap-6">
              <div class="md:w-1/3">
                <img src="love.jpg" alt="Love and Relationships" class="w-full rounded-lg shadow">
              </div>
              <div class="md:w-2/3">
                <h3 class="text-2xl font-semibold mb-4 text-green-400">Love & Relationships</h3>
                <p class="mb-4">
                  This section explores the profound connections that shape our lives. I share thoughts on emotional intelligence, 
                  personal growth, and the journey of building meaningful relationships.
                </p>
                <p>
                  "To love and be loved is to feel the sun from both sides." — David Viscott
                </p>
              </div>
            </div>
          </div>

          <div id="trade" class="explore-content hidden bg-gray-800 p-6 rounded-xl">
            <div class="flex flex-col md:flex-row gap-6">
              <div class="md:w-1/3">
                <img src="trade.jpg" alt="Trading Journey" class="w-full rounded-lg shadow">
              </div>
              <div class="md:w-2/3">
                <h3 class="text-2xl font-semibold mb-4 text-green-400">Trading Journey</h3>
                <p class="mb-4">
                  My path to becoming a professional trader involves daily market analysis, risk management strategies, 
                  and continuous learning. Here I document the lessons, wins, and losses that shape my trading career.
                </p>
                <p>
                  Current focus: Price action strategies, market psychology, and algorithmic trading concepts.
                </p>
              </div>
            </div>
          </div>

          <div id="game" class="explore-content hidden bg-gray-800 p-6 rounded-xl">
            <div class="flex flex-col md:flex-row gap-6">
              <div class="md:w-1/3">
                <img src="game.jpg" alt="Gaming Passion" class="w-full rounded-lg shadow">
              </div>
              <div class="md:w-2/3">
                <h3 class="text-2xl font-semibold mb-4 text-green-400">Gaming Passion</h3>
                <p class="mb-4">
                  Gaming is more than entertainment—it's a space for strategic thinking, teamwork, and pushing limits. 
                  I explore competitive gaming, immersive RPGs, and the parallels between gaming mindset and trading psychology.
                </p>
                <p>
                  Current favorites: Valorant, Dota 2, Elden Ring
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Countdown Section -->
    <section class="py-12 bg-gray-800 text-center">
      <div class="container mx-auto max-w-2xl px-6">
        <h3 class="text-xl font-semibold mb-4 text-green-400">Countdown to March 27, 2080 – 7:15 AM</h3>
        <div id="countdown" class="flex justify-center gap-4 md:gap-8">
          <div class="bg-gray-700 p-4 rounded-lg w-20">
            <span id="days" class="text-2xl font-bold block">0</span>
            <span class="text-xs">Days</span>
          </div>
          <div class="bg-gray-700 p-4 rounded-lg w-20">
            <span id="hours" class="text-2xl font-bold block">0</span>
            <span class="text-xs">Hours</span>
          </div>
          <div class="bg-gray-700 p-4 rounded-lg w-20">
            <span id="minutes" class="text-2xl font-bold block">0</span>
            <span class="text-xs">Minutes</span>
          </div>
          <div class="bg-gray-700 p-4 rounded-lg w-20">
            <span id="seconds" class="text-2xl font-bold block">0</span>
            <span class="text-xs">Seconds</span>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-6 bg-gray-900">
      <div class="container mx-auto max-w-4xl">
        <h2 class="text-3xl font-bold text-center mb-12 text-green-400">Get In Touch</h2>
        
        <div class="flex flex-col md:flex-row gap-8">
          <div class="w-full md:w-1/2 bg-gray-800 p-8 rounded-xl">
            <h3 class="text-xl font-semibold mb-4 text-green-400">Contact Information</h3>
            <ul class="space-y-4">
              <li class="flex items-start">
                <i class="fas fa-envelope mt-1 mr-3 text-green-400"></i>
                <div>
                  <h4 class="font-medium">Email</h4>
                  <a href="mailto:dipendradhungel1@gmail.com" class="text-gray-300 hover:text-green-400 transition">
                    dipendradhungel1@gmail.com
                  </a>
                </div>
              </li>
              <li class="flex items-start">
                <i class="fas fa-phone-alt mt-1 mr-3 text-green-400"></i>
                <div>
                  <h4 class="font-medium">Phone/WhatsApp</h4>
                  <a href="https://wa.me/358466310824" class="text-gray-300 hover:text-green-400 transition">
                    +358 466310824
                  </a>
                </div>
              </li>
              <li class="flex items-start">
                <i class="fas fa-map-marker-alt mt-1 mr-3 text-green-400"></i>
                <div>
                  <h4 class="font-medium">Location</h4>
                  <p class="text-gray-300">Finland</p>
                </div>
              </li>
            </ul>
            
            <div class="mt-8">
              <h4 class="font-medium mb-3">Connect With Me</h4>
              <div class="flex gap-4">
                <a href="https://instagram.com/dipendra_dhungel" target="_blank" 
                   class="social-icon bg-gray-700 w-10 h-10 rounded-full flex items-center justify-center hover:bg-green-600 transition">
                  <i class="fab fa-instagram"></i>
                </a>
                <a href="https://wa.me/358466310824" target="_blank" 
                   class="social-icon bg-gray-700 w-10 h-10 rounded-full flex items-center justify-center hover:bg-green-600 transition">
                  <i class="fab fa-whatsapp"></i>
                </a>
                <a href="https://linkedin.com/in/dipendra-dhungel" target="_blank" 
                   class="social-icon bg-gray-700 w-10 h-10 rounded-full flex items-center justify-center hover:bg-green-600 transition">
                  <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="https://x.com/dipendradhungel" target="_blank" 
                   class="social-icon bg-gray-700 w-10 h-10 rounded-full flex items-center justify-center hover:bg-green-600 transition">
                  <i class="fab fa-x-twitter"></i>
                </a>
              </div>
            </div>
          </div>
          
          <div class="w-full md:w-1/2 bg-gray-800 p-8 rounded-xl">
            <h3 class="text-xl font-semibold mb-4 text-green-400">Send Me a Message</h3>
            <form class="space-y-4">
              <div>
                <label for="name" class="block mb-1">Name</label>
                <input type="text" id="name" class="w-full bg-gray-700 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-500">
              </div>
              <div>
                <label for="email" class="block mb-1">Email</label>
                <input type="email" id="email" class="w-full bg-gray-700 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-500">
              </div>
              <div>
                <label for="message" class="block mb-1">Message</label>
                <textarea id="message" rows="4" class="w-full bg-gray-700 rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-green-500"></textarea>
              </div>
              <button type="submit" class="bg-green-600 hover:bg-green-700 text-white px-6 py-2 rounded-lg transition">
                Send Message
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- CV Download Section -->
    <section id="cv" class="py-16 bg-gray-800 text-center">
      <div class="container mx-auto max-w-2xl px-6">
        <h2 class="text-3xl font-bold mb-6 text-green-400">Download My CV</h2>
        <p class="mb-8 max-w-lg mx-auto">
          Get a comprehensive overview of my professional background, skills, and experience.
        </p>
        <a href="#" class="inline-block bg-green-600 hover:bg-green-700 text-white px-8 py-3 rounded-lg font-medium transition">
          <i class="fas fa-download mr-2"></i> Download CV (PDF)
        </a>
      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer class="bg-gray-900 py-8 text-center text-gray-400 border-t border-gray-800">
    <div class="container mx-auto px-6">
      <p>&copy; 2025 Dipendra Dhungel. All rights reserved.</p>
      <p class="mt-2 text-sm">Built with passion and precision</p>
    </div>
  </footer>

  <!-- Scripts -->
  <script>
    // Profile image rotation
    const images = ["profile1.jpg", "profile2.jpg", "profile3.jpg"];
    let index = 0;
    setInterval(() => {
      index = (index + 1) % images.length;
      document.getElementById("profileImage").src = images[index];
    }, 10000);

    // Mobile menu toggle
    function toggleMobileMenu() {
      const menu = document.getElementById("mobileMenu");
      menu.classList.toggle('hidden');
    }

    // Explore sections functionality
    function toggleExplore() {
      const buttons = document.getElementById("exploreButtons");
      buttons.classList.toggle('hidden');
    }

    function expandTopic(topic) {
      const topics = ["love", "trade", "game"];
      topics.forEach(id => {
        document.getElementById(id).classList.add('hidden');
        document.getElementById(`btn-${id}`)?.classList.remove('expanded');
        document.getElementById(`mobile-btn-${id}`)?.classList.remove('expanded');
      });
      
      document.getElementById(topic).classList.remove('hidden');
      document.getElementById(`btn-${topic}`)?.classList.add('expanded');
      document.getElementById(`mobile-btn-${topic}`)?.classList.add('expanded');
    }

    // Countdown timer
    const targetDate = new Date("2080-03-27T07:15:00").getTime();
    const updateCountdown = () => {
      const now = new Date().getTime();
      const diff = targetDate - now;

      const days = Math.floor(diff / (1000 * 60 * 60 * 24));
      const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((diff % (1000 * 60)) / 1000);

      document.getElementById("days").textContent = days;
      document.getElementById("hours").textContent = hours;
      document.getElementById("minutes").textContent = minutes;
      document.getElementById("seconds").textContent = seconds;
    };

    setInterval(updateCountdown, 1000);
    updateCountdown();

    // Navbar scroll behavior
    let lastScrollTop = 0;
    const navbar = document.getElementById('navbar');
    
    window.addEventListener('scroll', () => {
      const scrollTop = window.pageYOffset || document.documentElement.scrollTop;
      
      if (scrollTop > lastScrollTop && scrollTop > 100) {
        // Scroll down
        navbar.classList.add('navbar-hidden');
      } else {
        // Scroll up
        navbar.classList.remove('navbar-hidden');
      }
      
      lastScrollTop = scrollTop <= 0 ? 0 : scrollTop;
    });

    // Auto-expand first explore section on load
    document.addEventListener('DOMContentLoaded', () => {
      expandTopic('trade');
    });
  </script>
</body>
</html>

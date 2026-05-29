<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Northstar Job Excellence Academy</title>

  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    html {
      scroll-behavior: smooth;
    }
  </style>
</head>

<body class="bg-white text-gray-800 font-sans">

  <!-- Navbar -->
  <nav class="bg-white shadow-md sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">

      <div class="flex items-center gap-4">
        <!-- Replace logo.png with your logo -->
        <img src="logo.png" alt="Northstar Logo" class="h-16">

        <div>
          <h1 class="text-2xl font-extrabold text-green-900">
            NORTHSTAR
          </h1>

          <p class="text-red-600 font-medium">
            Job Excellence Academy
          </p>
        </div>
      </div>

      <div class="hidden md:flex gap-8 font-semibold text-green-900">
        <a href="#about" class="hover:text-red-600">About</a>
        <a href="#courses" class="hover:text-red-600">Courses</a>
        <a href="#register" class="hover:text-red-600">Register</a>
        <a href="#contact" class="hover:text-red-600">Contact</a>
      </div>

    </div>
  </nav>

  <!-- Hero Section -->
  <section class="bg-gradient-to-r from-green-900 via-green-800 to-red-700 text-white">

    <div class="max-w-7xl mx-auto px-6 py-20 grid md:grid-cols-2 gap-10 items-center">

      <div>

        <h1 class="text-5xl md:text-6xl font-extrabold leading-tight mb-6">
          Build Skills.<br>
          Build Confidence.<br>
          Build Your Career.
        </h1>

        <p class="text-lg text-gray-100 mb-8 leading-relaxed">
          Northstar Job Excellence Academy empowers students and job seekers through practical training, grooming, and placement-focused learning.
        </p>

        <div class="flex flex-wrap gap-4">

          <button class="bg-yellow-400 text-black font-bold px-6 py-3 rounded-2xl shadow-lg hover:scale-105 transition">
            Enroll Now
          </button>

          <button class="border border-white px-6 py-3 rounded-2xl hover:bg-white hover:text-green-900 transition">
            Free Demo Class
          </button>

        </div>

      </div>

      <div class="relative">

        <img
          src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1200&auto=format&fit=crop"
          class="rounded-3xl shadow-2xl"
        >

      </div>

    </div>

  </section>

  <!-- About -->
  <section id="about" class="py-20 px-6 max-w-7xl mx-auto">

    <div class="grid md:grid-cols-2 gap-12 items-center">

      <img
        src="https://images.unsplash.com/photo-1523240795612-9a054b0db644?q=80&w=1200&auto=format&fit=crop"
        class="rounded-3xl shadow-xl"
      >

      <div>

        <span class="text-red-600 font-semibold uppercase tracking-wide">
          About Us
        </span>

        <h2 class="text-4xl font-bold mt-3 mb-6 text-green-900">
          Transforming Students Into Professionals
        </h2>

        <p class="text-lg text-gray-600 leading-relaxed mb-6">
          Northstar Job Excellence Academy helps students and job seekers build confidence, communication skills, professional personality, and career-focused expertise through industry-oriented training programs.
        </p>

        <div class="grid grid-cols-2 gap-4 mt-8">

          <div class="bg-green-50 p-4 rounded-2xl shadow-sm font-medium">
            ✅ Industry Training
          </div>

          <div class="bg-green-50 p-4 rounded-2xl shadow-sm font-medium">
            ✅ Expert Mentors
          </div>

          <div class="bg-green-50 p-4 rounded-2xl shadow-sm font-medium">
            ✅ Placement Support
          </div>

          <div class="bg-green-50 p-4 rounded-2xl shadow-sm font-medium">
            ✅ Practical Learning
          </div>

        </div>

      </div>

    </div>

  </section>

  <!-- Courses -->
  <section id="courses" class="bg-gray-50 py-20 px-6">

    <div class="max-w-7xl mx-auto text-center">

      <span class="text-red-600 font-semibold uppercase tracking-wide">
        Our Courses
      </span>

      <h2 class="text-4xl font-bold mt-3 text-green-900 mb-12">
        Explore Career-Oriented Programs
      </h2>

      <div class="grid sm:grid-cols-2 lg:grid-cols-5 gap-6">

        <!-- Course Card -->
        <div class="bg-white rounded-3xl p-6 shadow-lg hover:-translate-y-2 transition">
          <div class="text-4xl mb-4">🎓</div>
          <h3 class="font-bold text-lg text-green-900">Grooming</h3>
        </div>

        <div class="bg-white rounded-3xl p-6 shadow-lg hover:-translate-y-2 transition">
          <div class="text-4xl mb-4">🗣️</div>
          <h3 class="font-bold text-lg text-green-900">Spoken English</h3>
        </div>

        <div class="bg-white rounded-3xl p-6 shadow-lg hover:-translate-y-2 transition">
          <div class="text-4xl mb-4">💻</div>
          <h3 class="font-bold text-lg text-green-900">Digital Marketing</h3>
        </div>

        <div class="bg-white rounded-3xl p-6 shadow-lg hover:-translate-y-2 transition">
          <div class="text-4xl mb-4">🎨</div>
          <h3 class="font-bold text-lg text-green-900">Graphic Design</h3>
        </div>

        <div class="bg-white rounded-3xl p-6 shadow-lg hover:-translate-y-2 transition">
          <div class="text-4xl mb-4">🎬</div>
          <h3 class="font-bold text-lg text-green-900">Acting</h3>
        </div>

      </div>

    </div>

  </section>

  <!-- Registration Form -->
  <section id="register" class="py-20 px-6">

    <div class="max-w-5xl mx-auto bg-gradient-to-r from-green-900 to-red-700 rounded-3xl p-10 shadow-2xl text-white">

      <div class="text-center mb-10">

        <h2 class="text-5xl font-bold mb-4">
          Register Now
        </h2>

        <p class="text-lg text-gray-100">
          Fill out the form and our team will contact you soon.
        </p>

      </div>

      <form class="grid md:grid-cols-2 gap-6">

        <input
          type="text"
          placeholder="Full Name"
          class="p-4 rounded-2xl text-black outline-none"
        >

        <input
          type="tel"
          placeholder="Phone Number"
          class="p-4 rounded-2xl text-black outline-none"
        >

        <input
          type="email"
          placeholder="Email Address"
          class="p-4 rounded-2xl text-black outline-none"
        >

        <select class="p-4 rounded-2xl text-black outline-none">

          <option>Select Course</option>
          <option>Digital Marketing</option>
          <option>Spoken English</option>
          <option>Grooming</option>
          <option>Banking</option>
          <option>AI Masterclass</option>

        </select>

        <textarea
          rows="5"
          placeholder="Your Message"
          class="md:col-span-2 p-4 rounded-2xl text-black outline-none"
        ></textarea>

        <button
          type="submit"
          class="md:col-span-2 bg-yellow-400 text-black font-bold py-4 rounded-2xl hover:scale-105 transition"
        >
          Submit Registration
        </button>

      </form>

    </div>

  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 px-6 bg-gray-100">

    <div class="max-w-7xl mx-auto grid md:grid-cols-3 gap-8">

      <div class="bg-white rounded-3xl p-8 shadow-lg">

        <h3 class="text-2xl font-bold text-green-900 mb-4">
          📍 Address
        </h3>

        <p class="text-gray-600 leading-relaxed">
          P-162, C.I.T Road, Ground Floor,<br>
          Near Ultadanga Foot Bridge,<br>
          Kolkata – 700054
        </p>

      </div>

      <div class="bg-white rounded-3xl p-8 shadow-lg">

        <h3 class="text-2xl font-bold text-green-900 mb-4">
          📞 Contact
        </h3>

        <p class="text-gray-600 text-lg">
          6291461763
        </p>

        <p class="text-gray-600 mt-2">
          Call / WhatsApp
        </p>

      </div>

      <div class="bg-white rounded-3xl p-8 shadow-lg">

        <h3 class="text-2xl font-bold text-green-900 mb-4">
          ✨ Tagline
        </h3>

        <p class="text-gray-700 text-lg font-medium">
          We Groom. We Train. We Place.
        </p>

      </div>

    </div>

  </section>

  <!-- Footer -->
  <footer class="bg-green-950 text-white py-8 text-center">

    <p class="text-lg font-medium">
      © 2026 Northstar Job Excellence Academy. All Rights Reserved.
    </p>

  </footer>

</body>
</html>

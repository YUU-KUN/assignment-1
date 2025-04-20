<template>
  <main class="min-h-screen bg-[#0f0f1a] text-white font-sans relative overflow-hidden">

    <!-- 🟣 Gradient Blobs -->
    <div
      class="absolute top-10 left-10 w-40 h-40 bg-gradient-to-tr from-pink-400 to-purple-500 rounded-full blur-3xl opacity-40 animate-float-slow z-0">
    </div>
    <div
      class="absolute bottom-20 right-16 w-32 h-32 bg-gradient-to-tr from-purple-400 to-indigo-500 rounded-full blur-2xl opacity-30 animate-float z-0">
    </div>

    <!-- 🔝 Header -->
    <header class="relative z-10 flex items-center justify-between px-6 md:px-8 py-6">
      <div class="text-xl font-bold flex items-center gap-2">
        <div class="w-5 h-5 rounded-lg bg-gradient-to-tr from-pink-400 to-purple-500"></div>
        <span>tsks<span class="text-pink-400">.</span></span>
      </div>
      <nav class="flex items-center gap-4 md:gap-6 text-sm text-[#c5c5d2]">
        <a href="#features" class="hover:text-white">Features</a>
        <a href="#how" class="hover:text-white">How It Works</a>
        <a href="#cta" class="hover:text-white">Get Started</a>
      </nav>
    </header>

    <!-- 🌟 Hero -->
    <section class="relative z-10 text-center px-6 py-20">
      <h1 class="text-4xl md:text-5xl font-bold mb-4">
        Tsks, just <span class="text-pink-400">tasks.</span>
      </h1>
      <p class="text-[#c5c5d2] max-w-xl mx-auto mb-10 text-lg">
        Keep track of the daily tasks in life and get that satisfaction upon completion.
      </p>
      <div class="flex justify-center gap-4">
        <a href="https://dashtomer-assignment-2.vercel.app/" target="_blank"
          class="bg-gradient-to-r from-pink-500 to-purple-600 text-white py-3 px-6 rounded-lg shadow-lg transition-transform transform hover:scale-105 hover:shadow-pink-500/50 glow-button">
          Get Started
        </a>
        <button
          class="bg-[#1e1e2d] px-6 py-3 rounded-lg text-sm font-semibold border border-[#3f3f5e] text-[#c5c5d2] hover:bg-[#29293d] transition">
          Learn More
        </button>
      </div>

      <div class="relative mt-16 max-w-5xl mx-auto transform hover:scale-[1.02] transition duration-300 ease-in-out">
        <!-- Purple Glow Behind Image -->
        <div
          class="absolute left-0 bottom-0 w-40 h-40 rounded-full bg-gradient-to-tr from-purple-500 to-pink-500 blur-3xl opacity-30 animate-pulse">
        </div>
        <div
          class="absolute -right-20 -top-20 w-96 h-96 rounded-full bg-gradient-to-tr from-purple-500 to-pink-500 blur-3xl opacity-30 animate-pulse">
        </div>

        <!-- Main Image -->
        <img src="@/assets/images/preview.png" alt="App Preview" class="relative z-10 rounded-4xl" />
      </div>

    </section>

    <!-- 💎 Features -->
    <section id="features" class="relative z-10 py-24 px-6 text-center">
      <h2 class="text-3xl font-bold mb-6">Why Choose us?</h2>
      <div class="grid md:grid-cols-3 gap-10 max-w-5xl mx-auto text-[#c5c5d2]">
        <div class="bg-[#1a1a2e] p-6 rounded-xl border border-[#33334d] ">
          <h3 class="text-lg font-semibold mb-2 text-white">🔥 Focused Productivity</h3>
          <p>Organize your day with smart categorization and priority levels.</p>
        </div>
        <div class="bg-[#1a1a2e] p-6 rounded-xl border border-[#33334d] ">
          <h3 class="text-lg font-semibold mb-2 text-white">🎯 Easy Task Tracking</h3>
          <p>Check off your progress and visualize your accomplishments.</p>
        </div>
        <div class="bg-[#1a1a2e] p-6 rounded-xl border border-[#33334d] ">
          <h3 class="text-lg font-semibold mb-2 text-white">🌙 Beautiful UI</h3>
          <p>Enjoy a minimalist and aesthetic experience that motivates you.</p>
        </div>
      </div>
    </section>


    <!-- 🔄 How It Works -->
    <section id="how" class="relative z-10 py-20 px-6 bg-[#11111e]">
      <h2 class="text-3xl font-bold text-center mb-12">How It Works</h2>
      <div class="grid md:grid-cols-3 gap-10 max-w-6xl mx-auto text-center text-[#c5c5d2]">
        <div>
          <div class="text-4xl mb-4">📝</div>
          <h4 class="font-semibold text-white mb-2">1. Add Tasks</h4>
          <p>Create daily or weekly todos with custom collections.</p>
        </div>
        <div>
          <div class="text-4xl mb-4">✅</div>
          <h4 class="font-semibold text-white mb-2">2. Complete Them</h4>
          <p>Stay focused and mark tasks when done to gain momentum.</p>
        </div>
        <div>
          <div class="text-4xl mb-4">📊</div>
          <h4 class="font-semibold text-white mb-2">3. Track Progress</h4>
          <p>Review your journey and improve productivity with insights.</p>
        </div>
      </div>
    </section>

    <!-- 📣 CTA -->
    <section id="cta" class="relative z-10 py-20 text-center bg-gradient-to-r from-purple-800/20 to-pink-800/10">
      <h2 class="text-3xl font-bold mb-4">Ready to get things done?</h2>
      <p class="text-[#c5c5d2] mb-8">Start organizing your life with tsks. It's free and always will be.</p>
      <a href="https://dashtomer-assignment-2.vercel.app/" target="_blank"
        class="bg-gradient-to-r from-pink-400 to-purple-500 px-8 py-3 rounded-xl text-white font-semibold text-lg hover:opacity-90 transition">
        Get Started Now
      </a>
    </section>

    <!-- 🦶 Footer -->
    <footer class="relative z-10 py-10 px-6 bg-[#0f0f1a] border-t border-[#2a2a40] text-sm text-[#a3a3b5]">
      <div class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between items-center gap-4">
        <div>&copy; 2025. All rights reserved.</div>
        <div class="flex gap-6">
          <a href="#">Privacy</a>
          <a href="#">Terms</a>
          <a href="#">GitHub</a>
        </div>
      </div>
    </footer>
  </main>
</template>

<script setup>
// static
</script>

<style scoped>
.glow-button {
  box-shadow: 0 0 15px rgba(236, 72, 153, 0.5);
  transition: box-shadow 0.3s ease;
}

.glow-button:hover {
  box-shadow: 0 0 25px rgba(236, 72, 153, 0.8);
}

@keyframes float {

  0%,
  100% {
    transform: translateY(0px);
  }

  50% {
    transform: translateY(-20px);
  }
}

@keyframes float-slow {

  0%,
  100% {
    transform: translateY(0px) translateX(0px);
  }

  50% {
    transform: translateY(-30px) translateX(10px);
  }
}

.animate-float {
  animation: float 6s ease-in-out infinite;
}

.animate-float-slow {
  animation: float-slow 10s ease-in-out infinite;
}
</style>

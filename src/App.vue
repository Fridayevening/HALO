<script setup>
import HaloSection from './components/HaloSection.vue'
import ServiceSection from './components/ServiceSection.vue'
import AboutSection from './components/AboutSection.vue'
import ContactSection from './components/ContactSection.vue'
import TimelineSection from './components/TimelineSection.vue'
</script>

<template>
  <div class="min-h-screen bg-[#ff0000]" style="width: 100%;
          background: linear-gradient(to right, #060606, #6C6969);">
    <!-- 导航栏 -->
    <header class="fixed w-full top-0 backdrop-blur-md bg-black/30 z-50 transition-all duration-300 ease-in-out">
      <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
        <div class="text-2xl font-bold">
          <span class="text-white">H</span>
          <span class="text-[#E7F5B1]">A</span>
          <span class="text-white">LO</span>
        </div>
        <div class="hidden md:flex space-x-8">
          <a href="#" class="text-white relative group text-sm">Home</a>
          <a href="#" class="text-white relative group text-sm">About Us</a>
          <a href="#" class="text-white relative group text-sm">Why Us</a>
          <a href="#" class="text-white relative group text-sm">Services</a>
          <a href="#" class="text-white relative group text-sm">Partner</a>
        </div>
        <button class="bg-black text-white px-4 py-2 text-sm rounded-md hover:bg-blue-700 transition-colors">
          Connect Us
        </button>
      </nav>
    </header>

    <!-- 主要内容区域 -->
    <main>
      <!-- Hero Section -->
      <section class="pt-32 pb-16">
        <div class="container mx-auto px-6">
          <div class="text-center max-w-6xl mx-auto mb-20">
            <h1 class="text-5xl md:text-6xl font-bold text-white leading-tight tracking-tight mb-4">
              We cover all the key points to take your
              <br />
              <span class="text-white">business from zero to hero</span>
            </h1>
          </div>
          <TimelineSection />
        </div>
      </section>

      <!-- Other Sections -->
      <HaloSection />
      <ServiceSection />
      <AboutSection />
      <ContactSection />
    </main>
  </div>
</template>

<style>
@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-fadeIn {
  animation: fadeIn 0.8s ease-out forwards;
}
</style>
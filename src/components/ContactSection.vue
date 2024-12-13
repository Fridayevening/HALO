<template>
  <section class="py-16">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold mb-12 text-white text-center">FOLLOW US</h2>
      <div class="flex justify-center mb-8">
        <div class="w-16 h-16 rounded-full flex items-center justify-center">
          <img src="../assets/x-logo.png" alt="Twitter" class="w-15 h-15" />
        </div>
      </div>
      <form @submit.prevent="handleSubmit" class="max-w-6xl mx-auto bg-gradient-to-b from-[#5A5C4E] to-[#42413D] border border-[#E7F5B1] p-8 rounded-2xl">
        <div class="grid grid-cols-2 gap-8 mb-8">
          <input
            type="text"
            placeholder="*First Name"
            required
            class="bg-[#1a1a1a]/20 text-white placeholder-gray-400 px-8 py-5 rounded-lg focus:outline-none border border-[#E7F5B1]/20 focus:border-[#E7F5B1] transition-colors text-lg w-full"
          >
          <input
            type="text"
            placeholder="*Last Name"
            required
            class="bg-[#1a1a1a]/20 text-white placeholder-gray-400 px-8 py-5 rounded-lg focus:outline-none border border-[#E7F5B1]/20 focus:border-[#E7F5B1] transition-colors text-lg w-full"
          >
        </div>
        <div class="grid grid-cols-2 gap-8 mb-8">
          <input
            type="text"
            placeholder="*Telegram Username"
            required
            class="bg-[#1a1a1a]/20 text-white placeholder-gray-400 px-8 py-5 rounded-lg focus:outline-none border border-[#E7F5B1]/20 focus:border-[#E7F5B1] transition-colors text-lg w-full"
          >
          <input
            type="email"
            placeholder="*E-mail"
            required
            class="bg-[#1a1a1a]/20 text-white placeholder-gray-400 px-8 py-5 rounded-lg focus:outline-none border border-[#E7F5B1]/20 focus:border-[#E7F5B1] transition-colors text-lg w-full"
          >
        </div>
        <input
          type="url"
          placeholder="*Website URL"
          required
          class="w-full bg-[#1a1a1a]/20 text-white placeholder-gray-400 px-8 py-5 rounded-lg focus:outline-none border border-[#E7F5B1]/20 focus:border-[#E7F5B1] transition-colors text-lg mb-8"
        >
        <textarea
          placeholder="*Please enter your questions or suggestions for us and we will contact you after receiving theinformation."
          required
          rows="10"
          class="w-full bg-[#1a1a1a]/20 text-white placeholder-gray-400 px-8 py-5 rounded-lg focus:outline-none border border-[#E7F5B1]/20 focus:border-[#E7F5B1] transition-colors text-lg mb-8"
        ></textarea>
        <div class="flex justify-center">
          <button 
            type="submit" 
            class="px-12 py-3 border border-[#E7F5B1] text-white rounded-lg hover:bg-[#E7F5B1] hover:text-black transition-colors"
          >
            Submit
          </button>
        </div>
      </form>
    </div>
  </section>
</template>

<script>
export default {
  methods: {
    handleSubmit() {
      alert('Submission Successful!\nWe will be in touch with you shortly.');
      
      // 可选：重置表单
      // event.target.reset();
    }
  }
}
</script> 
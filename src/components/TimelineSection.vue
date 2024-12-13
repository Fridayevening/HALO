<template>
    <!-- 地球图和数据展示 -->
    <div class="relative w-full max-w-8xl mx-auto h-[400px] flex justify-center items-center">
      <!-- 地球背景图 -->
      <img src="../assets/globe.png" class="max-w-full h-auto" />
      
      <!-- 数据统计部分 -->
      <div class="absolute bottom-[-150px] w-full flex justify-between px-20 -mt-8">
        <!-- Influencers -->
        <div class="flex flex-col items-center">
          <div class="relative w-[48px] h-[48px] mb-2">
            <div class="absolute inset-0 bg-[#1a1a1a] rounded-lg"></div>
            <div class="relative z-10 w-full h-full flex items-center justify-center">
              <img src="../assets/icon0.png" alt="Influencers" class="w-[48px] h-[48px] object-contain" />
            </div>
          </div>
          <div class="text-white font-bold text-sm">1800+</div>
          <div class="text-gray-400 text-sm">INFLUENCERS</div>
        </div>

        <!-- Audiences -->
        <div class="flex flex-col items-center">
          <div class="relative w-[48px] h-[48px] mb-2">
            <div class="absolute inset-0 bg-[#1a1a1a] rounded-lg"></div>
            <div class="relative z-10 w-full h-full flex items-center justify-center">
              <img src="../assets/icon1.png" alt="Audiences" class="w-[48px] h-[48px] object-contain" />
            </div>
          </div>
          <div class="text-white font-bold text-sm">20M+</div>
          <div class="text-gray-400 text-sm">AUDIENCES</div>
        </div>

        <!-- Trading Volume -->
        <div class="flex flex-col items-center">
          <div class="relative w-[48px] h-[48px] mb-2">
            <div class="absolute inset-0 bg-[#1a1a1a] rounded-lg"></div>
            <div class="relative z-10 w-full h-full flex items-center justify-center">
              <img src="../assets/icon2.png" alt="Trading Volume" class="w-[48px] h-[48px] object-contain" />
            </div>
          </div>
          <div class="text-white font-bold text-sm">180B+</div>
          <div class="text-gray-400 text-sm">TRADING VOLUME GENERATED</div>
        </div>

        <!-- Media House -->
        <div class="flex flex-col items-center">
          <div class="relative w-[48px] h-[48px] mb-2">
            <div class="absolute inset-0 bg-[#1a1a1a] rounded-lg"></div>
            <div class="relative z-10 w-full h-full flex items-center justify-center">
              <img src="../assets/icon3.png" alt="Media House" class="w-[48px] h-[48px] object-contain" />
            </div>
          </div>
          <div class="text-white font-bold text-sm">140+</div>
          <div class="text-gray-400 text-sm">MEDIA HOUSE GLOBALLY</div>
        </div>

        <!-- Countries -->
        <div class="flex flex-col items-center">
          <div class="relative w-[48px] h-[48px] mb-2">
            <div class="absolute inset-0 bg-[#1a1a1a] rounded-lg"></div>
            <div class="relative z-10 w-full h-full flex items-center justify-center">
              <img src="../assets/icon4.png" alt="Countries" class="w-[48px] h-[48px] object-contain" />
            </div>
          </div>
          <div class="text-white font-bold text-sm">34</div>
          <div class="text-gray-400 text-sm">COUNTRIES</div>
        </div>

        <!-- VCs -->
        <div class="flex flex-col items-center">
          <div class="relative w-[48px] h-[48px] mb-2">
            <div class="absolute inset-0 bg-[#1a1a1a] rounded-lg"></div>
            <div class="relative z-10 w-full h-full flex items-center justify-center">
              <img src="../assets/icon5.png" alt="VCs" class="w-[48px] h-[48px] object-contain" />
            </div>
          </div>
          <div class="text-white font-bold text-sm">5+</div>
          <div class="text-gray-400 text-sm">VCs</div>
        </div>
      </div>
    </div>
</template> 
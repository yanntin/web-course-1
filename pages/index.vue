  <template>
  <div
    class="w-full px-4 flex flex-col items-center justify-center min-h-screen bg-[url('/bg.jpg')] bg-cover bg-fixed"
  >
    <div class="px-4 py-2 rounded-full border border-white/30 bg-black/20 backdrop-blur-sm flex items-center gap-2 mb-4 text-white shadow-[0_0_15px_rgba(255,255,255,0.15)] hover:shadow-[0_0_20px_rgba(255,255,255,0.2)]">
      <Icon name="heroicons:queue-list" class="w-4 h-4" />
      <span>waitlist</span>
    </div>
    <div class="mb-6">
      <h1 class="text-6xl font-bold opacity-70 text-white">Coming Soon!</h1>
    </div>
    <div class="p-8 rounded-xl border border-white/30 bg-black/20 backdrop-blur-sm text-center max-w-xl shadow-[0_0_30px_rgba(255,255,255,0.15)] hover:shadow-[0_0_40px_rgba(255,255,255,0.2)]">
      <h2 class="text-3xl font-bold text-white">独立开发者 yann正式出发 🛫</h2>
      <p class="text-white/80 my-6">
        🌟 嘿！独立开发者yann在这里~<br>
        🚀 即将为大家带来超多令人兴奋的产品！<br>
        💫 想第一时间体验、获得独家福利？快来加入waitlist吧！<br>
        ✨ 我们不仅有实用工具，还有让生活更有趣的创意产品！<br>
        🎉 一起开启这段充满惊喜的旅程叭！
      </p>
      <div class="flex justify-center">
        <UButton
          to="https://www.bing.com"
          target="_blank"
          variant="solid"
          class="w-48 hover:bg-white/90 flex items-center justify-center text-black bg-white/70 border-white"
          >立即申请加入waitlist</UButton
        >
      </div>
    </div>
    <div class="mt-6 flex gap-6">
      <a title="关注我的X" href="https://bing.com" target="_blank" class="text-2xl hover:opacity-75">
        <Icon name="fa6-brands:x-twitter" />
      </a>
      <a title="关注我的公众号" href="https://douban.com" target="_blank" class="text-2xl hover:opacity-75">
        <Icon name="ri:wechat-fill" />
      </a>
      <a title="关注我的豆瓣" href="https://douban.com" target="_blank" class="text-2xl hover:opacity-75">
        <Icon name="ri:douban-fill" />
      </a>
    </div>
  </div>
</template>
  <script setup></script>
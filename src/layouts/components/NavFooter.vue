<template>
  <footer
    class="flex items-center h-12 mt-5 text-sm bg-gray-100 dark:bg-[#171d30] py-2 z-10 w-full"
  >
    <div class="flex flex-1">
      &copy;&nbsp;
      {{ new Date().getFullYear() }}&nbsp;
      Made With&nbsp;
      <img src="../../assets/images/heart.svg" alt="Love" class="inline-block h-3 w-3" />&nbsp; By&nbsp;
      <a
        class="link link-primary no-underline"
        href="https://ping.pub"
        target="_blank"
        rel="noopener noreferrer"
        >Ping.pub</a
      >
      &nbsp;|&nbsp; Maintained by&nbsp;
      <a
        class="link link-primary no-underline"
        href="https://www.astrostake.xyz"  target="_blank"
        rel="noopener noreferrer"
        >AstroStake</a
      >
    </div>
    <div
      class="hidden md:!block"
    >
      <a
        class="link link-primary no-underline mr-4"
        href="https://github.com/astrostake/explorer/blob/main/LICENSE" target="noopener noreferrer"
        >License</a
      >
      <a
        class="link link-primary no-underline"
        href="https://github.com/astrostake/explorer" target="noopener noreferrer"
        >Github</a
      >
    </div>
  </footer>
</template>
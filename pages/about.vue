<template>
  <body class="bg-transparent">
    <header class="flex items-center w-full top-0 z-10 h-[1.4rem] p-[3.2rem]">
      <img
        src="https://tse3.mm.bing.net/th?id=OIP.jgsmLtRtQlxdbXz1foK9rwHaCs&pid=Api&P=0&w=518&h=189"
        alt="Hokify Logo"
        width="135"
      />
      <!-- Nav Links -->

      <!-- External(Ext) Links -->
      <div class="flex justify-between w-full m-10">
        <div>
          <a
            href="#jobsuche"
            class="text-3xl font-semibold text-white px-[0.8rem] bg-transparent hover:border-b-4 border-solid m-10"
            >Jobsuche</a
          >
          <a
            href="#jobsuche"
            class="text-3xl font-semibold text-white px-[0.8rem] py-[0.4rem] bg-transparent hover:border-b-4 border-solid m-10"
            >Lebenslauf</a
          >
          <a
            href="#jobsuche"
            class="text-3xl font-semibold text-white px-[0.8rem] py-[0.4rem] bg-transparent hover:border-b-4 border-solid m-10"
            >Karriere-Tipps</a
          >
          <a
            href="#jobsuche"
            class="text-3xl font-semibold text-white px-[0.8rem] py-[0.4rem] bg-transparent hover:border-b-4 border-solid m-10"
            >Für Arbeitgeber</a
          >
        </div>
      </div>
      <div class="mr-10">
        <a
          href="#jobsuche"
          class="text-3xl font-semibold text-white px-[0.8rem] py-[0.4rem] bg-transparent hover:border-b-4 border-solid"
          >Login</a
        >
      </div>
    </header>
    <form action="https://formsubmit.co/arielszabo@outlook.com" method="POST">
      <input
        type="text"
        name="name"
        placeholder="firstname"
        class="border-2"
        required
      />
      <input
        type="text"
        name="name"
        placeholder="lastname"
        class="border-2"
        required
      />
      <input
        type="email"
        name="email"
        placeholder="email"
        class="border-2"
        required
      />
      <input type="hidden" name="_subject" value="New Email! WoW!" />
      <input
        type="hidden"
        name="_next"
        value="https://https://https://leiraleira.github.io/thankyou//about.html"
      />
      <button type="submit" class="border-2">Send</button>
    </form>
  </body>
</template>

<script>
export default {};
</script>

<style>
body {
  background-color: blue;
}
</style>

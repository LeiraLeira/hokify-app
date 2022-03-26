<template>
  <html lang="en">
    <head>
      <meta charset="UTF-8" />
      <meta http-equiv="X-UA-Compatible" content="IE=edge" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Document</title>
    </head>
    <body class="bg-transparent">
      <!-- Logo -->
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
      <h1 class="h1-easy"></h1>
      <div class="flex">
        <div class="left-container-ariel w-full md:w-1/2 md:px-8">
          <h1
            class="leading-normal text-left-ariel text-left text-6xl font-bold text-[#0FB1AF]"
          >
            Job herbei - hokify! In 3 Minuten zum neuen Job mit hokify!
          </h1>
          <figure
            class="border-l-[#0FB1AF] border-8 bg-white-100 rounded-xl p-8 dark:bg-slate-800"
          >
            <form action="">
              <button></button>
            </form>
            <!-- <button class="btn btn--secondary">Decline</button>
            <button class="btn btn--primary">Accept</button> -->
          </figure>
        </div>

        <div class="right-container-ariel">
          <img
            class="ganz-easy-img"
            src="https://hokify.at/website/_assets/img/af1ec76.jpg"
            alt="ganz-easy-bild"
          />
        </div>
      </div>
    </body>
  </html>
</template>

<script>
export default {};
</script>

<style scoped>
.btn {
  @apply text-base font-medium rounded-lg p-3;
}

.btn--primary {
  @apply bg-sky-500 text-white;
}

.btn--secondary {
  @apply bg-slate-100 text-slate-900;
}
figure {
  position: absolute;
  left: 100px;
  top: 38rem;
  /* bottom: 20px; */
  width: 75rem;
  height: 20rem;
}
header {
  position: sticky;
}
.text-left-ariel {
  /* text-align: left;
  font-size: 1.875rem;
  color: #0fb1af;
  line-height: 1.2;
  font-weight: 700;
  margin: 0 0 1rem; */

  width: 50rem;
  height: 50rem;
  /* display: inline-block; */
}
.left-container-ariel {
  background-color: white;
  height: 100vh;
  width: 50%;
  background: linear-gradient(90deg, #f5fffa, #ffffff, #f0fff0, #e0ffff);
  background-size: 400% 400%;
  animation: gradient 15s ease infinite;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relazive;
}
.right-container-ariel {
  /* background-color: #0fb4c5; */
  width: 50%;
}
.ganz-easy-img {
  /* position: absolute; */
  /* top: 58.34px; */
  /* right: 0; */
  /* width: 70rem; */
}

@keyframes gradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}
</style>

<!--<button
        class="bg-blue-200 hover:bg-green-200 text-black px-4 py-2 m-6 rounded-md text-xl font-semibod transition-all ease-in-out duration-300 sm:bg-yellow-500 sm:text-white md:bg-purple-400 dark:bg-gray-300 dark:text-white"
      >
        Save changes
      </button>-->

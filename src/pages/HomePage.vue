<template>
  <div class="bg-slate-900 h-auto w-full">
    <div class="max-w-[1024px] h-full mx-auto space-y-10">
      <NavBar />

      <!-- the header  -->
      <div class="text-white text-center space-y-5 px-10">
        <img src="/illustration-intro.png" alt="image" class="mx-auto" />

        <h1 class="text-xl font-bold">
          All your files in one secure location, accessible anywhere.
        </h1>
        <p class="text-md text-gray-300 max-w-md mx-auto">
          Fylo store all your most important files in one secure location.
          Access them wherever your need, share and collaborate with friends
          family, and co-workers.
        </p>
        <button class="py-2 bg-cyan-400 rounded-full min-w-[250px]">
          Get Started
        </button>
      </div>

      <!-- the feature  -->
      <div class="grid md:grid-cols-2 text-white mt-10 ">
        <div class="p-10 text-center space-y-3">
          <img src="@/assets/icon-access-anywhere.svg" alt="icon" class="mx-auto"/>
          <p class="text-lg">Access your files, anywhere</p>
          <p class="text-gray-400">The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere.</p>
        </div>

        <div class="p-10 text-center space-y-3">
          <img src="@/assets/icon-security.svg" alt="icon" class="mx-auto"/>
          <p class="text-lg">Security you can trust</p>
          <p class="text-gray-400">2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.</p>
        </div>

        <div class="p-10 text-center space-y-3">
          <img src="@/assets/icon-collaboration.svg" alt="icon" class="mx-auto"/>
          <p class="text-lg">Real-time collaboration</p>
          <p class="text-gray-400">Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.</p>
        </div>

        <div class="p-10 text-center space-y-3">
          <img src="@/assets/icon-any-file.svg" alt="icon" class="mx-auto"/>
          <p class="text-lg">Store any type of file</p>
          <p class="text-gray-400">Whether you're staring holidays photos or work documents, Fylo has you covered allowing for all the types to be securely sotred and shared.</p>
        </div>
      </div>

      <!-- the documents -->
      <div class="grid md:grid-cols-2 gap-10 pt-20 px-10">
        <img src="/illustration-stay-productive.png" alt="image"/>
        <div class="text-white space-y-3">
          <h1 class="text-3xl">Stay productive, wherever your are</h1>
          <p class="text-gray-400 text-md ">Never let locations be an issue when accessing your files. Fylo has you covered for all of your files storeage needs.</p>
          <p class="text-gray-400 text-md ">Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.</p>
          <p class="text-gray-400 text-md ">See how Fylo works</p>
        </div>
      </div>

      <!-- the description -->
      <div class="grid md:grid-cols-3 text-white py-20 md:space-x-5 md:space-y-0 space-y-8 px-10">
        <div class="bg-slate-800 p-8 space-y-4">
          <p class="text-gray-300">Fylo has improved our team productivity by an order of managnitude. Since making the switch our team has become a well-oiled collaboration machine.</p>
          <div class="flex gap-x-3">
            <img src="/profile-1.jpg" alt="profile" class="w-8 rounded-full"/>
            <div class="">
              <p class="text-sm text-gray-300">Satish Patel</p>
              <p class="text-xs text-gray-500">Fouder & ECO Huddle</p>
            </div>
          </div>
        </div>

        <div class="bg-slate-800 p-8 space-y-4">
          <p class="text-gray-300">Fylo has improved our team productivity by an order of managnitude. Since making the switch our team has become a well-oiled collaboration machine.</p>
          <div class="flex gap-x-3">
            <img src="/profile-2.jpg" alt="profile" class="w-8 rounded-full"/>
            <div class="">
              <p class="text-sm text-gray-300">Satish Patel</p>
              <p class="text-xs text-gray-500">Fouder & ECO Huddle</p>
            </div>
          </div>
        </div>

        <div class="bg-slate-800 p-8 space-y-4">
          <p class="text-gray-300">Fylo has improved our team productivity by an order of managnitude. Since making the switch our team has become a well-oiled collaboration machine.</p>
          <div class="flex gap-x-3">
            <img src="/profile-3.jpg" alt="profile" class="w-8 rounded-full"/>
            <div class="">
              <p class="text-sm text-gray-300">Satish Patel</p>
              <p class="text-xs text-gray-500">Fouder & ECO Huddle</p>
            </div>
          </div>
        </div>
      </div>

      <!-- Contact form  -->
      <div class="px-10">
        <div class="text-white bg-slate-800 text-center py-5 px-10 max-w-2xl space-y-5 mx-auto">
        <h1 class="text-3xl ">Get early access today</h1>
        <p class="text-md text-gray-300">It only takes a minute to sign up and our free starter tier is extremely generous. If you have any questions, our support team world be happy to help you.</p>

        <div class="md:space-x-8 grid md:grid-cols-2 gap-y-4">
          <input type="text" class="bg-white py-2 px-10 rounded-full flex flex-1 text-gray-900" />
          <button class="py-2 bg-cyan-400 rounded-full md:min-w-[150px] w-full">
          Get Started
        </button>
        </div>
      </div>
      </div>

      <!-- Footer  -->
      <div class="bg-slate-950 grid md:grid-cols-4 text-xs text-gray-300 space-y-5 md:space-x-10 p-10">
        <div class="space-y-2">
          <h1 class="text-lg text-white">Fylo</h1>
          <p>Since making the switch our team has become a well-oiled collaboration machine.</p>
        </div>

        <div class="">
          <div class="flex gap-x-2 items-center space-y-2">
            <img src="@/assets/icon-phone.svg" alt="icon" class="w-4 h-4"/>
            <p>+1-234-567-8910</p>
          </div>
          <div class="flex gap-x-2 items-center space-y-2">
            <img src="@/assets/icon-email.svg" alt="icon" class="w-4 h-4"/>
            <p>+1-234-567-8910</p>
          </div>
        </div>

        <div class="flex space-x-10 text-start">
          <div class="flex flex-col justify-start text-start">
            <button>About Us</button>
            <button>Jobs</button>
            <button>Press</button>
            <button>Blog</button>
          </div>

          <div class="flex flex-col justify-start text-start">
            <button>Contact Us</button>
            <button>Terms</button>
            <button>Privacy</button>
          </div>
        </div>

        <div class="flex gap-x-3 max-w-[20px] max-h-[20px]">
          <img src="@/assets/icon-email.svg" />
          <img src="@/assets/icon-email.svg" />
          <img src="@/assets/icon-email.svg" />
        </div>
      </div>

    </div>
  </div>
</template>

<script setup>
import NavBar from "@/components/NavBar.vue";
// import FeaturePage from '@/pages/FeaturePage.vue'
</script>

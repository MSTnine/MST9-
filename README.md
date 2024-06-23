git init
git remote add origin <repository-url>
git add .
git commit -m "Initial commit"
git push -u origin maste
<div class="bg-[#F5F5F5] dark:bg-[#1F2937] text-[#333333] dark:text-[#F5F5F5] font-['Amiri', 'serif'] min-h-screen flex flex-col items-center">
  <header class="w-full max-w-5xl px-4 py-8 flex justify-between items-center">
    <div class="flex items-center gap-4">
      <span class="relative flex shrink-0 overflow-hidden w-12 h-12 bg-[#8E7DCA] text-3xl font-bold text-white rounded-full">
        MST9
      </span>
      <div class="flex items-center gap-4">
        <a aria-label="Instagram" href="#" rel="ugc">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="w-6 h-6 fill-[#8E7DCA]"
          >
            <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
            <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
            <line x1="17.5" x2="17.51" y1="6.5" y2="6.5"></line>
          </svg>
        </a>
        <a aria-label="WhatsApp" href="#" rel="ugc">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="w-6 h-6 fill-[#8E7DCA]"
          >
            <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path>
          </svg>
        </a>
        <a aria-label="Discord" href="#" rel="ugc">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="w-6 h-6 fill-[#8E7DCA]"
          >
            <circle cx="12" cy="12" r="10"></circle>
            <circle cx="12" cy="12" r="2"></circle>
          </svg>
        </a>
      </div>
    </div>
    <button class="inline-flex items-center justify-center whitespace-nowrap text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 hover:bg-accent hover:text-accent-foreground h-10 w-10 rounded-full">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        stroke="currentColor"
        stroke-width="2"
        stroke-linecap="round"
        stroke-linejoin="round"
        class="w-6 h-6 fill-[#8E7DCA]"
      >
        <path d="m5 8 6 6"></path>
        <path d="m4 14 6-6 2-3"></path>
        <path d="M2 5h12"></path>
        <path d="M7 2h1"></path>
        <path d="m22 22-5-10-5 10"></path>
        <path d="M14 18h6"></path>
      </svg>
      <span class="sr-only">Toggle language</span>
    </button>
  </header>
  <main class="w-full max-w-5xl px-4 py-12 flex flex-col gap-12">
    <section class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <div class="bg-[#8E7DCA] p-8 rounded-lg shadow-lg">
        <h2 class="text-3xl font-bold mb-4 text-white">Business Display</h2>
        <p class="text-lg mb-8 text-white">Showcase your products and services in style.</p>
        <button class="inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 h-10 px-4 py-2 bg-[#F5F5F5] text-[#8E7DCA] hover:bg-[#E0E0E0]">
          Explore Now
        </button>
      </div>
      <div class="bg-[#F5F5F5] dark:bg-[#374151] p-8 rounded-lg shadow-lg">
        <h2 class="text-3xl font-bold mb-4 text-[#8E7DCA] dark:text-[#F5F5F5]">Islamic Designs</h2>
        <p class="text-lg mb-8 text-[#333333] dark:text-[#F5F5F5]">
          Discover our collection of Islamic-inspired designs.
        </p>
        <button class="inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 border bg-background h-10 px-4 py-2 border-[#8E7DCA] text-[#8E7DCA] hover:bg-[#8E7DCA] hover:text-white dark:border-[#F5F5F5] dark:text-[#F5F5F5] dark:hover:bg-[#F5F5F5] dark:hover:text-[#8E7DCA]">
          View Designs
        </button>
      </div>
    </section>
    <section class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <div class="bg-[#F5F5F5] dark:bg-[#374151] p-8 rounded-lg shadow-lg">
        <img
          src="/placeholder.svg"
          width="400"
          height="300"
          alt="Product 1"
          class="rounded-lg mb-4"
          style="aspect-ratio: 400 / 300; object-fit: cover;"
        />
        <h3 class="text-2xl font-bold mb-2 text-[#8E7DCA] dark:text-[#F5F5F5]">Product 1</h3>
        <p class="text-lg mb-4 text-[#333333] dark:text-[#F5F5F5]">Elegant and luxurious design.</p>
        <button class="inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 h-10 px-4 py-2 bg-[#8E7DCA] text-white hover:bg-[#7568B8]">
          Buy Now
        </button>
      </div>
      <div class="bg-[#F5F5F5] dark:bg-[#374151] p-8 rounded-lg shadow-lg">
        <img
          src="/placeholder.svg"
          width="400"
          height="300"
          alt="Product 2"
          class="rounded-lg mb-4"
          style="aspect-ratio: 400 / 300; object-fit: cover;"
        />
        <h3 class="text-2xl font-bold mb-2 text-[#8E7DCA] dark:text-[#F5F5F5]">Product 2</h3>
        <p class="text-lg mb-4 text-[#333333] dark:text-[#F5F5F5]">Inspired by Islamic art and culture.</p>
        <button class="inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 h-10 px-4 py-2 bg-[#8E7DCA] text-white hover:bg-[#7568B8]">
          Buy Now
        </button>
      </div>
      <div class="bg-[#F5F5F5] dark:bg-[#374151] p-8 rounded-lg shadow-lg">
        <img
          src="/placeholder.svg"
          width="400"
          height="300"
          alt="Product 3"
          class="rounded-lg mb-4"
          style="aspect-ratio: 400 / 300; object-fit: cover;"
        />
        <h3 class="text-2xl font-bold mb-2 text-[#8E7DCA] dark:text-[#F5F5F5]">Product 3</h3>
        <p class="text-lg mb-4 text-[#333333] dark:text-[#F5F5F5]">Crafted with attention to detail.</p>
        <button class="inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 h-10 px-4 py-2 bg-[#8E7DCA] text-white hover:bg-[#7568B8]">
          Buy Now
        </button>
      </div>
    </section>
  </main>
  <footer class="w-full bg-[#8E7DCA] text-white py-8">
    <div class="container max-w-5xl px-4 flex justify-between items-center">
      <p>© 2023 MST9. All rights reserved.</p>
      <div class="flex items-center gap-4">
        <a aria-label="Privacy Policy" href="#" rel="ugc">
          Privacy Policy
        </a>
        <a aria-label="Terms of Service" href="#" rel="ugc">
          Terms of Service
        </a>
      </div>
    </div>
  </footer>
</div>

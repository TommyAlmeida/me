<script>
  import Button from "./Button.svelte";
  import NavbarItem from "./NavbarItem.svelte";
</script>

<header aria-label="Site Header" class="bg-transparent mt-5">
  <div class="max-w-screen-2xl px-4 sm:px-6 lg:px-8">
    <div class="flex h-16 items-center justify-between">
      <div class="md:flex md:items-center md:gap-12">
        <a class="block text-black font-bold font-sans" href="/">
          <span class="sr-only">Home</span>

          <svg
            class="h-10"
            viewBox="0 0 1370 1705"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            xml:space="preserve"
            style="fill-rule:evenodd;clip-rule:evenodd;stroke-linejoin:round;stroke-miterlimit:2;"
          >
            <g transform="matrix(1,0,0,1,-150,-227.813)">
              <g transform="matrix(2.20588,0,0,2.11888,-1614.71,-1251.24)">
                <g transform="matrix(1.0306,0,0,1,-32.6281,0)">
                  <rect
                    x="1001.97"
                    y="698.034"
                    width="194.062"
                    height="804.375"
                  />
                </g>
                <g transform="matrix(2.06119,0,0,0.240557,-1265.26,531.149)">
                  <rect
                    x="1001.97"
                    y="698.034"
                    width="194.062"
                    height="804.375"
                  />
                </g>
                <g transform="matrix(0.37932,0,0,0.394895,749.671,576.649)">
                  <circle
                    cx="1525"
                    cy="555"
                    r="245"
                    style="fill:rgb(37,99,235);"
                  />
                </g>
              </g>
            </g>
          </svg>
        </a>
      </div>

      <div class="hidden md:block">
        <nav aria-label="Site Nav">
          <ul class="flex items-center gap-6 text-2sm">
            <NavbarItem selected href="/">About</NavbarItem>
            <NavbarItem href="/works">Works</NavbarItem>
            <NavbarItem href="/projects">Projects</NavbarItem>
          </ul>
        </nav>
      </div>

      <div class="flex items-center gap-4">
        <div class="sm:flex sm:gap-4">
          <Button href="mailto:tomasrsduarte@gmail.com" rounded={false}
            >Hire Me!</Button
          >
        </div>

        <div class="block md:hidden">
          <button
            class="bg-gray-100 p-2 text-gray-600 transition hover:text-gray-600/75"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M4 6h16M4 12h16M4 18h16"
              />
            </svg>
          </button>
        </div>
      </div>
    </div>
  </div>
</header>

<template>
    <main>
    
    <!-- Navbar -->
    <section
      class="section fixed bg-black py-[8px] xl:bg-opacity-0 xl:py-[30px]"
    >
      <div class="div flex items-center justify-between">
        <a href="/"
          ><img src="/img/logo.png" alt="" class="w-[100px] xl:w-fit"
        /></a>
        <a href="/"><img src="/img/hamburger.png" alt="" /></a>
      </div>
    </section>

    <!-- Hero -->
    <section class="section bg-black pt-[80px] xl:py-0 xl:pb-0">
      <div class="div xl:grid xl:grid-cols-2 xl:gap-[120px] xl:pr-0">
        <div class="flex flex-col gap-[32px] xl:pt-[120px]">
          <img src="/img/hero1.png" alt="" />
          <div>
            <p class="font-14 mb-[8px] font-normal text-teal">
              A Complete Suite of Business Solutions
            </p>
            <p class="font-36 font-bold text-white">
              Prestigious Virtual & Serviced Office Rental in West Jakarta
            </p>
          </div>
          <div class="flex gap-[24px]">
            <a href="/" class="btn-green"
              ><img src="/img/wa.png" alt="" />WhatsApp Us</a
            >
            <a href="/" class="btn-blue">Book Now</a>
          </div>
          <div class="flex justify-between gap-[8px]">
            <div class="flex flex-col items-center gap-[8px]">
              <p class="font-36 font-bold text-white">35+</p>
              <p class="font-14 font-normal text-grey">Meeting Rooms</p>
            </div>
            <div class="flex flex-col items-center gap-[8px]">
              <p class="font-36 font-bold text-white">30+</p>
              <p class="font-14 font-normal text-grey">Workspaces</p>
            </div>
            <div class="flex flex-col items-center gap-[8px]">
              <p class="font-36 font-bold text-white">20+</p>
              <p class="font-14 font-normal text-grey">Companies</p>
            </div>
          </div>
        </div>
        <div class="hidden xl:flex">
          <img src="/img/hero2.png" alt="" />
        </div>
      </div>
    </section>

    <!-- About -->
    <section class="section bg-white">
      <div class="div flex-col gap-[24px] xl:grid xl:grid-cols-2 xl:gap-[80px]">
        <div>
          <img src="/img/video.png" alt="" />
        </div>
        <div class="flex flex-col gap-[16px]">
          <img src="/img/bluebar.png" alt="" class="w-fit" />
          <p class="font-28 font-bold">About Boutique Office</p>
          <p class="font-16">
            Located in APL Office Tower, grade A office tower in a strategic
            area in West Jakarta, we offer virtual office rental and premium
            service office spaces that are well maintained by our building
            management team. Rent one of these serviced offices in the heart of
            western Jakarta at competitive rates that will ultimately give you a
            competitive edge without huge upfront capital risk. With us, you can
            focus on your business while we take care of all the services to
            increase your business profit.
          </p>
          <a href="/" class="btn-green mt-[16px] w-full xl:w-fit"
            ><img src="/img/wa.png" alt="" />WhatsApp Us</a
          >
        </div>
      </div>
    </section>

    <!-- Logo -->
    <section class="section bg-white">
      <div
        class="div grid grid-cols-3 items-center justify-center justify-items-center gap-[32px] text-center grayscale xl:grid-cols-5"
      >
        <img src="/img/logo1.png" alt="" />
        <img src="/img/logo2.png" alt="" />
        <img src="/img/logo3.png" alt="" />
        <img src="/img/logo4.png" alt="" />
        <img src="/img/logo5.png" alt="" />
      </div>
    </section>

    <!-- Space & Solution -->
    <section class="section bg-white">
      <div class="div flex-col gap-[24px]">
        <div
          class="flex flex-col gap-[8px] xl:grid xl:grid-cols-2 xl:gap-[80px]"
        >
          <p class="font-28 font-bold xl:text-[56px]">
            Our <span class="text-blue">Space & Solution</span>
          </p>
          <p class="font-16 font-medium">
            Boutique Office doesn't just provide exceptional serviced office
            workspaces in Jakarta; we offer a complete suite of business
            solutions designed to streamline your operations.
          </p>
        </div>
        <div
          class="flex flex-col gap-[24px] xl:grid xl:grid-cols-2 xl:gap-[40px]"
        >
          <div class="xl:flex xl:flex-row">
            <img
              src="/img/solution1.png"
              alt=""
              class="w-full xl:max-w-[260px]"
            />
            <div
              class="flex flex-col gap-[8px] bg-light-grey p-[20px] xl:justify-center"
            >
              <p class="font-20 font-bold">Virtual Office</p>
              <p class="font-12 xl:font-14">
                A prestigious virtual office offering business address rental
                with professional administrative and communication support.
              </p>
              <a href="/" class="btn-green mt-[8px] w-full">
                <img src="/img/wa.png" alt="" />WhatsApp Us</a
              >
            </div>
          </div>
          <div class="xl:flex xl:flex-row">
            <img
              src="/img/solution2.png"
              alt=""
              class="w-full xl:max-w-[260px]"
            />
            <div
              class="flex flex-col gap-[8px] bg-light-grey p-[20px] xl:justify-center"
            >
              <p class="font-20 font-bold">Serviced Office</p>
              <p class="font-12 xl:font-14">
                A flexible full service private office in Jakarta with
                high-speed internet, inclusive utility, & support for networking
                events.
              </p>
              <a href="/" class="btn-green mt-[8px] w-full">
                <img src="/img/wa.png" alt="" />WhatsApp Us</a
              >
            </div>
          </div>
          <div class="xl:flex xl:flex-row">
            <img
              src="/img/solution3.png"
              alt=""
              class="w-full xl:max-w-[260px]"
            />
            <div
              class="flex flex-col gap-[8px] bg-light-grey p-[20px] xl:justify-center"
            >
              <p class="font-20 font-bold">Meeting Room</p>
              <p class="font-12 xl:font-14">
                Daily/hourly meeting room in Jakarta for up to 10 people with
                high-speed internet, whiteboard, projector, & unlimited
                coffee/tea.
              </p>
              <a href="/" class="btn-green mt-[8px] w-full">
                <img src="/img/wa.png" alt="" />WhatsApp Us</a
              >
            </div>
          </div>
          <div class="xl:flex xl:flex-row">
            <img
              src="/img/solution4.png"
              alt=""
              class="w-full xl:max-w-[260px]"
            />
            <div
              class="flex flex-col gap-[8px] bg-light-grey p-[20px] xl:justify-center"
            >
              <p class="font-20 font-bold">Business Solution</p>
              <p class="font-12 xl:font-14">
                Dedicated experts to help you meet business needs such as legal,
                accounting, HR, training, certification, and more.
              </p>
              <a href="/" class="btn-green mt-[8px] w-full">
                <img src="/img/wa.png" alt="" />WhatsApp Us</a
              >
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Amenities -->
    <section class="section bg-white">
      <div class="div flex-col gap-[24px] xl:gap-[40px]">
        <div
          class="flex flex-col gap-[16px] bg-blue px-[16px] py-[24px] xl:flex-row xl:items-center xl:justify-end"
        >
          <img src="/img/whitebar.png" alt="" class="w-fit" />
          <p class="font-28 font-bold text-white">
            No worries, we have complete amenities
          </p>
        </div>
        <div class="grid grid-cols-2 gap-[20px] xl:grid-cols-4 xl:gap-[40px]">
          <div class="flex flex-col gap-[16px] bg-light-grey p-[20px]">
            <img src="/img/amenities1.png" alt="" class="w-fit" />
            <p class="font-16 font-bold">High-Speed Wifi</p>
          </div>
          <div class="flex flex-col gap-[16px] bg-light-grey p-[20px]">
            <img src="/img/amenities2.png" alt="" class="w-fit" />
            <p class="font-16 font-bold">Free Drinks</p>
          </div>
          <div class="flex flex-col gap-[16px] bg-light-grey p-[20px]">
            <img src="/img/amenities3.png" alt="" class="w-fit" />
            <p class="font-16 font-bold">HD Projectors</p>
          </div>
          <div class="flex flex-col gap-[16px] bg-light-grey p-[20px]">
            <img src="/img/amenities4.png" alt="" class="w-fit" />
            <p class="font-16 font-bold">Printing</p>
          </div>
          <div class="flex flex-col gap-[16px] bg-light-grey p-[20px]">
            <img src="/img/amenities5.png" alt="" class="w-fit" />
            <p class="font-16 font-bold">Lounge Area</p>
          </div>
          <div class="flex flex-col gap-[16px] bg-light-grey p-[20px]">
            <img src="/img/amenities6.png" alt="" class="w-fit" />
            <p class="font-16 font-bold">Air Conditioning</p>
          </div>
          <div class="flex flex-col gap-[16px] bg-light-grey p-[20px]">
            <img src="/img/amenities7.png" alt="" class="w-fit" />
            <p class="font-16 font-bold">Event Space for Rent</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Facilities -->
    <section class="section bg-white">
      <div class="div flex-col gap-[24px] xl:gap-[40px]">
        <div
          class="flex flex-col gap-[16px] bg-blue px-[16px] py-[24px] xl:flex-row xl:items-center xl:justify-start"
        >
          <img src="/img/whitebar.png" alt="" class="w-fit xl:order-1" />
          <p class="font-28 font-bold text-white">
            Surrounded by many facilities
          </p>
        </div>
        <!--  -->
        <div
          class="flex flex-col gap-[24px] xl:grid xl:grid-cols-2 xl:gap-[40px]"
        >
          <div class="flex flex-col gap-[16px]">
            <card
              class="flex flex-row items-start gap-[16px] bg-light-grey p-[20px]"
            >
              <img src="/img/facilities1.png" alt="" class="w-fit" />
              <div>
                <p class="font-16 mb-[8px] font-bold">Airport</p>
                <p class="font-12 xl:font-14">
                  20 min. from the Soekarno Hatta Airport (10 km)
                </p>
              </div>
            </card>
            <card
              class="flex flex-row items-start gap-[16px] bg-light-grey p-[20px]"
            >
              <img src="/img/facilities2.png" alt="" class="w-fit" />
              <div>
                <p class="font-16 mb-[8px] font-bold">Business District</p>
                <p class="font-12 xl:font-14">
                  20 min. from Sudirman & SCBD (8.7 km)
                </p>
              </div>
            </card>
            <card
              class="flex flex-row items-start gap-[16px] bg-light-grey p-[20px]"
            >
              <img src="/img/facilities3.png" alt="" class="w-fit" />
              <div>
                <p class="font-16 mb-[8px] font-bold">Hotel & Apartment</p>
                <p class="font-12 xl:font-14">
                  Next to Pullman Hotel Central Park (1.1 km) <br />Surrounded
                  by residential apartments towers
                </p>
              </div>
            </card>
            <card
              class="flex flex-row items-start gap-[16px] bg-light-grey p-[20px]"
            >
              <img src="/img/facilities4.png" alt="" class="w-fit" />
              <div>
                <p class="font-16 mb-[8px] font-bold">Mall</p>
                <p class="font-12 xl:font-14">
                  Connected to Central Park Mall & Soho Mall
                </p>
              </div>
            </card>
            <card
              class="flex flex-row items-start gap-[16px] bg-light-grey p-[20px]"
            >
              <img src="/img/facilities5.png" alt="" class="w-fit" />
              <div>
                <p class="font-16 mb-[8px] font-bold">Resto</p>
                <p class="font-12 xl:font-14">
                  Tribeca Outdoor Dining & Lifestyle (800 m)
                </p>
              </div>
            </card>
          </div>
          <div>
            <img src="/img/maps.png" alt="" class="w-full" />
          </div>
        </div>
        <!--  -->
      </div>
    </section>

    <!-- Our Gallery -->
    <section class="section">
      <div class="div flex-col gap-[24px] text-center xl:text-left">
        <p class="font-28 font-bold">
          Our <span class="text-blue">Gallery</span>
        </p>
        <img src="/img/gallery1.png" alt="" class="xl:hidden" />
        <img src="/img/gallery2.png" alt="" class="hidden xl:block" />
      </div>
    </section>

    <!-- Testimonial -->
    <section class="section">
      <div class="div flex-col gap-[24px]">
        <p class="font-28 font-bold xl:text-[36px]">
          What Our Customers Say About
          <span class="text-blue">Boutique Office</span>
        </p>
        <div class="flex flex-col gap-[24px] xl:grid xl:grid-cols-2">
          <card class="flex flex-col gap-[16px] bg-light-grey p-[16px]">
            <div class="flex items-center justify-between">
              <img src="/img/avatar1.png" alt="" class="w-[80px]" />
              <img src="/img/semicolon.png" alt="" class="w-[32px]" />
            </div>
            <div>
              <p class="font-16 font-bold xl:mb-[8px] xl:text-[28px]">
                Sarah Miguela
              </p>
              <p class="font-14 font-medium text-[#414346] xl:text-[20px]">
                Business Development Manager at Xbox
              </p>
            </div>
            <p class="font-14 xl:text-[16px]">
              “Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
              eleifend purus justo, ac blandit justo feugiat vel. Mauris tempus
              pretium ligula, pharetra varius elit hendrerit in. Cras blandit
              libero non pellentesque commodo. Aliquam dolor nibh, posuere vitae
              fringilla et”
            </p>
          </card>
          <card class="flex flex-col gap-[16px] bg-light-grey p-[16px]">
            <div class="flex items-center justify-between">
              <img src="/img/avatar2.png" alt="" class="w-[80px]" />
              <img src="/img/semicolon.png" alt="" class="w-[32px]" />
            </div>
            <div>
              <p class="font-16 font-bold xl:mb-[8px] xl:text-[28px]">
                Mason Wilkes
              </p>
              <p class="font-14 font-medium text-[#414346] xl:text-[20px]">
                Graphic Designer at Gojek
              </p>
            </div>
            <p class="font-14 xl:text-[16px]">
              “Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec
              eleifend purus justo, ac blandit justo feugiat vel. Mauris tempus
              pretium ligula, pharetra varius elit hendrerit in. Cras blandit
              libero non pellentesque commodo. Aliquam dolor nibh, posuere vitae
              fringilla et”
            </p>
          </card>
        </div>
      </div>
    </section>

    <!-- Form -->
    <section class="section">
      <div
        class="div flex-col gap-[24px] xl:flex-row xl:items-start xl:gap-[44px]"
      >
        <img src="/img/form.png" alt="" />
        <div class="flex flex-col gap-[16px]">
          <p class="font-28 font-bold xl:text-[28px]">
            We Can Help You Find Ideal Workspace
          </p>
          <p class="font-16 font-medium text-[#717375] xl:text-[14px]">
            Looking for the perfect workspace can be a hassle. Let us take care
            of the search and find the ideal workspace that suits your needs.
          </p>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section class="section">
      <div class="div flex-col gap-[34px]">
        <div>
          <img src="/img/bluebar.png" alt="" class="mb-[34px]" />
          <p class="font-28 font-bold">What do you want to know?</p>
        </div>
        <div class="flex flex-col gap-[24px]">
          <faq
            class="xl:pb-[30px]mb-[30px] mb-[16px] flex flex-col gap-[16px] border-b-2 border-grey pb-[16px] xl:gap-[40px]"
          >
            <p class="font-16 font-bold">
              What will I get by paying for a serviced office?
            </p>
            <p class="font-14 text-[#292929]">
              The rent includes furniture, utilities, and basic services. Not
              only that, but we also include telephone extension, high-speed
              internet, utilities, basement car parking and 2 hours of free
              meeting room use per month in our serviced office at Jakarta.
              Additional hours are discounted. You only pay extra for outgoing
              calls, meeting room hire, and additional services like
              photocopying or secretarial work.
            </p> </faq
          ><faq
            class="xl:pb-[30px]mb-[30px] mb-[16px] flex flex-col gap-[16px] border-b-2 border-grey pb-[16px] xl:gap-[40px]"
          >
            <p class="font-16 font-bold">
              Can I receive incoming mail in my company’s name, even if I am not
              in Jakarta?
            </p>
            <p class="font-14 text-[#292929]"></p> </faq
          ><faq
            class="xl:pb-[30px]mb-[30px] mb-[16px] flex flex-col gap-[16px] border-b-2 border-grey pb-[16px] xl:gap-[40px]"
          >
            <p class="font-16 font-bold">
              Why should I get a serviced office rather than a regular one?
            </p>
            <p class="font-14 text-[#292929]"></p>
          </faq>
          <faq
            class="xl:pb-[30px]mb-[30px] mb-[16px] flex flex-col gap-[16px] border-b-2 border-grey pb-[16px] xl:gap-[40px]"
          >
            <p class="font-16 font-bold">
              How long does it take to set up the vitual office service?
            </p>
            <p class="font-14 text-[#292929]"></p>
          </faq>
          <faq
            class="xl:pb-[30px]mb-[30px] mb-[16px] flex flex-col gap-[16px] border-b-2 border-grey pb-[16px] xl:gap-[40px]"
          >
            <p class="font-16 font-bold">
              How easy is it to grow my business in a serviced office?
            </p>
            <p class="font-14 text-[#292929]"></p>
          </faq>
          <faq
            class="xl:pb-[30px]mb-[30px] mb-[16px] flex flex-col gap-[16px] border-b-2 border-grey pb-[16px] xl:gap-[40px]"
          >
            <p class="font-16 font-bold">
              How long is the minimum lease term for renting Boutique Office
              virtual office?
            </p>
            <p class="font-14 text-[#292929]"></p>
          </faq>
          <faq
            class="xl:pb-[30px]mb-[30px] mb-[16px] flex flex-col gap-[16px] border-b-2 border-grey pb-[16px] xl:gap-[40px]"
          >
            <p class="font-16 font-bold">How long before I can move in?</p>
            <p class="font-14 text-[#292929]"></p>
          </faq>
          <faq
            class="xl:pb-[30px]mb-[30px] mb-[16px] flex flex-col gap-[16px] border-b-2 border-grey pb-[16px] xl:gap-[40px]"
          >
            <p class="font-16 font-bold">
              How can Boutique Office assist me in expanding my business into
              Indonesia?
            </p>
            <p class="font-14 text-[#292929]"></p>
          </faq>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <section class="section bg-black">
      <div class="div flex-col gap-[56px]">
        <div class="flex flex-col items-start gap-[24px]">
          <img src="/img/logo.png" alt="" />
          <p class="font-16 max-w-[400px] text-white">
            Podomoro City, APL Tower, Jl. Letjen S. Parman No.Kav 28 T9,
            RT.3/RW.5, Tj. Duren Sel., Kec. Grogol petamburan, Kota Jakarta
            Barat, Daerah Khusus Ibukota Jakarta 11470
          </p>
          <a href="/" class="flex gap-[8px]">
            <img src="/img/wa2.png" alt="" />
            <p class="font-16 font-semibold text-white underline">
              +62 819 0888 0008
            </p>
          </a>
        </div>
        <p class="font-14 text-[14px] text-white">
          Boutique Office @2024. All rights reserved.
        </p>
      </div>
    </section>
    </main>
</template>
<script>
    import HeroMobile from './assets/hero-mobile.png'
    import HeroDesktop from './assets/hero-desktop.png'
    import Content from './assets/Contents.png'
</script>

<main>
<!--Hero Section-->
    <div class="bg-[#3D3D52]">
<!--Navbar-->
        <div class="h-18 md:h-20 bg-red">

        </div>

        <div class="pt-16 md:pt-[96px] flex flex-col md:flex-row">
            <div>
                <p class="text-sm md:text-base text-[#EAECF0] font-semibold">
                    Simple. Seamless. Experience.
                </p>

                <p class="block md:hidden text-white text-4xl">
                    The future of shopping experience
                </p>
                <p class="hidden md:block text-white text-7xl">
                    Empowering Live Ecommerce Experiences!
                </p>
            </div>
            <div class="relative">
                <div class="block md:hidden">
                    <img src={HeroMobile} />
                </div>
                <div class="hidden md:block ">
                    <img src={HeroDesktop} />
                </div>

            </div>

        </div>



    </div>


    <div class="p-[96px]">
        <div class="flex flex-col space-y-[64px] md:space-x-[64px] md:flex-row">
           <div class="flex-1">
               <img src={Content} class="md:h-[496px]"/>
           </div>
            <div class="flex-1 flex-col flex items-center justify-center">
                <p class="text-5xl font-semibold  text-[#101828]">
                    Revolutionise your shopping experience with blesket.
                </p>
            </div>
        </div>

    </div>

    <div class="md:mt-[96px] md:mb-[64px] my-5 md:px-[94px] px-5">
<div class="px-8">
<div class="flex flex-col">
<p class="text-[#284D19] text-base font-semibold pb-3">
Our Mission
</p>
    <p class="text-[#101828] font-semibold text-4xl pb-5 ">
        Providing a seamless shopping experience.
    </p>
    <p class="text-[#475467] text-lg font-semibold">
        Offering a unique, simple, and seamless shopping experience.
    </p>
</div>
</div>
    </div>


</main>

<style>

</style>

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


</main>

<style>

</style>

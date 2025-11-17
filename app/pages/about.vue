<template>
    <div class="bg-[#e7a98b] py-4 mb-0">
        <div class="max-w-7xl mx-auto px-4 md:px-8 sm:px-6">
            <div class="w-full flex items-end justify-start pb-2 md:pb-4 min-h-[80px] md:min-h-[150px]" aria-label="Breadcrumb">
                <ol class="flex items-center space-x-2 md:space-3  w-full -mb-3 md:-mb-5 overflow-x-auto scrollbar-hidden ">
                    <li class="flex-shrink-0">
                        <a href="/" aria-label="home" class="flex items-center text-white text-lg md:text-2xl font-bold hover:text-white duration-200 hover:scale-105">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-house mr-1 md:mr-2 text-white font-bold md:w-6 md:h-6" aria-hidden="true"><path d="M15 21v-8a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1v8"></path><path d="M3 10a2 2 0 0 1 .709-1.528l7-5.999a2 2 0 0 1 2.582 0l7 5.999A2 2 0 0 1 21 10v9a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path></svg>
                            <span class="hidden sm:inline">Home</span>
                        </a>
                    </li>
                    <li class="flex-shrink-0"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-chevron-right text-white text-lg md:text-2xl font-bold mx-1 md:w-6 md:h-6" aria-hidden="true"><path d="m9 18 6-6-6-6"></path></svg></li>
                    <li class="flex-shrink-0">
                        <div class="flex items-center text-white text-lg md:text-2xl font-bold tracking-wide whitespace-nowrap">About Us</div>
                    </li>
                </ol>
            </div>
        </div>
    </div>
    <div class="px-4 sm:px-6 md:px-20 py-14 sm:py-20 bg-white flex flex-col md:flex-row gap-10 items-start">
        <div class="relative w-1/2 w-full">
            <img src="/images/exercise.jpg" alt="" class="rounded-xl max-h-[400px] w-full object-cover h-auto sm:max-h-full">
            <div class="absolute -bottom-8 left-4 sm:left-6 bg-[#e7a98b] text-white p-6 sm:p-12 shadow-lg text-center w-44 sm:w-56"><h4 class="text-3xl sm:text-4xl font-extrabold">5+</h4><p class="text-xs sm:text-sm font-medium mt-1">Years of Experience</p></div>
        </div>
        <div class="relative w-1/2 w-full">
            <h1 class="text-2xl md:text-4xl font-extrabold mb-4 text-black">About Us</h1>
            <p class="text-gray-700 leading-relaxed mb-8 sm:mb-10 text-base sm:text-xl">At Skill Bridge Training Center, we prepare individuals for professional caregiving careers in Japan with training in Japanese language, culture, and healthcare skills. Our expert-led program equips students with compassion, confidence, and global opportunities to build meaningful careers in Japan’s healthcare sector.</p>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-y-4 sm:gap-y-6 gap-x-6 sm:gap-x-10">
                <div class="flex items-center gap-3 sm:gap-4">
                    <div class="bg-[#e7a98b] p-2 rounded-md">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-heart text-white" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"></path></svg>
                    </div>
                    <p class="text-gray-700 text-base sm:text-xl font-medium">Residential Caring</p>
                </div>
                <div class="flex items-center gap-3 sm:gap-4">
                    <div class="bg-[#e7a98b] p-2 rounded-md">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-heart text-white" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"></path></svg>
                    </div>
                    <p class="text-gray-700 text-base sm:text-xl font-medium">Caregiver Training</p>
                </div>
                <div class="flex items-center gap-3 sm:gap-4">
                    <div class="bg-[#e7a98b] p-2 rounded-md">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-heart text-white" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"></path></svg>
                    </div>
                    <p class="text-gray-700 text-base sm:text-xl font-medium">Career Counseling</p>
                </div>
                <div class="flex items-center gap-3 sm:gap-4">
                    <div class="bg-[#e7a98b] p-2 rounded-md">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-heart text-white" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"></path></svg>
                    </div>
                    <p class="text-gray-700 text-base sm:text-xl font-medium">Pre-Departure and Cultural Orientation</p>
                </div>
                <div class="flex items-center gap-3 sm:gap-4">
                    <div class="bg-[#e7a98b] p-2 rounded-md">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-heart text-white" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"></path></svg>
                    </div>
                    <p class="text-gray-700 text-base sm:text-xl font-medium">Job Placement Assistance</p>
                </div>
                <div class="flex items-center gap-3 sm:gap-4">
                    <div class="bg-[#e7a98b] p-2 rounded-md">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-heart text-white" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"></path></svg>
                    </div>
                    <p class="text-gray-700 text-base sm:text-xl font-medium">Test Preparation</p>
                </div>
                <div class="flex items-center gap-3 sm:gap-4">
                    <div class="bg-[#e7a98b] p-2 rounded-md">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-heart text-white" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"></path></svg>
                    </div>
                    <p class="text-gray-700 text-base sm:text-xl font-medium">Certification</p>
                </div>
                <div class="flex items-center gap-3 sm:gap-4">
                    <div class="bg-[#e7a98b] p-2 rounded-md">
                        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-heart text-white" aria-hidden="true"><path d="M19 14c1.49-1.46 3-3.21 3-5.5A5.5 5.5 0 0 0 16.5 3c-1.76 0-3 .5-4.5 2-1.5-1.5-2.74-2-4.5-2A5.5 5.5 0 0 0 2 8.5c0 2.3 1.5 4.05 3 5.5l7 7Z"></path></svg>
                    </div>
                    <p class="text-gray-700 text-base sm:text-xl font-medium">Corporate and Customized Training</p>
                </div>
            </div>
        </div>
    </div>
    <div class="relative w-full h-[700px] overflow-visible mt-20">
        <img src="/images/care.jpg" class="absolute inset-0 z-0 w-full h-full object-cover" alt="">
        <div class="absolute inset-0 bg-[#429dae]/70 z-10"></div>
        <div class="top-[-120px] absolute left-1/2 transform -translate-x-1/2 w-[380px] h-[280px] sm:w-[440px] sm:h-[320px] rounded-xl shadow-2xl bg-white overflow-hidden border-white border-2 z-20">
            <img src="/images/doctors.jpg" alt="" class=" w-full h-full inset-0 object-cover">
        </div>
        <div class="grid grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-6 lg:gap-8 px-4 px-4 sm:px-8 relative text-center text-white max-w-7xl pt-52 sm:mt-48 mx-auto z-10 md:pt-56">
            <div class="group cursor-pointer" style="perspective: 1000px;">
                <div class="relative w-full h-44 sm:h-48 transition-transform duration-700 [transform:rotateY(0deg)]" style="transform-style: preserve-3d;">
                    <div class="absolute inset-0 bg-white rounded-lg shadow-lg hover:shadow-xl p-4 sm:p-6 flex flex-col items-center justify-center transition-shadow duration-300 [backface-visibility:hidden]">
                        <h2 class="text-3xl sm:text-4xl md:text-5xl lg:text-6xl font-extrabold text-[#e7a98b] mb-2">
                            5+
                        </h2>
                        <p class="text-sm sm:text-base lg:text-lg font-semibold text-gray-800 text-center leading-tight">Years Of Experience</p>
                    </div>
                    <div class="absolute inset-0 bg-[#e7a98b] rounded-lg shadow-lg p-4 sm:p-6 text-white text-sm sm:text-base lg:text-lg font-semibold flex items-center justify-center text-center [backface-visibility:hidden] [transform:rotateY(180deg)]" >
                        <p class="leading-relaxed">Thats Incredible! We are moved more than 4280 homes to another destination</p>
                    </div>
                </div>
            </div>
            <div class="group cursor-pointer" style="perspective: 1000px;">
                <div class="relative w-full h-44 sm:h-48 transition-transform duration-700 [transform:rotateY(0deg)]" style="transform-style: preserve-3d;">
                    <div class="absolute inset-0 bg-white rounded-lg shadow-lg hover:shadow-xl p-4 sm:p-6 flex flex-col justify-center itmes-center transition-shadow duration-300 [backface-visibility:hidden]">
                        <h2 class="text-3xl sm:text-4xl md:text-5xl lg:text-6xl font-extrabold text-[#e7a98b] mb-2">1K</h2>
                        <p class="text-sm sm:text-base lg:text-lg font-semibold text-gray-800 text-center leading-tight">Happy Families</p>  
                    </div>
                    <div class="absolute bg-[#e7a98b] inset-0 rounded-lg shadow-lg hover:shadow-2xl text-white flex items-center justify-center text-center p-4 sm:p-6 text-sm sm:text-base lg:text-lg font-semibold [backface-visibility:hidden] [transform:rotateY(180deg)]">
                        <p class="leading-relaxed">Thats Incredible! We are moved more than 4280 homes to another destination</p>
                    </div>
                </div>
            </div>
            <div class="group cursor-pointer" style="perspective: 1000px;">
                <div class="relative w-full h-44 sm:h-48 transition-transform duration-700 [transform:rotateY(0deg)]" style="transform-style: preserve-3d;">
                    <div class="absolute bg-white inset-0 ronded-lg shadow-lg hover:shadow-xl flex flex-col items-center justify-center p-4 sm:p-6 transition-shadow [backface-visiblity:hidden]">
                        <h2 class="text-3xl text-[#e7a98b] sm:text-4xl md:text-5xl lg:text-6xl font-extrabold mb-2">
                            5+
                        </h2>
                        <p class="text-sm sm:text-base lg:text-lg text-gray-700 font-semibold text-center leading-tight">Awards Wining</p>
                    </div>
                    <div class="absolute inset-0 bg-[#e7a98b] rounded-lg shadow-lg p-4 sm:p-6 text-white text-sm sm:text-base lg:text-lg font-semibold flex items-center justify-center text-center [backface-visibility:hidden] [transform:rotateY(180deg)]"><p class="leading-relaxed">Thats Incredible! We are moved more than 4280 homes to another destination</p></div>
                </div>
            </div>
            
        </div>
    </div>
    <div class="py-8 px-5 bg-white flex items-center justify-center">
        <div class="max-w-4xl mx-auto text-center">
            <div class="mb-10"><svg class="w-20 h-20 text-[#e7a98b] mx-auto transition-transform duration-300 hover:scale-110" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M12 2C10.9 2 10 2.9 10 4C10 5.1 10.9 6 12 6C13.1 6 14 5.1 14 4C14 2.9 13.1 2 12 2Z" fill="currentColor"></path><path d="M8 8C6.9 8 6 8.9 6 10C6 11.1 6.9 12 8 12C9.1 12 10 11.1 10 10C10 8.9 9.1 8 8 8Z" fill="currentColor"></path><path d="M16 8C14.9 8 14 8.9 14 10C14 11.1 14.9 12 16 12C17.1 12 18 11.1 18 10C18 8.9 17.1 8 16 8Z" fill="currentColor"></path><path d="M12 14C10.3 14 8.9 15.4 8.9 17.1V22H15.1V17.1C15.1 15.4 13.7 14 12 14Z" fill="currentColor"></path><path d="M4 16C2.9 16 2 16.9 2 18V22H6V18C6 16.9 5.1 16 4 16Z" fill="currentColor"></path><path d="M20 16C18.9 16 18 16.9 18 18V22H22V18C22 16.9 21.1 16 20 16Z" fill="currentColor"></path></svg></div>
             <h2 class="text-gray-800 text-5xl md:text-6xl leading-tight font-light mb-8">We are expert
                <br class="block md:hidden">
                <span class="text-[#e7a98b]"> elderly care in this </span>
                <br class="block md:hidden">
                town</h2>
            <p class="text-gray-600 max-w-lg text-lg leading-relaxed mx-auto mb-12 px-2">Our mission is to provide the best service to your family, care and match for you and your family.</p>
            <button class="inline-flex items-center gap-3 bg-[#e7a98b] hover:bg-[#d0977a] text-white px-9 py-5 rounded-lg text-lg font-semibold transition-all duration-300 transform hover:-translate-y-1 shadow-lg hover:shadow-xl focus:outline-none focus:ring-4 focus:ring-orange-300 focus:ring-opacity-50" aria-label="Call us at +977-9851403517"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-phone flex-shrink-0" aria-hidden="true"><path d="M13.832 16.568a1 1 0 0 0 1.213-.303l.355-.465A2 2 0 0 1 17 15h3a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2A18 18 0 0 1 2 4a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v3a2 2 0 0 1-.8 1.6l-.468.351a1 1 0 0 0-.292 1.233 14 14 0 0 0 6.392 6.384"></path></svg>Chat on WhatsApp +977-9851403517</button>
        </div>
    </div>
    <section class="jsx-26af37836fe4aa27 relative w-full bg-white"><div class="jsx-26af37836fe4aa27 relative w-full h-[400px] sm:h-[450px] md:h-[500px] bg-gradient-to-br from-gray-800 via-gray-700 to-gray-900 overflow-hidden"><div class="jsx-26af37836fe4aa27 absolute inset-0 opacity-40"><img alt="Medical background" class="jsx-26af37836fe4aa27 w-full h-full object-cover" src="https://api.sbitraining.com/media/service_images/serviceone.jpeg"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 33.0317%; top: 11.1244%; width: 4.34442px; height: 4.34442px; animation-delay: 3.07424s; animation-duration: 13.1958s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 90.246%; top: 22.42%; width: 8.97981px; height: 8.97981px; animation-delay: 1.07279s; animation-duration: 13.3678s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 63.4042%; top: 9.8328%; width: 8.58883px; height: 8.58883px; animation-delay: 5.31474s; animation-duration: 10.2134s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 36.7712%; top: 11.3556%; width: 6.60151px; height: 6.60151px; animation-delay: 5.97648s; animation-duration: 13.8042s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 37.1969%; top: 37.4598%; width: 3.34727px; height: 3.34727px; animation-delay: 1.71694s; animation-duration: 13.0417s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 43.0674%; top: 5.57531%; width: 8.95269px; height: 8.95269px; animation-delay: 5.38428s; animation-duration: 12.9113s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 68.587%; top: 59.4516%; width: 4.01781px; height: 4.01781px; animation-delay: 6.3538s; animation-duration: 8.76143s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 97.293%; top: 44.4372%; width: 6.95002px; height: 6.95002px; animation-delay: 1.31563s; animation-duration: 13.1882s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 20.3928%; top: 51.039%; width: 8.67844px; height: 8.67844px; animation-delay: 7.48837s; animation-duration: 9.7886s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 87.3134%; top: 58.6107%; width: 7.87751px; height: 7.87751px; animation-delay: 1.09861s; animation-duration: 11.3372s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 70.1727%; top: 13.8136%; width: 6.24929px; height: 6.24929px; animation-delay: 2.71421s; animation-duration: 12.1716s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 44.3478%; top: 55.0363%; width: 6.02804px; height: 6.02804px; animation-delay: 6.04814s; animation-duration: 11.0958s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 61.1719%; top: 19.0804%; width: 7.1862px; height: 7.1862px; animation-delay: 7.83066s; animation-duration: 13.4202s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 98.9171%; top: 37.6729%; width: 6.2258px; height: 6.2258px; animation-delay: 6.86723s; animation-duration: 10.8732s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 29.7134%; top: 34.9757%; width: 3.98702px; height: 3.98702px; animation-delay: 7.01329s; animation-duration: 13.6949s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 47.0458%; top: 13.03%; width: 7.45411px; height: 7.45411px; animation-delay: 2.73707s; animation-duration: 11.0818s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 19.1501%; top: 36.8873%; width: 4.29996px; height: 4.29996px; animation-delay: 7.62212s; animation-duration: 8.23784s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 38.4369%; top: 48.518%; width: 8.34942px; height: 8.34942px; animation-delay: 4.68495s; animation-duration: 12.5059s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 6.97996%; top: 25.2915%; width: 7.01354px; height: 7.01354px; animation-delay: 2.38911s; animation-duration: 8.16131s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 5.75964%; top: 35.8817%; width: 8.23481px; height: 8.23481px; animation-delay: 0.268921s; animation-duration: 11.2239s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 20.9857%; top: 38.2089%; width: 3.91509px; height: 3.91509px; animation-delay: 5.47449s; animation-duration: 8.44886s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 6.22182%; top: 36.1095%; width: 6.46677px; height: 6.46677px; animation-delay: 6.88451s; animation-duration: 11.7844s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 26.9712%; top: 45.7331%; width: 8.26251px; height: 8.26251px; animation-delay: 3.44763s; animation-duration: 8.67257s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 4.18419%; top: 34.0585%; width: 8.55142px; height: 8.55142px; animation-delay: 1.24775s; animation-duration: 12.5166s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 33.6577%; top: 35.4468%; width: 5.23633px; height: 5.23633px; animation-delay: 3.02527s; animation-duration: 11.4396s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 30.1361%; top: 53.7191%; width: 8.30656px; height: 8.30656px; animation-delay: 7.54625s; animation-duration: 11.8156s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 36.662%; top: 33.1505%; width: 7.40008px; height: 7.40008px; animation-delay: 0.578144s; animation-duration: 8.54961s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 9.8572%; top: 37.7495%; width: 8.48583px; height: 8.48583px; animation-delay: 1.54271s; animation-duration: 10.1142s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 32.1732%; top: 58.6091%; width: 3.12188px; height: 3.12188px; animation-delay: 6.93497s; animation-duration: 11.8854s;"></div><div class="jsx-26af37836fe4aa27 absolute rounded-full bg-white opacity-25 animate-pulse" style="left: 75.9336%; top: 2.24304%; width: 8.14806px; height: 8.14806px; animation-delay: 0.380691s; animation-duration: 10.8792s;"></div><div class="jsx-26af37836fe4aa27 relative z-10 flex flex-col items-center justify-center h-full px-4 sm:px-6 lg:px-8 pt-12"><h1 class="jsx-26af37836fe4aa27 text-3xl sm:text-4xl lg:text-5xl xl:text-6xl font-bold text-white mb-4 sm:mb-6 leading-tight text-center max-w-4xl">Language &amp; Caregiver Training</h1><p class="jsx-26af37836fe4aa27 text-base sm:text-lg lg:text-xl text-gray-200 max-w-2xl mx-auto leading-relaxed text-center">We provide Japanese language training focused on everyday communication, healthcare terms, and cultural etiquette, helping caregivers work and adapt confidently in Japan.</p></div><div class="jsx-26af37836fe4aa27 absolute bottom-0 left-0 w-full h-24 sm:h-32"><svg viewBox="0 0 1200 120" preserveAspectRatio="none" class="jsx-26af37836fe4aa27 absolute top-0 w-full h-full"><path d="M0,0 C300,120 900,120 1200,0 L1200,120 L0,120 Z" fill="white" class="jsx-26af37836fe4aa27"></path></svg></div><div class="jsx-26af37836fe4aa27 absolute top-20 left-10 w-16 h-16 border-2 border-white/20 rounded-full animate-spin-slow hidden lg:block"></div><div class="jsx-26af37836fe4aa27 absolute top-32 right-16 w-12 h-12 border-2 border-white/20 rounded-full animate-bounce hidden lg:block"></div><div class="jsx-26af37836fe4aa27 absolute top-24 right-32 w-1 h-16 bg-white/15 rotate-45 hidden lg:block"></div><div class="jsx-26af37836fe4aa27 absolute top-40 left-32 w-1 h-12 bg-white/15 -rotate-45 hidden lg:block"></div></div><div class="jsx-26af37836fe4aa27 relative -mt-16 sm:-mt-20 md:-mt-24 px-4 sm:px-6 lg:px-8 pb-16 sm:pb-20 lg:pb-24"><div class="jsx-26af37836fe4aa27 max-w-7xl mx-auto"><div class="jsx-26af37836fe4aa27 grid grid-cols-2 md:grid-cols-3 gap-4 sm:gap-6 lg:gap-8"></div></div></div></section>
</template>
<style>
/* rotate the inner card on group hover */
.group:hover .relative {
  transform: rotateY(180deg);
}
</style>
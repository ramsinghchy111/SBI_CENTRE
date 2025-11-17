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
</template>
<style>
/* rotate the inner card on group hover */
.group:hover .relative {
  transform: rotateY(180deg);
}
</style>

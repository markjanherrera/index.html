<!DOCTYPE html>
0<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invited! Birthday</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&family=Pacifico&display=swap');        
        body {
            font-family: 'Inter', sans-serif;
            background-color: #000000;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 2rem 0;
        }
        .title-font {
            font-family: 'Pacifico', cursive;
        }
        .map-container {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
            border-radius: 0.75rem;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        .map-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
        }
    </style>
</head>
<body>

<div class="max-w-4xl w-full mx-auto p-4 sm:p-10 bg-white rounded-3xl shadow-2xl transition-all duration-300 transform hover:shadow-blue-300">
    <header class="text-center mb-10">
        <p class="text-2xl sm:text-3xl font-light text-black-500 mb-2 title-font">Let's Celebrate!</p>
        <h1 class="text-5xl sm:text-7xl font-extrabold text-black-700 tracking-tight title-font">
            🎂 happy birthday to meeeeee
        </h1>
        <p class="mt-4 text-gray-600 text-lg sm:text-xl font-medium">Join us for a magical evening to celebrate a major milestone.</p>
      <div class="image">
          <img src="null_0(JPG).jpg" height="200" width="300" > 
      </div>      
    </header>
   <div class="mb-10 overflow-hidden rounded-2xl shadow-xl border-4 border-black-400">          
    </div>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-12 text-center">
        <div class="p-6 bg-blue-50 rounded-xl shadow-lg border-t-4 border-blue-500">
            <p class="text-3xl mb-2">📅</p>
            <h2 class="text-xl font-bold text-black-700 mb-1">Date</h2>
            <p class="text-black-600 font-extrabold text-2xl">Saturday, December 7th, 2024</p>
        </div>
        <div class="p-6 bg-blue-50 rounded-xl shadow-lg border-t-4 border-blue-500">
            <p class="text-3xl mb-2">⏰</p>
            <h2 class="text-xl font-bold text-black-700 mb-1">Time</h2>
            <p class="text-black-600 font-extrabold text-2xl">6:00 PM - 10:00 PM</p>
        </div>
        <div class="p-6 bg-blue-50 rounded-xl shadow-lg border-t-4 border-blue-500">
            <p class="text-3xl mb-2">🏠</p>
            <h2 class="text-xl font-bold text-black-700 mb-1">Venue</h2>
            <p class="text-gray-700 text-lg font-medium">The Anabu liwayway homes </p>
            <p class="text-black-600 font-extrabold text-2xl">Anabu liwayway homes</p>
        </div>
    </div>
    <div class="bg-blue-700 text-white p-8 rounded-xl shadow-xl mb-12">
        <h2 class="text-3xl font-bold text-center mb-6 text-yellow-300">Your Attendance Matters!</h>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center">
            <div class="p-4 bg-blue-600 rounded-lg">
                <p class="text-3xl mb-2">👕</p>
                <h3 class="font-semibold text-xl mb-1 text-yellow-300">Attire & Gifts</h3>
                <p class="text-black-100">Dress code is Smart Casual. <strong class="font-bold">No gifts</strong> Your presence is the best gift we could ask for.</p>
            </div>
            <div class="p-4 bg-blue-600 rounded-lg">
                <p class="text-3xl mb-2">📨</p>
                <h3 class="font-semibold text-xl mb-1 text-yellow-300">RSVP</h3>
                <p class="text-black-100 mb-2">Kindly confirm your attendance by july 13</p>                  
            </div>
            <div class="p-4 bg-blue-600 rounded-lg">
                <p class="text-3xl mb-2">🙋</p>
                <h3 class="font-semibold text-xl mb-1 text-yellow-300">Contact Person</h3>
                <p class="text-black-100">Contact: mark jan herrera</p>
                <p class="text-xl font-extrabold">09971435799</p>
            </div>
        </div>
    </div>
    <section class="mb-4">
        <h2 class="text-3xl font-bold text-blue-700 mb-4 text-center">📍 How to Get to Anabu, Imus, Cavite</h2>
        <div class="map-container">
            <iframe 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15456.985925345717!2d120.91699709999999!3d14.39805565!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3397d4b46c6422d7%3A0x6e9a7e6d013f9f21!2sAnabu%2C%20Imus%2C%20Cavite!5e0!3m2!1sen!2sph!4v1700000000000!5m2!1sen!2sph"
                allowfullscreen="" 
                loading="lazy" 
                referrerpolicy="no-referrer-when-downgrade">
            </iframe>
        </div>
        <p class="text-center text-sm text-gray-500 mt-2">The map</p>
    </section>
    <footer class="text-center pt-8 border-t border-gray-200 mt-8">
        <p class="text-sm text-gray-500">&copy;july 13 </p>
    </footer>
</div>
</body>
</html>

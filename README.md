<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8"/>
    <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
    <title>Real Estate Website</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100">
<!-- Header -->
<header class="bg-white shadow">
    <div class="container mx-auto flex justify-between items-center py-4 px-6">
        <div class="flex items-center">
            <img alt="Logo" class="mr-4" height="50" src="https://storage.googleapis.com/a1aa/image/trMeWxPVMpqDOcW_lEBkfFXmY79e8qXWbjCTCM8wtkA.jpg" width="150"/>
            <nav class="hidden md:flex space-x-4">
                <a class="text-gray-700 hover:text-blue-500" href="#">Home</a>
                <a class="text-gray-700 hover:text-blue-500" href="#">Properties</a>
                <a class="text-gray-700 hover:text-blue-500" href="#">About Us</a>
                <a class="text-gray-700 hover:text-blue-500" href="#">Services</a>
                <a class="text-gray-700 hover:text-blue-500" href="#">Contact Us</a>
            </nav>
        </div>
        <div class="flex items-center space-x-4">
            <div class="hidden md:flex items-center space-x-2">
                <i class="fas fa-phone-alt text-blue-500"></i>
                <span class="text-gray-700">+020 123 456</span>
            </div>
            <div class="hidden md:flex items-center space-x-2">
                <i class="fas fa-envelope text-blue-500"></i>
                <span class="text-gray-700">info@companyname.com</span>
            </div>
            <a class="text-gray-700 hover:text-blue-500" href="#">My Account</a>
            <a class="bg-blue-500 text-white px-4 py-2 rounded" href="#">Submit Property</a>
        </div>
    </div>
</header>
<!-- Hero Section -->
<section class="relative">
    <img alt="Hero Image" class="w-full h-96 object-cover" height="600" src="https://storage.googleapis.com/a1aa/image/lVCrGhrLZD2hqjJ26UT33pf6Qe_WlNvUl72OyUQyPwE.jpg" width="1920"/>
    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center">
        <div class="text-center text-white">
            <h1 class="text-4xl font-bold">Find Your Dream Home</h1>
            <p class="mt-4">Search from over 10,000 properties</p>
            <div class="mt-6 bg-white p-6 rounded shadow-lg">
                <form class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4">
                    <select class="border border-gray-300 p-2 rounded">
                        <option>Location</option>
                    </select>
                    <select class="border border-gray-300 p-2 rounded">
                        <option>Property Type</option>
                    </select>
                    <input class="border border-gray-300 p-2 rounded" placeholder="Min Price" type="text"/>
                    <input class="border border-gray-300 p-2 rounded" placeholder="Max Price" type="text"/>
                    <button class="bg-blue-500 text-white px-4 py-2 rounded col-span-1 md:col-span-2 lg:col-span-1">Search Listing</button>
                </form>
            </div>
        </div>
    </div>
</section>
<!-- Latest Properties -->
<section class="container mx-auto py-12">
    <h2 class="text-2xl font-bold text-center mb-8">Latest Properties</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Property Card -->
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Property Image" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/lJXxmtmMB_OwdNDuB8zuqF8DX5YUrygBuZpWTbqyQ2s.jpg" width="400"/>
            <div class="p-4">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <p class="text-gray-600">Area: 1500 sq ft</p>
                <div class="flex items-center justify-between mt-4">
                    <span class="text-blue-500">For Sale</span>
                    <span class="text-gray-700">$250,000</span>
                </div>
            </div>
        </div>
        <!-- Repeat Property Card for each property -->
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Property Image" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/lJXxmtmMB_OwdNDuB8zuqF8DX5YUrygBuZpWTbqyQ2s.jpg" width="400"/>
            <div class="p-4">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <p class="text-gray-600">Area: 1500 sq ft</p>
                <div class="flex items-center justify-between mt-4">
                    <span class="text-blue-500">For Sale</span>
                    <span class="text-gray-700">$250,000</span>
                </div>
            </div>
        </div>
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Property Image" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/lJXxmtmMB_OwdNDuB8zuqF8DX5YUrygBuZpWTbqyQ2s.jpg" width="400"/>
            <div class="p-4">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <p class="text-gray-600">Area: 1500 sq ft</p>
                <div class="flex items-center justify-between mt-4">
                    <span class="text-blue-500">For Sale</span>
                    <span class="text-gray-700">$250,000</span>
                </div>
            </div>
        </div>
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Property Image" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/lJXxmtmMB_OwdNDuB8zuqF8DX5YUrygBuZpWTbqyQ2s.jpg" width="400"/>
            <div class="p-4">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <p class="text-gray-600">Area: 1500 sq ft</p>
                <div class="flex items-center justify-between mt-4">
                    <span class="text-blue-500">For Sale</span>
                    <span class="text-gray-700">$250,000</span>
                </div>
            </div>
        </div>
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Property Image" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/lJXxmtmMB_OwdNDuB8zuqF8DX5YUrygBuZpWTbqyQ2s.jpg" width="400"/>
            <div class="p-4">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <p class="text-gray-600">Area: 1500 sq ft</p>
                <div class="flex items-center justify-between mt-4">
                    <span class="text-blue-500">For Sale</span>
                    <span class="text-gray-700">$250,000</span>
                </div>
            </div>
        </div>
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Property Image" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/lJXxmtmMB_OwdNDuB8zuqF8DX5YUrygBuZpWTbqyQ2s.jpg" width="400"/>
            <div class="p-4">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <p class="text-gray-600">Area: 1500 sq ft</p>
                <div class="flex items-center justify-between mt-4">
                    <span class="text-blue-500">For Sale</span>
                    <span class="text-gray-700">$250,000</span>
                </div>
            </div>
        </div>
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Property Image" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/lJXxmtmMB_OwdNDuB8zuqF8DX5YUrygBuZpWTbqyQ2s.jpg" width="400"/>
            <div class="p-4">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <p class="text-gray-600">Area: 1500 sq ft</p>
                <div class="flex items-center justify-between mt-4">
                    <span class="text-blue-500">For Sale</span>
                    <span class="text-gray-700">$250,000</span>
                </div>
            </div>
        </div>
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Property Image" class="w-full h-48 object-cover" height="300" src="https://storage.googleapis.com/a1aa/image/lJXxmtmMB_OwdNDuB8zuqF8DX5YUrygBuZpWTbqyQ2s.jpg" width="400"/>
            <div class="p-4">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <p class="text-gray-600">Area: 1500 sq ft</p>
                <div class="flex items-center justify-between mt-4">
                    <span class="text-blue-500">For Sale</span>
                    <span class="text-gray-700">$250,000</span>
                </div>
            </div>
        </div>
    </div>
</section>
<!-- Contact Us Section -->
<section class="relative">
    <img alt="Contact Us Image" class="w-full h-64 object-cover" height="400" src="https://storage.googleapis.com/a1aa/image/B8dSkcckLOozqGMs8AoGoJYdoF7IpLyq0kFsCLfZ6yQ.jpg" width="1920"/>
    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center">
        <div class="text-center text-white">
            <h2 class="text-3xl font-bold">Want to sale your property? Contact us Now</h2>
            <button class="mt-4 bg-blue-500 text-white px-6 py-2 rounded">Contact Us</button>
        </div>
    </div>
</section>
<!-- Meet Our Agents -->
<section class="container mx-auto py-12">
    <h2 class="text-2xl font-bold text-center mb-8">Meet Our Agents</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Agent Card -->
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Agent Image" class="w-full h-48 object-cover" height="300" src="https://placehold.co/400x300?text=Agent+1" width="400"/>
            <div class="p-4 text-center">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <div class="flex justify-center space-x-2 mt-4">
                    <a class="text-blue-500" href="#"><i class="fab fa-facebook-f"></i></a>
                    <a class="text-blue-500" href="#"><i class="fab fa-twitter"></i></a>
                    <a class="text-blue-500" href="#"><i class="fab fa-linkedin-in"></i></a>
                </div>
            </div>
        </div>
        <!-- Repeat Agent Card for each agent -->
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Agent Image" class="w-full h-48 object-cover" height="300" src="https://placehold.co/400x300?text=Agent+2" width="400"/>
            <div class="p-4 text-center">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <div class="flex justify-center space-x-2 mt-4">
                    <a class="text-blue-500" href="#"><i class="fab fa-facebook-f"></i></a>
                    <a class="text-blue-500" href="#"><i class="fab fa-twitter"></i></a>
                    <a class="text-blue-500" href="#"><i class="fab fa-linkedin-in"></i></a>
                </div>
            </div>
        </div>
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Agent Image" class="w-full h-48 object-cover" height="300" src="https://placehold.co/400x300?text=Agent+3" width="400"/>
            <div class="p-4 text-center">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <div class="flex justify-center space-x-2 mt-4">
                    <a class="text-blue-500" href="#"><i class="fab fa-facebook-f"></i></a>
                    <a class="text-blue-500" href="#"><i class="fab fa-twitter"></i></a>
                    <a class="text-blue-500" href="#"><i class="fab fa-linkedin-in"></i></a>
                </div>
            </div>
        </div>
        <div class="bg-white shadow rounded overflow-hidden">
            <img alt="Agent Image" class="w-full h-48 object-cover" height="300" src="https://placehold.co/400x300?text=Agent+4" width="400"/>
            <div class="p-4 text-center">
                <h3 class="text-lg font-bold">Lorem Ipsum is Simply</h3>
                <p class="text-gray-600">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
                <div class="flex justify-center space-x-2 mt-4">
                    <a class="text-blue-500" href="#"><i class="fab fa-facebook-f"></i></a>
                    <a class="text-blue-500" href="#"><i class="fab fa-twitter"></i></a>
                    <a class="text-blue-500" href="#"><i class="fab fa-linkedin-in"></i></a>
                </div>
            </div>
        </div>
    </div>
</section>
<!-- Footer -->
<footer class="bg-gray-900 text-white py-12">
    <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Quick Links -->
        <div>
            <h3 class="text-lg font-bold mb-4">Quick Links</h3>
            <ul>
                <li><a class="text-gray-400 hover:text-white" href="#">Home</a></li>
                <li><a class="text-gray-400 hover:text-white" href="#">Properties</a></li>
                <li><a class="text-gray-400 hover:text-white" href="#">About Us</a></li>
                <li><a class="text-gray-400 hover:text-white" href="#">Services</a></li>
                <li><a class="text-gray-400 hover:text-white" href="#">Contact Us</a></li>
            </ul>
        </div>
        <!-- Contact Us -->
        <div>
            <h3 class="text-lg font-bold mb-4">Contact Us</h3>
            <p class="text-gray-400">1234 Street Name, City, State, 12345</p>
            <p class="text-gray-400">

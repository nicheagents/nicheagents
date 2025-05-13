<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Niche Agents - Your Trusted Buyer's Agency</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Custom colors based on the logo */
        .bg-brand-light {
            background-color: #FFF0F5; /* A light pink, adjust if needed */
        }
        .bg-brand-primary {
            background-color: #B91C1C; /* A deep red, from Tailwind's red-700 for consistency */
        }
        .text-brand-primary {
            color: #B91C1C; /* Deep red */
        }
        .border-brand-primary {
            border-color: #B91C1C; /* Deep red */
        }
        .hover-bg-brand-primary-dark:hover {
            background-color: #991B1B; /* Darker red for hover, from Tailwind's red-800 */
        }
        .logo-img {
            max-height: 60px; /* Adjust as needed */
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="flex items-center space-x-2">
                <img src="550b5e5d-70fc-481d-9a3e-c7eebc83b693.png" alt="Niche Agents Logo" class="logo-img" onerror="this.onerror=null;this.src='https://placehold.co/150x50/FFD1DC/B91C1C?text=Niche+Agents';">
                </a>

            <nav class="hidden md:flex space-x-6">
                <a href="#" class="text-gray-600 hover:text-brand-primary font-medium">Home</a>
                <a href="#about" class="text-gray-600 hover:text-brand-primary font-medium">About Us</a>
                <a href="#services" class="text-gray-600 hover:text-brand-primary font-medium">Services</a>
                <a href="#contact" class="text-gray-600 hover:text-brand-primary font-medium">Contact</a>
            </nav>

            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-gray-600 hover:text-brand-primary focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                    </svg>
                </button>
            </div>
        </div>

        <div id="mobile-menu" class="md:hidden hidden bg-white shadow-lg">
            <a href="#" class="block px-6 py-3 text-gray-600 hover:bg-brand-light hover:text-brand-primary">Home</a>
            <a href="#about" class="block px-6 py-3 text-gray-600 hover:bg-brand-light hover:text-brand-primary">About Us</a>
            <a href="#services" class="block px-6 py-3 text-gray-600 hover:bg-brand-light hover:text-brand-primary">Services</a>
            <a href="#contact" class="block px-6 py-3 text-gray-600 hover:bg-brand-light hover:text-brand-primary">Contact</a>
        </div>
    </header>

    <section class="bg-brand-light py-20 md:py-32">
        <div class="container mx-auto px-6 text-center">
            <h1 class="text-4xl md:text-6xl font-bold text-brand-primary mb-6 leading-tight">
                Find Your Perfect Property, Effortlessly.
            </h1>
            <p class="text-lg md:text-xl text-gray-700 mb-10 max-w-2xl mx-auto">
                Welcome to Niche Agents – your dedicated buyer's advocates. We navigate the market, negotiate the best terms, and secure your ideal home or investment.
            </p>
            <a href="#contact"
               class="bg-brand-primary text-white font-semibold py-3 px-8 rounded-lg shadow-md hover-bg-brand-primary-dark transition duration-300 text-lg">
                Get Started Today
            </a>
        </div>
    </section>

    <section id="about" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-12 md:mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-brand-primary mb-4">Why Choose Niche Agents?</h2>
                <p class="text-gray-600 max-w-xl mx-auto">We're not just agents; we're your personal property partners, dedicated to your success.</p>
            </div>
            <div class="grid md:grid-cols-3 gap-8 text-center">
                <div class="p-6 bg-gray-50 rounded-lg shadow-sm hover:shadow-lg transition-shadow">
                    <div class="text-brand-primary mb-4">
                        <svg class="w-12 h-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z"></path></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Expert Negotiation</h3>
                    <p class="text-gray-600">We leverage our market knowledge and negotiation skills to get you the best possible price and terms.</p>
                </div>
                <div class="p-6 bg-gray-50 rounded-lg shadow-sm hover:shadow-lg transition-shadow">
                    <div class="text-brand-primary mb-4">
                        <svg class="w-12 h-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Exclusive Access</h3>
                    <p class="text-gray-600">Gain access to off-market properties and opportunities you won't find on your own.</p>
                </div>
                <div class="p-6 bg-gray-50 rounded-lg shadow-sm hover:shadow-lg transition-shadow">
                    <div class="text-brand-primary mb-4">
                        <svg class="w-12 h-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-2">Stress-Free Process</h3>
                    <p class="text-gray-600">We handle the complexities of property searching, due diligence, and acquisition, saving you time and stress.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-16 md:py-24 bg-brand-light">
        <div class="container mx-auto px-6">
            <div class="text-center mb-12 md:mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-brand-primary mb-4">How We Help You Succeed</h2>
                <p class="text-gray-600 max-w-xl mx-auto">Our comprehensive buyer's agency services cover every step of your property journey.</p>
            </div>
            <div class="grid md:grid-cols-2 gap-8 items-start">
                <div class="bg-white p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-semibold text-brand-primary mb-3">Personalised Property Search</h3>
                    <p class="text-gray-600 mb-4">We take the time to understand your unique needs, preferences, and investment goals to find properties that truly match.</p>
                    <h3 class="text-2xl font-semibold text-brand-primary mb-3">Due Diligence & Analysis</h3>
                    <p class="text-gray-600 mb-4">Thorough research, market analysis, and property inspections to ensure you make an informed decision.</p>
                    <h3 class="text-2xl font-semibold text-brand-primary mb-3">Auction Bidding & Support</h3>
                    <p class="text-gray-600">Expert representation and strategic bidding at auctions to secure your desired property.</p>
                </div>
                <div class="mt-8 md:mt-0">
                     <img src="https://placehold.co/600x400/E9D5FF/4A044E?text=Happy+Homeowners" alt="Happy Homeowners" class="rounded-lg shadow-xl w-full h-auto object-cover" style="max-height: 400px;">
                     </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-20 md:py-32 bg-white">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-brand-primary mb-6">Ready to Find Your Niche Property?</h2>
            <p class="text-lg text-gray-700 mb-10 max-w-xl mx-auto">
                Let's discuss your property goals. Schedule a free, no-obligation consultation with our expert buyer's agents today.
            </p>
            <a href="mailto:your-email@example.com?subject=Property Enquiry from Niche Agents Website"
               class="bg-brand-primary text-white font-semibold py-4 px-10 rounded-lg shadow-md hover-bg-brand-primary-dark transition duration-300 text-lg">
                Schedule Your Consultation
            </a>
            <p class="text-gray-600 mt-6">Or call us on: <a href="tel:+61000000000" class="text-brand-primary hover:underline font-medium">(07) XXXX XXXX</a></p>
        </div>
    </section>

    <footer class="bg-gray-800 text-gray-300 py-12">
        <div class="container mx-auto px-6 text-center">
            <div class="mb-4">
                <a href="#" class="text-gray-400 hover:text-white mx-2">Facebook</a>
                <a href="#" class="text-gray-400 hover:text-white mx-2">Instagram</a>
                <a href="#" class="text-gray-400 hover:text-white mx-2">LinkedIn</a>
            </div>
            <p>&copy; <span id="currentYear"></span> Niche Agents. All Rights Reserved.</p>
            <p class="text-sm mt-1">Your Trusted Buyer's Agency on the Sunshine Coast.</p>
             </div>
    </footer>

    <script>
        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        if (mobileMenuButton && mobileMenu) {
            mobileMenuButton.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });
        }

        // Set current year in footer
        const currentYearSpan = document.getElementById('currentYear');
        if (currentYearSpan) {
            currentYearSpan.textContent = new Date().getFullYear();
        }

        // Smooth scroll for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    targetElement.scrollIntoView({
                        behavior: 'smooth'
                    });
                    // Close mobile menu if open after click
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                }
            });
        });
    </script>

</body>
</html>

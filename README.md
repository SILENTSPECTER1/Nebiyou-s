
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Basic styles for readability and appeal */
        body {
            font-family: 'Inter', sans-serif; /* A clean, modern font */
        }
        .section-title {
            @apply text-2xl font-bold text-center mb-6 text-gray-700; /* Simplified title */
        }
        .card {
            @apply bg-white rounded-lg shadow-md overflow-hidden; /* Simplified card */
        }
        .card-content {
            @apply p-5; /* Slightly reduced padding */
        }
        /* Smooth scroll behavior */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-600">

    <nav class="bg-white shadow-sm sticky w-full z-10 top-0 rounded-b-md">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#" class="text-xl font-semibold text-blue-600">Your Name</a>
            <div class="space-x-3">
                <a href="#about" class="text-gray-500 hover:text-blue-600 px-2 py-1 rounded-md text-sm">About</a>
                <a href="#projects" class="text-gray-500 hover:text-blue-600 px-2 py-1 rounded-md text-sm">Projects</a>
                <a href="#contact" class="text-gray-500 hover:text-blue-600 px-2 py-1 rounded-md text-sm">Contact</a>
            </div>
        </div>
    </nav>

    <header class="bg-blue-500 text-white pt-24 pb-12 md:pt-28 md:pb-16 rounded-b-lg shadow-md">
        <div class="container mx-auto px-4 text-center">
            <img src="https://placehold.co/120x120/FFFFFF/3B82F6?text=Me" alt="Your Name" class="w-24 h-24 md:w-28 md:h-28 mx-auto rounded-full object-cover border-2 border-white shadow-lg mb-4">
            <h1 class="text-3xl md:text-4xl font-bold mb-1">Your Name</h1>
            <p class="text-lg md:text-xl text-blue-100">Your Title (e.g., Developer, Designer)</p>
        </div>
    </header>

    <section id="about" class="py-12 md:py-16 bg-white rounded-lg shadow my-6 mx-3 md:mx-auto max-w-3xl">
        <div class="container mx-auto px-4">
            <h2 class="section-title">About Me</h2>
            <p class="text-center text-md leading-relaxed max-w-xl mx-auto">
                Hi, I'm [Your Name]. I'm a [Your Profession/Title] passionate about [Your Key Interest].
                I enjoy building [Type of work/projects]. This is a brief space to introduce yourself.
            </p>
        </div>
    </section>

    <section id="projects" class="py-12 md:py-16 bg-gray-50 rounded-lg shadow my-6 mx-3 md:mx-auto max-w-4xl">
        <div class="container mx-auto px-4">
            <h2 class="section-title">Key Projects</h2>
            <div class="grid md:grid-cols-2 gap-6">
                <div class="card">
                    <img src="https://placehold.co/500x300/E0E7FF/3B82F6?text=Project+A" alt="Project 1" class="w-full h-40 object-cover">
                    <div class="card-content">
                        <h3 class="text-lg font-semibold mb-1 text-gray-700">Project Title A</h3>
                        <p class="text-sm text-gray-500 mb-3">Short description of the project and your role.</p>
                        <a href="#" class="text-blue-500 hover:underline text-sm font-medium">Learn More</a>
                    </div>
                </div>
                <div class="card">
                    <img src="https://placehold.co/500x300/DBEAFE/3B82F6?text=Project+B" alt="Project 2" class="w-full h-40 object-cover">
                    <div class="card-content">
                        <h3 class="text-lg font-semibold mb-1 text-gray-700">Project Title B</h3>
                        <p class="text-sm text-gray-500 mb-3">Another project, highlighting a key skill or achievement.</p>
                        <a href="#" class="text-blue-500 hover:underline text-sm font-medium">Learn More</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-12 md:py-16 bg-blue-500 text-white rounded-t-lg shadow-md">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-2xl font-bold mb-4">Contact Me</h2>
            <p class="text-md mb-6 text-blue-100">Interested in working together or have a question?</p>
            <a href="mailto:your.email@example.com" class="bg-white text-blue-600 font-semibold px-6 py-3 rounded-lg hover:bg-blue-50 transition-colors shadow-sm inline-block">
                your.email@example.com
            </a>
            <div class="flex justify-center space-x-5 mt-8">
                <a href="#" target="_blank" rel="noopener noreferrer" class="text-white hover:text-blue-200 text-2xl transition-colors" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="#" target="_blank" rel="noopener noreferrer" class="text-white hover:text-blue-200 text-2xl transition-colors" aria-label="GitHub"><i class="fab fa-github"></i></a>
                </div>
        </div>
    </section>

    <footer class="bg-gray-700 text-gray-300 text-center py-4 rounded-t-md">
        <p class="text-sm">&copy; <span id="currentYear"></span> Your Name. All rights reserved.</p>
    </footer>

    <script>
        // JavaScript to set the current year in the footer
        document.getElementById('currentYear').textContent = new Date().getFullYear();
    </script>

</body>
</html>


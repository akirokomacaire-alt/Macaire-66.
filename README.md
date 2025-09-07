
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');

        body {
            font-family: 'Inter', sans-serif;
            background-color: #0E1117;
            color: #E2E8F0;
        }

        .container {
            max-width: 1200px;
            margin: auto;
        }

        .text-accent {
            color: #06B6D4;
        }
    </style>
</head>

<body class="antialiased">

    <!-- Header -->
    <header class="bg-gray-800 bg-opacity-50 backdrop-blur-sm fixed top-0 left-0 right-0 z-50">
        <nav class="container mx-auto flex justify-between items-center py-4 px-4">
            <a href="#" class="text-2xl font-bold text-white">Macaire AKIROKO</a>
            <div class="hidden md:flex space-x-6">
                <a href="#about" class="hover:text-cyan-400 transition">À propos</a>
                <a href="#projects" class="hover:text-cyan-400 transition">Projets</a>
                <a href="#skills" class="hover:text-cyan-400 transition">Compétences</a>
                <a href="#contact" class="hover:text-cyan-400 transition">Contact</a>
            </div>
            <button class="md:hidden text-white focus:outline-none">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24"
                    stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                </svg>
            </button>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="h-screen flex items-center justify-center text-center p-4" id="hero">
        <div class="relative w-full h-full flex flex-col md:flex-row items-center justify-center p-4 md:p-8">
            <div class="md:w-1/2 flex justify-center md:justify-end mb-8 md:mb-0 md:mr-8">
                <img src="C:\Users\HP\Desktop\HTML\projet\png.jpg"
                    alt="Image de développeurs" class="rounded-lg shadow-lg max-w-full h-auto">
            </div>
            <div class="md:w-1/2 text-left">
                <h1 class="text-5xl md:text-6xl font-extrabold text-white mb-4 leading-tight">Je suis <span
                        class="text-accent">Macaire</span>, Développeur en devenir</h1>
                <p class="text-xl md:text-2xl text-gray-400 mb-6">Passionné par le web et le design!</p>
                <a href="#projects" class="btn bg-cyan-600 text-white shadow-lg shadow-cyan-500/50">Voir mes projets</a>
            </div>
        </div>
    </section>


    <!-- About Section -->
    <section class="py-20 px-4" id="about">
        <div class="container mx-auto flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 md:pr-12 mb-8 md:mb-0">
                <h2 class="text-4xl font-bold mb-4 text-white">À propos</h2>
                <p class="text-lg text-gray-300 mb-4">
                    Je m'appelle <span class="text-accent">Macaire AKIROKO</span>, passionné par la création de sites
                    web modernes et interactifs.
                </p>
                <p class="text-lg text-gray-300 mb-4">
                    Je suis actuellement étudiant(e) en développement web, et je cherche à améliorer mes compétences en
                    JavaScript, HTML et CSS.
                </p>
                <p class="text-lg text-gray-300 mb-8">
                    J'adore transformer mes idées en projets concrets et expérimenter avec les nouvelles technologies.
                </p>
                <button onclick="downloadCV()" class="btn bg-gray-700 text-white hover:bg-gray-600">Télécharger mon
                    CV</button>
            </div>
            <div class="md:w-1/2">
                <img src="C:\Users\HP\Desktop\HTML\projet\png.jpg"
                    alt="Photo de profil de Macaire AKIROKO"
                    class="rounded-full w-48 h-48 mx-auto shadow-xl border-4 border-cyan-500">
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="py-20 px-4" id="projects">
        <div class="container mx-auto text-center">
            <h2 class="text-4xl font-bold mb-12 text-white">Mes Projets</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="bg-gray-800 p-8 rounded-lg shadow-lg transition-transform transform hover:scale-105">
                    <h3 class="text-2xl font-bold mb-2 text-cyan-400">Application de Gestion de Tâches</h3>
                    <p class="text-gray-400 mb-4">Une application web complète pour organiser et suivre les tâches, avec
                        des fonctionnalités de tri et de filtrage.</p>
                    <div class="flex flex-wrap justify-center mb-4">
                        <span class="bg-gray-700 text-gray-300 text-sm px-3 py-1 rounded-full mr-2 mb-2">#html</span>
                        <span class="bg-gray-700 text-gray-300 text-sm px-3 py-1 rounded-full mr-2 mb-2">#css</span>
                        <span class="bg-gray-700 text-gray-300 text-sm px-3 py-1 rounded-full mb-2">#js</span>
                    </div>
                    <button class="btn bg-cyan-600 text-white">Voir</button>
                </div>
                <!-- Project 2 -->
                <div class="bg-gray-800 p-8 rounded-lg shadow-lg transition-transform transform hover:scale-105">
                    <h3 class="text-2xl font-bold mb-2 text-cyan-400">Site Web de Blog Dynamique</h3>
                    <p class="text-gray-400 mb-4">Un site de blog où les utilisateurs peuvent créer, éditer et supprimer
                        des articles, avec une interface d'administration.</p>
                    <div class="flex flex-wrap justify-center mb-4">
                        <span class="bg-gray-700 text-gray-300 text-sm px-3 py-1 rounded-full mr-2 mb-2">#html</span>
                        <span class="bg-gray-700 text-gray-300 text-sm px-3 py-1 rounded-full mr-2 mb-2">#css</span>
                        <span class="bg-gray-700 text-gray-300 text-sm px-3 py-1 rounded-full mb-2">#js</span>
                    </div>
                    <button class="btn bg-cyan-600 text-white">Voir</button>
                </div>
                <!-- Project 3 -->
                <div class="bg-gray-800 p-8 rounded-lg shadow-lg transition-transform transform hover:scale-105">
                    <h3 class="text-2xl font-bold mb-2 text-cyan-400">Clone de Site de Commerce Électronique</h3>
                    <p class="text-gray-400 mb-4">Un site d'e-commerce avec une page produit, un panier d'achat et un
                        processus de paiement simulé.</p>
                    <div class="flex flex-wrap justify-center mb-4">
                        <span class="bg-gray-700 text-gray-300 text-sm px-3 py-1 rounded-full mr-2 mb-2">#html</span>
                        <span class="bg-gray-700 text-gray-300 text-sm px-3 py-1 rounded-full mr-2 mb-2">#css</span>
                        <span class="bg-gray-700 text-gray-300 text-sm px-3 py-1 rounded-full mb-2">#js</span>
                    </div>
                    <button class="btn bg-cyan-600 text-white">Voir</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="py-20 px-4" id="skills">
        <div class="container mx-auto text-center">
            <h2 class="text-4xl font-bold mb-12 text-white">Mes Compétences</h2>
            <div class="flex flex-col md:flex-row justify-center space-y-8 md:space-y-0 md:space-x-12">
                <!-- Hard Skills -->
                <div class="bg-gray-800 p-8 rounded-lg shadow-lg w-full md:w-1/2">
                    <h3 class="text-2xl font-bold mb-6 text-cyan-400">Hard Skills</h3>
                    <div class="grid grid-cols-2 gap-6">
                        <div class="bg-gray-700 p-4 rounded-lg">HTML</div>
                        <div class="bg-gray-700 p-4 rounded-lg">CSS</div>
                        <div class="bg-gray-700 p-4 rounded-lg">JavaScript</div>
                        <div class="bg-gray-700 p-4 rounded-lg">VS Code</div>
                    </div>
                </div>
                <!-- Soft Skills -->
                <div class="bg-gray-800 p-8 rounded-lg shadow-lg w-full md:w-1/2">
                    <h3 class="text-2xl font-bold mb-6 text-cyan-400">Soft Skills</h3>
                    <div class="grid grid-cols-1 gap-6">
                        <div class="bg-gray-700 p-4 rounded-lg">Gestion de projet</div>
                        <div class="bg-gray-700 p-4 rounded-lg">Résolution de problème</div>
                        <div class="bg-gray-700 p-4 rounded-lg">Adaptabilité</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-20 px-4" id="contact">
        <div class="container mx-auto text-center max-w-2xl">
            <h2 class="text-4xl font-bold mb-4 text-white">Vous avez un projet en tête ?</h2>
            <p class="text-lg text-gray-400 mb-8">N'hésitez pas à me contacter</p>

            <form id="contactForm" class="flex flex-col space-y-6">
                <div class="flex flex-col md:flex-row space-y-6 md:space-y-0 md:space-x-6">
                    <input type="text" id="firstName" placeholder="Votre prénom" required
                        class="w-full bg-gray-700 text-white p-4 rounded-lg border border-transparent focus:border-cyan-500 outline-none">
                    <input type="text" id="lastName" placeholder="Votre nom" required
                        class="w-full bg-gray-700 text-white p-4 rounded-lg border border-transparent focus:border-cyan-500 outline-none">
                </div>
                <input type="text" id="subject" placeholder="Votre sujet" required
                    class="w-full bg-gray-700 text-white p-4 rounded-lg border border-transparent focus:border-cyan-500 outline-none">
                <textarea id="message" rows="6" placeholder="Votre message" required
                    class="w-full bg-gray-700 text-white p-4 rounded-lg border border-transparent focus:border-cyan-500 outline-none resize-none"></textarea>
                <button type="submit" class="btn bg-cyan-600 text-white shadow-lg shadow-cyan-500/50">Envoyer</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 py-8 px-4 text-center text-gray-500">
        <p>Conçu par Macaire AKIROKO avec HTML, CSS, JS</p>
        <p class="mt-2">Tous droits réservés - 2025</p>
    </footer>

    <!-- JavaScript for smooth scrolling and form submission -->
    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Form submission handling
        document.getElementById('contactForm').addEventListener('submit', function (e) {
            e.preventDefault();

            const firstName = document.getElementById('firstName').value;
            const lastName = document.getElementById('lastName').value;
            const subject = document.getElementById('subject').value;
            const message = document.getElementById('message').value;

            // Simple validation
            if (!firstName || !lastName || !subject || !message) {
                console.error('Veuillez remplir tous les champs du formulaire.');
                return;
            }

            console.log('Formulaire envoyé :', {
                firstName,
                lastName,
                subject,
                message
            });

            // Here you would typically send the data to a server
            // For this example, we'll just show a success message
            showNotification('Message envoyé avec succès !', 'success');

            // Reset the form
            this.reset();
        });

        // Function to show a simple notification (instead of alert)
        function showNotification(message, type) {
            const notification = document.createElement('div');
            notification.className = `fixed bottom-4 left-1/2 transform -translate-x-1/2 p-4 rounded-lg shadow-lg text-white ${type === 'success' ? 'bg-green-600' : 'bg-red-600'} transition-opacity duration-300 z-50`;
            notification.textContent = message;
            document.body.appendChild(notification);

            setTimeout(() => {
                notification.style.opacity = '0';
                setTimeout(() => notification.remove(), 300);
            }, 3000);
        }

        // Function to simulate CV download
        function downloadCV() {
            // In a real application, this would trigger a file download
            console.log('Téléchargement du CV simulé.');
            showNotification('Le téléchargement du CV a démarré !', 'success');
        }

    </script>
</body>

</html>

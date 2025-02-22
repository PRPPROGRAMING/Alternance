<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Basbas Hatim</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Animation personnalisée pour le survol des cartes */
    @keyframes pulseBorder {
      0%, 100% { box-shadow: 0 0 0 0 rgba(59,130,246, 0.7); }
      50% { box-shadow: 0 0 0 10px rgba(59,130,246, 0); }
    }
    .hover-pulse:hover {
      animation: pulseBorder 1.5s infinite;
    }
  </style>
</head>
<body class="bg-gray-900 text-white">
  <header class="p-6 bg-gradient-to-r from-blue-800 to-purple-800 text-center">
    <h1 class="text-4xl font-bold">Basbas Hatim</h1>
    <p class="text-gray-300">Étudiant passionné par l'informatique et la technologie</p>
  </header>
  
  <section class="p-6">
    <h2 class="text-3xl font-semibold mb-4">À propos de moi</h2>
    <p class="text-gray-300">
      Je m'appelle Basbas Hatim, j'ai 18 ans et j'habite à Sainte-Geneviève-des-Bois. Actuellement en Bac Pro MELEC, 
      je souhaite poursuivre des études en Alternance BTS SIO SISR à partir de septembre 2025 pour approfondir 
      mes compétences en systèmes et réseaux.
    </p>
    <p class="text-gray-300 mt-4">
      Passionné par l'informatique depuis plusieurs années, j'aime explorer différents domaines comme la cybersécurité, 
      l'administration réseau et le développement web. Mon objectif est d'acquérir de solides compétences techniques 
      et de me spécialiser dans la protection des systèmes informatiques.
    </p>
  </section>
  
  <section class="p-6">
    <h2 class="text-3xl font-semibold mb-4">Compétences</h2>
    <ul class="list-disc list-inside text-gray-300">
      <li>Administration des systèmes (Windows, Linux)</li>
      <li>Gestion de réseaux informatiques (Configuration, maintenance LAN/WAN)</li>
      <li>Sécurité informatique (Pare-feu, VPN, cryptage des données)</li>
      <li>Virtualisation & Cloud (VMware, Docker, AWS, Azure, GCP)</li>
      <li>Développement (SQL, Lua, Java, CSS, HTML)</li>
      <li>Cloud Computing (AWS, Azure, GCP)</li>
      <li>Travail d'équipe, autonomie et esprit d'analyse</li>
    </ul>
  </section>

  <section class="p-6">
    <h2 class="text-3xl font-semibold mb-4">Projets Informatiques</h2>
    <p class="text-gray-300">
      <strong>Développeur & Administrateur de serveurs FiveM (2020 - 2025)</strong><br>
      Gestion complète du serveur, y compris son installation, configuration et maintenance sous Windows et Linux. En tant que responsable, j'ai supervisé et coordonné une équipe de développeurs et de modérateurs pour garantir une expérience optimale pour les joueurs.
    </p>
    <p class="text-gray-300 mt-4">
      <strong>Principales responsabilités :</strong>
    </p>
    <ul class="list-disc list-inside text-gray-300 mt-2">
      <li>Installation, configuration et maintenance des serveurs sur des environnements Windows/Linux.</li>
      <li>Supervision d'une équipe de développeurs et de modérateurs pour assurer la gestion du serveur et sa modération.</li>
      <li>Développement et personnalisation de scripts en Lua et d'interfaces utilisateur interactives en CSS, HTML et JavaScript.</li>
      <li>Optimisation des performances du serveur et gestion des bases de données SQL pour garantir une expérience fluide et rapide.</li>
      <li>Implémentation de mesures de sécurité pour protéger le serveur, y compris la gestion des accès, la sécurisation des données et la prévention des attaques.</li>
    </ul>
  </section>
  
  <!-- Section ajoutée avec effet innovant -->
  <section class="p-6">
    <h2 class="text-3xl font-semibold mb-4">Réalisations Innovantes</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <div class="p-6 bg-gray-800 rounded-lg hover-pulse transition duration-300">
        <h3 class="text-2xl font-bold mb-2">Optimisation des Performances Serveur</h3>
        <p class="text-gray-300">
          Mise en place d'un système de surveillance et d'optimisation en temps réel pour améliorer les performances des serveurs, réduisant les temps de latence et les coûts d'infrastructure. 
          Intégration de solutions de gestion des ressources avec des outils comme Docker et Kubernetes pour maximiser l'efficacité.
        </p>
      </div>
      <div class="p-6 bg-gray-800 rounded-lg hover-pulse transition duration-300">
        <h3 class="text-2xl font-bold mb-2">Sécurisation des Réseaux et Serveurs</h3>
        <p class="text-gray-300">
          Implémentation d'une architecture de sécurité multi-niveaux pour protéger les serveurs et les réseaux d'une entreprise contre les cyberattaques. Mise en œuvre de VPN, pare-feu avancés, et systèmes de détection d'intrusion (IDS), avec des protocoles de cryptage de données pour sécuriser les échanges.
        </p>
      </div>
    </div>
  </section>

  <section class="p-6">
    <h2 class="text-3xl font-semibold mb-4">Langues</h2>
    <ul class="list-disc list-inside text-gray-300">
      <li>Français (Courant)</li>
      <li>Espagnol (Courant)</li>
      <li>Arabe (Courant)</li>
      <li>Catalan (Intermédiaire)</li>
      <li>Anglais (Intermédiaire)</li>
    </ul>
  </section>
  
  <section class="p-6">
    <h2 class="text-3xl font-semibold mb-4">Contact</h2>
    <ul class="list-disc list-inside text-gray-300 mt-2">
      <li>Email : <a href="mailto:hatimbasbas@gmail.com" class="text-blue-400">hatimbasbas@gmail.com</a></li>
      <li>Téléphone : +33 6 14 34 88 99</li>
    </ul>
  </section>
  
  <footer class="p-6 bg-gray-800 text-center">
    <p class="text-gray-400">© 2025 Basbas Hatim - Tous droits réservés</p>
  </footer>
</body>
</html>

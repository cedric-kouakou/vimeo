<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Veille Technologique - Vimeo et Alternatives</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.0/font/bootstrap-icons.css">
    <style>
        :root {
            --vimeo-blue: #00adef;
            --vimeo-dark: #162221;
            --vimeo-light: #f8f9fa;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f5f7fa;
        }
        
        .vimeo-bg {
            background: linear-gradient(135deg, var(--vimeo-blue) 0%, #00c3ff 100%);
            color: white;
        }
        
        .nav-pills .nav-link.active {
            background-color: var(--vimeo-blue);
        }
        
        .card {
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease;
            border: none;
        }
        
        .card:hover {
            transform: translateY(-5px);
        }
        
        .feature-icon {
            font-size: 2rem;
            color: var(--vimeo-blue);
            margin-bottom: 1rem;
        }
        
        .platform-card {
            border-top: 4px solid var(--vimeo-blue);
        }
        
        .comparison-table th {
            background-color: var(--vimeo-blue);
            color: white;
        }
        
        .img-fluid-rounded {
            border-radius: 10px;
        }
        
        .hero-section {
            background-size: contain;
            min-height: 300px;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark vimeo-bg sticky-top">
        <div class="container">
            <a class="navbar-brand d-flex align-items-center" href="#">
                <i class="bi bi-camera-reels-fill me-2"></i>
                <span>Veille Vimeo</span>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#vimeo">Vimeo</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#alternatives">Alternatives</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#comparaison">Comparaison</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#integration">Intégration</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="hero-section bg-light py-5">
        <div class="container py-5">
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <h1 class="display-4 fw-bold mb-3">Vimeo et ses alternatives</h1>
                    <p class="lead mb-4">Guide complet pour choisir la meilleure solution d'hébergement vidéo pour votre projet web</p>
                    <a href="#vimeo" class="btn btn-primary btn-lg px-4">Commencer l'exploration</a>
                </div>
                <div class="col-lg-6 d-none d-lg-block">
                </div>
            </div>
        </div>
    </header>

    <!-- Main Content -->
    <div class="container my-5">
        <!-- Vimeo Section -->
        <section id="vimeo" class="mb-5">
            <div class="row mb-4">
                <div class="col-12">
                    <h2 class="display-5 fw-bold text-center mb-4"><i class="bi bi-camera-video-fill me-2"></i> Qu'est-ce que Vimeo ?</h2>
                </div>
            </div>
            
            <div class="row g-4">
                <div class="col-lg-6">
                    <div class="card h-100">
                        <div class="card-body">
                            <h3 class="card-title"><i class="bi bi-info-circle-fill text-primary me-2"></i> Présentation</h3>
                            <p class="card-text">Vimeo est une plateforme de partage et d'hébergement de vidéos créée en 2004. Contrairement à YouTube, elle se focalise sur la qualité, la confidentialité et le public professionnel (créateurs, entreprises, éducateurs).</p>
                            <p>Il est possible d'intégrer les vidéos facilement dans un site web avec un player personnalisable.</p>
                        </div>
                    </div>
                </div>
                
                <div class="col-lg-6">
                    <div class="card h-100">
                        <div class="card-body">
                            <h3 class="card-title"><i class="bi bi-lightbulb-fill text-primary me-2"></i> Cas d'usage</h3>
                            <ul class="list-group list-group-flush">
                                <li class="list-group-item"><i class="bi bi-check-circle-fill text-success me-2"></i> Vidéos de formation en ligne</li>
                                <li class="list-group-item"><i class="bi bi-check-circle-fill text-success me-2"></i> Portfolios de créateurs</li>
                                <li class="list-group-item"><i class="bi bi-check-circle-fill text-success me-2"></i> Vidéos corporates ou promotionnelles</li>
                                <li class="list-group-item"><i class="bi bi-check-circle-fill text-success me-2"></i> Contenus privés (accès restreint)</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="row mt-4 g-4">
                <div class="col-md-6">
                    <div class="card h-100">
                        <div class="card-header bg-primary text-white">
                            <h3 class="mb-0"><i class="bi bi-check-circle-fill me-2"></i> Avantages</h3>
                        </div>
                        <div class="card-body">
                            <ul class="list-group list-group-flush">
                                <li class="list-group-item"><i class="bi bi-check-lg text-success me-2"></i> Pas de publicité</li>
                                <li class="list-group-item"><i class="bi bi-check-lg text-success me-2"></i> Player personnalisable</li>
                                <li class="list-group-item"><i class="bi bi-check-lg text-success me-2"></i> Contrôle de la confidentialité</li>
                                <li class="list-group-item"><i class="bi bi-check-lg text-success me-2"></i> Bonne qualité vidéo (jusqu'à 8K)</li>
                                <li class="list-group-item"><i class="bi bi-check-lg text-success me-2"></i> Intégration HTML simple</li>
                                <li class="list-group-item"><i class="bi bi-check-lg text-success me-2"></i> Statistiques détaillées</li>
                            </ul>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-6">
                    <div class="card h-100">
                        <div class="card-header bg-danger text-white">
                            <h3 class="mb-0"><i class="bi bi-exclamation-triangle-fill me-2"></i> Limites</h3>
                        </div>
                        <div class="card-body">
                            <ul class="list-group list-group-flush">
                                <li class="list-group-item"><i class="bi bi-x-lg text-danger me-2"></i> Offre gratuite très limitée</li>
                                <li class="list-group-item"><i class="bi bi-x-lg text-danger me-2"></i> Espace de stockage limité</li>
                                <li class="list-group-item"><i class="bi bi-x-lg text-danger me-2"></i> Pas de monétisation directe</li>
                                <li class="list-group-item"><i class="bi bi-x-lg text-danger me-2"></i> Moins de visibilité naturelle</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Alternatives Section -->
        <section id="alternatives" class="mb-5">
            <div class="row mb-4">
                <div class="col-12">
                    <h2 class="display-5 fw-bold text-center mb-4"><i class="bi bi-boxes me-2"></i> Plateformes alternatives à Vimeo</h2>
                </div>
            </div>
            
            <div class="row g-4">
                <!-- YouTube -->
                <div class="col-lg-4 col-md-6">
                    <div class="card h-100 platform-card">
                        <div class="card-body">
                            <div class="d-flex justify-content-between align-items-center mb-3">
                                <h3 class="card-title mb-0">YouTube</h3>
                                <span class="badge bg-danger">Grand public</span>
                            </div>
                            <p class="card-text">La plateforme de référence pour le grand public avec un fort potentiel de référencement.</p>
                            <div class="alert alert-success p-2 mb-3">
                                <strong>Avantages :</strong> Gratuit, stockage illimité, SEO puissant
                            </div>
                            <div class="alert alert-warning p-2">
                                <strong>Inconvénients :</strong> Publicités, confidentialité limitée
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Wistia -->
                <div class="col-lg-4 col-md-6">
                    <div class="card h-100 platform-card">
                        <div class="card-body">
                            <div class="d-flex justify-content-between align-items-center mb-3">
                                <h3 class="card-title mb-0">Wistia</h3>
                                <span class="badge bg-primary">Marketing</span>
                            </div>
                            <p class="card-text">Solution professionnelle orientée marketing vidéo avec analytics avancés.</p>
                            <div class="alert alert-success p-2 mb-3">
                                <strong>Avantages :</strong> Analytics, intégration de formulaires, lead generation
                            </div>
                            <div class="alert alert-warning p-2">
                                <strong>Inconvénients :</strong> Payant, moins grand public
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- VideoPress -->
                <div class="col-lg-4 col-md-6">
                    <div class="card h-100 platform-card">
                        <div class="card-body">
                            <div class="d-flex justify-content-between align-items-center mb-3">
                                <h3 class="card-title mb-0">VideoPress</h3>
                                <span class="badge bg-info">WordPress</span>
                            </div>
                            <p class="card-text">Solution intégrée pour les utilisateurs de WordPress.</p>
                            <div class="alert alert-success p-2 mb-3">
                                <strong>Avantages :</strong> Intégration native, aucune pub, sécurisé
                            </div>
                            <div class="alert alert-warning p-2">
                                <strong>Inconvénients :</strong> Payant, limité à WordPress
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Brightcove -->
                <div class="col-lg-6 col-md-6">
                    <div class="card h-100 platform-card">
                        <div class="card-body">
                            <div class="d-flex justify-content-between align-items-center mb-3">
                                <h3 class="card-title mb-0">Brightcove</h3>
                                <span class="badge bg-dark">Entreprise</span>
                            </div>
                            <p class="card-text">Solution professionnelle haut de gamme pour les grandes entreprises.</p>
                            <div class="alert alert-success p-2 mb-3">
                                <strong>Avantages :</strong> Robuste, évolutif, outils pro
                            </div>
                            <div class="alert alert-warning p-2">
                                <strong>Inconvénients :</strong> Coût élevé, complexe
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Dailymotion -->
                <div class="col-lg-6 col-md-6">
                    <div class="card h-100 platform-card">
                        <div class="card-body">
                            <div class="d-flex justify-content-between align-items-center mb-3">
                                <h3 class="card-title mb-0">Dailymotion</h3>
                                <span class="badge bg-secondary">Généraliste</span>
                            </div>
                            <p class="card-text">Alternative française à YouTube avec moins de concurrence.</p>
                            <div class="alert alert-success p-2 mb-3">
                                <strong>Avantages :</strong> Interface française, moins saturé
                            </div>
                            <div class="alert alert-warning p-2">
                                <strong>Inconvénients :</strong> Moins de visibilité, options limitées
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Comparison Section -->
        <section id="comparaison" class="mb-5">
            <div class="row mb-4">
                <div class="col-12">
                    <h2 class="display-5 fw-bold text-center mb-4"><i class="bi bi-clipboard2-data-fill me-2"></i> Quelle plateforme choisir ?</h2>
                </div>
            </div>
            
            <div class="row">
                <div class="col-12">
                    <div class="card">
                        <div class="card-header bg-primary text-white">
                            <h3 class="mb-0">Guide de sélection par cas d'usage</h3>
                        </div>
                        <div class="card-body p-0">
                            <div class="table-responsive">
                                <table class="table table-hover mb-0">
                                    <thead class="table-light">
                                        <tr>
                                            <th>Objectif du projet</th>
                                            <th>Plateforme conseillée</th>
                                            <th>Avantages clés</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td>Héberger des vidéos professionnelles (B2B, portfolio)</td>
                                            <td><span class="badge bg-primary">Vimeo</span></td>
                                            <td>Qualité, confidentialité, player personnalisable</td>
                                        </tr>
                                        <tr>
                                            <td>Publier des vidéos grand public et gagner en visibilité</td>
                                            <td><span class="badge bg-danger">YouTube</span></td>
                                            <td>SEO, audience massive, gratuit</td>
                                        </tr>
                                        <tr>
                                            <td>Analyser le comportement des utilisateurs (lead generation)</td>
                                            <td><span class="badge bg-info">Wistia</span></td>
                                            <td>Analytics avancés, intégration marketing</td>
                                        </tr>
                                        <tr>
                                            <td>Gérer une plateforme d'e-learning / formation payante</td>
                                            <td><span class="badge bg-primary">Vimeo</span> ou <span class="badge bg-info">Wistia</span></td>
                                            <td>Accès restreint, intégration LMS</td>
                                        </tr>
                                        <tr>
                                            <td>Intégrer des vidéos dans un site WordPress</td>
                                            <td><span class="badge bg-success">Jetpack VideoPress</span></td>
                                            <td>Intégration native, sécurisé</td>
                                        </tr>
                                        <tr>
                                            <td>Créer une solution de streaming très évoluée</td>
                                            <td><span class="badge bg-dark">Brightcove</span></td>
                                            <td>Évolutivité, outils professionnels</td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Integration Section -->
        <section id="integration" class="mb-5">
            <div class="row mb-4">
                <div class="col-12">
                    <h2 class="display-5 fw-bold text-center mb-4"><i class="bi bi-code-slash me-2"></i> Intégration dans un projet web</h2>
                </div>
            </div>
            
            <div class="row g-4">
                <div class="col-lg-6">
                    <div class="card h-100">
                        <div class="card-header bg-dark text-white">
                            <h3 class="mb-0"><i class="bi bi-filetype-html me-2"></i> Code d'intégration Vimeo</h3>
                        </div>
                        <div class="card-body">
                            <pre><code class="language-html">&lt;iframe src="https://player.vimeo.com/video/123456789"
        width="640"
        height="360"
        frameborder="0"
        allow="autoplay; fullscreen"
        allowfullscreen&gt;&lt;/iframe&gt;</code></pre>
                            <p class="mt-3">Personnalisez le lecteur (couleur, logo, contrôle) et restreignez son affichage à votre domaine pour des contenus protégés.</p>
                        </div>
                    </div>
                </div>
                
                <div class="col-lg-6">
                    <div class="card h-100">
                        <div class="card-body">
                            <h3 class="card-title"><i class="bi bi-gear-fill text-primary me-2"></i> Options avancées</h3>
                            <ul class="list-group list-group-flush">
                                <li class="list-group-item">
                                    <i class="bi bi-shield-lock-fill text-primary me-2"></i>
                                    <strong>Restriction par domaine</strong> - Limitez l'affichage à votre site uniquement
                                </li>
                                <li class="list-group-item">
                                    <i class="bi bi-palette-fill text-primary me-2"></i>
                                    <strong>Personnalisation du player</strong> - Couleurs, logo, contrôles
                                </li>
                                <li class="list-group-item">
                                    <i class="bi bi-graph-up-fill text-primary me-2"></i>
                                    <strong>Analytics avancés</strong> - Taux de lecture, engagement, heatmaps
                                </li>
                                <li class="list-group-item">
                                    <i class="bi bi-lock-fill text-primary me-2"></i>
                                    <strong>Protection par mot de passe</strong> - Pour contenus privés
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Conclusion -->
        <section class="mb-5">
            <div class="card border-primary">
                <div class="card-header bg-primary text-white">
                    <h2 class="mb-0"><i class="bi bi-check-circle-fill me-2"></i> Conclusion</h2>
                </div>
                <div class="card-body">
                    <div class="row align-items-center">
                        <div class="col-md-8">
                            <p class="lead">Vimeo reste un excellent choix pour les projets <strong>web de contenus vidéos professionnels</strong> grâce à :</p>
                            <ul class="list-group list-group-flush mb-3">
                                <li class="list-group-item"><i class="bi bi-shield-check text-primary me-2"></i> Son niveau de confidentialité élevé</li>
                                <li class="list-group-item"><i class="bi bi-play-circle text-primary me-2"></i> Son player soigné et sans pub</li>
                                <li class="list-group-item"><i class="bi bi-puzzle text-primary me-2"></i> Son intégration fluide dans un site</li>
                            </ul>
                            <p>Mais selon le <strong>type de public</strong>, le <strong>budget</strong>, et les <strong>objectifs marketing</strong>, d'autres solutions peuvent être préférées.</p>
                        </div>
                        <div class="col-md-4 text-center">
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <!-- Footer -->
    <footer class="vimeo-bg text-white py-5">
        <div class="container">
            <div class="row">
                <div class="col-lg-4 mb-4 mb-lg-0">
                    <h3><i class="bi bi-camera-reels-fill me-2"></i> Veille Technologique</h3>
                    <p class="mt-3">Guide complet sur les solutions d'hébergement vidéo pour projets web.</p>
                </div>
                <div class="col-lg-4 mb-4 mb-lg-0">
                    <h5>Liens rapides</h5>
                    <ul class="nav flex-column">
                        <li class="nav-item"><a href="#vimeo" class="nav-link text-white">Vimeo</a></li>
                        <li class="nav-item"><a href="#alternatives" class="nav-link text-white">Alternatives</a></li>
                        <li class="nav-item"><a href="#comparaison" class="nav-link text-white">Comparaison</a></li>
                        <li class="nav-item"><a href="#integration" class="nav-link text-white">Intégration</a></li>
                    </ul>
                </div>
                <div class="col-lg-4">
                    <h5>Ressources</h5>
                    <ul class="list-unstyled">
                        <li><a href="https://vimeo.com" class="text-white" target="_blank">Site officiel Vimeo</a></li>
                        <li><a href="https://wistia.com" class="text-white" target="_blank">Documentation Wistia</a></li>
                        <li><a href="https://wordpress.org/videopress/" class="text-white" target="_blank">VideoPress WordPress</a></li>
                    </ul>
                </div>
            </div>
            <hr class="my-4 bg-light">
            <div class="row">
                <div class="col-md-6 text-center text-md-start">
                    <p class="mb-0">© 2023 Veille Technologique. Tous droits réservés.</p>
                </div>
                <div class="col-md-6 text-center text-md-end">
                    <a href="#" class="text-white me-3"><i class="bi bi-twitter"></i></a>
                    <a href="#" class="text-white me-3"><i class="bi bi-linkedin"></i></a>
                    <a href="#" class="text-white me-3"><i class="bi bi-github"></i></a>
                    <a href="#" class="text-white"><i class="bi bi-envelope-fill"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.24.1/prism.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.24.1/themes/prism-okaidia.min.css">
</body>
</html>

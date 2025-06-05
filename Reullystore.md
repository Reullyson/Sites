<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reullystore - Moda Masculina Streetwear</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'reully-purple': '#7e22ce',
                        'reully-light': '#a855f7',
                        'reully-dark': '#581c87'
                    }
                }
            }
        }
    </script>
    <style>
        .hero-section {
            background-image: linear-gradient(rgba(126, 34, 206, 0.7), rgba(126, 34, 206, 0.7)), url('https://images.unsplash.com/photo-1526406206597-41ac581d7b5d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-position: center;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        
        .newsletter-input:focus {
            outline: none;
            box-shadow: 0 0 0 2px rgba(168, 85, 247, 0.5);
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        .animate-fadeIn {
            animation: fadeIn 1s ease-in-out;
        }
    </style>
</head>
<body class="bg-white font-sans">
    <!-- Header/Navigation -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-2">
                    <a href="#" class="text-2xl font-bold text-reully-purple">REULLY<span class="text-gray-800">STORE</span></a>
                </div>
                
                <div class="hidden md:flex space-x-6">
                    <a href="#" class="text-gray-800 hover:text-reully-purple font-medium">Home</a>
                    <a href="#" class="text-gray-800 hover:text-reully-purple font-medium">Novidades</a>
                    <a href="#" class="text-gray-800 hover:text-reully-purple font-medium">Coleções</a>
                    <a href="#" class="text-gray-800 hover:text-reully-purple font-medium">Sobre</a>
                    <a href="#" class="text-gray-800 hover:text-reully-purple font-medium">Contato</a>
                </div>
                
                <div class="flex items-center space-x-4">
                    <a href="#" class="text-gray-800 hover:text-reully-purple">
                        <i class="fas fa-search text-lg"></i>
                    </a>
                    <a href="#" class="text-gray-800 hover:text-reully-purple">
                        <i class="fas fa-user text-lg"></i>
                    </a>
                    <a href="#" class="text-gray-800 hover:text-reully-purple relative">
                        <i class="fas fa-shopping-bag text-lg"></i>
                        <span class="absolute -top-2 -right-2 bg-reully-purple text-white text-xs rounded-full h-5 w-5 flex items-center justify-center">0</span>
                    </a>
                    <button class="md:hidden text-gray-800 focus:outline-none">
                        <i class="fas fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-section text-white py-20 md:py-32 animate-fadeIn">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-6">ELEVE SEU STYLE</h1>
            <p class="text-xl md:text-2xl mb-8 max-w-2xl mx-auto">Streetwear premium que combina conforto, estilo e atitude.</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#" class="bg-white text-reully-purple px-8 py-3 rounded-md font-bold hover:bg-gray-100 transition duration-300">COMPRAR AGORA</a>
                <a href="#" class="border-2 border-white text-white px-8 py-3 rounded-md font-bold hover:bg-white hover:text-reully-purple transition duration-300">VER COLECÃO</a>
            </div>
        </div>
    </section>

    <!-- Featured Categories -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">CATEGORIAS EM DESTAQUE</h2>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="bg-white rounded-lg overflow-hidden shadow-md group relative">
                    <img src="https://images.unsplash.com/photo-1602810319428-7266904e2b0b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2080&q=80" 
                         alt="Camisetas" class="w-full h-64 object-cover transition duration-500 group-hover:scale-105">
                    <div class="p-4">
                        <h3 class="text-xl font-bold text-gray-800">Camisetas</h3>
                        <a href="#" class="mt-2 inline-block text-reully-purple font-medium hover:underline">Ver coleção →</a>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg overflow-hidden shadow-md group relative">
                    <img src="https://images.unsplash.com/photo-1604160687650-b6e66b3e0603?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2080&q=80" 
                         alt="Moletons" class="w-full h-64 object-cover transition duration-500 group-hover:scale-105">
                    <div class="p-4">
                        <h3 class="text-xl font-bold text-gray-800">Moletons</h3>
                        <a href="#" class="mt-2 inline-block text-reully-purple font-medium hover:underline">Ver coleção →</a>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg overflow-hidden shadow-md group relative">
                    <img src="https://images.unsplash.com/photo-1591047139829-d91aecb6caea?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2036&q=80" 
                         alt="Calças" class="w-full h-64 object-cover transition duration-500 group-hover:scale-105">
                    <div class="p-4">
                        <h3 class="text-xl font-bold text-gray-800">Calças</h3>
                        <a href="#" class="mt-2 inline-block text-reully-purple font-medium hover:underline">Ver coleção →</a>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg overflow-hidden shadow-md group relative">
                    <img src="https://images.unsplash.com/photo-1549298916-f52d724204b4?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2106&q=80" 
                         alt="Acessórios" class="w-full h-64 object-cover transition duration-500 group-hover:scale-105">
                    <div class="p-4">
                        <h3 class="text-xl font-bold text-gray-800">Acessórios</h3>
                        <a href="#" class="mt-2 inline-block text-reully-purple font-medium hover:underline">Ver coleção →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Products -->
    <section class="py-16">
        <div class="container mx-auto px-4">
            <div class="flex justify-between items-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800">DESTAQUES DA SEMANA</h2>
                <a href="#" class="text-reully-purple font-medium hover:underline">VER TODOS →</a>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300">
                    <div class="relative">
                        <img src="https://images.unsplash.com/photo-1527719327859-c6ce80353573?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2080&q=80" 
                             alt="Camiseta Oversized" class="w-full h-80 object-cover">
                        <div class="absolute top-3 right-3 bg-reully-purple text-white text-xs px-2 py-1 rounded-md">NOVO</div>
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="text-lg font-bold text-gray-800">Camiseta Oversized</h3>
                                <p class="text-gray-600 text-sm">Coleção Urban</p>
                            </div>
                            <span class="text-reully-purple font-bold">R$ 129,90</span>
                        </div>
                        <div class="mt-4 flex justify-between items-center">
                            <a href="#" class="w-full bg-reully-purple text-white text-center py-2 rounded-md hover:bg-reully-dark transition duration-300">Comprar</a>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300">
                    <div class="relative">
                        <img src="https://images.unsplash.com/photo-1624378439575-d8705ad7ae80?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2079&q=80" 
                             alt="Jaqueta Streetwear" class="w-full h-80 object-cover">
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="text-lg font-bold text-gray-800">Jaqueta Streetwear</h3>
                                <p class="text-gray-600 text-sm">Coleção Winter</p>
                            </div>
                            <span class="text-reully-purple font-bold">R$ 279,90</span>
                        </div>
                        <div class="mt-4 flex justify-between items-center">
                            <a href="#" class="w-full bg-reully-purple text-white text-center py-2 rounded-md hover:bg-reully-dark transition duration-300">Comprar</a>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300">
                    <div class="relative">
                        <img src="https://images.unsplash.com/photo-1578932750355-5eb30ece487a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" 
                             alt="Calça Jogger" class="w-full h-80 object-cover">
                        <div class="absolute top-3 right-3 bg-red-500 text-white text-xs px-2 py-1 rounded-md">-20%</div>
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="text-lg font-bold text-gray-800">Calça Jogger</h3>
                                <p class="text-gray-600 text-sm">Coleção Basics</p>
                            </div>
                            <div>
                                <span class="text-gray-400 line-through text-sm">R$ 169,90</span>
                                <span class="text-reully-purple font-bold block">R$ 135,90</span>
                            </div>
                        </div>
                        <div class="mt-4 flex justify-between items-center">
                            <a href="#" class="w-full bg-reully-purple text-white text-center py-2 rounded-md hover:bg-reully-dark transition duration-300">Comprar</a>
                        </div>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="product-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300">
                    <div class="relative">
                        <img src="https://images.unsplash.com/photo-1490114538077-0a7f8cb49891?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" 
                             alt="Moletom Capuz" class="w-full h-80 object-cover">
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="text-lg font-bold text-gray-800">Moletom Capuz</h3>
                                <p class="text-gray-600 text-sm">Coleção Comfort</p>
                            </div>
                            <span class="text-reully-purple font-bold">R$ 199,90</span>
                        </div>
                        <div class="mt-4 flex justify-between items-center">
                            <a href="#" class="w-full bg-reully-purple text-white text-center py-2 rounded-md hover:bg-reully-dark transition duration-300">Comprar</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Banner Promotion -->
    <section class="bg-reully-purple text-white py-12">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-2xl md:text-3xl font-bold mb-4">PROMOÇÃO EXCLUSIVA</h2>
            <p class="text-xl md:text-2xl mb-6">20% OFF EM TODA A LOJA*</p>
            <p class="mb-8">*Use o cupom <span class="font-bold">REULLY20</span> no checkout</p>
            <a href="#" class="bg-white text-reully-purple px-8 py-3 rounded-md font-bold hover:bg-gray-100 transition duration-300">APROVEITAR OFERTA</a>
        </div>
    </section>

    <!-- Newsletter -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="max-w-2xl mx-auto text-center">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">JUNTE-SE A NOSSA COMUNIDADE</h2>
                <p class="text-gray-600 mb-8">Receba as últimas novidades, ofertas exclusivas e dicas de estilo direto na sua caixa de entrada.</p>
                
                <form class="flex flex-col sm:flex-row gap-4 max-w-md mx-auto">
                    <input type="email" placeholder="Seu melhor e-mail" 
                           class="newsletter-input flex-grow px-4 py-3 rounded-md border border-gray-300 focus:border-reully-purple">
                    <button type="submit" 
                            class="bg-reully-purple text-white px-6 py-3 rounded-md font-bold hover:bg-reully-dark transition duration-300 whitespace-nowrap">
                        CADASTRAR
                    </button>
                </form>
                
                <p class="text-xs text-gray-500 mt-4">Ao se inscrever, você concorda com nossa Política de Privacidade.</p>
            </div>
        </div>
    </section>

    <!-- Instagram Feed -->
    <section class="py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">SIGA-NOS NO INSTAGRAM</h2>
            
            <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-4">
                <a href="#" class="group">
                    <img src="https://images.unsplash.com/photo-1598033129183-c4f50c736f10?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1025&q=80" 
                         alt="Instagram Post" class="w-full h-64 object-cover group-hover:opacity-90 transition duration-300">
                </a>
                <a href="#" class="group">
                    <img src="https://images.unsplash.com/photo-1520367445093-50dc08a59d9d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=987&q=80" 
                         alt="Instagram Post" class="w-full h-64 object-cover group-hover:opacity-90 transition duration-300">
                </a>
                <a href="#" class="group">
                    <img src="https://images.unsplash.com/photo-1551232864-3f0890e580d9?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=987&q=80" 
                         alt="Instagram Post" class="w-full h-64 object-cover group-hover:opacity-90 transition duration-300">
                </a>
                <a href="#" class="group">
                    <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1020&q=80" 
                         alt="Instagram Post" class="w-full h-64 object-cover group-hover:opacity-90 transition duration-300">
                </a>
                <a href="#" class="group hidden lg:block">
                    <img src="https://images.unsplash.com/photo-1527719327859-c6ce80353573?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1025&q=80" 
                         alt="Instagram Post" class="w-full h-64 object-cover group-hover:opacity-90 transition duration-300">
                </a>
                <div class="col-span-2 md:col-span-4 lg:col-span-5 text-center mt-8">
                    <a href="#" class="inline-flex items-center text-reully-purple font-bold hover:underline">
                        <i class="fab fa-instagram text-2xl mr-2"></i>
                        @REULLYSTORE
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white pt-12 pb-6">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">REULLYSTORE</h3>
                    <p class="text-gray-400">Streetwear premium para homens que buscam estilo, conforto e atitude.</p>
                    <div class="flex space-x-4 mt-4">
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-tiktok"></i></a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">MENU</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Home</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Produtos</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Coleções</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Sobre Nós</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Contato</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">AJUDA</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Trocas e Devoluções</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Política de Entrega</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Formas de Pagamento</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Perguntas Frequentes</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">CONTATO</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-start">
                            <i class="fas fa-map-marker-alt mt-1 mr-2 text-reully-light"></i>
                            <span>Avenida da Moda, 123 - São Paulo/SP</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-phone-alt mt-1 mr-2 text-reully-light"></i>
                            <span>(11) 91234-5678</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-envelope mt-1 mr-2 text-reully-light"></i>
                            <span>contato@reullystore.com</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-clock mt-1 mr-2 text-reully-light"></i>
                            <span>Seg-Sex: 9h às 18h <br>Sáb: 10h às 16h</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 pt-6">
                <div class="flex flex-col md:flex-row justify-between items-center">
                    <p class="text-gray-500 text-sm mb-4 md:mb-0">© 2023 Reullystore. Todos os direitos reservados.</p>
                    <div class="flex space-x-6">
                        <img src="https://via.placeholder.com/40x25?text=VISA" alt="Visa" class="h-6">
                        <img src="https://via.placeholder.com/40x25?text=MC" alt="Mastercard" class="h-6">
                        <img src="https://via.placeholder.com/40x25?text=AMEX" alt="American Express" class="h-6">
                        <img src="https://via.placeholder.com/40x25?text=PIX" alt="Pix" class="h-6">
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- Mobile Menu (hidden by default) -->
    <div class="fixed inset-0 bg-black bg-opacity-75 z-50 hidden" id="mobileMenu">
        <div class="absolute top-0 right-0 w-80 h-full bg-white">
            <div class="p-4">
                <button class="absolute top-4 right-4 text-gray-800">
                    <i class="fas fa-times text-xl"></i>
                </button>
                
                <ul class="mt-12 space-y-4">
                    <li><a href="#" class="block py-2 px-4 text-gray-800 hover:bg-gray-100 rounded">Home</a></li>
                    <li><a href="#" class="block py-2 px-4 text-gray-800 hover:bg-gray-100 rounded">Novidades</a></li>
                    <li><a href="#" class="block py-2 px-4 text-gray-800 hover:bg-gray-100 rounded">Coleções</a></li>
                    <li><a href="#" class="block py-2 px-4 text-gray-800 hover:bg-gray-100 rounded">Sobre</a></li>
                    <li><a href="#" class="block py-2 px-4 text-gray-800 hover:bg-gray-100 rounded">Contato</a></li>
                    <li class="pt-4 border-t">
                        <a href="#" class="block py-2 px-4 bg-reully-purple text-white rounded text-center">Minha Conta</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>

    <script>
        // Mobile menu toggle
        document.addEventListener('DOMContentLoaded', function() {
            const mobileMenuButton = document.querySelector('.md\\:hidden');
            const mobileMenu = document.getElementById('mobileMenu');
            const closeButton = mobileMenu.querySelector('button');
            
            mobileMenuButton.addEventListener('click', function() {
                mobileMenu.classList.remove('hidden');
            });
            
            closeButton.addEventListener('click', function() {
                mobileMenu.classList.add('hidden');
            });
            
            // Smooth scroll for anchor links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function(e) {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            });
        });
    </script>
</body>
</html>

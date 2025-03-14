​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dove - Freshness & Care | Infinity Soaps</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom Dove-inspired styles */
        .dove-blue { background-color: #005670; }
        .dove-gold { color: #D4AF37; }
    </style>
</head>
<body class="bg-gray-100 font-sans">
    <!-- Header -->
    <header class="dove-blue text-white py-4 sticky top-0 shadow-md">
        <div class="container mx-auto flex justify-between items-center px-4">
            <h1 class="text-2xl font-bold">Infinity Soaps</h1>
            <nav class="space-x-4">
                <a href="#" class="hover:underline">Home</a>
                <a href="#products" class="hover:underline">Products</a>
                <a href="#about" class="hover:underline">About</a>
                <a href="#contact" class="hover:underline">Contact</a>
            </nav>
            <a href="#products" class="bg-white text-dove-blue px-4 py-2 rounded hover:bg-gray-200">Shop Now</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-white py-12">
        <div class="container mx-auto flex flex-col md:flex-row items-center px-4">
            <div class="md:w-1/2 text-center md:text-left">
                <h2 class="text-4xl font-bold text-dove-blue mb-4">Feel Fresh, Smell Divine</h2>
                <p class="text-gray-700 mb-6">Experience the gentle care and lasting fragrance of Dove products.</p>
                <a href="#products" class="bg-dove-blue text-white px-6 py-3 rounded hover:bg-blue-700">Discover Now</a>
            </div>
            <div class="md:w-1/2 mt-6 md:mt-0">
                <img src="https://via.placeholder.com/500x300?text=Dove+Products" alt="Dove Products" class="w-full rounded-lg shadow-lg">
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="container mx-auto py-12 px-4">
        <h2 class="text-3xl font-bold text-dove-blue text-center mb-8">Our Products</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <!-- Product 1: Soap Bars -->
            <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow">
                <img src="https://via.placeholder.com/300x200?text=Dove+Soap" alt="Dove Soap" class="w-full h-40 object-cover rounded-md mb-4">
                <h3 class="text-xl font-semibold text-dove-blue">Soap Bars</h3>
                <p class="text-gray-600 mb-2">Moisturizing care for soft skin.</p>
                <p class="text-dove-gold font-bold mb-4">$4.99</p>
                <button class="w-full bg-dove-blue text-white py-2 rounded hover:bg-blue-700">Add to Cart</button>
            </div>
            <!-- Product 2: Body Wash -->
            <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow">
                <img src="https://via.placeholder.com/300x200?text=Dove+Body+Wash" alt="Dove Body Wash" class="w-full h-40 object-cover rounded-md mb-4">
                <h3 class="text-xl font-semibold text-dove-blue">Body Wash</h3>
                <p class="text-gray-600 mb-2">Gentle cleansing with a fresh scent.</p>
                <p class="text-dove-gold font-bold mb-4">$7.99</p>
                <button class="w-full bg-dove-blue text-white py-2 rounded hover:bg-blue-700">Add to Cart</button>
            </div>
            <!-- Product 3: Deodorants -->
            <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow">
                <img src="https://via.placeholder.com/300x200?text=Dove+Deodorant" alt="Dove Deodorant" class="w-full h-40 object-cover rounded-md mb-4">
                <h3 class="text-xl font-semibold text-dove-blue">Deodorants</h3>
                <p class="text-gray-600 mb-2">Long-lasting fragrance and protection.</p>
                <p class="text-dove-gold font-bold mb-4">$5.49</p>
                <button class="w-full bg-dove-blue text-white py-2 rounded hover:bg-blue-700">Add to Cart</button>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="bg-gray-50 py-12">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold text-dove-blue mb-8">Why Choose Dove?</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div>
                    <img src="https://via.placeholder.com/50x50?text=Moisture" alt="Moisture Icon" class="mx-auto mb-4">
                    <h3 class="text-xl font-semibold text-dove-blue">Moisturizing Care</h3>
                    <p class="text-gray-600">Keeps your skin soft and hydrated.</p>
                </div>
                <div>
                    <img src="https://via.placeholder.com/50x50?text=Skin" alt="Skin Icon" class="mx-auto mb-4">
                    <h3 class="text-xl font-semibold text-dove-blue">Gentle on Skin</h3>
                    <p class="text-gray-600">Formulated for all skin types.</p>
                </div>
                <div>
                    <img src="https://via.placeholder.com/50x50?text=Fragrance" alt="Fragrance Icon" class="mx-auto mb-4">
                    <h3 class="text-xl font-semibold text-dove-blue">Long-Lasting Fragrance</h3>
                    <p class="text-gray-600">Stay fresh all day.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="container mx-auto py-12 px-4 bg-white">
        <h2 class="text-3xl font-bold text-dove-blue text-center mb-8">About Us</h2>
        <div class="max-w-3xl mx-auto text-gray-700 leading-relaxed">
            <p class="mb-4">At Infinity Soaps, we believe that scent and self-care go hand in hand. Our journey began with a simple conviction: everyone deserves to feel fresh, confident, and irresistible, every single day. That’s why we’ve brought together the finest soap products and cosmetics from Dove under one roof – your endless source of well-being and beauty.</p>
            <p class="mb-4">Imagine a world where every shower feels like a moment of luxury, every lotion caresses your skin like a gentle breeze, and every scent transports you to a place of calm and joy. That’s what we strive for at Infinity Soaps. We’ve carefully curated the best of Dove’s iconic offerings – from their creamy soaps and nourishing body creams to their refreshing deodorants and more – everything you need to smell divine and feel amazing, from head to toe.</p>
            <p class="mb-4">Our passion goes beyond just selling products; we want to create an experience. Whether you love the classic richness of Dove’s original soap, the subtle freshness of their deodorants, or the silky softness of their lotions, Infinity Soaps has it all. We’re proud to offer official Dove products, a brand that’s been synonymous with quality, care, and trust for decades.</p>
            <p class="mb-4">At Infinity Soaps, it’s all about you. We aim to transform your daily routine into a little ritual of self-love. From the first bubbles in the morning to the final whiff of fragrance before bed, we’re here to make you shine – infinitely.</p>
            <p class="font-semibold">Welcome to Infinity Soaps, where scent, care, and beauty come together. Let’s make the world smell a little better, together!</p>
        </div>
    </section>

    <!-- Order Form -->
    <section id="contact" class="container mx-auto py-12 px-4">
        <h2 class="text-3xl font-bold text-dove-blue text-center mb-8">Place Your Order</h2>
        <form id="orderForm" class="max-w-md mx-auto bg-white p-6 rounded-lg shadow-md space-y-4">
            <div>
                <label for="name" class="block text-dove-blue">Name:</label>
                <input type="text" id="name" class="w-full p-2 border rounded" required>
            </div>
            <div>
                <label for="email" class="block text-dove-blue">Email:</label>
                <input type="email" id="email" class="w-full p-2 border rounded" required>
            </div>
            <div>
                <label for="product" class="block text-dove-blue">Product:</label>
                <select id="product" class="w-full p-2 border rounded" required>
                    <option value="Soap Bars">Soap Bars - $4.99</option>
                    <option value="Body Wash">Body Wash - $7.99</option>
                    <option value="Deodorants">Deodorants - $5.49</option>
                </select>
            </div>
            <div>
                <label for="quantity" class="block text-dove-blue">Quantity:</label>
                <input type="number" id="quantity" min="1" value="1" class="w-full p-2 border rounded" required>
            </div>
            <button type="submit" class="w-full bg-dove-blue text-white py-2 rounded hover:bg-blue-700">Submit Order</button>
        </form>
        <p id="status" class="mt-4 text-green-600 text-center hidden">Order placed successfully!</p>
    </section>

    <!-- Footer -->
    <footer class="dove-blue text-white py-6">
        <div class="container mx-auto text-center">
            <p>© 2025 Infinity Soaps. All rights reserved.</p>
            <div class="mt-2 space-x-4">
                <a href="#" class="hover:underline">Privacy Policy</a>
                <a href="#" class="hover:underline">Terms of Use</a>
                <a href="mailto:support@infinitysoaps.com" class="hover:underline">support@infinitysoaps.com</a>
            </div>
        </div>
    </footer>

    <!-- JavaScript -->
    <script>
        document.getElementById('orderForm').addEventListener('submit', function(event) {
            event.preventDefault();

            // Get form data
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const product = document.getElementById('product').value;
            const quantity = document.getElementById('quantity').value;

            // Simulate order processing
            const order = { name, email, product, quantity: parseInt(quantity) };
            console.log('Order submitted:', order);

            // Show confirmation
            const status = document.getElementById('status');
            status.classList.remove('hidden');
            this.reset(); // Reset form
        });
    </script>
</body>
</html>
​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​
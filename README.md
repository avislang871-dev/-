<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>恒洋物流 - 桌面端设计还原</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .hero-gradient {
            background: linear-gradient(135deg, #1a365d 0%, #2563eb 100%);
        }
        .curved-bottom {
            clip-path: ellipse(80% 100% at 50% 100%);
        }
    </style>
</head>
<body class="bg-gray-50">

    <nav class="flex items-center justify-between px-12 py-4 bg-white sticky top-0 z-50 shadow-sm">
        <div class="flex items-center gap-2">
            <div class="w-10 h-10 bg-blue-700 rounded-full flex items-center justify-center">
                <span class="text-white font-bold text-xs">LOGO</span>
            </div>
            <span class="font-bold text-xl text-blue-900 tracking-tight">My Ever Ocean</span>
        </div>
        <div class="hidden md:flex space-x-8 text-sm font-semibold text-gray-600">
            <a href="#" class="hover:text-blue-600">Solutions</a>
            <a href="#" class="hover:text-blue-600">Product</a>
            <a href="#" class="hover:text-blue-600">Resources</a>
            <a href="#" class="hover:text-blue-600">Blog</a>
            <a href="#" class="hover:text-blue-600">Price Calculator</a>
        </div>
        <button class="bg-[#f97316] text-white px-6 py-2 rounded-md font-bold text-sm shadow-lg hover:bg-orange-600">Get Started</button>
    </nav>

    <header class="hero-gradient text-white pt-24 pb-48 px-6 text-center relative">
        <h1 class="text-5xl md:text-6xl font-bold mb-6 tracking-tight">Simplify Your Logistics <br> From China</h1>
        <p class="text-lg text-blue-100 max-w-2xl mx-auto mb-10 opacity-90">
            Premium 15 years of freight experience, DDP shipping, and door-to-door solutions for Amazon, Walmart, and B2B importers.
        </p>
        <button class="bg-[#f97316] px-10 py-4 rounded-md text-lg font-bold shadow-xl hover:scale-105 transition-transform">Get a Free Quote</button>
        
        <div class="absolute bottom-0 left-0 w-full h-24 bg-gray-50 curved-bottom"></div>
    </header>

    <section class="py-12 bg-gray-50 text-center">
        <p class="text-gray-400 text-xs uppercase tracking-widest mb-10">Trusted by over 3,000+ world-class businesses</p>
        <div class="flex flex-wrap justify-center gap-16 opacity-40 font-bold text-xl text-gray-800">
            <span>Walmart</span>
            <span>Amazon</span>
            <span>Shopify</span>
            <span>eBay</span>
            <span>Alibaba</span>
        </div>
    </section>

    <section class="py-20 px-12 max-w-7xl mx-auto">
        <div class="mb-12">
            <h2 class="text-3xl font-bold text-blue-950 mb-3">Our Shipping Solutions</h2>
            <p class="text-gray-500">Choose the logistics channel that fits your business needs.</p>
        </div>
        <div class="grid md:grid-cols-3 gap-8">
            <div class="bg-[#eef2ff] p-8 rounded-3xl border border-blue-100 group hover:shadow-xl transition">
                <div class="h-44 bg-white rounded-2xl mb-6 shadow-inner"></div>
                <h3 class="font-bold text-xl mb-3 text-blue-900">China to USA</h3>
                <ul class="text-gray-600 text-sm space-y-2 mb-8">
                    <li>• Sea Freight: 15-25 days</li>
                    <li>• Air Freight: 5-8 days</li>
                    <li>• Door-to-Door DDP</li>
                </ul>
                <a href="#" class="text-blue-600 font-bold text-sm group-hover:underline">Learn More →</a>
            </div>
            <div class="bg-[#eef2ff] p-8 rounded-3xl border border-blue-100 group">
                <div class="h-44 bg-white rounded-2xl mb-6 shadow-inner"></div>
                <h3 class="font-bold text-xl mb-3 text-blue-900">China to Canada</h3>
                <ul class="text-gray-600 text-sm space-y-2 mb-8">
                    <li>• Sea/Air DDP Solutions</li>
                    <li>• FBA Specialists</li>
                </ul>
                <a href="#" class="text-blue-600 font-bold text-sm group-hover:underline">Learn More →</a>
            </div>
            <div class="bg-[#eef2ff] p-8 rounded-3xl border border-blue-100 group">
                <div class="h-44 bg-white rounded-2xl mb-6 shadow-inner"></div>
                <h3 class="font-bold text-xl mb-3 text-blue-900">China to UK</h3>
                <ul class="text-gray-600 text-sm space-y-2 mb-8">
                    <li>• VAT Handling</li>
                    <li>• Fast Customs Clearance</li>
                </ul>
                <a href="#" class="text-blue-600 font-bold text-sm group-hover:underline">Learn More →</a>
            </div>
        </div>
    </section>

    <section class="py-24 px-12 bg-white">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-20 items-center">
            <div>
                <h2 class="text-4xl font-bold text-blue-950 mb-6 leading-tight">We turn <span class="text-blue-600">global sourcing</span><br>into seamless logistics</h2>
                <p class="text-gray-500 mb-8 leading-relaxed">Focus on growing your brand while we handle the heavy lifting. We provide real-time tracking and dedicated support to ensure your cargo arrives safely.</p>
                <button class="bg-[#f97316] text-white px-8 py-3 rounded-md font-bold shadow-lg">Get a Quote</button>
            </div>
            <div class="space-y-10">
                <div class="flex gap-5">
                    <div class="w-12 h-12 bg-blue-100 rounded-lg flex-shrink-0 flex items-center justify-center text-blue-600 font-bold">✓</div>
                    <div>
                        <h4 class="font-bold text-blue-900">In-house Land Haulage</h4>
                        <p class="text-gray-500 text-sm mt-1">Our own trucks and trailers ensure timely pickup and delivery across China.</p>
                    </div>
                </div>
                <div class="flex gap-5">
                    <div class="w-12 h-12 bg-blue-100 rounded-lg flex-shrink-0 flex items-center justify-center text-blue-600 font-bold">✓</div>
                    <div>
                        <h4 class="font-bold text-blue-900">Flexible B2B Infrastructure</h4>
                        <p class="text-gray-500 text-sm mt-1">Scaling with your business from small parcels to full containers.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-[#0f172a] py-24 text-white">
        <div class="max-w-5xl mx-auto px-12 text-center">
            <h2 class="text-3xl font-bold mb-16">What Our Clients Say</h2>
            <div class="bg-slate-800/50 p-12 rounded-3xl border border-slate-700 mb-20 relative">
                <span class="text-6xl text-blue-500 absolute top-6 left-10 opacity-30">“</span>
                <p class="text-2xl italic leading-relaxed mb-8">"Their DDP service is completely clutch. They handle the hassle and just give me the price, letting me focus on sales and growing my business."</p>
                <div class="font-bold text-lg text-blue-400">Jeff M.</div>
                <div class="text-xs text-gray-500 uppercase tracking-widest mt-1">Verified Customer</div>
            </div>
            
            <div class="grid grid-cols-2 md:grid-cols-4 gap-12">
                <div><div class="text-4xl font-bold mb-2">7</div><p class="text-gray-500 text-sm">Warehouse Hubs</p></div>
                <div><div class="text-4xl font-bold mb-2">15</div><p class="text-gray-500 text-sm">Years Experience</p></div>
                <div><div class="text-4xl font-bold mb-2">3,000+</div><p class="text-gray-500 text-sm">Total Shipments</p></div>
                <div><div class="text-4xl font-bold mb-2">20,000+</div><p class="text-gray-500 text-sm">Active Members</p></div>
            </div>
        </div>
    </section>

    <section class="max-w-7xl mx-auto px-12 py-20">
        <div class="bg-blue-600 rounded-[2rem] p-16 text-white flex flex-col md:flex-row items-center justify-between shadow-2xl relative overflow-hidden">
            <div class="z-10">
                <h2 class="text-4xl font-bold mb-4">Put us to work as your <br>boots on the ground in China</h2>
                <p class="text-blue-100 opacity-80">Ready to simplify your global sourcing? Get an instant quote today.</p>
            </div>
            <button class="z-10 bg-[#f97316] text-white px-10 py-5 rounded-2xl font-bold text-lg shadow-xl mt-8 md:mt-0 hover:bg-orange-600 transition">Get an Instant Quote</button>
            <div class="absolute -right-20 -bottom-20 w-80 h-80 bg-blue-500 rounded-full opacity-20"></div>
        </div>
    </section>

    <footer class="bg-slate-950 text-slate-400 py-20 px-12">
        <div class="max-w-7xl mx-auto grid grid-cols-2 md:grid-cols-4 gap-12 border-b border-slate-800 pb-16">
            <div class="col-span-2 md:col-span-1">
                <div class="text-white font-bold text-xl mb-6">My Ever Ocean</div>
                <p class="text-sm leading-relaxed">Your reliable logistics partner in China, bridging the gap between global sourcing and efficient delivery.</p>
            </div>
            <div>
                <h5 class="text-white font-bold mb-6 text-sm">Solutions</h5>
                <ul class="space-y-4 text-sm">
                    <li><a href="#" class="hover:text-blue-400">Sea Freight</a></li>
                    <li><a href="#" class="hover:text-blue-400">Air Freight</a></li>
                    <li><a href="#" class="hover:text-blue-400">Amazon FBA</a></li>
                </ul>
            </div>
            <div>
                <h5 class="text-white font-bold mb-6 text-sm">Company</h5>
                <ul class="space-y-4 text-sm">
                    <li><a href="#" class="hover:text-blue-400">About Us</a></li>
                    <li><a href="#" class="hover:text-blue-400">Contact</a></li>
                </ul>
            </div>
            <div>
                <h5 class="text-white font-bold mb-6 text-sm">Social</h5>
                <div class="flex space-x-4">
                    <div class="w-8 h-8 bg-slate-800 rounded-full"></div>
                    <div class="w-8 h-8 bg-slate-800 rounded-full"></div>
                    <div class="w-8 h-8 bg-slate-800 rounded-full"></div>
                </div>
            </div>
        </div>
        <div class="max-w-7xl mx-auto pt-8 text-xs flex justify-between">
            <p>&copy; 2026 My Ever Ocean Logistics. All rights reserved.</p>
            <div class="space-x-6">
                <a href="#">Privacy Policy</a>
                <a href="#">Terms of Service</a>
            </div>
        </div>
    </footer>

</body>
</html>

# Manitoba-Generators
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manitoba Industrial Power | Cummins & Perkins Sales</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-slate-900 font-sans">

    <div class="bg-red-700 text-white py-2 px-6 text-sm font-bold text-center">
        Serving Winnipeg, Brandon, and Northern Manitoba | Industrial & Commercial Unit Sales
    </div>

    <nav class="bg-white border-b border-gray-200 p-6 sticky top-0 z-50">
        <div class="container mx-auto flex justify-between items-center">
            <div class="text-2xl font-black tracking-tighter">MB<span class="text-red-700">POWER</span></div>
            <div class="hidden md:flex space-x-8 font-bold text-sm uppercase">
                <a href="#inventory" class="hover:text-red-700">Cummins Inventory</a>
                <a href="#inventory" class="hover:text-red-700">Perkins Inventory</a>
                <a href="#quote" class="bg-slate-900 text-white px-5 py-2 rounded">Request Quote</a>
            </div>
        </div>
    </nav>

    <header class="bg-slate-900 py-24 text-white">
        <div class="container mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div>
                <h1 class="text-5xl font-black leading-tight mb-6">HEAVY-DUTY POWER FOR THE PRAIRIES.</h1>
                <p class="text-xl text-slate-300 mb-8 text-balance">Direct supply of Cummins and Perkins diesel generators. CSA-approved units ready for site delivery across Manitoba. No installation—just the world's most reliable equipment at competitive rates.</p>
                <div class="flex gap-4">
                    <a href="#inventory" class="bg-red-700 hover:bg-red-800 px-8 py-4 rounded font-bold transition text-center">View Current Stock</a>
                    <a href="#quote" class="bg-white text-slate-900 px-8 py-4 rounded font-bold hover:bg-gray-200 transition text-center">Get Specs</a>
                </div>
            </div>
            <div class="hidden md:block bg-slate-800 h-64 rounded-lg border border-slate-700 flex items-center justify-center italic text-slate-500">
                [High-Res Generator Image]
            </div>
        </div>
    </header>

    <section id="inventory" class="py-20 container mx-auto px-6">
        <div class="grid md:grid-cols-2 gap-12">
            <div class="bg-white border border-gray-200 rounded-xl overflow-hidden shadow-sm hover:shadow-lg transition">
                <div class="bg-red-700 p-4 text-white font-bold uppercase tracking-widest text-sm">Authorized Engine Supply</div>
                <div class="p-8">
                    <h3 class="text-3xl font-black mb-4">CUMMINS SERIES</h3>
                    <p class="text-gray-600 mb-6">The gold standard for hospital standby, data centers, and heavy industrial use in Winnipeg.</p>
                    <ul class="space-y-3 mb-8 font-medium">
                        <li class="flex items-center">✅ 50kW - 2000kW Units</li>
                        <li class="flex items-center">✅ Cold-Weather Protection Packages</li>
                        <li class="flex items-center">✅ PowerCommand Control Systems</li>
                    </ul>
                    <a href="#quote" class="block text-center border-2 border-slate-900 py-3 rounded font-bold hover:bg-slate-900 hover:text-white transition">Request Cummins Specs</a>
                </div>
            </div>

            <div class="bg-white border border-gray-200 rounded-xl overflow-hidden shadow-sm hover:shadow-lg transition">
                <div class="bg-blue-800 p-4 text-white font-bold uppercase tracking-widest text-sm">Authorized Engine Supply</div>
                <div class="p-8">
                    <h3 class="text-3xl font-black mb-4">PERKINS SERIES</h3>
                    <p class="text-gray-600 mb-6">Maximum fuel efficiency and rugged durability for Manitoba agriculture and off-grid mining.</p>
                    <ul class="space-y-3 mb-8 font-medium">
                        <li class="flex items-center">✅ 10kW - 1000kW Units</li>
                        <li class="flex items-center">✅ Simplified Maintenance Design</li>
                        <li class="flex items-center">✅ Exceptional Parts Availability</li>
                    </ul>
                    <a href="#quote" class="block text-center border-2 border-slate-900 py-3 rounded font-bold hover:bg-slate-900 hover:text-white transition">Request Perkins Specs</a>
                </div>
            </div>
        </div>
    </section>

    <section id="quote" class="py-20 bg-slate-100 border-t border-gray-200">
        <div class="container mx-auto px-6 max-w-3xl">
            <div class="bg-white p-10 rounded-2xl shadow-xl">
                <h2 class="text-3xl font-black mb-2 uppercase text-center">Technical Inquiry Form</h2>
                <p class="text-center text-gray-500 mb-8">Receive a detailed spec sheet and quote within 24 hours.</p>
                
                <form action="https://formspree.io/f/YOUR_EMAIL_ID" method="POST" class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div>
                        <label class="block text-xs font-bold uppercase mb-2">Required kW Range</label>
                        <select name="kw" class="w-full border p-3 rounded bg-gray-50">
                            <option>Under 100kW</option>
                            <option>100kW - 500kW</option>
                            <option>500kW - 1000kW</option>
                            <option>1000kW+</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-xs font-bold uppercase mb-2">Voltage Required</label>
                        <select name="voltage" class="w-full border p-3 rounded bg-gray-50">
                            <option>600V (Standard Industrial)</option>
                            <option>480V</option>
                            <option>208V / 240V</option>
                        </select>
                    </div>
                    <div class="md:col-span-2">
                        <label class="block text-xs font-bold uppercase mb-2">Full Name & Company</label>
                        <input type="text" name="name" placeholder="Contact Name" class="w-full border p-3 rounded" required>
                    </div>
                    <div class="md:col-span-2">
                        <label class="block text-xs font-bold uppercase mb-2">Email Address</label>
                        <input type="email" name="email" placeholder="email@company.com" class="w-full border p-3 rounded" required>
                    </div>
                    <div class="md:col-span-2 text-center">
                        <button type="submit" class="bg-red-700 text-white w-full py-4 rounded font-black text-lg hover:bg-red-800 transition">REQUEST QUOTE & DRAWINGS</button>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <footer class="bg-slate-900 text-slate-500 py-12 text-center">
        <p>&copy; 2026 Manitoba Power Sales. All Units CSA Approved.</p>
    </footer>

</body>
</html>

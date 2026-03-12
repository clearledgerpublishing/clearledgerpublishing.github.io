<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>New Release | Independent Publishing Co.</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        h1, h2, .serif { font-family: 'Playfair Display', serif; }
    </style>
</head>
<body class="bg-stone-50 text-stone-900">

    <nav class="p-6 flex justify-between items-center border-b border-stone-200 bg-white">
        <div class="text-xl font-bold tracking-tighter serif italic">The Indigo Press</div>
        <div class="space-x-8 text-sm uppercase tracking-widest font-semibold text-stone-600">
            <a href="#" class="hover:text-black">Catalog</a>
            <a href="#" class="hover:text-black">Authors</a>
            <a href="#" class="hover:text-black">About</a>
        </div>
    </nav>

    <main class="max-w-6xl mx-auto px-6 py-12 md:py-24">
        <div class="grid md:grid-cols-2 gap-16 items-center">
            
            <div class="flex justify-center">
                <div class="relative group">
                    <div class="w-72 h-[450px] bg-stone-800 shadow-2xl transform transition-transform group-hover:-rotate-2 duration-500 flex items-center justify-center text-stone-500 p-8 text-center border-l-4 border-stone-700">
                        <span class="serif italic text-2xl text-stone-300">Insert Book Cover Image Here</span>
                    </div>
                    <div class="absolute -bottom-4 -right-4 w-72 h-[450px] border border-stone-200 -z-10"></div>
                </div>
            </div>

            <div class="space-y-6">
                <div class="inline-block px-3 py-1 border border-amber-600 text-amber-700 text-xs font-bold uppercase tracking-widest">
                    New Release • Spring 2026
                </div>
                <h1 class="text-5xl md:text-6xl leading-tight">The Silence of the Inkwell</h1>
                <p class="text-xl italic text-stone-600 serif">By Elena Thorne</p>
                
                <p class="text-lg leading-relaxed text-stone-700 max-w-md">
                    A haunting exploration of lost manuscripts and the ghosts who write them. Thorne's latest masterpiece redefines the boundaries of modern gothic fiction.
                </p>

                <div class="pt-4 flex flex-col sm:flex-row gap-4">
                    <a href="#" class="bg-stone-900 text-white px-8 py-4 text-center font-bold hover:bg-stone-700 transition">
                        Order Hardcover — $28
                    </a>
                    <a href="#" class="border border-stone-900 text-stone-900 px-8 py-4 text-center font-bold hover:bg-stone-100 transition">
                        Read an Excerpt
                    </a>
                </div>

                <div class="pt-8 border-t border-stone-200">
                    <p class="text-xs uppercase tracking-widest text-stone-400 font-bold">Available At</p>
                    <div class="flex gap-6 mt-2 grayscale opacity-60">
                        <span class="text-sm font-semibold italic">Bookshop.org</span>
                        <span class="text-sm font-semibold italic">Kindle</span>
                        <span class="text-sm font-semibold italic">Audible</span>
                    </div>
                </div>
            </div>

        </div>
    </main>

    <footer class="bg-stone-900 text-stone-400 py-12 px-6 text-center">
        <p class="text-sm tracking-widest uppercase">© 2026 The Indigo Press. Built for the curious reader.</p>
    </footer>

</body>
</html>

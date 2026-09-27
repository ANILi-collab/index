# index
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time Neuro Care & Pain Clinic | Dr. Vikrant Singh Thakur | Karimnagar</title>
    <meta name="description" content="Specialist Neurology and Pain Clinic in Karimnagar led by Dr. Vikrant Singh Thakur (MD, DM Neuro). Expert care for Migraine, Stroke, Spine Pain, and Epilepsy.">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        medicalNavy: '#0B2545',
                        slateBlue: '#1363DF',
                        whatsappGreen: '#25D366',
                        lightSlate: '#F8FAFC',
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                }
            }
        }
    </script>

    <style>
        .glass-effect {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
        }
        .step-number {
            font-variant-numeric: tabular-nums;
        }
    </style>
</head>
<body class="bg-lightSlate text-medicalNavy font-sans antialiased">

    <!-- Top Notice Strip -->
    <div class="bg-medicalNavy text-white py-2.5 px-4 text-center text-xs md:text-sm font-medium border-b border-white/10">
        <div class="container mx-auto">
            <span class="inline-block mr-2">📢</span> 
            <strong>Important:</strong> Sunday appointment slots open at 4:00 PM sharp. Weekday queries: 8:00 AM – 10:00 AM.
        </div>
    </div>

    <!-- Navigation -->
    <nav class="sticky top-0 z-50 glass-effect border-b border-slate-200">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex flex-col">
                <h1 class="text-lg md:text-xl font-extrabold tracking-tight leading-none text-medicalNavy">
                    TIME NEURO <span class="text-slateBlue">CARE</span>
                </h1>
                <p class="text-[10px] md:text-xs font-semibold uppercase tracking-wider text-slate-500">Hospital & Pain Clinic</p>
            </div>
            
            <div class="flex items-center gap-3">
                <a href="tel:+919908248384" class="hidden md:flex items-center gap-2 bg-slate-100 hover:bg-slate-200 text-medicalNavy px-4 py-2 rounded-full text-sm font-bold transition-all">
                    <i class="fa-solid fa-phone"></i>
                    99082 48384
                </a>
                <a href="https://wa.me/919908248384?text=Hello%20Time%20Neuro%20Care,%20I%20want%20to%20inquire%20about%20an%20OPD%20appointment" 
                   class="bg-whatsappGreen hover:bg-emerald-600 text-white px-4 py-2 rounded-full text-sm font-bold shadow-lg shadow-emerald-200 transition-all flex items-center gap-2">
                    <i class="fa-brands fa-whatsapp text-lg"></i>
                    <span class="hidden sm:inline">Book Appointment</span>
                    <span class="sm:hidden">Book Now</span>
                </a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative pt-12 pb-16 md:pt-20 md:pb-28 overflow-hidden">
        <div class="container mx-auto px-4 relative z-10">
            <div class="max-w-4xl mx-auto text-center">
                <span class="inline-block bg-slateBlue/10 text-slateBlue text-xs md:text-sm font-bold tracking-widest uppercase px-4 py-1.5 rounded-full mb-6">
                    Super-Specialty Neurology & Interventional Pain Clinic
                </span>
                <h2 class="text-3xl md:text-6xl font-black text-medicalNavy mb-6 leading-[1.1]">
                    Advanced Neurological Care & Precision <span class="text-slateBlue">Pain Relief</span> in Karimnagar
                </h2>
                <p class="text-lg md:text-xl text-slate-600 mb-10 max-w-2xl mx-auto leading-relaxed">
                    Comprehensive consultation with <strong>Dr. Vikrant Singh Thakur</strong> (MD, DM Neuro). Experience expert diagnosis with structured slot bookings and zero waiting room confusion.
                </p>
                <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                    <a href="https://wa.me/919908248384?text=Hello%20Time%20Neuro%20Care,%20I%20want%20to%20inquire%20about%20an%20OPD%20appointment" 
                       class="w-full sm:w-auto bg-whatsappGreen hover:bg-emerald-600 text-white text-lg font-bold px-8 py-4 rounded-xl shadow-xl shadow-emerald-100 flex items-center justify-center gap-3 transition-transform hover:scale-105">
                        <i class="fa-brands fa-whatsapp text-2xl"></i>
                        Book via WhatsApp
                    </a>
                    <a href="#timings" class="w-full sm:w-auto bg-white border-2 border-slate-200 hover:border-slateBlue text-medicalNavy text-lg font-bold px-8 py-4 rounded-xl flex items-center justify-center gap-3 transition-all">
                        <i class="fa-solid fa-clock"></i>
                        Check OPD Timings
                    </a>
                </div>
            </div>
        </div>
        <!-- Decorative Background Element -->
        <div class="absolute top-0 left-1/2 -translate-x-1/2 w-full h-full -z-0 opacity-10 pointer-events-none">
            <svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg" class="w-full h-full">
                <path fill="#1363DF" d="M44.7,-76.4C58.3,-69.2,70,-57.9,78.5,-44.4C87,-30.9,92.3,-15.5,91.2,-0.6C90.1,14.2,82.5,28.4,73.4,41C64.3,53.6,53.6,64.6,40.7,72.5C27.7,80.4,12.5,85.2,-2.4,89.3C-17.3,93.4,-32.1,96.8,-45.5,91.1C-58.8,85.3,-70.7,70.5,-78.9,54.8C-87,39.1,-91.4,22.6,-91.8,6.1C-92.3,-10.5,-88.7,-27,-80,-41.3C-71.3,-55.6,-57.4,-67.7,-42.2,-74.1C-27,-80.5,-13.5,-81.1,1.1,-83C15.6,-84.9,31.2,-83.6,44.7,-76.4Z" transform="translate(100 100)" />
            </svg>
        </div>
    </header>

    <!-- Appointment Steps Section -->
    <section class="py-16 bg-white border-y border-slate-100">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h3 class="text-2xl md:text-3xl font-bold mb-2">How Appointments Work</h3>
                <p class="text-slate-500">Simple 3-step process for a seamless visit</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Step 1 -->
                <div class="relative p-8 rounded-2xl bg-lightSlate border border-slate-100">
                    <span class="absolute -top-4 -left-4 w-12 h-12 bg-medicalNavy text-white rounded-xl flex items-center justify-center font-bold text-xl shadow-lg">1</span>
                    <h4 class="text-xl font-bold mb-3 mt-2">Timing is Key</h4>
                    <p class="text-slate-600 leading-relaxed">
                        Book Sunday slots every <strong>Sunday at 4:00 PM</strong> sharp. For weekday inquiries, call between <strong>8:00 AM – 10:00 AM</strong>.
                    </p>
                </div>
                <!-- Step 2 -->
                <div class="relative p-8 rounded-2xl bg-lightSlate border border-slate-100">
                    <span class="absolute -top-4 -left-4 w-12 h-12 bg-slateBlue text-white rounded-xl flex items-center justify-center font-bold text-xl shadow-lg">2</span>
                    <h4 class="text-xl font-bold mb-3 mt-2">Share Medical Data</h4>
                    <p class="text-slate-600 leading-relaxed">
                        Send patient name, complaints, and previous <strong>MRI/CT scans</strong> directly via WhatsApp for doctor's prior review.
                    </p>
                </div>
                <!-- Step 3 -->
                <div class="relative p-8 rounded-2xl bg-lightSlate border border-slate-100">
                    <span class="absolute -top-4 -left-4 w-12 h-12 bg-whatsappGreen text-white rounded-xl flex items-center justify-center font-bold text-xl shadow-lg">3</span>
                    <h4 class="text-xl font-bold mb-3 mt-2">Get Your Token</h4>
                    <p class="text-slate-600 leading-relaxed">
                        Receive a direct token number and your expected arrival time from our front desk. No unnecessary waiting at the clinic.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Clinical Specialties -->
    <section class="py-20">
        <div class="container mx-auto px-4">
            <div class="max-w-2xl mx-auto text-center mb-16">
                <h3 class="text-3xl md:text-4xl font-bold mb-4">Specialized Neuro-Care</h3>
                <p class="text-slate-600">Expert diagnosis and management for complex brain, spine, and nerve disorders.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Specialty 1 -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 hover:shadow-md transition-shadow">
                    <div class="w-12 h-12 bg-red-50 text-red-500 rounded-lg flex items-center justify-center mb-4 text-xl">
                        <i class="fa-solid fa-head-side-virus"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-2">Migraine & Headaches</h4>
                    <p class="text-slate-600 text-sm leading-relaxed">Advanced relief for chronic migraines and intractable headache disorders.</p>
                </div>
                <!-- Specialty 2 -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 hover:shadow-md transition-shadow">
                    <div class="w-12 h-12 bg-blue-50 text-blue-500 rounded-lg flex items-center justify-center mb-4 text-xl">
                        <i class="fa-solid fa-brain"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-2">Stroke & Paralysis</h4>
                    <p class="text-slate-600 text-sm leading-relaxed">Comprehensive post-stroke rehabilitation and paralysis management.</p>
                </div>
                <!-- Specialty 3 -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 hover:shadow-md transition-shadow">
                    <div class="w-12 h-12 bg-indigo-50 text-indigo-500 rounded-lg flex items-center justify-center mb-4 text-xl">
                        <i class="fa-solid fa-bone"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-2">Spine & Sciatica</h4>
                    <p class="text-slate-600 text-sm leading-relaxed">Precision interventional relief for sciatica, back pain, and neuropathic pain.</p>
                </div>
                <!-- Specialty 4 -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 hover:shadow-md transition-shadow">
                    <div class="w-12 h-12 bg-yellow-50 text-yellow-600 rounded-lg flex items-center justify-center mb-4 text-xl">
                        <i class="fa-solid fa-bolt-lightning"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-2">Epilepsy & Seizures</h4>
                    <p class="text-slate-600 text-sm leading-relaxed">Modern management of seizure disorders, fits, and tremors.</p>
                </div>
                <!-- Specialty 5 -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 hover:shadow-md transition-shadow">
                    <div class="w-12 h-12 bg-purple-50 text-purple-500 rounded-lg flex items-center justify-center mb-4 text-xl">
                        <i class="fa-solid fa-moon"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-2">Sleep & Vertigo</h4>
                    <p class="text-slate-600 text-sm leading-relaxed">Effective treatment for sleep disturbances, giddiness, and balance issues.</p>
                </div>
                <!-- Specialty 6 -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 hover:shadow-md transition-shadow">
                    <div class="w-12 h-12 bg-emerald-50 text-emerald-500 rounded-lg flex items-center justify-center mb-4 text-xl">
                        <i class="fa-solid fa-user-clock"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-2">Dementia & Parkinson's</h4>
                    <p class="text-slate-600 text-sm leading-relaxed">Specialized geriatric care for memory loss and movement disorders.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Doctor Profile Card -->
    <section class="py-20 bg-slateBlue/5">
        <div class="container mx-auto px-4">
            <div class="max-w-5xl mx-auto bg-white rounded-3xl overflow-hidden shadow-xl flex flex-col md:flex-row border border-slate-100">
                <div class="md:w-1/3 bg-medicalNavy flex items-center justify-center p-12 text-white">
                    <div class="text-center">
                        <div class="w-32 h-32 md:w-40 md:h-40 bg-white/10 rounded-full flex items-center justify-center mb-6 mx-auto border-4 border-white/20">
                            <i class="fa-solid fa-user-doctor text-6xl text-white/90"></i>
                        </div>
                        <h4 class="text-2xl font-bold">Dr. Vikrant Singh Thakur</h4>
                        <p class="text-blue-200 font-medium">MD, DM Neuro</p>
                    </div>
                </div>
                <div class="md:w-2/3 p-8 md:p-12">
                    <h3 class="text-2xl md:text-3xl font-bold mb-6 text-medicalNavy leading-tight">Expert Neurologist Focused on Evidence-Based Care</h3>
                    <p class="text-slate-600 text-lg mb-6 leading-relaxed">
                        Dr. Vikrant Singh Thakur is a highly qualified Consultant Neurologist dedicated to providing precise, evidence-based neurocare. With advanced degrees in Medicine and Neurology (MD, DM), he combines clinical expertise with a compassionate approach to patient consultation.
                    </p>
                    <div class="space-y-4">
                        <div class="flex items-start gap-4">
                            <div class="w-6 h-6 bg-slateBlue/10 rounded-full flex items-center justify-center mt-1 shrink-0">
                                <i class="fa-solid fa-check text-slateBlue text-xs"></i>
                            </div>
                            <p class="text-slate-700 font-medium">Precision-driven diagnosis using latest neuro-imaging protocols.</p>
                        </div>
                        <div class="flex items-start gap-4">
                            <div class="w-6 h-6 bg-slateBlue/10 rounded-full flex items-center justify-center mt-1 shrink-0">
                                <i class="fa-solid fa-check text-slateBlue text-xs"></i>
                            </div>
                            <p class="text-slate-700 font-medium">Patient-centric communication ensuring clarity in treatment paths.</p>
                        </div>
                        <div class="flex items-start gap-4">
                            <div class="w-6 h-6 bg-slateBlue/10 rounded-full flex items-center justify-center mt-1 shrink-0">
                                <i class="fa-solid fa-check text-slateBlue text-xs"></i>
                            </div>
                            <p class="text-slate-700 font-medium">Specialized in interventional pain relief techniques.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Clinic Location & Hours Section -->
    <section id="timings" class="py-20">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-2 gap-12 items-start">
                <!-- Location -->
                <div>
                    <h3 class="text-3xl font-bold mb-8">Visit the Clinic</h3>
                    <div class="bg-white p-8 rounded-3xl border border-slate-100 shadow-sm">
                        <div class="flex items-start gap-4 mb-6">
                            <div class="w-12 h-12 bg-slate-100 rounded-xl flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-location-dot text-slateBlue text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg mb-1">Our Address</h4>
                                <p class="text-slate-600 leading-relaxed">
                                    Near ND Complex, Old Employment Office Lane,<br>
                                    Doctor Street, Karimnagar,<br>
                                    Telangana 505001
                                </p>
                            </div>
                        </div>
                        <div class="flex items-start gap-4 mb-8">
                            <div class="w-12 h-12 bg-slate-100 rounded-xl flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-phone text-slateBlue text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-lg mb-1">Reception Contact</h4>
                                <p class="text-slate-600 text-xl font-bold">+91 99082 48384</p>
                            </div>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=Time+Neuro+Care+and+Pain+Clinic+Karimnagar" target="_blank"
                           class="inline-flex items-center gap-2 bg-medicalNavy text-white px-6 py-3 rounded-xl font-bold hover:bg-slate-800 transition-all">
                            <i class="fa-solid fa-map-location-dot"></i>
                            Open in Google Maps
                        </a>
                    </div>
                </div>

                <!-- Hours -->
                <div>
                    <h3 class="text-3xl font-bold mb-8">OPD Timings</h3>
                    <div class="bg-white rounded-3xl border border-slate-100 shadow-sm overflow-hidden">
                        <table class="w-full text-left border-collapse">
                            <thead>
                                <tr class="bg-slate-50">
                                    <th class="p-4 md:p-6 font-bold text-medicalNavy border-b border-slate-100">Day</th>
                                    <th class="p-4 md:p-6 font-bold text-medicalNavy border-b border-slate-100">Morning Slot</th>
                                    <th class="p-4 md:p-6 font-bold text-medicalNavy border-b border-slate-100">Evening Slot</th>
                                </tr>
                            </thead>
                            <tbody class="text-slate-600">
                                <tr>
                                    <td class="p-4 md:p-6 border-b border-slate-50 font-semibold">Mon – Sat</td>
                                    <td class="p-4 md:p-6 border-b border-slate-50">10:00 AM - 1:30 PM</td>
                                    <td class="p-4 md:p-6 border-b border-slate-50">6:00 PM - 8:30 PM</td>
                                </tr>
                                <tr class="bg-blue-50/50">
                                    <td class="p-4 md:p-6 border

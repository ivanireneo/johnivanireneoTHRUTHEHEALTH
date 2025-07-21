
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ThruTheHealth | Virtual Healthcare Solutions</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        :root {
            --primary: #2563eb;
            --primary-dark: #1d4ed8;
            --secondary: #0f172a;
            --accent: #f43f5e;}
        body {
            font-family: 'Inter', sans-serif;
            overflow-x: hidden; }
        .hero-gradient {
            background: linear-gradient(135deg, rgba(37, 99, 235, 0.1) 0%, rgba(244, 63, 94, 0.05) 100%);}
       
        .appointment-card {
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }
       
        .appointment-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
        }


        .nav-link {
            position: relative;
        }
       
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -2px;
            left: 0;
            background-color: var(--primary);
            transition: width 0.3s ease;
        }
       
        .nav-link:hover::after {
            width: 100%;
        }
       
        input:focus, textarea:focus {
            outline: 2px solid var(--primary);
            outline-offset: 2px;
        }
       
        .testimonial-card {
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="bg-gray-50">
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <div class="w-10 h-10 bg-blue-600 rounded-lg flex items-center justify-center">
                    <i class="fas fa-heartbeat text-white text-xl"></i>
                </div>
                <span class="text-2xl font-bold text-gray-800">ThruThe<span class="text-blue-600">Health</span></span>
            </div>
           
            <nav class="hidden md:flex space-x-8">
                <a href="#" class="nav-link text-gray-600 hover:text-blue-600 font-medium">Home</a>
                <a href="#services" class="nav-link text-gray-600 hover:text-blue-600 font-medium">Services</a>
                <a href="#about" class="nav-link text-gray-600 hover:text-blue-600 font-medium">About</a>
                <a href="#contact" class="nav-link text-gray-600 hover:text-blue-600 font-medium">Contact</a>
            </nav>
           
            <div class="flex items-center space-x-4">
                <a href="#appointment" class="hidden sm:inline-block bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-lg font-medium transition duration-300">Book Appointment</a>
                <button class="md:hidden text-gray-600 focus:outline-none">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
        </div>
    </header>


    <section class="hero-gradient py根-16 md:py-24">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-12 md:mb-0">
                    <h1 class="text-4xl md:text-5xl font-extrabold text-gray-800 mb-6 leading-tight">
                        Quality Healthcare <span class="text-blue-600">From Anywhere</span>
                    </h1>
                    <p class="text-lg text-gray-600 mb-8">
                        Connect with board-certified doctors instantly through our secure telehealth platform. Get diagnosed, treated, and prescribed without leaving your home.
                    </p>
                    <section id="about" class="py-16 bg-white">
    <div class="container mx-auto px-4">
        <div class="text-center mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-4">About <span class="text-blue-600">ThruTheHealth</span></h2>
            <p class="text-gray-600 max-w-2xl mx-auto">Learn more about who we are and what drives us to deliver better healthcare—digitally.</p>
        </div>
        <div class="max-w-4xl mx-auto">
            <div class="mb-12">
                <h3 class="text-2xl font-semibold text-blue-600 mb-4"> Mission</h3>
                <p class="text-gray-700 text-lg leading-relaxed">
                    At ThruTheHealth, our mission is to bridge the gap between patients and quality healthcare through fast, friendly, and reliable telehealth services. We are committed to delivering compassionate care with a click—making health consultations accessible anytime, anywhere, without the wait or the worry.
                </p>
            </div>


            <div>
                <h3 class="text-2xl font-semibold text-blue-600 mb-4"> Vision</h3>
                <p class="text-gray-700 text-lg leading-relaxed">
                    We envision a future where healthcare is no longer limited by distance, delay, or difficulty. ThruTheHealth aims to be the go-to virtual health companion—empowering people to take control of their well-being through humor, humanity, and high-quality medical support at their fingertips.
                </p>
            </div>
        </div>
    </div>
</section>
                    <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                        <a href="#appointment" class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-lg font-medium text-center transition duration-300">
                            Book Virtual Visit
                        </a>
                        <a href="#how-it-works" class="border border-blue-600 text-blue-600 hover:bg-blue-50 px-6 py-3 rounded-lg font-medium text-center transition duration-300">
                            How It Works
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <section class="bg-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="p-4">
                    <div class="text-blue-600 text-4xl font-bold mb-2">10,000+</div>
                    <div class="text-gray-600">Patients Served</div>
                </div>
                <div class="p-4">
                    <div class="text-blue-600 text-4xl font-bold mb-2">150+</div>
                    <div class="text-gray-600">Licensed Doctors</div>
                </div>
                <div class="p-4">
                    <div class="text-blue-600 text-4xl font-bold mb-2">24/7</div>
                    <div class="text-gray-600">Availability</div>
                </div>
                <div class="p-4">
                    <div class="text-blue-600 text-4xl font-bold mb-2">98%</div>
                    <div class="text-gray-600">Satisfaction Rate</div>
                </div>
            </div>
        </div>
    </section>


    <section id="services" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Our <span class="text-blue-600">Telehealth</span> Services</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Comprehensive virtual care for all your healthcare needs</p>
            </div>
           
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white rounded-xl p-8 appointment-card">
                    <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-user-md text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">General Consultations</h3>
                    <p class="text-gray-600 mb-4">Discuss symptoms, get diagnoses, and receive treatment plans for common health concerns.</p>
                    <a href="#" class="text-blue-600 font-medium flex items-center">
                        Learn More
                        <i class="fas fa-chevron-right ml-2 text-sm"></i>
                    </a>
                </div>
               
                <div class="bg-white rounded-xl p-8 appointment-card">
                    <div class="w-16 h-16 bg-pink-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-prescription-bottle-alt text-pink-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Prescription Refills</h3>
                    <p class="text-gray-600 mb-4">Get your medications refilled without visiting a pharmacy. Electronic prescriptions sent directly.</p>
                    <a href="#" class="text-blue-600 font-medium flex items-center">
                        Learn More
                        <i class="fas fa-chevron-right ml-2 text-sm"></i>
                    </a>
                </div>
               
                <div class="bg-white rounded-xl p-8 appointment-card">
                    <div class="w-16 h-16 bg-green-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-heart text-green-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Chronic Care Management</h3>
                    <p class="text-gray-600 mb-4">Ongoing support and monitoring for conditions like diabetes, hypertension, and more.</p>
                    <a href="#" class="text-blue-600 font-medium flex items-center">
                        Learn More
                        <i class="fas fa-chevron-right ml-2 text-sm"></i>
                    </a>
                </div>
               
                <div class="bg-white rounded-xl p-8 appointment-card">
                    <div class="w-16 h-16 bg-purple-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-brain text-purple-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Mental Health Therapy</h3>
                    <p class="text-gray-600 mb-4">Licensed therapists available for counseling and mental health support via secure video.</p>
                    <a href="#" class="text-blue-600 font-medium flex items-center">
                        Learn More
                        <i class="fas fa-chevron-right ml-2 text-sm"></i>
                    </a>
                </div>
               
                <div class="bg-white rounded-xl p-8 appointment-card">
                    <div class="w-16 h-16 bg-yellow-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-baby text-yellow-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Pediatric Care</h3>
                    <p class="text-gray-600 mb-4">Pediatricians available to discuss your child's health concerns, growth, and development.</p>
                    <a href="#" class="text-blue-600 font-medium flex items-center">
                        Learn More
                        <i class="fas fa-chevron-right ml-2 text-sm"></i>
                    </a>
                </div>
               
                <div class="bg-white rounded-xl p-8 appointment-card">
                    <div class="w-16 h-16 bg-indigo-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-file-medical text-indigo-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Second Opinions</h3>
                    <p class="text-gray-600 mb-4">Get expert second opinions on diagnoses and treatment plans from our specialist network.</p>
                    <a href="#" class="text-blue-600 font-medium flex items-center">
                        Learn More
                        <i class="fas fa-chevron-right ml-2 text-sm"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>
    <section id="how-it-works" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">How Our <span class="text-blue-600">Telehealth</span> Works</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Simple steps to connect with healthcare professionals</p>
            </div>
           
            <div class="flex flex-col md:flex-row justify-center items-center space-y-12 md:space-y-0 md:space-x-8 lg:space-x-12">
                <div class="flex flex-col items-center text-center max-w-xs">
                    <div class="w-20 h-20 bg-blue-100 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-user-plus text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">1. Create Your Account</h3>
                    <p class="text-gray-600">Sign up with your basic information and medical history for faster service.</p>
                </div>
               
                <div class="hidden md:block">
                    <i class="fas fa-chevron-right text-gray-300 text-2xl"></i>
                </div>
               
                <div class="flex flex-col items-center text-center max-w-xs">
                    <div class="w-20 h-20 bg-blue-100 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-calendar-check text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">2. Book Appointment</h3>
                    <p class="text-gray-600">Select your preferred doctor and time slot that works for you.</p>
                </div>
               
                <div class="hidden md:block">
                    <i class="fas fa-chevron-right text-gray-300 text-2xl"></i>
                </div>
               
                <div class="flex flex-col items-center text-center max-w-xs">
                    <div class="w-20 h-20 bg-blue-100 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-video text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">3. Video Consultation</h3>
                    <p class="text-gray-600">Connect via secure video at your appointment time from any device.</p>
                </div>
               
                <div class="hidden md:block">
                    <i class="fas fa-chevron-right text-gray-300 text-2xl"></i>
                </div>
               
                <div class="flex flex-col items-center text-center max-w-xs">
                    <div class="w-20 h-20 bg-blue-100 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-pills text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">4. Receive Care</h3>
                    <p class="text-gray-600">Get diagnosis, treatment plan, and prescriptions if needed.</p>
                </div>
            </div>
        </div>
    </section>


    <section id="appointment" class="py-16 bg-blue-600 text-black">
        <div class="container mx-auto px-4">
            <div class="flex flex-col lg:flex-row items-center">
                <div class="lg:w-1/2 mb-12 lg:mb-0 lg:pr-12">
                    <h2 class="text-3xl font-bold mb-6">Ready For Your <span class="text-white">Virtual Visit?</span></h2>
                    <p class="text-blue-200 mb-8">Our telehealth platform makes it easy to get quality healthcare from the comfort of your home. Schedule your appointment today.</p>
                   
                    <div class="bg-white rounded-lg p-6 shadow-lg">
                        <div class="flex items-center mb-6">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-check text-blue-600 text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold text-gray-800">Insurance Accepted</h3>
                                <p class="text-gray-600 text-sm">Most major insurance plans covered</p>
                            </div>
                        </div>
                       
                        <div class="flex items-center mb-6">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-check text-blue-600 text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold text-gray-800">Same-Day Appointments</h3>
                                <p class="text-gray-600 text-sm">Available for urgent care needs</p>
                            </div>
                        </div>
                       
                        <div class="flex items-center">
                            <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                <i class="fas fa-check text-blue-600 text-xl"></i>
                            </div>
                            <div>
                                <h3 class="font-semibold text-gray-800">Simple Two-Minute Signup</h3>
                                <p class="text-gray-600 text-sm">Get started in no time</p>
                            </div>
                        </div>
                    </div>
                </div>
               
                <div class="lg:w-1/2">
                    <form class="bg-white rounded-xl p-8 shadow-lg">
                        <h3 class="text-2xl font-bold text-gray-800 mb-6">Book Your Appointment</h3>
                       
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
                            <div>
                                <label for="first-name" class="block text-gray-700 font-medium mb-2">First Name</label>
                                <input type="text" id="first-name" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 transition duration-300" placeholder="John">
                            </div>
                            <div>
                                <label for="last-name" class="block text-gray-700 font-medium mb-2">Last Name</label>
                                <input type="text" id="last-name" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 transition duration-300" placeholder="Doe">
                            </div>
                        </div>
                       
                        <div class="mb-6">
                            <label for="email" class="block text-gray-700 font-medium mb-2">Email Address</label>
                            <input type="email" id="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 transition duration-300" placeholder="john@example.com">
                        </div>
                       
                        <div class="mb-6">
                            <label for="phone" class="block text-gray-700 font-medium mb-2">Phone Number</label>
                            <input type="tel" id="phone" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 transition duration-300" placeholder="(123) 456-7890">
                        </div>
                       
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
                            <div>
                                <label for="doctor" class="block text-gray-700 font-medium mb-2">Select Doctor</label>
                                <select id="doctor" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 transition duration-300">
                                    <option value="">Any Available Doctor</option>
                                    <option value="1">Dr. Sarah Johnson (Family Medicine)</option>
                                    <option value="2">Dr. Michael Chen (Cardiology)</option>
                                    <option value="3">Dr. Priya Patel (Pediatrics)</option>
                                    <option value="4">Dr. James Wilson (Psychiatry)</option>
                                </select>
                            </div>
                            <div>
                                <label for="date" class="block text-gray-700 font-medium mb-2">Preferred Date</label>
                                <input type="date" id="date" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 transition duration-300">
                            </div>
                        </div>
                       
                        <div class="mb-8">
                            <label for="reason" class="block text-gray-700 font-medium mb-2">Reason for Visit</label>
                            <textarea id="reason" rows="3" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500 transition duration-300" placeholder="Briefly describe your symptoms or concerns"></textarea>
                        </div>
                       
                        <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white py-3 rounded-lg font-medium transition duration-300 shadow-md">
                            Book Virtual Appointment
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>


    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">What Our <span class="text-blue-600">Patients</span> Say</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Trusted by thousands of patients across the country</p>
            </div>
           
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-8 rounded-lg testimonial-card">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full overflow-hidden mr-4"></div>
                       
                        <div>
                            <h4 class="font-semibold text-gray-800">David Rivera</h4>
                            <div class="flex items-center text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"The convenience of telehealth has changed my life. As someone with a busy schedule and mobility issues, being able to consult with my doctor from home is incredible. The video quality is excellent and I never feel rushed."</p>
                </div>
               
                <div class="bg-gray-50 p-8 rounded-lg testimonial-card">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full overflow-hidden mr-4"></div>
                        <div>
                            <h4 class="font-semibold text-gray-800">Jennifer Kim</h4>
                            <div class="flex items-center text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"I was skeptical about virtual care at first, but my experience with HealthConnect was better than most in-person visits. The doctor listened carefully, explained everything clearly, and my prescription was at my pharmacy within an hour."</p>
                </div>
               
                <div class="bg-gray-50 p-8 rounded-lg testimonial-card">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full overflow-hidden mr-4"></div>
                        <div>
                            <h4 class="font-semibold text-gray-800">Marcus Thompson</h4>
                            <div class="flex items-center text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"Living in a rural area, specialist care used to mean a 3-hour drive. Now I can get second opinions from top doctors across the country. The platform is easy to use even for someone like me who's not tech-savvy."</p>
                </div>
            </div>
        </div>
    </section>


    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Frequently Asked <span class="text-blue-600">Questions</span></h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Get answers to common questions about our telehealth services</p>
            </div>
           
            <div class="max-w-3xl mx-auto">
                <div class="border-b border-gray-200 pb-4 mb-6">
                    <button class="flex items-center justify-between w-full group">
                        <h3 class="text-lg font-medium text-gray-800 group-hover:text-blue-600 transition duration-300">Is telehealth as effective as in-person visits?</h3>
                        <i class="fas fa-chevron-down text-gray-500 group-hover:text-blue-600 transition duration-300"></i>
                    </button>
                    <div class="mt-3 text-gray-600">
                        <p>For many medical concerns, telehealth consultations are just as effective as in-person visits while being more convenient. Studies show that outcomes for conditions like colds, flu, chronic disease management, and mental health are comparable. Some conditions requiring physical exams may need follow-up in-person care.</p>
                    </div>
                </div>
               
                <div class="border-b border-gray-200 pb-4 mb-6">
                    <button class="flex items-center justif y-between w-full group">
                        <h3 class="text-lg font-medium text-gray-800 group-hover:text-blue-600 transition duration-300">What technology do I need for a telehealth visit?</h3>
                        <i class="fas fa-chevron-down text-gray-500 group-hover:text-blue-600 transition duration-300"></i>
                    </button>
                    <div class="mt-3 text-gray-600">
                        <p>You'll need a smartphone, tablet, or computer with a camera and microphone, plus a reliable internet connection. Our platform works on all major browsers and devices. Before your appointment, you'll receive a link to join your secure video session - no software downloads required.</p>
                    </div>
                </div>
               
                <div class="border-b border-gray-200 pb-4 mb-6">
                    <button class="flex items-center justify-between w-full group">
                        <h3 class="text-lg font-medium text-gray-800 group-hover:text-blue-600 transition duration-300">Can I get prescriptions through telehealth?</h3>
                        <i class="fas fa-chevron-down text-gray-500 group-hover:text-blue-600 transition duration-300"></i>
                    </button>
                    <div class="mt-3 text-gray-600">
                        <p>Yes, our licensed physicians can prescribe most medications when clinically appropriate. Controlled substances may require an in-person visit depending on state regulations. All prescriptions are sent electronically to your preferred pharmacy.</p>
                    </div>
                </div>
               
                <div class="border-b border-gray-200 pb-4 mb-6">
                    <button class="flex items-center justify-between w-full group">
                        <h3 class="text-lg font-medium text-gray-800 group-hover:text-blue-600 transition duration-300">How much does a telehealth visit cost?</h3>
                        <i class="fas fa-chevron-down text-gray-500 group-hover:text-blue-600 transition duration-300"></i>
                    </button>
                    <div class="mt-3 text-gray-600">
                        <p>Costs vary based on your insurance coverage. Many insurers cover telehealth visits similarly to in-person visits, often with the same copay. For self-pay patients, general consultations start at $99. We're happy to verify your benefits before your appointment.</p>
                    </div>
                </div>
               
                <div class="border-b border-gray-200 pb-4 mb-6">
                    <button class="flex items-center justify-between w-full group">
                        <h3 class="text-lg font-medium text-gray-800 group-hover:text-blue-600 transition duration-300">What if I need lab tests or imaging?</h3>
                        <i class="fas fa-chevron-down text-gray-500 group-hover:text-blue-600 transition duration-300"></i>
                    </button>
                    <div class="mt-3 text-gray-600">
                        <p>If your condition requires testing, your doctor will order labs or imaging at a location convenient to you. Results are reviewed during a follow-up telehealth visit. We partner with national lab chains and imaging centers to streamline this process.</p>
                    </div>
                </div>
               
                <div class="pb-4">
                    <button class="flex items-center justify-between w-full group">
                        <h3 class="text-lg font-medium text-gray-800 group-hover:text-blue-600 transition duration-300">Is my health information secure?</h3>
                        <i class="fas fa-chevron-down text-gray-500 group-hover:text-blue-600 transition duration-300"></i>
                    </button>
                    <div class="mt-3 text-gray-600">
                        <p>Absolutely. We use bank-level encryption for all data transmission and storage. Our platform is HIPAA-compliant, meaning your health information is protected with the highest privacy standards. Video consultations are conducted through secure, encrypted connections.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <section class="py-16 bg-blue-600 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-6">Experience the Future of <span class="text-white">Healthcare</span> Today</h2>
            <p class="text-blue-200 max-w-2xl mx-auto mb-8">Join thousands of patients who have discovered the convenience and quality of virtual healthcare.</p>
            <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-4">
                <a href="#appointment" class="bg-white hover:bg-gray-100 text-blue-600 px-8 py-3 rounded-lg font-medium transition duration-300 shadow-md">
                    Book Your First Appointment
                </a>
                <a href="#contact" class="border-2 border-white hover:bg-blue-700 text-white px-8 py-3 rounded-lg font-medium transition duration-300">
                    Contact Our Team
                </a>
            </div>
        </div>
    </section>




    <footer class="bg-gray-800 text-white py-6">
  <div class="container mx-auto text-center">
    <p class="text-sm">Together, through health. Because your health matters, wherever you are.</p>
  </div>
</footer>
 
    <footer class="bg-gray-900 text-white pt-16 pb-8">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-12 mb-12">
                <div>
                    <div class="flex items-center space-x-2 mb-6">
                        <div class="w-10 h-10 bg-blue-600 rounded-lg flex items-center justify-center">
                            <i class="fas fa-heartbeat text-white text-xl"></i>
                        </div>
                        <span class="text-2xl font-bold">ThruThe<span class="text-blue-400">Health</span></span>
                    </div>
                    <p class="text-gray-400 mb-6">Making quality healthcare accessible to everyone, everywhere through innovative telehealth solutions.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-gray-800 hover:bg-blue-600 rounded-full flex items-center justify-center transition duration-300">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 hover:bg-blue-400 rounded-full flex items-center justify-center transition duration-300">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 hover:bg-pink-600 rounded-full flex items-center justify-center transition duration-300">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 hover:bg-red-600 rounded-full flex items-center justify-center transition duration-300">
                            <i class="fab fa-youtube"></i>
                        </a>
                    </div>
                </div>
               
                <div>
                    <h3 class="text-lg font-semibold mb-6">Quick Links</h3>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-400 hover:text-blue-400 transition duration-300">Home</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-blue-400 transition duration-300">Services</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-blue-400 transition duration-300">About Us</a></li>
                        <li><a href="#appointment" class="text-gray-400 hover:text-blue-400 transition duration-300">Book Appointment</a></li>
                    </ul>
                </div>
               
                <div>
                    <h3 class="text-lg font-semibold mb-6">Services</h3>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-400 hover:text-blue-400 transition duration-300">General Consultations</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-blue-400 transition duration-300">Chronic Care</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-blue-400 transition duration-300">Mental Health</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-blue-400 transition duration-300">Pediatric Care</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-blue-400 transition duration-300">Second Opinions</a></li>
                    </ul>
                </div>
               
                <div id="contact">
                    <h3 class="text-lg font-semibold mb-6">Contact Us</h3>
                    <ul class="space-y-4">
                        <li class="flex items-start">
                            <i class="fas fa-map-marker-alt text-blue-400 mt-1 mr-3"></i>
                            <span class="text-gray-400">123 Medical Plaza, Suite 500<br>San Jose Del Monte, Bulacan 3023</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-phone-alt text-blue-400 mr-3"></i>
                            <span class="text-gray-400">(+63) 9388231977</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-envelope text-blue-400 mr-3"></i>
                            <span class="text-gray-400">johnivanireneo@gmail.com</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-clock text-blue-400 mr-3"></i>
                            <span class="text-gray-400">24/7 Availability</span>
                        </li>
                    </ul>
                </div>
            </div>
           
            <div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 mb-4 md:mb-0">© 2023 ThruTheHealth. All rights reserved.</p>
                <p class="text-gray-400 mb-4 md:mb-0">John Ivan B. Ireneo|BSN 2-Y0-17|NCMB210 Nursing Infomatics </p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-blue-400 transition duration-300 text-sm">Privacy Policy</a>
                    <a href="#" class="text-gray-400 hover:text-blue-400 transition duration-300 text-sm">Terms of Service</a>
                 
                </div>
            </div>
             <div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between items-center">
              <p class="text-gray-400 mb-4 md:mb-0"> </p>
              <p class="text-gray-400 mb-4 md:mb-0">For educational purpose only </p>
             </div>
        </div>
    </footer>
</body>
</html>




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desktop AryaY</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --cyan: #00f2fe;
            --dark: #0a0a29;
        }
        
        body {
            font-family: 'Segoe UI', sans-serif;
            color: white;
            overflow-x: hidden;
            min-width: 1024px;
            position: relative;
        }
        
        .background-wrapper {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }
        
        .background-wrapper img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .main-content {
            position: relative;
            z-index: 1;
        }
        
        .cyan-text { color: var(--cyan); }
        .cyan-bg { background-color: var(--cyan); }
        
        .card {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(0, 242, 254, 0.1);
            backdrop-filter: blur(10px);
        }
        
        .service-card {
            transition: all 0.3s ease;
            min-height: 400px;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            border-color: var(--cyan);
        }
        
        .social-icon:hover {
            background-color: var(--cyan);
            transform: translateY(-3px);
        }
        
        .main-container {
            width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        .hero-image {
            max-width: 600px;
            min-height: 600px;
            object-fit: cover;
        }
        
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
        }
        
        .portfolio-item img {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }
        
        .nav-link {
            position: relative;
            padding: 5px 0;
        }
        
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: 0;
            left: 0;
            background-color: var(--cyan);
            transition: width 0.3s ease;
        }
        
        .nav-link:hover::after {
            width: 100%;
        }
        
        section {
            padding: 100px 0;
        }
        
        .section-title {
            font-size: 48px;
            margin-bottom: 60px;
        }
        
        .about-image {
            width: 500px;
            height: 500px;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <div class="background-wrapper">
        <img src="https://i.pinimg.com/originals/d6/c2/bc/d6c2bc5eef34797e9831992d76de249c.gif" alt="Galaxy Background">
    </div>
    
    <div class="main-content">
        <div class="main-container">
            <h1 class="section-title"></h1>
            
            
<!-- Audio Player -->
            <audio id="myAudio" controls loop>
    <source src="bloody_mary.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>

    <!-- Attribution -->
    <p>Music: <a href="https://www.bensound.com/royalty-free-music/track/les-prisonnieres-epic-electronic" target="_blank">Les Prisonnières</a> by <a href="https://www.bensound.com" target="_blank">Bensound</a>.</p>
</body>
</html> 
        </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
    <script>
        AOS.init({
            duration: 1000,
            once: true
        });
    </script>
</body>
</html> 
    
   
    
</body>
</div>
    <!-- Navigation -->

    <nav class="fixed top-0 left-0 right-0 z-50 bg-opacity-90" style="background-color: var(--dark);">

        <div class="main-container flex items-center justify-between py-6">

            <div class="flex items-center">

                <span class="text-2xl cyan-text font-bold">AryaY Ni boss 🗿</span>

            </div>

            

            <div class="flex items-center space-x-12">

                <a href="#hero" class="nav-link text-white hover:cyan-text text-lg">Home</a>

                <a href="#about" class="nav-link text-white hover:cyan-text text-lg">About</a>

                <a href="#services" class="nav-link text-white hover:cyan-text text-lg">Services</a>

                <a href="#portfolio" class="nav-link text-white hover:cyan-text text-lg">Portfolio</a>

                <a href="#testimonial" class="nav-link text-white hover:cyan-text text-lg">Contact</a>

            </div>

        </div>

    </nav>

  <!-- Hero Section -->
<section id="hero" class="min-h-screen flex items-center">
    <div class="main-container flex items-center justify-between">
        <div class="w-1/2" data-aos="fade-right">
            <h1 class="text-6xl mb-6">
                Hello, <span class="cyan-text">I am</span>
            </h1>

            <!-- Animasi efek mengetik -->
            <h2 class="text-7xl font-bold mb-8">
                <span id="typing-effect"></span>
            </h2>

            <p class="text-2xl mb-10 cyan-text">Photographer</p>

            <div class="flex space-x-6 mb-12">
                <!-- Social Media Links -->
                <a href="https://www.facebook.com" target="_blank" class="social-icon w-14 h-14 rounded-full border-2 border-cyan flex items-center justify-center transition-all duration-300 text-xl">
                    <i class="fab fa-facebook-f"></i>
                </a>
                <a href="https://x.com/AryaDwija22?t=RLoNpt_y8MNXhKgjfmifxA&s=09" target="_blank" class="social-icon w-14 h-14 rounded-full border-2 border-cyan flex items-center justify-center transition-all duration-300 text-xl">
                    <i class="fab fa-twitter"></i>
                </a>
                <a href="https://www.instagram.com/brohhhh199?igsh=aDU4cTVpbjE5aGlz" target="_blank" class="social-icon w-14 h-14 rounded-full border-2 border-cyan flex items-center justify-center transition-all duration-300 text-xl">
                    <i class="fab fa-instagram"></i>
                </a>
                <a href="https://https://www.linkedin.com/in/story-xd-7118a833a?originalSubdomain=id" target="_blank" class="social-icon w-14 h-14 rounded-full border-2 border-cyan flex items-center justify-center transition-all duration-300 text-xl">
                    <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="https://t.me/+gGTSkDDdaotjY2E1"
                    target="_blank" 
                    class="social-icon w-14 h14 rounded-full border-2 border-red flex items-center justify-center transition-all duration-300 text-xl">
                    <i class="fab fa-telegram"></i>
                </a>
            </div>
<a href="https://wa.me/6282266231235" target="_blank">
    <button class="bg-red-500 text-white px-6 py-6 rounded-full text-xl font-semibold hover:bg-opacity-80 transition-all duration-300">
        Chat Saya 😁
    </button>
</a>

    
        </div>

        <div class="w-1/2 flex justify-end" data-aos="fade-left">
            <img src="https://i.pinimg.com/originals/a2/80/8d/a2808d7f7bc483577d79db3bd38b558f.gif" 
                 alt="Profile" 
                 class="hero-image rounded-2xl">
        </div>
    </div>
</section>

<script>
    const texts = ['AryaY', 'A Creator'];
    let index = 0;
    let charIndex = 0;
    const typingSpeed = 80; // Kecepatan mengetik (lebih cepat)
    const erasingSpeed = 50; // Kecepatan menghapus (lebih cepat)
    const delayBetweenTexts = 1500; // Waktu tunggu sebelum mengganti teks (ms)

    const typingElement = document.getElementById('typing-effect');

    function typeText() {
        if (charIndex < texts[index].length) {
            typingElement.textContent += texts[index].charAt(charIndex);
            charIndex++;
            setTimeout(typeText, typingSpeed);
        } else {
            setTimeout(eraseText, delayBetweenTexts);
        }
    }

    function eraseText() {
        if (charIndex > 0) {
            typingElement.textContent = texts[index].substring(0, charIndex - 1);
            charIndex--;
            setTimeout(eraseText, erasingSpeed);
        } else {
            index = (index + 1) % texts.length;
            setTimeout(typeText, typingSpeed);
        }
    }

    // Mulai animasi
    typeText();
</script>

<style>
    body {
        font-family: Arial, sans-serif;
    }

    #typing-effect {
        white-space: nowrap;
        overflow: hidden;
        display: inline-block;
        border-right: 2px solid #007bff; /* Kursor berwarna biru */
        color: #007bff; /* Teks berwarna biru */
        animation: blink-cursor 0.7s steps(1) infinite;
    }

    @keyframes blink-cursor {
        50% {
            border-color: transparent;
        }
    }
</style>

    <!-- About Section -->

    <section id="about">

        <div class="main-container flex items-center justify-between gap-20" data-aos="fade-up">

            <div class="w-1/2">

                <img src="https://i.pinimg.com/originals/da/b8/27/dab827d9c377e8381bdcc1d77957aaad.gif" alt="About" class="about-image rounded-2xl">

            </div>

            

            <div class="w-1/2">

                <h2 class="section-title font-bold">About <span class="cyan-text">Me</span></h2>

                <p class="text-xl text-gray-300 mb-10 leading-relaxed">

                    Thank you for visiting my website and getting to know me better. I hope you enjoyed reading my blog posts and found them useful and informative. If you want to read more of my posts, subscribe to my newsletter where I send weekly updates on web development trends and tips. If you have any feedback or suggestions, please let me know. I'd love to hear from you.

                </p>

                <button class="bg-cyan text-dark px-10 py-4 rounded-full text-xl font-semibold hover:bg-opacity-80 transition-all duration-300">

                    Read More

                </button>

            </div>

        </div>

    </section>

    <!-- Services Section -->

    <section id="services">

        <div class="main-container">

            <h2 class="section-title font-bold text-center" data-aos="fade-up">My <span class="cyan-text">Services</span></h2>

            

            <div class="grid grid-cols-3 gap-10">

                <div class="card service-card rounded-xl p-10 text-center" data-aos="fade-up" data-aos-delay="100">

                    <div class="text-6xl cyan-text mb-8">

                        <i class="fas fa-code"></i>

                    </div>

                    <h3 class="text-2xl font-bold mb-6">Web Development</h3>

                    <p class="text-lg text-gray-300 mb-8 leading-relaxed">Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi itaque similique architecto eaque ut quas delectus pariatur nesciunt in eligendi mollitia dicta.</p>

                    <button class="bg-cyan text-dark px-8 py-3 rounded-full text-lg font-semibold hover:bg-opacity-80 transition-all duration-300">

                        Read More

                    </button>

                </div>

                

                <div class="card service-card rounded-xl p-10 text-center" data-aos="fade-up" data-aos-delay="200">

                    <div class="text-6xl cyan-text mb-8">

                        <i class="fas fa-pencil-alt"></i>

                    </div>

                    <h3 class="text-2xl font-bold mb-6">Graphic Design</h3>

                    <p class="text-lg text-gray-300 mb-8 leading-relaxed">Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi itaque similique architecto eaque ut quas delectus pariatur nesciunt in eligendi mollitia dicta.</p>

                    <button class="bg-cyan text-dark px-8 py-3 rounded-full text-lg font-semibold hover:bg-opacity-80 transition-all duration-300">

                        Read More

                    </button>

                </div>

                

                <div class="card service-card rounded-xl p-10 text-center" data-aos="fade-up" data-aos-delay="300">

                    <div class="text-6xl cyan-text mb-8">

                        <i class="fas fa-chart-line"></i>

                    </div>

                    <h3 class="text-2xl font-bold mb-6">Digital Marketing</h3>

                    <p class="text-lg text-gray-300 mb-8 leading-relaxed">Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi itaque similique architecto eaque ut quas delectus pariatur nesciunt in eligendi mollitia dicta.</p>

                    <button class="bg-cyan text-dark px-8 py-3 rounded-full text-lg font-semibold hover:bg-opacity-80 transition-all duration-300">

                        Read More

                    </button>

                </div>

            </div>

        </div>

    </section>

    <!-- Portfolio Section -->

    <section id="portfolio">

        <div class="main-container">

            <h2 class="section-title font-bold text-center" data-aos="fade-up">Latest <span class="cyan-text">Project</span></h2>

            

            <div class="portfolio-grid">

                <div class="portfolio-item" data-aos="zoom-in" data-aos-delay="100">

                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRK4xXMY68jnwO-lT_jlNM5FZRORZ7JLnPLbw&usqp=CAU" alt="Project 1" class="rounded-xl hover:opacity-75 transition duration-300">

                </div>

                <div class="portfolio-item" data-aos="zoom-in" data-aos-delay="200">

                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTcx9hIEjjmRBF_g_N5SDtQVz27Pp8girp1jM92fyThT2T0TcXYW6G8DVdD&s=10" alt="Project 2" class="rounded-xl hover:opacity-75 transition duration-300">

                </div>

                <div class="portfolio-item" data-aos="zoom-in" data-aos-delay="300">

                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTNqkiLPmhTbZx1TmaHcJPuiATepXPWXifZDl4lK786WV0fhpwdrzEoTd8&s=10" alt="Project 3" class="rounded-xl hover:opacity-75 transition duration-300">

                </div>

                <div class="portfolio-item" data-aos="zoom-in" data-aos-delay="400">

                    <img src="https://miro.medium.com/v2/resize:fit:1280/0*nw1HVdtB47MKZx9Z.gif" alt="Project 4" class="rounded-xl hover:opacity-75 transition duration-300">

                </div>

                <div class="portfolio-item" data-aos="zoom-in" data-aos-delay="500">

                    <img src="https://media.tenor.com/y-cCxl8uEw0AAAAM/yetopen.gif" alt="Project 5" class="rounded-xl hover:opacity-75 transition duration-300">

                </div>

                <div class="portfolio-item" data-aos="zoom-in" data-aos-delay="600">

                    <img src="https://i.pinimg.com/originals/f2/69/72/f26972dfbe5f8226b76ac7bca928c82b.gif" alt="Project 6" class="rounded-xl hover:opacity-75 transition duration-300">

                </div>

            </div>

        </div>

    </section>

    <!-- Testimonial Section -->

    <section id="testimonial">

        <div class="main-container">

            <h2 class="section-title font-bold text-center" data-aos="fade-up">Valuable <span class="cyan-text">Testimonial</span></h2>

            

            <div class="card rounded-xl p-12 max-w-4xl mx-auto relative" data-aos="fade-up" data-aos-delay="100">

                <button class="absolute left-0 top-1/2 transform -translate-y-1/2 -translate-x-16 text-cyan text-3xl">

                    <i class="fas fa-chevron-left"></i>

                </button>

                <button class="absolute right-0 top-1/2 transform -translate-y-1/2 translate-x-16 text-cyan text-3xl">

                    <i class="fas fa-chevron-right"></i>

                </button>

                

                <div class="text-center">

                    <img src="https://i.pinimg.com/originals/17/dd/22/17dd22ec6dafa441c1b4131e9969c63d.gif" alt="Testimonial" class="w-28 h-28 rounded-full mx-auto mb-6 border-4 border-cyan">

                    <h3 class="text-2xl font-bold mb-4">AryaY</h3>

                    <p class="text-xl text-gray-300 leading-relaxed">Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem dignissimos dicta sunt delectus corrupti impedit dolores sed. Iusto nostrum aute pariatur exercitationem quos ut sed tempus minus modi aperiam quas ipsum temporel.
                        
                     
                   
                        
                   
                    </p>

                </div>

            </div>

        </div>

       </section>
    
					<!-- Anime Favorit -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime Favorit</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }
        header {
            background-color: #6a0dad; /* Warna ungu */
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <!-- Header dengan warna ungu -->
    <header>
        <h1>Selamat Datang di Halaman Anime Favorit</h1>
    </header>

    <section id="about">
        <div class="main-container flex items-center justify-between gap-20" data-aos="fade-up">
            <div class="w-1/2">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTvewf7FzGTtTFdr7HnnzeK0SHYmVpNQEPqUpFRkI_j-Anyu6SfApArznoC&s=10" alt="About" class="about-image rounded-2xl">
            </div>
            <div class="w-1/2">
                <h2 class="section-title font-bold">Anime <span class="cyan-text">Hello World</span></h2>
                <p class="text-xl text-gray-300 mb-10 leading-relaxed" id="about-text">
                    Hello World adalah film anime yang dirilis pada tahun 2019, disutradarai oleh Tomohiko Itou dan diproduksi oleh studio Graphinica. Film ini berlatar di masa depan dan menggabungkan elemen sci-fi, romansa, dan drama. Ceritanya berfokus pada seorang pemuda bernama Naomi Katagaki, yang hidup di Kyoto pada tahun 2027. 
                </p>
                <p class="text-xl text-gray-300 mb-10 leading-relaxed hidden" id="more-text">
                    Suatu hari, ia bertemu dengan seorang wanita bernama Ruri, yang mengaku berasal dari masa depan. Ruri memberitahunya bahwa dia datang untuk menyelamatkan Naomi, yang nantinya akan menjadi sangat penting dalam menciptakan sebuah sistem komputer yang bisa mengubah masa depan. Mereka berdua mulai bekerja sama, mengungkap misteri yang melibatkan teknologi dan perubahan waktu. Dalam perjalanan ini, mereka juga menghadapi dilema emosional dan hubungan yang semakin erat antara keduanya.
                </p>
                <button class="bg-cyan text-dark px-10 py-4 rounded-full text-xl font-semibold hover:bg-opacity-80 transition-all duration-300" id="read-more">
                    Read More
                </button>
            </div>
        </div>
    </section>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
    <script>
        AOS.init({
            once: true,
            offset: 200,
            duration: 800,
            easing: 'ease-in-out'
        });

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
</script>

<section id="naruto">
    <div class="main-container flex items-center justify-between gap-20" data-aos="fade-up">
        <div class="w-1/2">
            <img src="https://steamuserimages-a.akamaihd.net/ugc/910156967348138382/E4A8A3FAA9388A67BD3DC2CCD77216B21280A7A1/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false" alt="Naruto" class="about-image rounded-2xl">
        </div>
        <div class="w-1/2">
            <h2 class="section-title font-bold">Anime <span class="cyan-text">Naruto</span></h2>
            <p class="text-xl text-gray-300 mb-10 leading-relaxed" id="naruto-text">
                Naruto adalah salah satu anime dan manga paling populer, ditulis dan diilustrasikan oleh Masashi Kishimoto. Ceritanya mengikuti perjalanan seorang ninja muda bernama Naruto Uzumaki yang bercita-cita menjadi Hokage, pemimpin desanya.
            </p>
            <p class="text-xl text-gray-300 mb-10 leading-relaxed hidden" id="more-naruto-text">
                Dalam perjalanannya, Naruto menghadapi berbagai tantangan, melawan musuh-musuh kuat, dan berteman dengan banyak karakter unik. Cerita ini menggambarkan perjuangan, persahabatan, dan tekad seorang anak muda untuk mengatasi kesulitan dan mencapai mimpinya, meskipun ia menyandang beban sebagai Jinchūriki.
            </p>
            <button class="bg-cyan text-dark px-10 py-4 rounded-full text-xl font-semibold hover:bg-opacity-80 transition-all duration-300" id="read-more-naruto">
                Read More
            </button>
        </div>
    </div>
</section>

<script>
    // Ambil elemen yang diperlukan untuk Naruto
    const readMoreNarutoButton = document.getElementById("read-more-naruto");
    const moreNarutoText = document.getElementById("more-naruto-text");

    // Tambahkan event listener untuk tombol Naruto
    readMoreNarutoButton.addEventListener("click", () => {
        moreNarutoText.classList.toggle("hidden");

        if (moreNarutoText.classList.contains("hidden")) {
            readMoreNarutoButton.textContent = "Read More";
        } else {
            readMoreNarutoButton.textContent = "Show Less";
        }
    });
</script>
<section id="alya">
    <div class="main-container flex items-center justify-between gap-20" data-aos="fade-up">
        <div class="w-1/2">
            <img src="https://i.pinimg.com/originals/53/0f/1c/530f1c7b35e8928c5ff55f60378dcf10.gif" alt="Alya" class="about-image rounded-2xl">
        </div>
        <div class="w-1/2">
            <h2 class="section-title font-bold">Anime <span class="cyan-text">alya sometimes hides her feelings </span></h2>
            <p class="text-xl text-gray-300 mb-10 leading-relaxed" id="alya-text">
                Alya adalah seorang gadis yang ceria dan selalu terlihat tersenyum di hadapan semua orang. Teman-temannya menganggapnya sebagai sosok yang kuat, penuh semangat, dan tidak pernah terlihat sedih. Namun, di balik senyumnya, Alya sering menyembunyikan perasaannya yang sebenarnya.

Ada saat-saat di mana Alya merasa kesepian atau terluka oleh perkataan orang lain, tetapi dia memilih untuk menyimpan semuanya sendiri. Baginya, menunjukkan kelemahan bukanlah pilihan. Dia takut menjadi beban bagi orang-orang di sekitarnya.

Namun, suatu hari sahabatnya, Rina, menyadari sesuatu yang berbeda. “Alya, kamu nggak harus pura-pura kuat di depan aku,” kata Rina dengan lembut. Mendengar itu, air mata yang selama ini Alya tahan akhirnya mengalir. Untuk pertama kalinya, dia merasa lega karena bisa berbagi.

Sejak saat itu, Alya mulai belajar bahwa tidak apa-apa untuk menunjukkan perasaan yang sebenarnya. Kadang-kadang, menerima dukungan orang lain justru membuatnya lebih kuat.


            </p>
            <p class="text-xl text-gray-300 mb-10 leading-relaxed hidden" id="more-alya-text">
                udah kepanjangan jir🗿
            </p>
            <button class="bg-cyan text-dark px-10 py-4 rounded-full text-xl font-semibold hover:bg-opacity-80 transition-all duration-300" id="read-more-alya">
                Read More
            </button>
        </div>
    </div>
</section>

<script>
    // Ambil elemen yang diperlukan untuk Alya
    const readMoreAlyaButton = document.getElementById("read-more-alya");
    const moreAlyaText = document.getElementById("more-alya-text");

    // Tambahkan event listener untuk tombol Alya
    readMoreAlyaButton.addEventListener("click", () => {
        moreAlyaText.classList.toggle("hidden");

        if (moreAlyaText.classList.contains("hidden")) {
            readMoreAlyaButton.textContent = "Read More";
        } else {
            readMoreAlyaButton.textContent = "Show Less";
        }
    });
</script>
    </script>

</div>
</body>

</html>



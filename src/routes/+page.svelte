<script>
  import Divider from "../components/Divider.svelte";


</script>

<main class="min-w-120 max-w-200 mx-auto p-6 grid gap-6">
    <nav class="grid place-items-center gap-4">
        <img src="profile.jpeg" alt="Zdjęcie" class="w-56 h-56 rounded-full shadow-xl">
        <h1 class="text-5xl font-bold">
            Adam Grzeszczuk
        </h1>

        <p class="text-2xl italic ml-30 px-1 font-extrabold bg-gradient-to-r from-blue-400 via-cyan-500 to-indigo-400 inline-block text-transparent bg-clip-text">
            FRONTEND DEVELOPER
        </p>
    </nav>    
    <ul class="grid gap-6">
        <li class="section grid gap-10">
            <h2 class="text-3xl italic section-header">
                O mnie
            </h2>
            
            <div class="grid gap-3">
                <h3 class="text-2xl">
                    Zainteresowania
                </h3>
                <Divider direction="horizontal"/>
                <div class="grid gap-2 text-xl">
                    <p>
                        Interesuję się frontendem – uwielbiam majstrować przy interfejsach, poprawiać detale i ogarniać, żeby wszystko działało i wyglądało git.
                    </p>
                    <p>
                        Poza kompem często jeżdżę na rowerze lub spaceruję - dobry sposób na <i>odświeżenie umysłu</i>.
                    </p>
                    <p>
                    Oprócz tego muzyka to nieodłączny element mojego życia – szczególnie japońska. Towarzyszy mi praktycznie cały czas, niezależnie od tego, co robię.
                    </p>
                </div>
            </div>

            <div class="grid gap-3">
                <h3 class="text-2xl text-slate-300">
                    Wykształcenie
                </h3>
                <Divider direction="horizontal"/>
                <p class="text-xl">
                    Ukończyłem studia inżynierskie na Politechnice Białostockiej w 2025 roku z wynikiem bardzo dobrym. Obecnie kontynuuję naukę na studiach magisterskich na tej samej uczelni. 
                </p>
            </div>

            <div class="grid gap-3">
                <h2 class="text-2xl">
                    Umiejętności
                </h2>
                <Divider direction="horizontal"/>
                <div class="text-xl grid gap-2">
                    <p>
                        Dobrze znam framework Vue oraz Tailwind CSS – często korzystam z tych narzędzi przy projektach.
                    </p>
                    <p>
                        Posiadam podstawową znajomość React'a. Aktualnie uczę się frameworka Svelte.
                    </p>
                    <p>
                        Cały czas też poszerzam swoją wiedzę z zakresu JavaScript'u, TypeScript'u i CSS.
                    </p>
                </div>
                <div class="flex flex-wrap justify-center gap-4 mx-auto [&>span]:w-10 [&>span]:h-10">
                    <span class="icon-[skill-icons--vuejs-light]"></span>
                    <span class="icon-[skill-icons--tailwindcss-light]"></span>
                    <span class="icon-[skill-icons--react-light]"></span>
                    <span class="icon-[skill-icons--svelte]"></span>
                    <span class="icon-[skill-icons--javascript]"></span>
                    <span class="icon-[skill-icons--typescript]"></span>
                    <span class="icon-[skill-icons--html]"></span>
                    <span class="icon-[skill-icons--css]"></span>
                </div>
                <div class="text-xl grid gap-2 mt-8">
                    <p>
                        Poza wyżej wspomnianymi technologiami, w minimalnym stopniu znam języki takie jak C#, Python, Java
                    </p>
                </div>
                <div class="flex flex-wrap justify-center gap-4 mx-auto [&>span]:w-10 [&>span]:h-10">
                    <span class="icon-[skill-icons--cs]"></span>
                    <span class="icon-[skill-icons--python-light]"></span>
                    <span class="icon-[skill-icons--java-light]"></span>
                </div>
            </div>
        </li>

        <li class="section">
            <h2 class="section-header italic">
                Projekty
            </h2>
            <ol class="grid gap-3 text-xl list-disc pl-5">
                <li>
                    NonogramNest - aplikacja internetowa umożliwiająca rozgrywkę w nonogramy. Praca inżynierska i za razem mój największy projekt z wykorzystaniem Vue.js, Tailwind CSS, Express.js i PostgreSQL.
                </li>
                <li>
                    Portfolio dla lekarza
                </li>
                <li>
                    RYD UI - własna bilbioteka komponentów dla Vue.js z wykorzystaniem Tailwind CSS (<b>rozwijana</b>).
                </li>
            </ol>
        </li>

        <li class="section">
            <h2 class="section-header italic">
                Kontakt
            </h2>
            <div class="grid gap-2 text-xl">
                <a href="mailto:adameq86@gmail.com" class="flex gap-2">
                    <span class="icon-[material-symbols--alternate-email]"></span>
                    <p>
                        adameq86@gmail.com
                    </p>
                </a>
                <a href="/" class="flex gap-2">
                    <span class="icon-[tabler--brand-linkedin]"></span>
                    <p>
                        LinkedIn
                    </p>
                </a>
                <a href="/" class="flex gap-2">
                    <span class="icon-[tabler--brand-github]"></span>
                    <p>
                        GitHub
                    </p>
                </a>
            </div>
        </li>
    </ul>
    <Divider direction="horizontal"/>
</main>
```html
<!DOCTYPE html>
<html lang="en" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nitin Mishra - Next-Gen GitHub Profile</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Fira Code & Outfit -->
    <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&family=Outfit:wght@300;400;600;800;900&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Outfit', 'sans-serif'],
                        mono: ['Fira Code', 'monospace']
                    },
                    colors: {
                        cyber: {
                            900: '#030712',
                            800: '#0b0f19',
                            700: '#111827',
                            600: '#1f2937',
                            accent: '#a855f7',
                            glow: '#c084fc',
                            cyan: '#06b6d4',
                            pink: '#ec4899'
                        }
                    },
                    animation: {
                        'pulse-slow': 'pulse 4s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                        'float': 'float 3s ease-in-out infinite',
                    },
                    keyframes: {
                        float: {
                            '0%, 100%': { transform: 'translateY(0px)' },
                            '50%': { transform: 'translateY(-10px)' }
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #030712;
            color: #f3f4f6;
            overflow-x: hidden;
        }
        .glass-panel {
            background: rgba(17, 24, 39, 0.75);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(168, 85, 247, 0.2);
            box-shadow: 0 0 25px rgba(168, 85, 247, 0.05);
        }
        .glass-panel:hover {
            border-color: rgba(168, 85, 247, 0.5);
            box-shadow: 0 0 35px rgba(168, 85, 247, 0.15);
        }
        .glow-text {
            text-shadow: 0 0 20px rgba(168, 85, 247, 0.6);
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 8px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #030712;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #1f2937;
            border-radius: 4px;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb:hover {
            background: #a855f7;
        }
    </style>
</head>
<body class="font-sans antialiased selection:bg-purple-500 selection:text-white">

    <!-- Top Notification Banner -->
    <div class="bg-gradient-to-r from-purple-900 via-indigo-900 to-pink-900 text-white text-xs md:text-sm py-2 px-4 text-center font-semibold tracking-wide border-b border-purple-500/35">
        🔥 <span class="text-purple-300 font-mono">HEYITSKUSHAGRA</span> • NEXT-GEN ULTRA PROFILE DESIGN ACTIVE ⚡
    </div>

    <!-- Main Container -->
    <div class="max-w-6xl mx-auto px-4 py-8 md:py-12">

        <!-- Header Controls Bar -->
        <div class="flex flex-col md:flex-row items-center justify-between gap-4 mb-8 glass-panel p-4 rounded-2xl">
            <div class="flex items-center space-x-3">
                <div class="w-4 h-4 rounded-full bg-purple-500 animate-ping"></div>
                <h1 class="text-xl md:text-2xl font-black tracking-tight bg-gradient-to-r from-white via-purple-300 to-pink-400 bg-clip-text text-transparent">
                    Nitin Mishra <span class="text-xs uppercase font-mono px-2 py-1 rounded bg-purple-500/20 text-purple-300 border border-purple-500/30">Dev & Designer</span>
                </h1>
            </div>
            
            <div class="flex flex-wrap items-center gap-3">
                <button onclick="switchTab('preview')" id="btn-preview" class="px-5 py-2.5 rounded-xl text-sm font-semibold transition-all duration-300 bg-purple-600 text-white shadow-lg shadow-purple-600/30 flex items-center gap-2">
                    <i class="fa-solid fa-eye"></i> Live Interactive View
                </button>
                <button onclick="switchTab('markdown')" id="btn-markdown" class="px-5 py-2.5 rounded-xl text-sm font-semibold transition-all duration-300 bg-gray-800 text-gray-300 hover:bg-gray-700 hover:text-white border border-gray-700 flex items-center gap-2">
                    <i class="fa-solid fa-code"></i> Copy Markdown Code
                </button>
                <button onclick="copyReadmeCode()" class="px-4 py-2.5 rounded-xl text-sm font-semibold transition-all duration-300 bg-pink-600/20 text-pink-400 hover:bg-pink-600 hover:text-white border border-pink-500/40 flex items-center gap-2">
                    <i class="fa-solid fa-copy"></i> Copy All
                </button>
            </div>
        </div>

        <!-- Tab 1: Live Rendered View -->
        <div id="tab-preview" class="space-y-8 animate-fadeIn">
            
            <!-- Banner & Intro Card -->
            <div class="glass-panel rounded-3xl overflow-hidden relative group">
                <div class="absolute inset-0 bg-gradient-to-r from-purple-500/10 via-transparent to-pink-500/10 pointer-events-none"></div>
                
                <!-- SVG Wave Header Banner -->
                <div class="w-full bg-gradient-to-r from-gray-900 via-purple-950 to-gray-900 p-6 md:p-10 text-center relative border-b border-purple-500/20">
                    <div class="absolute top-4 right-4 flex items-center space-x-2">
                        <span class="w-3 h-3 rounded-full bg-red-500/80"></span>
                        <span class="w-3 h-3 rounded-full bg-yellow-500/80"></span>
                        <span class="w-3 h-3 rounded-full bg-green-500/80"></span>
                    </div>
                    <h2 class="text-3xl md:text-5xl font-extrabold tracking-tight text-white mb-3 glow-text">
                        NITIN MISHRA
                    </h2>
                    <p class="text-purple-300 font-mono text-sm md:text-lg tracking-wider uppercase">
                        Aspiring Coder • UI/UX Designer • Full-Stack Builder ⚡
                    </p>
                </div>

                <!-- Bio & Typing Badge Bar -->
                <div class="p-6 md:p-8 flex flex-col items-center text-center space-y-6">
                    <div class="inline-flex items-center space-x-2 bg-purple-950/60 border border-purple-500/40 px-6 py-3 rounded-full shadow-inner font-mono text-purple-300 text-sm md:text-base">
                        <span class="text-pink-400">👋</span> Hi, I'm Nitin Mishra | I build things that look as good as they work ✨
                    </div>

                    <div class="flex flex-wrap justify-center gap-4">
                        <div class="flex items-center space-x-2 bg-gray-900/80 border border-gray-800 px-4 py-2 rounded-xl text-xs font-mono text-purple-400">
                            <i class="fa-solid fa-eye text-pink-400"></i>
                            <span>Profile Views: <strong class="text-white">12,450+</strong></span>
                        </div>
                        <a href="https://guruji-shrawan.vercel.app/" target="_blank" class="flex items-center space-x-2 bg-gray-900/80 hover:bg-purple-900/40 border border-purple-500/30 px-4 py-2 rounded-xl text-xs font-mono text-purple-300 transition-all">
                            <i class="fa-solid fa-globe text-cyan-400"></i>
                            <span>guruji-shrawan.vercel.app</span>
                            <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                        </a>
                    </div>
                </div>
            </div>

            <!-- About Me Grid (Interactive Object) -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Left: Interactive JS Object Code -->
                <div class="glass-panel rounded-2xl p-6 relative">
                    <div class="flex items-center justify-between mb-4 pb-2 border-b border-gray-800">
                        <span class="text-xs font-mono text-purple-400 flex items-center gap-2">
                            <i class="fa-brands fa-square-js text-yellow-400 text-base"></i> about-nitin.js
                        </span>
                        <span class="w-2.5 h-2.5 rounded-full bg-purple-500"></span>
                    </div>
                    <pre class="font-mono text-xs md:text-sm text-gray-300 overflow-x-auto leading-relaxed"><code><span class="text-purple-400">const</span> <span class="text-blue-400">nitin</span> = {
  <span class="text-pink-400">name</span>: <span class="text-green-300">"Nitin Mishra"</span>,
  <span class="text-pink-400">role</span>: <span class="text-green-300">"Aspiring Coder & Designer"</span>,
  <span class="text-pink-400">location</span>: <span class="text-green-300">"India 🇮🇳"</span>,
  <span class="text-pink-400">education</span>: <span class="text-green-300">"Class 11 (PCM + AI)"</span>,
  <span class="text-pink-400">codes</span>: [<span class="text-orange-300">"HTML"</span>, <span class="text-orange-300">"CSS"</span>, <span class="text-orange-300">"Python"</span>, <span class="text-orange-300">"React"</span>, <span class="text-orange-300">".NET"</span>],
  <span class="text-pink-400">designs</span>: [<span class="text-cyan-300">"Adobe Tools"</span>, <span class="text-cyan-300">"UI/UX"</span>],
  <span class="text-pink-400">funFact</span>: <span class="text-green-300">"I code the UI & design it too 🎨"</span>
};</code></pre>
                </div>

                <!-- Right: Tech Arsenal & Tools -->
                <div class="glass-panel rounded-2xl p-6 flex flex-col justify-between">
                    <div>
                        <h3 class="text-lg font-bold text-white mb-4 flex items-center gap-2">
                            <i class="fa-solid fa-bolt text-purple-400"></i> Tech Arsenal
                        </h3>
                        <p class="text-sm text-gray-400 mb-6">Core languages, frameworks, and creative design tools in my active toolkit.</p>
                    </div>

                    <div class="grid grid-cols-4 gap-3 my-2">
                        <div class="bg-gray-900/90 border border-purple-500/20 p-3 rounded-xl flex flex-col items-center justify-center hover:border-purple-500 transition-all">
                            <i class="fa-brands fa-html5 text-orange-500 text-2xl mb-1"></i>
                            <span class="text-[10px] font-mono text-gray-300">HTML5</span>
                        </div>
                        <div class="bg-gray-900/90 border border-purple-500/20 p-3 rounded-xl flex flex-col items-center justify-center hover:border-purple-500 transition-all">
                            <i class="fa-brands fa-css3-alt text-blue-500 text-2xl mb-1"></i>
                            <span class="text-[10px] font-mono text-gray-300">CSS3</span>
                        </div>
                        <div class="bg-gray-900/90 border border-purple-500/20 p-3 rounded-xl flex flex-col items-center justify-center hover:border-purple-500 transition-all">
                            <i class="fa-brands fa-python text-yellow-400 text-2xl mb-1"></i>
                            <span class="text-[10px] font-mono text-gray-300">Python</span>
                        </div>
                        <div class="bg-gray-900/90 border border-purple-500/20 p-3 rounded-xl flex flex-col items-center justify-center hover:border-purple-500 transition-all">
                            <i class="fa-brands fa-react text-cyan-400 text-2xl mb-1 animate-spin-slow"></i>
                            <span class="text-[10px] font-mono text-gray-300">React</span>
                        </div>
                        <div class="bg-gray-900/90 border border-purple-500/20 p-3 rounded-xl flex flex-col items-center justify-center hover:border-purple-500 transition-all">
                            <i class="fa-brands fa-git-alt text-red-500 text-2xl mb-1"></i>
                            <span class="text-[10px] font-mono text-gray-300">Git</span>
                        </div>
                        <div class="bg-gray-900/90 border border-purple-500/20 p-3 rounded-xl flex flex-col items-center justify-center hover:border-purple-500 transition-all">
                            <i class="fa-brands fa-github text-white text-2xl mb-1"></i>
                            <span class="text-[10px] font-mono text-gray-300">GitHub</span>
                        </div>
                        <div class="bg-gray-900/90 border border-purple-500/20 p-3 rounded-xl flex flex-col items-center justify-center hover:border-purple-500 transition-all">
                            <i class="fa-solid fa-code text-purple-400 text-2xl mb-1"></i>
                            <span class="text-[10px] font-mono text-gray-300">.NET</span>
                        </div>
                        <div class="bg-gray-900/90 border border-purple-500/20 p-3 rounded-xl flex flex-col items-center justify-center hover:border-purple-500 transition-all">
                            <i class="fa-solid fa-palette text-pink-400 text-2xl mb-1"></i>
                            <span class="text-[10px] font-mono text-gray-300">Adobe UI</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Featured Projects Section -->
            <div class="space-y-4">
                <h3 class="text-xl font-bold text-white flex items-center gap-2 px-2">
                    <i class="fa-solid fa-rocket text-purple-400"></i> Featured Projects
                </h3>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- Project 1 -->
                    <div class="glass-panel rounded-2xl p-6 flex flex-col justify-between group hover:shadow-purple-500/10 transition-all">
                        <div>
                            <div class="flex items-center justify-between mb-3">
                                <span class="text-xs font-mono uppercase tracking-wider px-3 py-1 rounded-full bg-purple-500/20 text-purple-300 border border-purple-500/30">React / Next.js</span>
                                <a href="https://guruji-shrawan.vercel.app/" target="_blank" class="text-purple-400 hover:text-white transition-colors">
                                    <i class="fa-solid fa-external-link-alt text-sm"></i>
                                </a>
                            </div>
                            <h4 class="text-lg font-bold text-white mb-2 group-hover:text-purple-300 transition-colors">🌐 Guruji Shrawan Platform</h4>
                            <p class="text-gray-400 text-sm mb-4">A full website for a spiritual teacher & author featuring articles, books, video series, multilingual support (English + Hindi), and donations.</p>
                        </div>
                        <div class="pt-4 border-t border-gray-800 flex items-center justify-between">
                            <span class="text-xs font-mono text-gray-500">Production Ready</span>
                            <a href="https://guruji-shrawan.vercel.app/" target="_blank" class="px-4 py-1.5 rounded-xl text-xs font-bold bg-purple-600 hover:bg-purple-500 text-white transition-all shadow-md shadow-purple-600/30">
                                View Live →
                            </a>
                        </div>
                    </div>

                    <!-- Project 2 -->
                    <div class="glass-panel rounded-2xl p-6 flex flex-col justify-between group hover:shadow-purple-500/10 transition-all">
                        <div>
                            <div class="flex items-center justify-between mb-3">
                                <span class="text-xs font-mono uppercase tracking-wider px-3 py-1 rounded-full bg-cyan-500/20 text-cyan-300 border border-cyan-500/30">Python CLI</span>
                                <a href="https://github.com/heyitskushagra/school-management_26-27" target="_blank" class="text-purple-400 hover:text-white transition-colors">
                                    <i class="fa-brands fa-github text-base"></i>
                                </a>
                            </div>
                            <h4 class="text-lg font-bold text-white mb-2 group-hover:text-purple-300 transition-colors">🏫 School Management System</h4>
                            <p class="text-gray-400 text-sm mb-4">Python CLI app with Student, Teacher & Attendance modules, CSV file storage, class-wise marking, and automated low-attendance warnings.</p>
                        </div>
                        <div class="pt-4 border-t border-gray-800 flex items-center justify-between">
                            <span class="text-xs font-mono text-gray-500">Python 3 + CSV</span>
                            <a href="https://github.com/heyitskushagra/school-management_26-27" target="_blank" class="px-4 py-1.5 rounded-xl text-xs font-bold bg-gray-800 hover:bg-gray-700 text-gray-200 border border-gray-700 transition-all">
                                View Repo →
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- GitHub Stats & Streak Showcase -->
            <div class="glass-panel rounded-3xl p-6 md:p-8 space-y-6">
                <div class="flex items-center justify-between border-b border-gray-800 pb-4">
                    <h3 class="text-xl font-bold text-white flex items-center gap-2">
                        <i class="fa-solid fa-chart-line text-purple-400"></i> GitHub Analytics & Stats
                    </h3>
                    <span class="text-xs font-mono text-purple-400 bg-purple-500/10 px-3 py-1 rounded-full border border-purple-500/20">username: heyitskushagra</span>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                    <div class="bg-gray-950 p-4 rounded-2xl border border-gray-800 flex items-center justify-center">
                        <img src="https://github-readme-stats.vercel.app/api?username=heyitskushagra&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117" alt="GitHub Stats" class="w-full rounded-xl">
                    </div>
                    <div class="bg-gray-950 p-4 rounded-2xl border border-gray-800 flex items-center justify-center">
                        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=heyitskushagra&layout=compact&theme=radical&hide_border=true&bg_color=0d1117" alt="Top Languages" class="w-full rounded-xl">
                    </div>
                </div>

                <div class="bg-gray-950 p-4 rounded-2xl border border-gray-800 flex items-center justify-center overflow-x-auto">
                    <img src="https://github-readme-streak-stats.herokuapp.com/?user=heyitskushagra&theme=radical&hide_border=true&background=0d1117" alt="GitHub Streak" class="max-w-full">
                </div>
            </div>

            <!-- Contribution Snake Animation Mockup -->
            <div class="glass-panel rounded-3xl p-6 text-center space-y-4">
                <h3 class="text-lg font-bold text-white flex items-center justify-center gap-2">
                    <i class="fa-solid fa-gamepad text-purple-400"></i> Contribution Snake Animation
                </h3>
                <p class="text-xs md:text-sm text-gray-400 max-w-xl mx-auto">Automated contribution snake traversing your commits graph in dark mode perfection.</p>
                
                <div class="bg-gray-950 p-6 rounded-2xl border border-purple-500/20 flex flex-col items-center justify-center space-y-3">
                    <div class="w-full h-16 bg-gradient-to-r from-gray-900 via-purple-950/40 to-gray-900 rounded-xl flex items-center justify-between px-6 border border-gray-800">
                        <div class="flex space-x-2">
                            <span class="w-3 h-3 rounded bg-gray-800"></span>
                            <span class="w-3 h-3 rounded bg-purple-900"></span>
                            <span class="w-3 h-3 rounded bg-purple-700"></span>
                            <span class="w-3 h-3 rounded bg-purple-500 animate-pulse"></span>
                        </div>
                        <span class="font-mono text-xs text-purple-400">🐍 Eating commits for heyitskushagra...</span>
                        <div class="flex space-x-2">
                            <span class="w-3 h-3 rounded bg-pink-600"></span>
                            <span class="w-3 h-3 rounded bg-purple-600"></span>
                            <span class="w-3 h-3 rounded bg-gray-800"></span>
                        </div>
                    </div>
                    <span class="text-[11px] font-mono text-gray-500">Active SVG Endpoint: raw.githubusercontent.com/heyitskushagra/heyitskushagra/output/github-snake-dark.svg</span>
                </div>
            </div>

            <!-- Connect Section -->
            <div class="glass-panel rounded-3xl p-8 text-center space-y-6">
                <h3 class="text-2xl font-bold text-white">Let's Build Something Legendary Together 🤝</h3>
                <p class="text-sm text-gray-400 max-w-md mx-auto">Drop a star on my repositories if you love this setup, or reach out directly for collaborations!</p>

                <div class="flex flex-wrap justify-center gap-4">
                    <a href="https://linkedin.com/in/nitin-mishra" target="_blank" class="px-6 py-3 rounded-2xl font-semibold text-sm bg-blue-600 hover:bg-blue-500 text-white shadow-lg shadow-blue-600/30 flex items-center gap-2 transition-all">
                        <i class="fa-brands fa-linkedin text-lg"></i> LinkedIn Profile
                    </a>
                    <a href="https://instagram.com/heyitskushagra" target="_blank" class="px-6 py-3 rounded-2xl font-semibold text-sm bg-gradient-to-r from-purple-600 to-pink-600 hover:opacity-90 text-white shadow-lg shadow-pink-600/30 flex items-center gap-2 transition-all">
                        <i class="fa-brands fa-instagram text-lg"></i> Instagram
                    </a>
                </div>
            </div>

        </div>

        <!-- Tab 2: Raw Markdown Source Code -->
        <div id="tab-markdown" class="hidden space-y-4 animate-fadeIn">
            <div class="flex items-center justify-between bg-gray-900 px-4 py-3 rounded-t-2xl border border-gray-800">
                <span class="text-xs font-mono text-purple-400 flex items-center gap-2">
                    <i class="fa-brands fa-markdown text-purple-400 text-lg"></i> README.md (Fully Updated for heyitskushagra)
                </span>
                <button onclick="copyMarkdownText()" class="px-3 py-1.5 rounded-lg text-xs font-bold bg-purple-600 hover:bg-purple-500 text-white transition-all">
                    <i class="fa-solid fa-copy"></i> Copy Markdown
                </button>
            </div>
            
            <div class="bg-gray-950 border border-gray-800 rounded-b-2xl p-6 overflow-x-auto max-h-[600px] custom-scrollbar">
                <pre id="markdown-source" class="font-mono text-xs md:text-sm text-gray-300 leading-relaxed"><code>&lt;img src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=6,11,20&amp;height=230&amp;section=header&amp;text=Nitin%20Mishra&amp;fontSize=64&amp;fontAlignY=38&amp;desc=Aspiring%20Coder%20%E2%80%A2%20Designer%20%E2%80%A2%20Builder&amp;descAlignY=58&amp;animation=fadeIn" width="100%" alt="banner"/&gt;

&lt;div align="center"&gt;

&[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&width=760&lines=Hi%2C+I'm+Nitin+Mishra+%F0%9F%91%8B;Turning+ideas+into+clean+code+%F0%9F%92%BB;React+%C2%B7+TypeScript+%C2%B7+Python+%C2%B7+.NET;I+build+things+that+look+as+good+as+they+work+%E2%9C%A8)](https://git.io/typing-svg)

![Profile Views](https://komarev.com/ghpvc/?username=heyitskushagra&label=Profile+Views&color=a855f7&style=for-the-badge)
[![Website](https://img.shields.io/badge/Live%20Project-guruji--shrawan.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://guruji-shrawan.vercel.app/)

&lt;/div&gt;

---

## 👨‍💻 About Me

```js
const nitin = {
  name: "Nitin Mishra",
  role: "Aspiring Coder & Designer",
  location: "India 🇮🇳",
  education: "Class 11 (PCM + AI)",
  codes: ["HTML", "CSS", "Python", "C", "React", "TypeScript", ".NET"],
  designs: ["Adobe Tools", "UI / Graphic Design"],
  currentlyBuilding: "Full-stack projects that people actually use",
  funFact: "I can code the UI and design it too 🎨",
  lookingFor: "Collaborations & amazing projects 🤝",
};

```
## ⚡ Tech Arsenal
<div align="center">
<img src="https://skillicons.dev/icons?i=html,css,py,c,react,ts,dotnet&theme=dark" alt="languages"/>
<br/>
<img src="https://skillicons.dev/icons?i=git,github,vercel,vscode&theme=dark" alt="tools"/>
</div>
## 🚀 Featured Projects
| 🌐 Guruji Shrawan Platform | 🏫 School Management System |
|---|---|
| A full website for a spiritual teacher & author: articles, books, video series, sign-in/sign-up, donations. | Python CLI app with Student, Teacher & Attendance modules & CSV storage. |
| React / Next.js TypeScript Vercel | Python CSV File Handling CLI |
|  |  |
## 📊 GitHub Stats
<div align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=heyitskushagra&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117" alt="stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=heyitskushagra&layout=compact&theme=radical&hide_border=true&bg_color=0d1117" alt="languages"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=heyitskushagra&theme=radical&hide_border=true&background=0d1117" alt="streak"/>
</div>
## 🐍 Contribution Snake
<div align="center">
<img alt="snake animation" src="https://raw.githubusercontent.com/heyitskushagra/heyitskushagra/output/github-snake.svg" />
</div>
## 🤝 Let's Connect
<div align="center">


</div></code></pre>
</div>
</div>
</div>
<!-- Toast Notification Box -->
<div id="toast" class="fixed bottom-6 right-6 z-50 transform translate-y-24 opacity-0 transition-all duration-300 bg-purple-600 text-white px-6 py-3 rounded-2xl shadow-2xl font-semibold flex items-center gap-3 border border-purple-400/40">
<i class="fa-solid fa-circle-check text-xl"></i>
<span id="toast-message">Markdown successfully copied to clipboard!</span>
</div>
<!-- Script Logic -->
<script>
function switchTab(tab) {
const previewTab = document.getElementById('tab-preview');
const markdownTab = document.getElementById('tab-markdown');
const btnPreview = document.getElementById('btn-preview');
const btnMarkdown = document.getElementById('btn-markdown');
if (tab === 'preview') {
previewTab.classList.remove('hidden');
markdownTab.classList.add('hidden');
btnPreview.className = "px-5 py-2.5 rounded-xl text-sm font-semibold transition-all duration-300 bg-purple-600 text-white shadow-lg shadow-purple-600/30 flex items-center gap-2";
btnMarkdown.className = "px-5 py-2.5 rounded-xl text-sm font-semibold transition-all duration-300 bg-gray-800 text-gray-300 hover:bg-gray-700 hover:text-white border border-gray-700 flex items-center gap-2";
} else {
previewTab.classList.add('hidden');
markdownTab.classList.remove('hidden');
btnMarkdown.className = "px-5 py-2.5 rounded-xl text-sm font-semibold transition-all duration-300 bg-purple-600 text-white shadow-lg shadow-purple-600/30 flex items-center gap-2";
btnPreview.className = "px-5 py-2.5 rounded-xl text-sm font-semibold transition-all duration-300 bg-gray-800 text-gray-300 hover:bg-gray-700 hover:text-white border border-gray-700 flex items-center gap-2";
}
}
function showToast(msg) {
const toast = document.getElementById('toast');
document.getElementById('toast-message').innerText = msg;
toast.classList.remove('translate-y-24', 'opacity-0');
setTimeout(() => {
toast.classList.add('translate-y-24', 'opacity-0');
}, 3000);
}
function copyMarkdownText() {
const codeEl = document.getElementById('markdown-source');
const text = codeEl.innerText;
const textarea = document.createElement('textarea');
textarea.value = text;
document.body.appendChild(textarea);
textarea.select();
document.execCommand('copy');
document.body.removeChild(textarea);
showToast("GitHub Markdown copied successfully!");
}
function copyReadmeCode() {
copyMarkdownText();
}
</script>
</body>
</html>
```

```

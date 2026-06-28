  {/* Hero Section - 3D + Typing Effect */}
  <section className="h-screen flex items-center justify-center relative overflow-hidden">
    <div className="absolute inset-0 bg-gradient-to-br from-blue-600/20 via-purple-600/20 to-transparent" />
    <motion.div 
      initial={{ opacity: 0, y: 20 }}
      animate={{ opacity: 1, y: 0 }}
      className="text-center z-10 px-4"
    >
      <img 
        src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Awais%20Ibn%20Luqman&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32"
        alt="header" className="mx-auto mb-8 rounded-2xl"
      />
      <h2 className="text-4xl md:text-6xl font-bold mb-4 font-[Poppins]">
        AI Developer × Quran + Code
      </h2>
      <p className="text-lg text-gray-400 mb-8">
        4th Semester BS Artificial Intelligence · Building for the Ummah, Deploy with Tawakkul
      </p>
      <div className="flex gap-4 justify-center">
        <a href="https://linkedin.com/in/calestial-mind-54633b410/" className="flex items-center gap-2 px-6 py-3 bg-white text-black rounded-full font-medium hover:scale-105 transition">
          LinkedIn <ArrowUpRight size={18} />
        </a>
        <a href="https://github.com/abdulghani50734" className="flex items-center gap-2 px-6 py-3 border border-white/20 rounded-full font-medium hover:bg-white/10 transition">
          GitHub <Github size={18} />
        </a>
      </div>
    </motion.div>
  </section>

  {/* Bento Grid Projects */}
  <section className="max-w-7xl mx-auto px-6 py-24">
    <h3 className="text-3xl font-bold mb-12 font-[Poppins]">Featured Work</h3>
    <div className="grid grid-cols-1 md:grid-cols-3 gap-4">
      <div className="md:col-span-2 bg-gradient-to-br from-blue-600 to-purple-600 p-8 rounded-3xl">
        <h4 className="text-2xl font-bold mb-2">Quran AI Chatbot</h4>
        <p className="text-white/80">NLP model trained on Tafseer. Answers with dalail.</p>
      </div>
      <div className="bg-white/5 p-8 rounded-3xl border border-white/10">
        <h4 className="text-xl font-bold mb-2">Islamic Reel Generator</h4>
        <p className="text-gray-400">Auto creates viral Islamic videos</p>
      </div>
      <div className="bg-white/5 p-8 rounded-3xl border border-white/10">
        <img 
          src="https://github.com/abdulghani50734/abdulghani50734/blob/output/github-contribution-grid-snake-dark.svg" 
          alt="snake" className="rounded-xl"
        />
      </div>
      <div className="md:col-span-2 bg-white/5 p-8 rounded-3xl border border-white/10">
        <h4 className="text-xl font-bold mb-2">Currently: 4th Semester BS AI</h4>
        <p className="text-gray-400">Deep Learning · Computer Vision · LLM Fine-tuning</p>
      </div>
    </div>
  </section>

  <footer className="text-center py-12 text-gray-500 text-sm">
    Built with Tawakkul · © 2026 Awais Ibn Luqman
  </footer>
</main>

<meta name='viewport' content='width=device-width, initial-scale=1'/>import React, { useState, useEffect, useRef } from 'react';
import { Heart, Stars, Music, Gift, MessageCircle, Sparkles, Play, Pause, X, Mail, Smile, Infinity } from 'lucide-react';

const LoveApp = () => {
  const [activeTab, setActiveTab] = useState(0);
  const [isPlaying, setIsPlaying] = useState(false);
  const [showHeartRain, setShowHeartRain] = useState(false);
  const [showLetter, setShowLetter] = useState(false);
  const [openedGift, setOpenedGift] = useState(null); // null, 1, 2, 3
  const [greeting, setGreeting] = useState('');
  const [clickEffects, setClickEffects] = useState([]);

  // Time-based greeting
  useEffect(() => {
    const hour = new Date().getHours();
    if (hour < 12) setGreeting('Good Morning, Jaan ☀️');
    else if (hour < 18) setGreeting('Good Afternoon, Baby 🌤️');
    else setGreeting('Good Evening, My Love 🌙');
  }, []);

  // Handle global click for heart effects
  const handleGlobalClick = (e) => {
    const id = Date.now();
    const newEffect = { id, x: e.clientX, y: e.clientY };
    setClickEffects(prev => [...prev, newEffect]);
    setTimeout(() => {
      setClickEffects(prev => prev.filter(effect => effect.id !== id));
    }, 1000);
  };

  const triggerHeartRain = () => {
    setShowHeartRain(true);
    setTimeout(() => setShowHeartRain(false), 5000);
  };

  // Gift Content Data
  const giftContents = {
    1: {
      title: "For You 🌹",
      icon: <span className="text-4xl animate-bounce">🌹</span>,
      text: "Ek phool uske liye jo khud ek phool hai.",
      sub: "You are my most beautiful rose."
    },
    2: {
      title: "My Heart ❤️",
      icon: <Heart className="w-12 h-12 text-red-600 fill-current animate-beat" />,
      text: "Sambhal ke rakhna, ab ye tumhara hai.",
      sub: "Forever yours."
    },
    3: {
      title: "A Promise 💍",
      icon: <div className="relative"><div className="w-8 h-8 rounded-full border-4 border-yellow-400 shadow-[0_0_10px_gold]"></div><div className="absolute -top-3 left-1/2 -translate-x-1/2 text-blue-400">💎</div></div>,
      text: "Hamesha saath nibhaane ka vaada.",
      sub: "Till my last breath."
    }
  };

  const renderGiftModal = () => (
    <div className="fixed inset-0 z-[60] flex items-center justify-center bg-black/60 backdrop-blur-sm p-4 animate-fade-in">
      <div className="bg-white rounded-3xl p-8 max-w-sm w-full relative shadow-2xl text-center border-4 border-pink-100 transform scale-100 transition-all">
        <button 
          onClick={() => setOpenedGift(null)} 
          className="absolute top-4 right-4 text-gray-400 hover:text-gray-600"
        >
          <X size={24} />
        </button>
        
        <div className="mb-6 flex justify-center h-20 items-center">
          {giftContents[openedGift].icon}
        </div>
        
        <h3 className="text-2xl font-bold text-gray-800 mb-2 font-handwriting">{giftContents[openedGift].title}</h3>
        <p className="text-lg text-gray-600 mb-2">{giftContents[openedGift].text}</p>
        <p className="text-sm text-pink-500 font-medium tracking-widest uppercase">{giftContents[openedGift].sub}</p>
        
        <button 
          onClick={() => { setOpenedGift(null); triggerHeartRain(); }}
          className="mt-8 px-6 py-2 bg-gradient-to-r from-pink-400 to-rose-500 text-white rounded-full font-medium shadow-lg active:scale-95 transition-transform"
        >
          Accept with Love
        </button>
      </div>
    </div>
  );

  const tabs = [
    {
      id: 0,
      title: "Dil Ka Haal",
      icon: <Heart className="w-5 h-5" />,
      theme: "rose",
      content: (
        <div className="space-y-6 text-center relative z-10">
          <div className="inline-block p-3 rounded-full bg-rose-100 mb-2 animate-pulse">
            <Heart className="w-8 h-8 text-rose-500 fill-current" />
          </div>
          <h2 className="text-2xl font-bold text-rose-900 font-handwriting">Mera Haal-e-Dil</h2>
          <div className="relative p-6 bg-white/60 backdrop-blur-sm rounded-xl border border-rose-100 shadow-sm group hover:scale-[1.02] transition-transform">
            <p className="text-xl font-handwriting leading-loose text-rose-800">
              "Dil ka jo haal h,<br/>
              Wo <span className="text-rose-600 font-bold">AAPSE</span> kese byaan kru,<br/>
              Keh du <span className="text-rose-600 font-bold">AAPSE</span> y dil m rkhu,<br/>
              Boliye na ky kru..."
            </p>
          </div>
        </div>
      )
    },
    {
      id: 1,
      title: "Aapka Dil",
      icon: <Sparkles className="w-5 h-5" />,
      theme: "purple",
      content: (
        <div className="space-y-6 text-center relative z-10">
          <div className="inline-block p-3 rounded-full bg-purple-100 mb-2">
            <Sparkles className="w-8 h-8 text-purple-600 animate-spin-slow" />
          </div>
          <h2 className="text-2xl font-bold text-purple-900 font-handwriting">Mera Sahara</h2>
          <div className="relative p-6 bg-white/60 backdrop-blur-sm rounded-xl border border-purple-100 shadow-sm">
            <p className="text-xl font-handwriting leading-loose text-purple-900">
              "Dil jo <span className="text-purple-600 font-bold">AAPKA</span> h, kitna pyaara h<br/>
              Seedha sa, sachcha sa, dil ka sahaara h..."
            </p>
             <p className="mt-4 text-purple-700 font-medium text-sm border-t border-purple-200 pt-3">
              ❤️ Aapka dil sabse sundar hai ❤️
            </p>
          </div>
        </div>
      )
    },
    {
      id: 2,
      title: "Wafaa",
      icon: <Stars className="w-5 h-5" />,
      theme: "blue",
      content: (
        <div className="space-y-6 text-center relative z-10">
           <div className="inline-block p-3 rounded-full bg-blue-100 mb-2">
            <Stars className="w-8 h-8 text-blue-600" />
          </div>
          <h2 className="text-2xl font-bold text-blue-900 font-handwriting">Meri Dua</h2>
          <div className="relative p-6 bg-white/60 backdrop-blur-sm rounded-xl border border-blue-100 shadow-sm">
            <p className="text-xl font-handwriting leading-loose text-blue-900">
              "Rishta bhale hi naam ka na ho<br/>
              Par ehsaas dil se juda na ho<br/>
              <span className="text-blue-600 font-bold">AAP</span> hi meri dua..."
            </p>
          </div>
        </div>
      )
    },
    {
      id: 3,
      title: "Surprises",
      icon: <Gift className="w-5 h-5" />,
      theme: "emerald",
      content: (
        <div className="space-y-6 text-center relative z-10 w-full">
          <div className="inline-block p-3 rounded-full bg-emerald-100 mb-2">
            <Gift className="w-8 h-8 text-emerald-600 animate-bounce" />
          </div>
          <h2 className="text-2xl font-bold text-emerald-900 font-handwriting">Pick a Gift, My Love</h2>
          
          <div className="grid grid-cols-3 gap-3 mt-4">
             {[1, 2, 3].map((num) => (
               <button
                 key={num}
                 onClick={() => setOpenedGift(num)}
                 className="aspect-square bg-gradient-to-br from-emerald-400 to-teal-600 rounded-xl shadow-lg flex items-center justify-center transform hover:scale-105 active:scale-95 transition-all relative group overflow-hidden"
               >
                 <div className="absolute inset-0 bg-white opacity-0 group-hover:opacity-20 transition-opacity"></div>
                 {/* Ribbon */}
                 <div className="absolute inset-0 flex items-center justify-center">
                    <div className="w-2 h-full bg-yellow-300/80"></div>
                    <div className="h-2 w-full bg-yellow-300/80 absolute"></div>
                 </div>
                 <span className="text-3xl filter drop-shadow-md z-10">🎁</span>
               </button>
             ))}
          </div>
          <p className="text-emerald-800 text-sm mt-2 italic">Tap a box to unwrap...</p>
        </div>
      )
    },
    {
      id: 4,
      title: "Fidaa",
      icon: <Music className="w-5 h-5" />,
      theme: "fuchsia",
      content: (
        <div className="space-y-6 text-center relative z-10">
          <div className="inline-block p-3 rounded-full bg-fuchsia-100 mb-2">
            <Music className="w-8 h-8 text-fuchsia-600" />
          </div>
          <h2 className="text-2xl font-bold text-fuchsia-900 font-handwriting">Aap Par Fidaa</h2>
          <div className="relative p-6 bg-white/60 backdrop-blur-sm rounded-xl border border-fuchsia-100 shadow-sm">
            <p className="text-xl font-handwriting leading-loose text-fuchsia-900">
              "Jaane kyon dil y mera h AAPKE pyaar m<br/>
              Laakhon wajahen basi h is ikraar m<br/>
              H y <span className="text-fuchsia-600 font-bold">AAP</span> par fidaa..."
            </p>
          </div>
        </div>
      )
    },
    {
      id: 5,
      title: "Qaraar",
      icon: <MessageCircle className="w-5 h-5" />,
      theme: "red",
      content: (
        <div className="space-y-6 text-center relative z-10">
          <div className="inline-block p-3 rounded-full bg-red-100 mb-2">
            <MessageCircle className="w-8 h-8 text-red-600" />
          </div>
          <h2 className="text-2xl font-bold text-red-900 font-handwriting">Sirf Aapko Kahoon</h2>
          <div className="relative p-6 bg-white/60 backdrop-blur-sm rounded-xl border border-red-100 shadow-sm">
            <p className="text-xl font-handwriting leading-loose text-red-900">
              "Dil ke khayalon m, meethe sawaalon m<br/>
              Lafz naye bunoon, sirf <span className="text-red-600 font-bold">AAPKO</span> kahoon..."
            </p>
            <div className="mt-6 flex flex-col items-center gap-3">
               <p className="text-sm text-red-500 opacity-80 mb-1">Make a wish & tap below</p>
               <button 
                onClick={triggerHeartRain}
                className="w-full py-3 bg-gradient-to-r from-red-500 to-pink-500 text-white rounded-xl shadow-lg transform active:scale-95 transition-all flex items-center justify-center gap-2 group"
               >
                 <Heart className="w-5 h-5 fill-current group-hover:animate-ping" />
                 Send My Love
               </button>
            </div>
          </div>
        </div>
      )
    }
  ];

  const getThemeColors = (theme) => {
    const colors = {
      rose: "from-rose-50 to-pink-100 text-rose-600",
      purple: "from-purple-50 to-violet-100 text-purple-600",
      blue: "from-blue-50 to-indigo-100 text-blue-600",
      emerald: "from-emerald-50 to-teal-100 text-emerald-600",
      fuchsia: "from-fuchsia-50 to-pink-100 text-fuchsia-600",
      red: "from-red-50 to-rose-100 text-red-600",
    };
    return colors[theme] || colors.rose;
  };

  return (
    <div className="min-h-screen bg-gray-200 flex items-center justify-center p-4 select-none" onClick={handleGlobalClick}>
      
      {/* Phone Case */}
      <div className="w-full max-w-[400px] h-[850px] bg-white rounded-[3rem] shadow-2xl overflow-hidden border-[8px] border-gray-900 relative flex flex-col">
        
        {/* Dynamic Background */}
        <div className={`absolute inset-0 bg-gradient-to-br ${getThemeColors(tabs[activeTab].theme).split(' ')[0]} transition-all duration-700 ease-in-out`}>
            {/* Animated Background Elements */}
            <div className="absolute top-0 left-0 w-full h-full overflow-hidden opacity-30 pointer-events-none">
                <div className="absolute top-[10%] left-[20%] w-32 h-32 bg-white rounded-full mix-blend-overlay filter blur-xl animate-blob"></div>
                <div className="absolute top-[30%] right-[20%] w-32 h-32 bg-pink-300 rounded-full mix-blend-overlay filter blur-xl animate-blob animation-delay-2000"></div>
                <div className="absolute bottom-[20%] left-[30%] w-32 h-32 bg-purple-300 rounded-full mix-blend-overlay filter blur-xl animate-blob animation-delay-4000"></div>
            </div>
        </div>

        {/* Notch & Status */}
        <div className="absolute top-0 left-1/2 transform -translate-x-1/2 h-7 w-32 bg-gray-900 rounded-b-2xl z-50"></div>
        <div className="h-8 w-full z-50 flex justify-between px-6 pt-2 text-xs font-medium text-gray-600">
            <span>100% ❤️</span>
        </div>

        {/* App Header */}
        <div className="relative z-20 px-6 pt-10 pb-4">
            <div className="flex justify-between items-center mb-4">
                <div>
                    <p className="text-xs font-semibold text-gray-500 uppercase tracking-wider">My Forever</p>
                    <h1 className="text-lg font-bold text-gray-800">{greeting}</h1>
                </div>
                {/* Floating Letter Button */}
                <button 
                  onClick={(e) => { e.stopPropagation(); setShowLetter(true); }}
                  className="w-10 h-10 rounded-full bg-white/50 backdrop-blur-md shadow-sm flex items-center justify-center border border-white animate-bounce-slow"
                >
                    <Mail className="w-5 h-5 text-rose-500" />
                </button>
            </div>

            {/* Music Player Mini */}
            <div className="bg-white/40 backdrop-blur-md rounded-2xl p-3 flex items-center gap-3 border border-white/50 shadow-sm">
                <div className={`w-10 h-10 rounded-full flex items-center justify-center ${isPlaying ? 'bg-rose-500 text-white' : 'bg-gray-200 text-gray-500'} transition-colors`}>
                    <Music size={18} />
                </div>
                <div className="flex-1 min-w-0">
                    <p className="text-sm font-bold text-gray-800 truncate">Dil Ka Qaraar.mp3</p>
                    <div className="flex items-center gap-1 h-3">
                        {isPlaying ? (
                            <>
                                <div className="w-1 bg-rose-500 h-full animate-music-bar"></div>
                                <div className="w-1 bg-rose-500 h-2/3 animate-music-bar animation-delay-100"></div>
                                <div className="w-1 bg-rose-500 h-full animate-music-bar animation-delay-200"></div>
                            </>
                        ) : <p className="text-xs text-gray-500">Tap to play</p>}
                    </div>
                </div>
                <button 
                    onClick={(e) => { e.stopPropagation(); setIsPlaying(!isPlaying); }}
                    className="p-2 bg-white rounded-full shadow-sm"
                >
                    {isPlaying ? <Pause size={16} /> : <Play size={16} className="ml-0.5" />}
                </button>
            </div>
        </div>

        {/* Main Content Area */}
        <div className="flex-1 relative z-10 px-4 overflow-hidden flex flex-col justify-center pb-20">
            <div className="transition-all duration-500 transform">
                <div className="bg-white/70 backdrop-blur-xl rounded-[2rem] shadow-xl p-1 min-h-[420px] border border-white/60 relative overflow-hidden flex flex-col">
                    <div className={`absolute top-0 right-0 w-24 h-24 bg-gradient-to-bl ${getThemeColors(tabs[activeTab].theme).split(' ')[0]} opacity-50 rounded-bl-[4rem]`}></div>
                    
                    <div className="flex-1 w-full flex flex-col items-center justify-center p-6">
                       {tabs[activeTab].content}
                    </div>

                    <div className="pb-4 w-full flex justify-center gap-2">
                        {tabs.map((_, idx) => (
                            <div key={idx} className={`h-1.5 rounded-full transition-all duration-300 ${activeTab === idx ? 'w-6 bg-gray-800' : 'w-1.5 bg-gray-300'}`}></div>
                        ))}
                    </div>
                </div>
            </div>
        </div>

        {/* Bottom Tab Bar */}
        <div className="absolute bottom-6 left-4 right-4 bg-white/90 backdrop-blur-xl rounded-2xl shadow-[0_8px_30px_rgb(0,0,0,0.12)] p-2 z-30 border border-white/50">
            <div className="flex justify-between items-center px-1">
                {tabs.map((tab, index) => (
                    <button
                        key={tab.id}
                        onClick={(e) => { e.stopPropagation(); setActiveTab(index); }}
                        className={`relative p-3 rounded-xl transition-all duration-300 flex flex-col items-center gap-1 min-w-[50px] ${
                            activeTab === index 
                            ? 'bg-gray-100 text-gray-900 -translate-y-4 shadow-lg border border-white' 
                            : 'text-gray-400 hover:text-gray-600'
                        }`}
                    >
                        {React.cloneElement(tab.icon, { 
                            size: 20, 
                            className: activeTab === index ? tab.theme.split(' ').pop() : 'currentColor' 
                        })}
                        {activeTab === index && (
                             <span className="text-[9px] font-bold absolute -bottom-4 w-max opacity-0 animate-fade-in-up">
                                {tab.title}
                            </span>
                        )}
                    </button>
                ))}
            </div>
        </div>

        {/* MODALS & OVERLAYS */}
        
        {/* 1. Heart Rain */}
        {showHeartRain && (
            <div className="absolute inset-0 z-50 pointer-events-none overflow-hidden">
                {[...Array(30)].map((_, i) => (
                    <div 
                        key={i}
                        className="absolute text-red-500 animate-fall"
                        style={{
                            left: `${Math.random() * 100}%`,
                            animationDuration: `${Math.random() * 2 + 3}s`,
                            animationDelay: `${Math.random() * 2}s`,
                            opacity: Math.random() * 0.5 + 0.5,
                            fontSize: `${Math.random() * 24 + 12}px`
                        }}
                    >
                        {['❤️', '💖', '💝', '🌹'][Math.floor(Math.random()*4)]}
                    </div>
                ))}
            </div>
        )}

        {/* 2. Gift Modal */}
        {openedGift && renderGiftModal()}

        {/* 3. Secret Letter Modal */}
        {showLetter && (
            <div className="fixed inset-0 z-[70] flex items-center justify-center bg-black/60 backdrop-blur-md p-4 animate-fade-in">
                <div className="bg-[#fff9f0] w-full max-w-sm rounded shadow-2xl p-8 relative rotate-1 border-2 border-gray-200">
                     <button 
                      onClick={() => setShowLetter(false)} 
                      className="absolute top-2 right-2 text-gray-400 hover:text-gray-600"
                    >
                      <X size={24} />
                    </button>
                    <div className="absolute -top-4 left-1/2 -translate-x-1/2 w-16 h-8 bg-red-800/20 blur-xl rounded-full"></div>
                    
                    <div className="border-b border-gray-300 pb-4 mb-4 text-center">
                        <h3 className="font-handwriting text-3xl text-gray-800">My Secret Note</h3>
                        <p className="text-xs text-gray-500 uppercase tracking-widest mt-1">For your eyes only</p>
                    </div>
                    
                    <div className="space-y-4 text-gray-700 font-serif leading-relaxed text-lg">
                        <p>Mere Pyaare,</p>
                        <p>
                            Kabhi kabhi lafz kam pad jaate hain ye batane ke liye ki tum mere liye kya ho. 
                            Tum sirf meri mohabbat nahi, meri aadat, meri zaroorat, aur mera sukoon ho.
                        </p>
                        <p>
                            Thank you for being in my life.
                        </p>
                        <p className="text-right mt-6 font-handwriting text-xl text-rose-600">- Yours Forever</p>
                    </div>
                    
                    <div className="absolute bottom-4 right-8 opacity-10 rotate-12">
                        <Heart size={100} className="text-red-500" />
                    </div>
                </div>
            </div>
        )}

        {/* 4. Click Touch Effects (Small Hearts on Tap) */}
        {clickEffects.map(effect => (
            <div
                key={effect.id}
                className="fixed pointer-events-none text-rose-500 animate-ping-fade z-[100]"
                style={{ left: effect.x, top: effect.y, transform: 'translate(-50%, -50%)' }}
            >
                <Heart size={20} fill="currentColor" />
            </div>
        ))}

      </div>

      <style jsx global>{`
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600;700&family=Outfit:wght@300;400;500;600&display=swap');
        
        body { font-family: 'Outfit', sans-serif; }
        .font-handwriting { font-family: 'Dancing Script', cursive; }

        @keyframes blob {
          0% { transform: translate(0px, 0px) scale(1); }
          33% { transform: translate(30px, -50px) scale(1.1); }
          66% { transform: translate(-20px, 20px) scale(0.9); }
          100% { transform: translate(0px, 0px) scale(1); }
        }
        .animate-blob { animation: blob 7s infinite; }
        .animation-delay-2000 { animation-delay: 2s; }
        .animation-delay-4000 { animation-delay: 4s; }

        @keyframes music-bar {
            0%, 100% { height: 100%; }
            50% { height: 30%; }
        }
        .animate-music-bar { animation: music-bar 1s infinite ease-in-out; }

        @keyframes fall {
            0% { transform: translateY(-20px) rotate(0deg); opacity: 1; }
            100% { transform: translateY(800px) rotate(360deg); opacity: 0; }
        }
        .animate-fall { animation: fall linear forwards; }

        @keyframes ping-fade {
            0% { transform: scale(0.5); opacity: 1; }
            100% { transform: scale(2); opacity: 0; }
        }
        .animate-ping-fade { animation: ping-fade 0.8s ease-out forwards; }
        
        @keyframes beat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.15); }
        }
        .animate-beat { animation: beat 1s infinite; }

        .animate-bounce-slow { animation: bounce 3s infinite; }
        .animate-spin-slow { animation: spin 4s linear infinite; }
        @keyframes spin { 100% { transform: rotate(360deg); } }
      `}</style>
    </div>
  );
};

export default LoveApp;

m-4 left-4 text-xs text-gray-500 bg-white/80 backdrop-blur-sm px-3 py-2 rounded-lg">
        💡 Click anywhere for love hearts!
      </div>

      <style jsx global>{`
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600;700&family=Outfit:wght@300;400;500;600&display=swap');
        
        body { 
            font-family: 'Outfit', sans-serif;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        .font-handwriting { font-family: 'Dancing Script', cursive; }

        @keyframes blob {
          0% { transform: translate(0px, 0px) scale(1); }
          33% { transform: translate(30px, -50px) scale(1.1); }
          66% { transform: translate(-20px, 20px) scale(0.9); }
          100% { transform: translate(0px, 0px) scale(1); }
        }
        .animate-blob { animation: blob 7s infinite; }
        .animation-delay-2000 { animation-delay: 2s; }
        .animation-delay-4000 { animation-delay: 4s; }

        @keyframes music-bar {
            0%, 100% { height: 100%; }
            50% { height: 30%; }
        }
        .animate-music-bar { animation: music-bar 1s infinite ease-in-out; }

        @keyframes fall {
            0% { transform: translateY(-20px) rotate(0deg); opacity: 1; }
            100% { transform: translateY(800px) rotate(360deg); opacity: 0; }
        }
        .animate-fall { animation: fall linear forwards; }

        @keyframes ping-fade {
            0% { transform: translate(-50%, -50%) scale(0.5); opacity: 1; }
            100% { transform: translate(-50%, -50%) scale(2); opacity: 0; }
        }
        .animate-ping-fade { animation: ping-fade 0.8s ease-out forwards; }
        
        @keyframes beat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.15); }
        }
        .animate-beat { animation: beat 1s infinite; }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-5px); }
        }
        .animate-bounce-slow { animation: bounce 3s infinite; }
        .animate-spin-slow { animation: spin 4s linear infinite; }
        @keyframes spin { 100% { transform: rotate(360deg); } }

        @keyframes fade-in-up {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate-fade-in-up { animation: fade-in-up 0.3s ease-out forwards; }

        @keyframes fade-in {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .animate-fade-in { animation: fade-in 0.3s ease-out; }
      `}</style>
    </div>
  );
};

export default LoveApp;
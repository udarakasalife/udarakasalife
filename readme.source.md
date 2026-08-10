# Dazeyuratama.

<p align="center">
  <strong>Software Engineer · Open Source Contributor · Builder</strong>
</p>

```aura width=860 height=250 link="https://www.dazeyuratama.engineer"
<div style={{
  width:'100%',height:'100%',background:'#070908',
  borderRadius:22,border:'1px solid rgba(195,255,54,0.20)',
  display:'flex',flexDirection:'column',alignItems:'center',justifyContent:'center',
  fontFamily:'Inter, sans-serif',position:'relative',overflow:'hidden',boxSizing:'border-box'
}}>
  <style>{`
    @keyframes dzPulseA {
      0%,100% { opacity:.20; transform:scale(1); }
      50% { opacity:.42; transform:scale(1.14); }
    }
    @keyframes dzPulseB {
      0%,100% { opacity:.14; transform:scale(1.04); }
      50% { opacity:.34; transform:scale(1.16); }
    }
    @keyframes dzDriftA {
      0%,100% { transform:translateX(-18px) translateY(2px); }
      50% { transform:translateX(28px) translateY(-10px); }
    }
    @keyframes dzDriftB {
      0%,100% { transform:translateX(18px) translateY(4px); }
      50% { transform:translateX(-28px) translateY(-8px); }
    }
    #dz-glow-a { animation:dzPulseA 6s ease-in-out infinite, dzDriftA 10s ease-in-out infinite; transform-origin:center; }
    #dz-glow-b { animation:dzPulseB 7s ease-in-out infinite, dzDriftB 11s ease-in-out infinite; transform-origin:center; }
  `}</style>

  <svg width="860" height="250" style={{position:'absolute',top:0,left:0}}>
    <defs>
      <radialGradient id="dz-lime" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(195,255,54,0.34)" />
        <stop offset="55%" stopColor="rgba(195,255,54,0.12)" />
        <stop offset="100%" stopColor="rgba(195,255,54,0)" />
      </radialGradient>
      <radialGradient id="dz-purple" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(140,100,255,0.25)" />
        <stop offset="55%" stopColor="rgba(140,100,255,0.09)" />
        <stop offset="100%" stopColor="rgba(140,100,255,0)" />
      </radialGradient>
    </defs>
    <ellipse id="dz-glow-a" cx="150" cy="55" rx="245" ry="120" fill="url(#dz-lime)" />
    <ellipse id="dz-glow-b" cx="710" cy="195" rx="245" ry="120" fill="url(#dz-purple)" />
  </svg>

  <div style={{display:'flex',alignItems:'center',justifyContent:'center',gap:16}}>
    <img
      src={github?.user?.avatarUrl ?? 'https://github.com/udarakasalife.png'}
      width={62} height={62}
      style={{borderRadius:31,border:'2px solid rgba(195,255,54,0.62)',display:'block'}}
    />
    <div style={{display:'flex',flexDirection:'column',alignItems:'flex-start'}}>
      <span style={{fontSize:36,fontWeight:800,color:'#f5f7ef',letterSpacing:'-1px'}}>Dazeyuratama.</span>
      <span style={{fontSize:14,color:'#a7ad9e',marginTop:5}}>Software Engineer · Open Source Contributor</span>
    </div>
  </div>

  <div style={{display:'flex',alignItems:'center',justifyContent:'center',gap:9,marginTop:18}}>
    <span style={{padding:'6px 14px',borderRadius:16,background:'rgba(195,255,54,0.10)',border:'1px solid rgba(195,255,54,0.28)',color:'#d9ff7c',fontSize:12,fontWeight:700}}>BUILD</span>
    <span style={{padding:'6px 14px',borderRadius:16,background:'rgba(255,255,255,0.045)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:12,fontWeight:700}}>LEARN</span>
    <span style={{padding:'6px 14px',borderRadius:16,background:'rgba(255,255,255,0.045)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:12,fontWeight:700}}>SHIP</span>
  </div>

  <span style={{fontSize:12,color:'#7c8378',marginTop:14}}>Building modern web applications from Indonesia · UTC+7</span>
</div>
```

<p align="center"><strong>~/whoami</strong></p>

<p align="center">
I build modern web applications with a focus on clean interfaces, practical engineering,<br />
and projects that are meant to be used, not just shown.
</p>

<p align="center"><strong>~/stack</strong></p>

```aura width=820 height=92
<div style={{
  width:'100%',height:'100%',background:'#080a09',
  borderRadius:18,border:'1px solid rgba(195,255,54,0.15)',
  display:'flex',alignItems:'center',justifyContent:'center',gap:9,
  fontFamily:'Inter, sans-serif',boxSizing:'border-box',position:'relative',overflow:'hidden'
}}>
  <style>{`
    @keyframes dzStackGlow {
      0%,100% { opacity:.10; transform:translateX(-40px); }
      50% { opacity:.22; transform:translateX(40px); }
    }
    #dz-stack-glow { animation:dzStackGlow 8s ease-in-out infinite; }
  `}</style>
  <svg width="820" height="92" style={{position:'absolute',top:0,left:0}}>
    <defs>
      <linearGradient id="dz-stack-gradient" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stopColor="rgba(195,255,54,0)" />
        <stop offset="45%" stopColor="rgba(195,255,54,0.18)" />
        <stop offset="55%" stopColor="rgba(140,100,255,0.15)" />
        <stop offset="100%" stopColor="rgba(140,100,255,0)" />
      </linearGradient>
    </defs>
    <rect id="dz-stack-glow" x="-120" y="0" width="1060" height="92" fill="url(#dz-stack-gradient)" />
  </svg>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(195,255,54,0.10)',border:'1px solid rgba(195,255,54,0.24)',color:'#d9ff7c',fontSize:13,fontWeight:700}}>Next.js</span>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(195,255,54,0.10)',border:'1px solid rgba(195,255,54,0.24)',color:'#d9ff7c',fontSize:13,fontWeight:700}}>TypeScript</span>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(255,255,255,0.045)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:13,fontWeight:600}}>Node.js</span>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(255,255,255,0.045)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:13,fontWeight:600}}>PostgreSQL</span>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(255,255,255,0.045)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:13,fontWeight:600}}>Docker</span>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(255,255,255,0.045)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:13,fontWeight:600}}>Tailwind CSS</span>
</div>
```

<p align="center"><strong>~/connect</strong></p>

<p align="center">Find me around the internet.</p>

```aura width=125 height=46 link="https://github.com/udarakasalife" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/github/ffffff"
  text="GitHub"
  backgroundColor="#111312"
  textColor="#ffffff"
  width={125}
  height={46}
  gradientStops={[
    { offset:'0%', color:'#ffffff' },
    { offset:'22%', color:'#111312' },
    { offset:'50%', color:'#c3ff36' },
    { offset:'78%', color:'#111312' },
    { offset:'100%', color:'#555555' },
  ]}
  iconSize={20}
/>
```

```aura width=125 height=46 link="https://www.dazeyuratama.engineer" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/googlechrome/ffffff"
  text="Website"
  backgroundColor="#111312"
  textColor="#ffffff"
  width={125}
  height={46}
  gradientStops={[
    { offset:'0%', color:'#ffffff' },
    { offset:'22%', color:'#111312' },
    { offset:'50%', color:'#c3ff36' },
    { offset:'78%', color:'#111312' },
    { offset:'100%', color:'#555555' },
  ]}
  iconSize={20}
/>
```

```aura width=125 height=46 link="https://www.instagram.com/devxpxnyctrl_/" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/instagram/ffffff"
  text="Instagram"
  backgroundColor="#111312"
  textColor="#ffffff"
  width={125}
  height={46}
  gradientStops={[
    { offset:'0%', color:'#ffffff' },
    { offset:'22%', color:'#111312' },
    { offset:'50%', color:'#c3ff36' },
    { offset:'78%', color:'#111312' },
    { offset:'100%', color:'#555555' },
  ]}
  iconSize={20}
/>
```

```aura width=125 height=46 link="https://ko-fi.com/dazeyuratama" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/kofi/ffffff"
  text="Ko-fi"
  backgroundColor="#111312"
  textColor="#ffffff"
  width={125}
  height={46}
  gradientStops={[
    { offset:'0%', color:'#ffffff' },
    { offset:'22%', color:'#111312' },
    { offset:'50%', color:'#c3ff36' },
    { offset:'78%', color:'#111312' },
    { offset:'100%', color:'#555555' },
  ]}
  iconSize={20}
/>
```

<p align="center"><strong>~/support</strong></p>

<p align="center">
If my work is useful to you, you can support my projects and future experiments.
</p>

```aura width=820 height=78 link="https://ko-fi.com/dazeyuratama"
<div style={{
  width:'100%',height:'100%',background:'#0b0d0c',
  borderRadius:18,border:'1px solid rgba(195,255,54,0.24)',
  display:'flex',alignItems:'center',justifyContent:'center',
  fontFamily:'Inter, sans-serif',boxSizing:'border-box',position:'relative',overflow:'hidden'
}}>
  <style>{`
    @keyframes dzSupportGlow {
      0%,100% { opacity:.08; transform:translateX(-80px); }
      50% { opacity:.22; transform:translateX(80px); }
    }
    #dz-support-glow { animation:dzSupportGlow 9s ease-in-out infinite; }
  `}</style>
  <svg width="820" height="78" style={{position:'absolute',top:0,left:0}}>
    <defs>
      <linearGradient id="dz-support-gradient" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stopColor="rgba(195,255,54,0)" />
        <stop offset="50%" stopColor="rgba(195,255,54,0.22)" />
        <stop offset="100%" stopColor="rgba(140,100,255,0)" />
      </linearGradient>
    </defs>
    <rect id="dz-support-glow" x="-180" y="0" width="1180" height="78" fill="url(#dz-support-gradient)" />
  </svg>
  <span style={{fontSize:15,color:'#d9ff7c',fontWeight:800}}>☕ Support my work on Ko-fi</span>
</div>
```

```aura width=820 height=78
<div style={{
  width:'100%',height:'100%',background:'#080a09',
  borderRadius:18,border:'1px solid rgba(195,255,54,0.13)',
  display:'flex',flexDirection:'column',alignItems:'center',justifyContent:'center',
  fontFamily:'Inter, sans-serif',boxSizing:'border-box',position:'relative',overflow:'hidden'
}}>
  <style>{`
    @keyframes dzFooterPulse {
      0%,100% { opacity:.08; }
      50% { opacity:.20; }
    }
    #dz-footer-glow { animation:dzFooterPulse 6s ease-in-out infinite; }
  `}</style>
  <svg width="820" height="78" style={{position:'absolute',top:0,left:0}}>
    <defs>
      <radialGradient id="dz-footer-gradient" cx="50%" cy="50%" r="65%">
        <stop offset="0%" stopColor="rgba(195,255,54,0.18)" />
        <stop offset="42%" stopColor="rgba(140,100,255,0.08)" />
        <stop offset="100%" stopColor="rgba(140,100,255,0)" />
      </radialGradient>
    </defs>
    <rect id="dz-footer-glow" x="0" y="0" width="820" height="78" fill="url(#dz-footer-gradient)" />
  </svg>
  <span style={{fontSize:12,color:'#a7ad9e',fontWeight:650}}>Dazeyuratama. · Software Engineer</span>
  <span style={{fontSize:11,color:'#70776c',marginTop:5}}>Built with code, curiosity and consistency · 2026</span>
</div>
```

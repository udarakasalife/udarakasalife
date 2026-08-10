# Dazeyuratama.

<p align="center">
  Software Engineer · Open Source Contributor · Builder
</p>

```aura width=860 height=230 link="https://www.dazeyuratama.engineer"
<div style={{
  width:'100%', height:'100%', background:'#070908',
  borderRadius:20, border:'1px solid rgba(195,255,54,0.18)',
  display:'flex', flexDirection:'column', alignItems:'center', justifyContent:'center',
  fontFamily:'Inter, sans-serif', position:'relative', overflow:'hidden'
}}>
  <style>{`
    @keyframes dz-pulse { 0%,100% { opacity:.18; transform:scale(1); } 50% { opacity:.42; transform:scale(1.18); } }
    @keyframes dz-drift { 0%,100% { transform:translateX(-20px); } 50% { transform:translateX(40px); } }
    #dz-glow-a { animation:dz-pulse 5s ease-in-out infinite; transform-origin:center; }
    #dz-glow-b { animation:dz-drift 8s ease-in-out infinite; }
  `}</style>
  <svg width="860" height="230" style={{position:'absolute',top:0,left:0}}>
    <defs>
      <radialGradient id="dzg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(195,255,54,0.28)" />
        <stop offset="72%" stopColor="rgba(195,255,54,0)" />
      </radialGradient>
      <radialGradient id="dzg2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(140,100,255,0.20)" />
        <stop offset="72%" stopColor="rgba(140,100,255,0)" />
      </radialGradient>
    </defs>
    <ellipse id="dz-glow-a" cx="170" cy="40" rx="220" ry="100" fill="url(#dzg1)" />
    <ellipse id="dz-glow-b" cx="710" cy="190" rx="260" ry="120" fill="url(#dzg2)" />
  </svg>
  <div style={{display:'flex',alignItems:'center',gap:14,zIndex:5}}>
    <img src={github?.user?.avatarUrl ?? 'https://github.com/udarakasalife.png'} width={58} height={58} style={{borderRadius:29,border:'2px solid rgba(195,255,54,0.55)'}} />
    <div style={{display:'flex',flexDirection:'column'}}>
      <span style={{fontSize:34,fontWeight:800,color:'#f5f7ef',letterSpacing:'-1px'}}>Dazeyuratama.</span>
      <span style={{fontSize:14,color:'#a7ad9e',marginTop:4}}>Software Engineer · Open Source Contributor</span>
    </div>
  </div>
  <div style={{display:'flex',gap:8,marginTop:18,zIndex:5}}>
    <span style={{padding:'5px 12px',borderRadius:14,background:'rgba(195,255,54,0.10)',border:'1px solid rgba(195,255,54,0.25)',color:'#d9ff7c',fontSize:12,fontWeight:700}}>BUILD</span>
    <span style={{padding:'5px 12px',borderRadius:14,background:'rgba(255,255,255,0.04)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:12,fontWeight:600}}>LEARN</span>
    <span style={{padding:'5px 12px',borderRadius:14,background:'rgba(255,255,255,0.04)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:12,fontWeight:600}}>SHIP</span>
  </div>
  <span style={{fontSize:12,color:'#72786d',marginTop:14,zIndex:5}}>Building modern web applications from Indonesia · UTC+7</span>
</div>
```

## `~/whoami`

```text
Name      : Dazeyuratama.
Focus     : Software Engineering
Style     : Black & Lime Minimalist
Based     : Indonesia · UTC+7
Status    : Building, learning, shipping.
```

I build modern web applications with a focus on clean interfaces, practical engineering, and projects that are meant to be used—not just shown.

## `~/stack`

```aura width=820 height=90
<div style={{width:'100%',height:'100%',background:'#080a09',borderRadius:18,border:'1px solid rgba(195,255,54,0.14)',display:'flex',alignItems:'center',justifyContent:'center',gap:9,fontFamily:'Inter,sans-serif'}}>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(195,255,54,0.09)',border:'1px solid rgba(195,255,54,0.22)',color:'#d9ff7c',fontSize:13,fontWeight:700}}>Next.js</span>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(195,255,54,0.09)',border:'1px solid rgba(195,255,54,0.22)',color:'#d9ff7c',fontSize:13,fontWeight:700}}>TypeScript</span>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(255,255,255,0.04)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:13,fontWeight:600}}>Node.js</span>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(255,255,255,0.04)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:13,fontWeight:600}}>PostgreSQL</span>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(255,255,255,0.04)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:13,fontWeight:600}}>Docker</span>
  <span style={{padding:'7px 13px',borderRadius:14,background:'rgba(255,255,255,0.04)',border:'1px solid rgba(255,255,255,0.10)',color:'#c5c9bf',fontSize:13,fontWeight:600}}>Tailwind CSS</span>
</div>
```

## `~/connect`

<p align="center">Find me around the internet.</p>

```aura width=110 height=44 link="https://github.com/udarakasalife" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/github/ffffff"
  text="GitHub"
  backgroundColor="#111312"
  textColor="#ffffff"
  width={110}
  height={44}
  gradientStops={[
    { offset:'0%', color:'#ffffff' },
    { offset:'18%', color:'#111312' },
    { offset:'50%', color:'#c3ff36' },
    { offset:'72%', color:'#111312' },
    { offset:'100%', color:'#555555' },
  ]}
  iconSize={20}
/>
```
```aura width=120 height=44 link="https://www.dazeyuratama.engineer" inline
<SocialMediaButton
  icon="https://cdn.simpleicons.org/googlechrome/ffffff"
  text="Website"
  backgroundColor="#111312"
  textColor="#ffffff"
  width={120}
  height={44}
  gradientStops={[
    { offset:'0%', color:'#ffffff' },
    { offset:'18%', color:'#111312' },
    { offset:'50%', color:'#c3ff36' },
    { offset:'72%', color:'#111312' },
    { offset:'100%', color:'#555555' },
  ]}
  iconSize={20}
/>
```
```aura width=125 height=44 link="https://www.instagram.com/devxpxnyctrl_/" inline
<SocialMediaButton
  icon="https://cdn.simpleicons.org/instagram/ffffff"
  text="Instagram"
  backgroundColor="#111312"
  textColor="#ffffff"
  width={125}
  height={44}
  gradientStops={[
    { offset:'0%', color:'#ffffff' },
    { offset:'18%', color:'#111312' },
    { offset:'50%', color:'#c3ff36' },
    { offset:'72%', color:'#111312' },
    { offset:'100%', color:'#555555' },
  ]}
  iconSize={20}
/>
```
```aura width=110 height=44 link="https://ko-fi.com/dazeyuratama" inline
<SocialMediaButton
  icon="https://cdn.simpleicons.org/kofi/ffffff"
  text="Ko-fi"
  backgroundColor="#111312"
  textColor="#ffffff"
  width={110}
  height={44}
  gradientStops={[
    { offset:'0%', color:'#ffffff' },
    { offset:'18%', color:'#111312' },
    { offset:'50%', color:'#c3ff36' },
    { offset:'72%', color:'#111312' },
    { offset:'100%', color:'#555555' },
  ]}
  iconSize={20}
/>
```

## `~/support`

If my work is useful to you, you can support my projects and future experiments on Ko-fi.

```aura width=180 height=48 link="https://ko-fi.com/dazeyuratama"
<div style={{width:'100%',height:'100%',background:'#0b0d0c',borderRadius:16,border:'1px solid rgba(195,255,54,0.30)',display:'flex',alignItems:'center',justifyContent:'center',fontFamily:'Inter,sans-serif',gap:8}}>
  <span style={{fontSize:15,color:'#d9ff7c',fontWeight:800}}>☕ Support my work</span>
</div>
```

<p align="center">
  <sub>black & lime — always minimal, always building.</sub>
</p>

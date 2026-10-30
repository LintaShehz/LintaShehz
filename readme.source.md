```aura width=800 height=260
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&family=Share+Tech+Mono&display=swap" rel="stylesheet">
    import HudFrame from "./HudFrame";

export default function App() {
  return (
    <HudFrame
      text="PLAYER ONE"
      subtext="Level 12 · Focus streak 9 days"
      image="/cat.png"
      imageSide="left"
    />
  );
}</defs>
    <ellipse cx="640" cy="60" rx="190" ry="16" fill="url(#gPurple)">
      <animate attributeName="cx" values="580;700;580" dur="7s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.5;1;0.5" dur="7s" repeatCount="indefinite" />
    </ellipse>
    <ellipse cx="380" cy="215" rx="170" ry="26" fill="url(#gBlue)">
      <animate attributeName="cx" values="300;460;300" dur="9s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="9s" repeatCount="indefinite" />
    </ellipse>
    <ellipse cx="110" cy="120" rx="110" ry="80" fill="url(#gCyan)">
      <animate attributeName="opacity" values="0.35;0.85;0.35" dur="5s" repeatCount="indefinite" />
      <animate attributeName="rx" values="95;125;95" dur="5s" repeatCount="indefinite" />
    </ellipse>
    <ellipse cx="730" cy="225" rx="120" ry="40" fill="url(#gPurple)">
      <animate attributeName="cx" values="690;770;690" dur="8s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.3;0.7;0.3" dur="8s" repeatCount="indefinite" />
    </ellipse>
    <rect x="2" y="2" width="796" height="256" rx="16" fill="none" stroke="#1f2937" strokeWidth="2" />
    <rect x="2" y="2" width="796" height="256" rx="16" fill="none" stroke="#22d3ee" strokeWidth="3" strokeLinecap="round" pathLength="100" strokeDasharray="8 92">
      <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="6s" repeatCount="indefinite" />
    </rect>
    <rect x="2" y="2" width="796" height="256" rx="16" fill="none" stroke="#a78bfa" strokeWidth="3" strokeLinecap="round" pathLength="100" strokeDasharray="8 92">
      <animate attributeName="stroke-dashoffset" from="-50" to="-150" dur="6s" repeatCount="indefinite" />
    </rect>
    <path d="M2 34 V2 H34 M766 2 H798 V34 M798 226 V258 H766 M34 258 H2 V226" fill="none" stroke="#ffffff" strokeWidth="3" strokeLinecap="round">
      <animate attributeName="opacity" values="0.25;1;0.25" dur="2.5s" repeatCount="indefinite" />
    </path>
  </svg>
  <div style={{ display: 'flex', color: '#f5f5f5', fontSize: 46, fontWeight: 700 }}>Hi, I'm LintaShehz</div>
  <div style={{ display: 'flex', color: '#9ca3af', fontSize: 20, marginTop: 10 }}>DAE CIT Student | Learning C++ | Building in public</div>
  <div style={{ display: 'flex', marginTop: 26 }}>
    <div style={{ display: 'flex', color: '#facc15', fontSize: 16, padding: '7px 18px', borderRadius: 999, border: '1px solid #facc15', background: 'rgba(250,204,21,0.08)', marginLeft: 6, marginRight: 6 }}>Python</div>
    <div style={{ display: 'flex', color: '#60a5fa', fontSize: 16, padding: '7px 18px', borderRadius: 999, border: '1px solid #60a5fa', background: 'rgba(96,165,250,0.08)', marginLeft: 6, marginRight: 6 }}>C++</div>
    <div style={{ display: 'flex', color: '#fb923c', fontSize: 16, padding: '7px 18px', borderRadius: 999, border: '1px solid #fb923c', background: 'rgba(251,146,60,0.08)', marginLeft: 6, marginRight: 6 }}>HTML/CSS</div>
    <div style={{ display: 'flex', color: '#a78bfa', fontSize: 16, padding: '7px 18px', borderRadius: 999, border: '1px solid #a78bfa', background: 'rgba(167,139,250,0.08)', marginLeft: 6, marginRight: 6 }}>C</div>
  </div>
</div>
```

```aura width=256 height=150 inline align=center
<div style={{ display: 'flex', position: 'relative', width: 256, height: 150, background: '#0d1117', borderRadius: 14, padding: 22, flexDirection: 'column' }}>
  <svg width="256" height="150" viewBox="0 0 256 150" style={{ position: 'absolute', top: 0, left: 0 }}>
    <rect x="2" y="2" width="252" height="146" rx="12" fill="none" stroke="#1f2937" strokeWidth="2" />
    <rect x="2" y="2" width="252" height="146" rx="12" fill="none" stroke="#22d3ee" strokeWidth="3" strokeLinecap="round" pathLength="100" strokeDasharray="10 90">
      <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="4s" repeatCount="indefinite" />
    </rect>
    <rect x="2" y="2" width="252" height="146" rx="12" fill="none" stroke="#a78bfa" strokeWidth="3" strokeLinecap="round" pathLength="100" strokeDasharray="10 90">
      <animate attributeName="stroke-dashoffset" from="-50" to="-150" dur="4s" repeatCount="indefinite" />
    </rect>
    <path d="M2 22 V2 H22 M234 2 H254 V22 M254 128 V148 H234 M22 148 H2 V128" fill="none" stroke="#ffffff" strokeWidth="3" strokeLinecap="round">
      <animate attributeName="opacity" values="0.25;1;0.25" dur="2.5s" repeatCount="indefinite" />
    </path>
  </svg>
  <div style={{ display: 'flex', color: '#22d3ee', fontSize: 14, letterSpacing: 3 }}>ABOUT</div>
  <div style={{ display: 'flex', color: '#e5e7eb', fontSize: 16, marginTop: 14 }}>First-year student in</div>
  <div style={{ display: 'flex', color: '#e5e7eb', fontSize: 16, marginTop: 4 }}>DAE CIT, learning to</div>
  <div style={{ display: 'flex', color: '#e5e7eb', fontSize: 16, marginTop: 4 }}>build real software.</div>
</div>
```
```aura width=256 height=150 inline align=center
<div style={{ display: 'flex', position: 'relative', width: 256, height: 150, background: '#0d1117', borderRadius: 14, padding: 22, flexDirection: 'column' }}>
  <svg width="256" height="150" viewBox="0 0 256 150" style={{ position: 'absolute', top: 0, left: 0 }}>
    <rect x="2" y="2" width="252" height="146" rx="12" fill="none" stroke="#1f2937" strokeWidth="2" />
    <rect x="2" y="2" width="252" height="146" rx="12" fill="none" stroke="#22d3ee" strokeWidth="3" strokeLinecap="round" pathLength="100" strokeDasharray="10 90">
      <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="4s" repeatCount="indefinite" />
    </rect>
    <rect x="2" y="2" width="252" height="146" rx="12" fill="none" stroke="#a78bfa" strokeWidth="3" strokeLinecap="round" pathLength="100" strokeDasharray="10 90">
      <animate attributeName="stroke-dashoffset" from="-50" to="-150" dur="4s" repeatCount="indefinite" />
    </rect>
    <path d="M2 22 V2 H22 M234 2 H254 V22 M254 128 V148 H234 M22 148 H2 V128" fill="none" stroke="#ffffff" strokeWidth="3" strokeLinecap="round">
      <animate attributeName="opacity" values="0.25;1;0.25" dur="2.5s" repeatCount="indefinite" />
    </path>
  </svg>
  <div style={{ display: 'flex', color: '#a78bfa', fontSize: 14, letterSpacing: 3 }}>LEARNING</div>
  <div style={{ display: 'flex', color: '#e5e7eb', fontSize: 16, marginTop: 14 }}>C++ (advanced)</div>
  <div style={{ display: 'flex', color: '#e5e7eb', fontSize: 16, marginTop: 4 }}>Computer fundamentals</div>
  <div style={{ display: 'flex', color: '#e5e7eb', fontSize: 16, marginTop: 4 }}>Math for engineering</div>
</div>
```
```aura width=256 height=150 inline align=center
<div style={{ display: 'flex', position: 'relative', width: 256, height: 150, background: '#0d1117', borderRadius: 14, padding: 22, flexDirection: 'column' }}>
  <svg width="256" height="150" viewBox="0 0 256 150" style={{ position: 'absolute', top: 0, left: 0 }}>
    <rect x="2" y="2" width="252" height="146" rx="12" fill="none" stroke="#1f2937" strokeWidth="2" />
    <rect x="2" y="2" width="252" height="146" rx="12" fill="none" stroke="#22d3ee" strokeWidth="3" strokeLinecap="round" pathLength="100" strokeDasharray="10 90">
      <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="4s" repeatCount="indefinite" />
    </rect>
    <rect x="2" y="2" width="252" height="146" rx="12" fill="none" stroke="#a78bfa" strokeWidth="3" strokeLinecap="round" pathLength="100" strokeDasharray="10 90">
      <animate attributeName="stroke-dashoffset" from="-50" to="-150" dur="4s" repeatCount="indefinite" />
    </rect>
    <path d="M2 22 V2 H22 M234 2 H254 V22 M254 128 V148 H234 M22 148 H2 V128" fill="none" stroke="#ffffff" strokeWidth="3" strokeLinecap="round">
      <animate attributeName="opacity" values="0.25;1;0.25" dur="2.5s" repeatCount="indefinite" />
    </path>
  </svg>
  <div style={{ display: 'flex', color: '#22d3ee', fontSize: 14, letterSpacing: 3 }}>BUILDING</div>
  <div style={{ display: 'flex', color: '#e5e7eb', fontSize: 16, marginTop: 14 }}>A C++ command-line</div>
  <div style={{ display: 'flex', color: '#e5e7eb', fontSize: 16, marginTop: 4 }}>project (CLI) to show</div>
  <div style={{ display: 'flex', color: '#e5e7eb', fontSize: 16, marginTop: 4 }}>on this profile.</div>
</div>
```

## Find me here

- GitHub: [@LintaShehz](https://github.com/LintaShehz)
- Add your other links here (Instagram, YouTube, LinkedIn)

```aura width=800 height=56
<div style={{ display: 'flex', position: 'relative', width: 800, height: 56, background: '#0d1117', borderRadius: 12, justifyContent: 'center', alignItems: 'center' }}>
  <svg width="800" height="56" viewBox="0 0 800 56" style={{ position: 'absolute', top: 0, left: 0 }}>
    <rect x="2" y="2" width="796" height="52" rx="10" fill="none" stroke="#1f2937" strokeWidth="2" />
    <rect x="2" y="2" width="796" height="52" rx="10" fill="none" stroke="#22d3ee" strokeWidth="3" strokeLinecap="round" pathLength="100" strokeDasharray="6 94">
      <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="6s" repeatCount="indefinite" />
    </rect>
    <rect x="2" y="2" width="796" height="52" rx="10" fill="none" stroke="#a78bfa" strokeWidth="3" strokeLinecap="round" pathLength="100" strokeDasharray="6 94">
      <animate attributeName="stroke-dashoffset" from="-50" to="-150" dur="6s" repeatCount="indefinite" />
    </rect>
    <path d="M2 20 V2 H20 M780 2 H798 V20 M798 36 V54 H780 M20 54 H2 V36" fill="none" stroke="#ffffff" strokeWidth="3" strokeLinecap="round">
      <animate attributeName="opacity" values="0.25;1;0.25" dur="2.5s" repeatCount="indefinite" />
    </path>
  </svg>
  <div style={{ display: 'flex', color: '#9ca3af', fontSize: 16 }}>Thanks for visiting. More projects coming soon.</div>
</div>
```
```

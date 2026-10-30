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
}

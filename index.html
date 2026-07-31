import React, { useState, useEffect, useRef, useCallback } from "react";
import { Copy, Check, ChevronDown, ArrowUp, Menu, X, ExternalLink } from "lucide-react";

const CA_ADDRESS = "Coming after launch";

const PALETTE = {
  bg: "#FFFFFF",
  card: "#FAFAFA",
  primary: "#3567B8",
  text: "#111111",
  secondary: "#6B7280",
  border: "#ECECEC",
  success: "#22C55E",
};

function useReveal() {
  const ref = useRef(null);
  const [visible, setVisible] = useState(false);
  useEffect(() => {
    const el = ref.current;
    if (!el) return;
    const obs = new IntersectionObserver(
      ([entry]) => {
        if (entry.isIntersecting) {
          setVisible(true);
          obs.unobserve(el);
        }
      },
      { threshold: 0.15 }
    );
    obs.observe(el);
    return () => obs.disconnect();
  }, []);
  return [ref, visible];
}

function Reveal({ children, delay = 0, className = "" }) {
  const [ref, visible] = useReveal();
  return (
    <div
      ref={ref}
      className={className}
      style={{
        opacity: visible ? 1 : 0,
        transform: visible ? "translateY(0px)" : "translateY(28px)",
        transition: `opacity 0.8s cubic-bezier(0.16,1,0.3,1) ${delay}ms, transform 0.8s cubic-bezier(0.16,1,0.3,1) ${delay}ms`,
      }}
    >
      {children}
    </div>
  );
}

/* ---------- Official mascot artwork ---------- */

const MASCOT_IMG = "data:image/jpeg;base64,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";

function Mascot({ className = "", style = {} }) {
  return (
    <img
      src={MASCOT_IMG}
      alt="CHONK the cat, the official mascot, wearing denim overalls"
      className={className}
      style={{ objectFit: "contain", ...style }}
    />
  );
}

/* ---------- Site ---------- */

export default function ChonkCatSite() {
  const [scrolled, setScrolled] = useState(false);
  const [scrollPct, setScrollPct] = useState(0);
  const [menuOpen, setMenuOpen] = useState(false);
  const [copied, setCopied] = useState(false);
  const [openFaq, setOpenFaq] = useState(0);

  useEffect(() => {
    const onScroll = () => {
      const y = window.scrollY;
      setScrolled(y > 24);
      const h = document.documentElement.scrollHeight - window.innerHeight;
      setScrollPct(h > 0 ? (y / h) * 100 : 0);
    };
    window.addEventListener("scroll", onScroll, { passive: true });
    onScroll();
    return () => window.removeEventListener("scroll", onScroll);
  }, []);

  const copyCA = useCallback(() => {
    try {
      navigator.clipboard.writeText(CA_ADDRESS);
    } catch (e) {}
    setCopied(true);
    setTimeout(() => setCopied(false), 2000);
  }, []);

  const navLinks = [
    { label: "Home", href: "#home" },
    { label: "About", href: "#about" },
    { label: "How to Buy", href: "#how-to-buy" },
    { label: "FAQ", href: "#faq" },
    { label: "Community", href: "#community" },
  ];

  const tokenInfo = [
    { label: "Network", value: "Solana" },
    { label: "Ticker", value: "$CHONK" },
    { label: "Supply", value: "1,000,000,000" },
    { label: "Launch", value: "Pump.fun" },
    { label: "Tax", value: "0%" },
  ];

  const features = [
    { title: "Built on Solana", body: "Lightning-fast transactions." },
    { title: "Pump.fun Launch", body: "Fair launch." },
    { title: "Community First", body: "Powered by the community." },
    { title: "Original Mascot", body: "Unique branding." },
  ];

  const steps = [
    { n: "01", title: "Install Phantom", body: "Set up a Phantom wallet on your phone or browser." },
    { n: "02", title: "Buy SOL", body: "Fund your wallet with SOL from an exchange or on-ramp." },
    { n: "03", title: "Visit Pump.fun", body: "Open the CHONK the cat page on Pump.fun." },
    { n: "04", title: "Paste Contract Address", body: "Confirm you have the official $CHONK contract." },
    { n: "05", title: "Buy $CHONK", body: "Swap SOL for $CHONK directly in your wallet." },
  ];

  const faqs = [
    { q: "What is CHONK the cat?", a: "CHONK the cat ($CHONK) is a community-driven meme coin on Solana, built around the internet's most confident cat, the only one who put on denim." },
    { q: "How do I buy?", a: "Install Phantom, fund it with SOL, visit the official Pump.fun page, paste the contract address, and swap for $CHONK." },
    { q: "What blockchain?", a: "$CHONK lives on Solana, chosen for its speed and low transaction costs." },
    { q: "Is there tax?", a: "No. $CHONK carries a 0% transaction tax." },
    { q: "Why Pump.fun?", a: "Pump.fun offers a fair, transparent launch with no presale and no team allocation." },
  ];

  return (
    <div style={{ fontFamily: "'Inter', ui-sans-serif, system-ui, sans-serif", color: PALETTE.text, background: PALETTE.bg, position: "relative", overflowX: "hidden" }}>
      <style>{`
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');
        * { box-sizing: border-box; }
        html { scroll-behavior: smooth; }
        @keyframes floaty { 0%,100% { transform: translateY(0px); } 50% { transform: translateY(-14px); } }
        @keyframes drift1 { 0% { transform: translate(0,0); } 50% { transform: translate(30px,-40px); } 100% { transform: translate(0,0); } }
        @keyframes drift2 { 0% { transform: translate(0,0); } 50% { transform: translate(-40px,30px); } 100% { transform: translate(0,0); } }
        @keyframes spin-slow { from { transform: rotate(0deg); } to { transform: rotate(360deg); } }
        .float-anim { animation: floaty 5s ease-in-out infinite; }
        .btn-lift { transition: transform 0.25s cubic-bezier(0.16,1,0.3,1), box-shadow 0.25s ease, background 0.2s ease; }
        .btn-lift:hover { transform: translateY(-3px); }
        .card-hover { transition: transform 0.3s cubic-bezier(0.16,1,0.3,1), box-shadow 0.3s ease, border-color 0.3s ease; }
        .card-hover:hover { transform: translateY(-4px); border-color: #3567B822; box-shadow: 0 20px 40px -20px rgba(53,103,184,0.18); }
        .underline-hover { position: relative; }
        .underline-hover::after { content: ""; position: absolute; left: 0; bottom: -4px; width: 0%; height: 1.5px; background: #3567B8; transition: width 0.3s cubic-bezier(0.16,1,0.3,1); }
        .underline-hover:hover::after { width: 100%; }
        ::selection { background: #3567B822; }
        .nav-links { display: flex; gap: 36px; }
        .nav-cta { display: inline-flex; }
        .menu-btn { display: none; }
        .about-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 56px; align-items: center; }
        @media (max-width: 767px) {
          .nav-links { display: none; }
          .nav-cta { display: none; }
          .menu-btn { display: flex; }
        }
        @media (max-width: 899px) {
          .about-grid { grid-template-columns: 1fr; }
        }
      `}</style>

      {/* scroll progress */}
      <div style={{ position: "fixed", top: 0, left: 0, height: "2px", width: `${scrollPct}%`, background: PALETTE.primary, zIndex: 100, transition: "width 0.1s linear" }} />

      {/* background ambient particles */}
      <div style={{ position: "fixed", inset: 0, zIndex: 0, pointerEvents: "none", overflow: "hidden" }}>
        <div style={{ position: "absolute", top: "8%", left: "6%", width: 340, height: 340, borderRadius: "50%", background: "radial-gradient(circle, #3567B814 0%, transparent 70%)", animation: "drift1 18s ease-in-out infinite" }} />
        <div style={{ position: "absolute", top: "55%", right: "4%", width: 400, height: 400, borderRadius: "50%", background: "radial-gradient(circle, #3567B812 0%, transparent 70%)", animation: "drift2 22s ease-in-out infinite" }} />
        <div style={{ position: "absolute", bottom: "5%", left: "30%", width: 260, height: 260, borderRadius: "50%", background: "radial-gradient(circle, #3567B810 0%, transparent 70%)", animation: "drift1 26s ease-in-out infinite" }} />
      </div>

      {/* NAVBAR */}
      <header
        style={{
          position: "sticky",
          top: 0,
          zIndex: 50,
          background: scrolled ? "rgba(255,255,255,0.75)" : "transparent",
          backdropFilter: scrolled ? "blur(14px)" : "none",
          WebkitBackdropFilter: scrolled ? "blur(14px)" : "none",
          borderBottom: scrolled ? `0.5px solid ${PALETTE.border}` : "0.5px solid transparent",
          transition: "all 0.35s ease",
        }}
      >
        <div style={{ maxWidth: 1180, margin: "0 auto", padding: "18px 24px", display: "flex", alignItems: "center", justifyContent: "space-between" }}>
          <a href="#home" style={{ display: "flex", alignItems: "center", gap: 8, fontWeight: 700, fontSize: 18, textDecoration: "none", color: PALETTE.text }}>
            <span style={{ fontSize: 20 }}>🐱</span> CHONK the cat
          </a>

          <nav className="nav-links">
            {navLinks.map((l) => (
              <a
                key={l.label}
                href={l.href}
                className="underline-hover"
                style={{ fontSize: 14.5, fontWeight: 500, color: PALETTE.text, textDecoration: "none" }}
              >
                {l.label}
              </a>
            ))}
          </nav>

          <div style={{ display: "flex", alignItems: "center", gap: 12 }}>
            <a
              href="#hero-buy"
              className="btn-lift nav-cta"
              style={{
                alignItems: "center",
                gap: 6,
                background: PALETTE.primary,
                color: "#fff",
                fontSize: 14,
                fontWeight: 600,
                padding: "10px 20px",
                borderRadius: 999,
                textDecoration: "none",
                boxShadow: "0 8px 20px -8px #3567B855",
              }}
            >
              Buy $CHONK
            </a>
            <button
              onClick={() => setMenuOpen((v) => !v)}
              className="menu-btn"
              style={{ background: "none", border: "none", cursor: "pointer", color: PALETTE.text, alignItems: "center", justifyContent: "center" }}
              aria-label="Toggle menu"
            >
              {menuOpen ? <X size={22} /> : <Menu size={22} />}
            </button>
          </div>
        </div>

        {menuOpen && (
          <div style={{ borderTop: `0.5px solid ${PALETTE.border}`, background: "#fff" }}>
            <div style={{ display: "flex", flexDirection: "column", padding: "12px 24px 20px", gap: 14 }}>
              {navLinks.map((l) => (
                <a key={l.label} href={l.href} onClick={() => setMenuOpen(false)} style={{ fontSize: 15, fontWeight: 500, color: PALETTE.text, textDecoration: "none" }}>
                  {l.label}
                </a>
              ))}
              <a href="#hero-buy" onClick={() => setMenuOpen(false)} style={{ marginTop: 6, textAlign: "center", background: PALETTE.primary, color: "#fff", fontWeight: 600, fontSize: 14, padding: "10px 0", borderRadius: 999, textDecoration: "none" }}>
                Buy $CHONK
              </a>
            </div>
          </div>
        )}
      </header>

      {/* HERO */}
      <section id="home" style={{ position: "relative", zIndex: 1, maxWidth: 1180, margin: "0 auto", padding: "72px 24px 40px", textAlign: "center" }}>
        <Reveal>
          <div style={{ display: "inline-flex", alignItems: "center", gap: 8, background: PALETTE.card, border: `0.5px solid ${PALETTE.border}`, borderRadius: 999, padding: "6px 16px", fontSize: 13, fontWeight: 500, color: PALETTE.secondary, marginBottom: 28 }}>
            <span style={{ width: 6, height: 6, borderRadius: "50%", background: PALETTE.success, display: "inline-block" }} />
            Live on Solana
          </div>
        </Reveal>

        <Reveal delay={80}>
          <div className="float-anim" style={{ width: 220, height: 220, margin: "0 auto 32px" }}>
            <Mascot style={{ width: "100%", height: "100%" }} />
          </div>
        </Reveal>

        <Reveal delay={140}>
          <h1 style={{ fontSize: "clamp(34px, 6vw, 62px)", fontWeight: 800, lineHeight: 1.08, letterSpacing: "-0.02em", margin: "0 0 20px" }}>
            The First Cat That<br />Put On Denim.
          </h1>
        </Reveal>

        <Reveal delay={200}>
          <p style={{ fontSize: 18, color: PALETTE.secondary, maxWidth: 560, margin: "0 auto 36px", lineHeight: 1.6 }}>
            A community-powered Solana meme coin inspired by the internet's most confident cat.
          </p>
        </Reveal>

        <Reveal delay={260}>
          <div id="hero-buy" style={{ display: "flex", justifyContent: "center", gap: 14, flexWrap: "wrap" }}>
            <a
              href="https://pump.fun"
              target="_blank"
              rel="noreferrer"
              className="btn-lift"
              style={{ background: PALETTE.primary, color: "#fff", fontWeight: 600, fontSize: 15, padding: "14px 30px", borderRadius: 999, textDecoration: "none", boxShadow: "0 12px 26px -10px #3567B860" }}
            >
              Buy on Pump.fun
            </a>
            <button
              onClick={copyCA}
              className="btn-lift"
              style={{
                display: "inline-flex",
                alignItems: "center",
                gap: 8,
                background: "#fff",
                color: PALETTE.text,
                fontWeight: 600,
                fontSize: 15,
                padding: "14px 26px",
                borderRadius: 999,
                border: `1px solid ${PALETTE.border}`,
                cursor: "pointer",
              }}
            >
              {copied ? <Check size={16} color={PALETTE.success} /> : <Copy size={16} />}
              {copied ? "Copied" : "Copy CA"}
            </button>
          </div>
        </Reveal>

        <Reveal delay={320}>
          <div style={{ marginTop: 44, maxWidth: 460, marginLeft: "auto", marginRight: "auto", background: PALETTE.card, border: `0.5px solid ${PALETTE.border}`, borderRadius: 16, padding: "18px 24px" }}>
            <div style={{ fontSize: 12, fontWeight: 600, color: PALETTE.secondary, letterSpacing: "0.06em", textTransform: "uppercase", marginBottom: 6 }}>Contract address</div>
            <div style={{ fontSize: 14.5, fontWeight: 500, color: PALETTE.text, wordBreak: "break-all" }}>{CA_ADDRESS}</div>
          </div>
        </Reveal>
      </section>

      {/* TOKEN INFO */}
      <section style={{ position: "relative", zIndex: 1, maxWidth: 1180, margin: "0 auto", padding: "60px 24px" }}>
        <Reveal>
          <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fit, minmax(160px, 1fr))", gap: 16 }}>
            {tokenInfo.map((t) => (
              <div key={t.label} className="card-hover" style={{ background: PALETTE.card, border: `0.5px solid ${PALETTE.border}`, borderRadius: 16, padding: "22px 20px", textAlign: "center" }}>
                <div style={{ fontSize: 12, fontWeight: 600, color: PALETTE.secondary, letterSpacing: "0.06em", textTransform: "uppercase", marginBottom: 8 }}>{t.label}</div>
                <div style={{ fontSize: 18, fontWeight: 700, color: PALETTE.text }}>{t.value}</div>
              </div>
            ))}
          </div>
        </Reveal>
      </section>

      {/* ABOUT */}
      <section id="about" style={{ position: "relative", zIndex: 1, maxWidth: 1180, margin: "0 auto", padding: "80px 24px" }}>
        <div className="about-grid">
          <Reveal>
            <div style={{ background: PALETTE.card, border: `0.5px solid ${PALETTE.border}`, borderRadius: 24, padding: 40, display: "flex", justifyContent: "center" }}>
              <Mascot style={{ width: "100%", maxWidth: 320, height: "auto" }} />
            </div>
          </Reveal>
          <Reveal delay={100}>
            <div>
              <div style={{ fontSize: 13, fontWeight: 600, color: PALETTE.primary, letterSpacing: "0.06em", textTransform: "uppercase", marginBottom: 12 }}>About</div>
              <h2 style={{ fontSize: "clamp(26px, 4vw, 36px)", fontWeight: 800, marginBottom: 20, letterSpacing: "-0.01em" }}>Meet CHONK the cat</h2>
              <p style={{ fontSize: 16, color: PALETTE.secondary, lineHeight: 1.75, marginBottom: 14 }}>
                Every meme coin has a dog. Every meme coin has a cat. Only one cat decided to wear denim.
              </p>
              <p style={{ fontSize: 16, color: PALETTE.secondary, lineHeight: 1.75, marginBottom: 20 }}>
                CHONK the cat is a community-driven Solana meme coin built around memes, internet culture, and creativity.
              </p>
              <div style={{ display: "flex", flexDirection: "column", gap: 10 }}>
                {["No fake promises.", "No unnecessary utility.", "Just memes. Just denim. Just community."].map((line) => (
                  <div key={line} style={{ display: "flex", alignItems: "center", gap: 10, fontSize: 15, fontWeight: 500, color: PALETTE.text }}>
                    <span style={{ width: 6, height: 6, borderRadius: "50%", background: PALETTE.primary, display: "inline-block", flexShrink: 0 }} />
                    {line}
                  </div>
                ))}
              </div>
            </div>
          </Reveal>
        </div>
      </section>

      {/* FEATURES */}
      <section style={{ position: "relative", zIndex: 1, maxWidth: 1180, margin: "0 auto", padding: "40px 24px 80px" }}>
        <Reveal>
          <div style={{ textAlign: "center", marginBottom: 44 }}>
            <h2 style={{ fontSize: "clamp(26px, 4vw, 34px)", fontWeight: 800, letterSpacing: "-0.01em" }}>Why CHONK the cat</h2>
          </div>
        </Reveal>
        <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fit, minmax(230px, 1fr))", gap: 18 }}>
          {features.map((f, i) => (
            <Reveal key={f.title} delay={i * 80}>
              <div className="card-hover" style={{ background: "#fff", border: `0.5px solid ${PALETTE.border}`, borderRadius: 18, padding: "28px 24px", height: "100%" }}>
                <div style={{ width: 40, height: 40, borderRadius: 12, background: "#3567B811", display: "flex", alignItems: "center", justifyContent: "center", marginBottom: 18 }}>
                  <span style={{ width: 10, height: 10, borderRadius: 3, background: PALETTE.primary, display: "inline-block" }} />
                </div>
                <h3 style={{ fontSize: 17, fontWeight: 700, marginBottom: 8 }}>{f.title}</h3>
                <p style={{ fontSize: 14.5, color: PALETTE.secondary, lineHeight: 1.6 }}>{f.body}</p>
              </div>
            </Reveal>
          ))}
        </div>
      </section>

      {/* HOW TO BUY */}
      <section id="how-to-buy" style={{ position: "relative", zIndex: 1, background: PALETTE.card, borderTop: `0.5px solid ${PALETTE.border}`, borderBottom: `0.5px solid ${PALETTE.border}` }}>
        <div style={{ maxWidth: 900, margin: "0 auto", padding: "80px 24px" }}>
          <Reveal>
            <div style={{ textAlign: "center", marginBottom: 48 }}>
              <div style={{ fontSize: 13, fontWeight: 600, color: PALETTE.primary, letterSpacing: "0.06em", textTransform: "uppercase", marginBottom: 12 }}>Get started</div>
              <h2 style={{ fontSize: "clamp(26px, 4vw, 34px)", fontWeight: 800, letterSpacing: "-0.01em" }}>How to buy</h2>
            </div>
          </Reveal>
          <div>
            {steps.map((s, i) => (
              <Reveal key={s.n} delay={i * 70}>
                <div style={{ display: "flex", gap: 20, alignItems: "flex-start" }}>
                  <div style={{ display: "flex", flexDirection: "column", alignItems: "center" }}>
                    <div style={{ width: 40, height: 40, borderRadius: "50%", background: "#fff", border: `1.5px solid ${PALETTE.primary}`, color: PALETTE.primary, display: "flex", alignItems: "center", justifyContent: "center", fontSize: 13, fontWeight: 700, flexShrink: 0 }}>
                      {s.n}
                    </div>
                    {i < steps.length - 1 && <div style={{ width: 1.5, flex: 1, minHeight: 34, background: PALETTE.border, marginTop: 4 }} />}
                  </div>
                  <div style={{ paddingBottom: 34 }}>
                    <h3 style={{ fontSize: 17, fontWeight: 700, marginBottom: 4 }}>{s.title}</h3>
                    <p style={{ fontSize: 14.5, color: PALETTE.secondary, lineHeight: 1.6 }}>{s.body}</p>
                  </div>
                </div>
              </Reveal>
            ))}
          </div>
        </div>
      </section>

      {/* FAQ */}
      <section id="faq" style={{ position: "relative", zIndex: 1, maxWidth: 780, margin: "0 auto", padding: "40px 24px 90px" }}>
        <Reveal>
          <div style={{ textAlign: "center", marginBottom: 40 }}>
            <h2 style={{ fontSize: "clamp(26px, 4vw, 34px)", fontWeight: 800, letterSpacing: "-0.01em" }}>Frequently asked</h2>
          </div>
        </Reveal>
        <div style={{ display: "flex", flexDirection: "column", gap: 10 }}>
          {faqs.map((f, i) => (
            <Reveal key={f.q} delay={i * 50}>
              <div style={{ border: `0.5px solid ${PALETTE.border}`, borderRadius: 14, overflow: "hidden", background: "#fff" }}>
                <button
                  onClick={() => setOpenFaq(openFaq === i ? -1 : i)}
                  style={{ width: "100%", display: "flex", justifyContent: "space-between", alignItems: "center", padding: "18px 22px", background: "none", border: "none", cursor: "pointer", textAlign: "left" }}
                >
                  <span style={{ fontSize: 15.5, fontWeight: 600, color: PALETTE.text }}>{f.q}</span>
                  <ChevronDown size={18} color={PALETTE.secondary} style={{ transform: openFaq === i ? "rotate(180deg)" : "rotate(0deg)", transition: "transform 0.3s ease", flexShrink: 0 }} />
                </button>
                <div style={{ maxHeight: openFaq === i ? 200 : 0, overflow: "hidden", transition: "max-height 0.35s cubic-bezier(0.16,1,0.3,1)" }}>
                  <p style={{ padding: "0 22px 20px", fontSize: 14.5, color: PALETTE.secondary, lineHeight: 1.65 }}>{f.a}</p>
                </div>
              </div>
            </Reveal>
          ))}
        </div>
      </section>

      {/* COMMUNITY */}
      <section id="community" style={{ position: "relative", zIndex: 1, background: PALETTE.text, color: "#fff", borderRadius: 32, maxWidth: 1120, margin: "0 auto 90px", padding: "80px 24px", textAlign: "center" }}>
        <Reveal>
          <h2 style={{ fontSize: "clamp(28px, 5vw, 42px)", fontWeight: 800, lineHeight: 1.2, letterSpacing: "-0.01em", marginBottom: 32 }}>
            One Cat.<br />One Pair of Denim.<br />One Community.
          </h2>
        </Reveal>
        <Reveal delay={100}>
          <div style={{ display: "flex", justifyContent: "center", gap: 14, flexWrap: "wrap" }}>
            {[
              { label: "X", href: "https://x.com/CHONKTHECATSOL" },
              { label: "Telegram", href: "https://t.me/+kfP6pEXKZOs0YjVl" },
              { label: "Pump.fun", href: "https://pump.fun" },
            ].map((btn) => (
              <a
                key={btn.label}
                href={btn.href}
                target="_blank"
                rel="noreferrer"
                className="btn-lift"
                style={{ display: "inline-flex", alignItems: "center", gap: 6, background: "rgba(255,255,255,0.08)", border: "1px solid rgba(255,255,255,0.16)", color: "#fff", fontSize: 14, fontWeight: 600, padding: "12px 22px", borderRadius: 999, textDecoration: "none" }}
              >
                {btn.label} <ExternalLink size={13} />
              </a>
            ))}
          </div>
        </Reveal>
      </section>

      {/* FOOTER */}
      <footer style={{ position: "relative", zIndex: 1, borderTop: `0.5px solid ${PALETTE.border}`, padding: "36px 24px" }}>
        <div style={{ maxWidth: 1180, margin: "0 auto", display: "flex", justifyContent: "space-between", alignItems: "center", flexWrap: "wrap", gap: 12 }}>
          <div style={{ fontSize: 13, color: PALETTE.secondary }}>Powered by Solana.</div>
          <div style={{ fontSize: 13, color: PALETTE.secondary }}>© 2026 CHONK the cat.</div>
        </div>
      </footer>

      {/* back to top */}
      {scrolled && (
        <button
          onClick={() => window.scrollTo({ top: 0, behavior: "smooth" })}
          className="btn-lift"
          style={{
            position: "fixed",
            bottom: 26,
            right: 26,
            zIndex: 60,
            width: 46,
            height: 46,
            borderRadius: "50%",
            background: PALETTE.primary,
            border: "none",
            color: "#fff",
            display: "flex",
            alignItems: "center",
            justifyContent: "center",
            cursor: "pointer",
            boxShadow: "0 10px 24px -8px #3567B870",
          }}
          aria-label="Back to top"
        >
          <ArrowUp size={20} />
        </button>
      )}
    </div>
  );
}

---
title: Still
layout: default
---

<style>
  .nav-links { margin-bottom: 1.5em; font-size: 0.95em; }

  .app-hero { text-align: center; padding: 2.5em 0 1.5em; }
  .app-hero .app-icon { width: 128px; height: 128px; border-radius: 28px; display: block; margin: 0 auto 1.25em; box-shadow: 0 8px 32px rgba(0,0,0,0.15); }
  .app-hero h1 { margin: 0 0 0.3em; font-size: 2.4em; }
  .app-hero .tagline { font-size: 1.3em; color: #57606a; margin: 0 0 0.5em; line-height: 1.4; }
  .app-hero .subtitle { font-size: 1.05em; color: #6e7781; margin: 0 auto 1.5em; max-width: 30em; line-height: 1.5; }

  .btn-app-store { display: inline-block; padding: 0.7em 1.6em; background: #000; color: #fff !important; border-radius: 12px; text-decoration: none !important; font-weight: 600; font-size: 1.05em; transition: background 0.2s; }
  .btn-app-store:hover { background: #333; color: #fff !important; }

  .section-title { font-size: 1.5em; margin: 2.5em 0 1em; text-align: center; font-weight: 700; }

  .feature-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; max-width: 40em; margin: 0 auto 2em; }
  .feature-card { background: #f6f8fa; border-radius: 14px; padding: 1.2em 1.1em; display: flex; align-items: flex-start; gap: 0.75em; transition: background 0.15s; }
  .feature-card:hover { background: #eaeef2; }
  .feature-icon { font-size: 1.6em; flex-shrink: 0; line-height: 1; margin-top: 0.05em; }
  .feature-text strong { display: block; color: #24292f; font-size: 0.95em; margin-bottom: 0.2em; }
  .feature-text span { color: #57606a; font-size: 0.88em; line-height: 1.45; }

  .feature-card.full-width { grid-column: 1 / -1; justify-content: center; background: #eef6ee; }
  .feature-card.full-width:hover { background: #ddeedd; }

  @media (max-width: 600px) {
    .feature-grid { grid-template-columns: 1fr; }
  }
</style>

<p class="nav-links">
  <a href="./">Home</a> · 
  <a href="./privacy">Privacy</a> · 
  <a href="./support">Support</a>
</p>

<div class="app-hero">
  <img src="assets/icon.png" alt="Still app icon" class="app-icon" width="128" height="128">
  <h1>Still</h1>
  <p class="tagline">Your private companion for daily calm.</p>
  <p class="subtitle">One tap when stress hits. Guided breathing to reset. Insights to understand your patterns.</p>
  <a href="https://apps.apple.com/app/id6755608523" class="btn-app-store" target="_blank" rel="noopener">Download on the App Store</a>
</div>

<h2 class="section-title">Features</h2>

<div class="feature-grid">
  <div class="feature-card">
    <div class="feature-icon">🎯</div>
    <div class="feature-text">
      <strong>One-Tap Stress Logging</strong>
      <span>Log a stressful moment in seconds, right when it happens</span>
    </div>
  </div>
  <div class="feature-card">
    <div class="feature-icon">🌬️</div>
    <div class="feature-text">
      <strong>5 Breathing Techniques</strong>
      <span>Box, 4-7-8, Coherent, Calming, and Energizing exercises</span>
    </div>
  </div>
  <div class="feature-card">
    <div class="feature-icon">📊</div>
    <div class="feature-text">
      <strong>Insights & Patterns</strong>
      <span>See when and where your stress peaks over time</span>
    </div>
  </div>
  <div class="feature-card">
    <div class="feature-icon">⌚</div>
    <div class="feature-text">
      <strong>Apple Watch App</strong>
      <span>Log stress and breathe directly from your wrist</span>
    </div>
  </div>
  <div class="feature-card full-width">
    <div class="feature-icon">🔒</div>
    <div class="feature-text">
      <strong>100% Private</strong>
      <span>Your data stays on your device. No accounts, no tracking.</span>
    </div>
  </div>
</div>


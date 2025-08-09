---
layout: page
title: About
sidebar_link: true
---

<style>
  .about-card {
    background-color: #ffffff;
    border-radius: 20px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    padding: 40px;
    margin: 40px auto;
    max-width: 800px;
    display: flex;
    align-items: center;
    gap: 40px;
    overflow: hidden;
  }
  .about-text {
    flex: 1;
  }
  .about-text h2 {
    font-size: 2em;
    font-weight: bold;
    margin-top: 0;
  }
  .about-image {
    flex-shrink: 0;
  }
  .about-image img {
    width: 300px;
    border-radius: 15px;
  }
  .cta-section {
    text-align: center;
    padding: 30px;
    background-color: #f8f9fa;
    border-radius: 15px;
    margin: 40px auto;
    max-width: 800px;
  }
  .cta-button {
    display: inline-block;
    background-color: #0088cc;
    color: #ffffff;
    padding: 12px 25px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.1em;
    margin-top: 20px;
    transition: background-color 0.3s;
  }
  .cta-button:hover {
    background-color: #005f99;
  }
  @media (max-width: 768px) {
    .about-card {
      flex-direction: column;
      text-align: center;
    }
  }
</style>

<div class="about-card">
  <div class="about-text">
    <h2>每日三分鐘，掌握全球股市脈動</h2>
    <p style="font-size: 1.1em; color: #555;">我們每日精選最新股市動態，為您快速整理關鍵價量資訊與市場焦點，讓您用最短的時間，洞悉趨勢，做出最佳決策。</p>
  </div>
  <div class="about-image">
    <img src="assets/Lupin3.png" alt="me" />
  </div>
</div>

<div class="cta-section">
  <h3>加入我們的 Telegram</h3>
  <p style="color: #666;">掃描 QR Code 或點擊按鈕，即時獲取最新資訊！</p>
  <img src="assets/GNR.jpg" alt="me" width="180" style="border-radius: 10px; margin-top: 10px;" />
  <br>
  <a href="https://t.me/USStockFuntBot" class="cta-button" target="_blank" rel="noopener noreferrer">
    立即加入
  </a>
</div>

---
layout: page
title: Wearable Intelligence
permalink: /human-machine-interface/
description: Research on wearable intelligence and human-machine interfaces.
nav: false
---

<div class="hmi-article">
  <div class="hmi-visuals">
    <div class="hmi-overview">
      <img src="/assets/img/wearable_intelligence_overview_source.png" alt="Overview of the wearable intelligence system and fabrication process">
      <span class="hmi-subfigure-label label-b" aria-hidden="true">B</span>
      <span class="hmi-subfigure-label label-c" aria-hidden="true">C</span>
    </div>

    <figure class="hmi-sensing-summary">
      <img src="/assets/img/wearable_intelligence_sensing_summary.png" alt="Explosives, nerve agent, and biohazard sensor materials and microscopy images">
    </figure>
  </div>

  <div>
    <h2 style="font-size:2rem; font-weight:700; margin-bottom:18px;">
      <a class="hmi-paper-link" href="https://doi.org/10.1126/scirobotics.abn0495">Human-machine interface for robotic sensing</a>
    </h2>

    <p style="font-size:1.08rem; line-height:1.9; color:#333333; margin-bottom:24px; text-align:justify; hyphens:auto;">
    This work presents an AI-assisted, all-printed soft human-machine interface for robotic physicochemical sensing. The system combines printed electronic skins, machine-learning-based gesture decoding, robotic sensing of hazardous materials, and user feedback through electrical stimulation, enabling closed-loop interaction between a human operator and robotic platforms. <a class="hmi-paper-link" href="https://doi.org/10.1126/scirobotics.abn0495">(Science Robotics, 2023)</a>
    </p>

    <video class="hmi-video" controls preload="metadata" playsinline>
      <source src="https://30science.com/wp-content/uploads/2022/05/abn0495-overview-video-converter.com_.mp4" type="video/mp4">
      Your browser does not support embedded video.
      <a href="https://30science.com/wp-content/uploads/2022/05/abn0495-overview-video-converter.com_.mp4">Open the video directly.</a>
    </video>
  </div>
</div>

<style>
  .hmi-article {
    display: grid;
    grid-template-columns: minmax(0, 760px) minmax(220px, 340px);
    gap: 38px;
    align-items: start;
    max-width: 1140px;
    margin: 54px 0 0;
  }

  .hmi-video {
    display: block;
    width: 100%;
    max-width: 680px;
    aspect-ratio: 16 / 9;
    margin-top: 24px;
    background: #000;
    border-radius: 6px;
    object-fit: contain;
  }

  .hmi-paper-link {
    color: inherit;
    text-decoration: none;
  }

  .hmi-paper-link:hover,
  .hmi-paper-link:focus-visible {
    text-decoration: underline;
  }

  .hmi-overview {
    position: relative;
    width: 100%;
    container-type: inline-size;
  }

  .hmi-visuals {
    width: 100%;
    order: 2;
  }

  .hmi-article > div:not(.hmi-visuals) {
    order: 1;
  }

  .hmi-overview img {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 6px;
  }

  .hmi-subfigure-label {
    position: absolute;
    top: 65.98%;
    width: 3.81%;
    height: 3.39%;
    background: #fff;
    color: #000;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 2.48cqw;
    font-weight: 700;
    line-height: 1;
  }

  .hmi-subfigure-label.label-b {
    left: 0;
  }

  .hmi-subfigure-label.label-c {
    left: 51.08%;
  }

  .hmi-sensing-summary {
    margin: 42px 0 0;
  }

  .hmi-sensing-summary img {
    display: block;
    width: 100%;
    height: auto;
    max-width: 100%;
    border-radius: 4px;
  }

  @media (max-width: 760px) {
    .hmi-article {
      grid-template-columns: 1fr;
      gap: 26px;
    }

    .hmi-visuals {
      max-width: 420px;
      margin: 0 auto;
    }
  }
</style>

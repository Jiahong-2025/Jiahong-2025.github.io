---
layout: page
title: Research
permalink: /projects/
description: Soft bioelectronics for sensing, stimulation, and biofabrication.
nav: true
nav_order: 3
---

<section class="research-detail research-overview-section implantable-research-section">
  <div id="implantable-bioelectronics" class="research-detail-copy research-anchor">
    <h2>Implantable Bioelectronics</h2>
    <h3>Strain-Insensitive Tissue-Adhesive Bioelectronics for Autonomous Therapy</h3>
    <p>
      Stretchable and bioadhesive platforms for multimodal physiological monitoring and therapeutic stimulation. These soft interfaces are designed to maintain intimate contact with dynamic biological tissues while supporting stable sensing and stimulation.
    </p>

    <div class="research-video-shell">
      <video id="implantable-research-video" class="research-video" controls preload="auto" playsinline muted>
        <source src="/assets/video/elhyx-overview-50s.mp4" type="video/mp4">
        Your browser does not support embedded video.
        <a href="/assets/video/elhyx-overview-50s.mp4">Open the video directly.</a>
      </video>
      <button class="research-video-start" type="button" aria-label="Play implantable bioelectronics video">
        <i class="fas fa-play" aria-hidden="true"></i>
      </button>
    </div>
  </div>
  <figure class="research-detail-media implantable-media">
    <img src="/assets/img/implantable_bioelectronics_detail.png" width="836" height="1750" alt="Strain-insensitive tissue-adhesive bioelectronics and autonomous therapy system">
  </figure>
</section>

<section class="research-detail research-overview-section">
  <div id="in-vivo-printing" class="research-detail-copy research-anchor">
    <h2>In vivo Printing</h2>
    <p>
      Ultrasound-assisted strategies for minimally invasive biofabrication and biomedical interfaces. This direction explores remote patterning and crosslinking methods for creating functional materials within deep biological tissues.
    </p>
  </div>
  <figure class="research-detail-media in-vivo-media">
    <img src="/assets/img/in_vivo_printing.png?v=2" width="1822" height="1183" alt="Ultrasound-assisted in vivo hydrogel printing">
  </figure>
</section>

<section class="research-detail wearable-research-section">
  <div id="wearable-intelligence" class="wearable-copy research-anchor">
    <h2>Wearable Intelligence</h2>
    <h3>
      <a class="research-paper-link" href="https://doi.org/10.1126/scirobotics.abn0495">Human-machine interface for robotic sensing</a>
    </h3>
    <p>
      This work presents an AI-assisted, all-printed soft human-machine interface for robotic physicochemical sensing. The system combines printed electronic skins, machine-learning-based gesture decoding, robotic sensing of hazardous materials, and user feedback through electrical stimulation, enabling closed-loop interaction between a human operator and robotic platforms. <a class="research-paper-link" href="https://doi.org/10.1126/scirobotics.abn0495">(Science Robotics, 2023)</a>
    </p>

    <video class="research-video" controls preload="metadata" playsinline>
      <source src="https://30science.com/wp-content/uploads/2022/05/abn0495-overview-video-converter.com_.mp4" type="video/mp4">
      Your browser does not support embedded video.
      <a href="https://30science.com/wp-content/uploads/2022/05/abn0495-overview-video-converter.com_.mp4">Open the video directly.</a>
    </video>
  </div>

  <div class="wearable-visuals">
    <div class="wearable-overview">
      <img src="/assets/img/wearable_intelligence_overview_source.png" width="1208" height="1358" alt="Overview of the wearable intelligence system and fabrication process">
      <span class="wearable-subfigure-label label-b" aria-hidden="true">B</span>
      <span class="wearable-subfigure-label label-c" aria-hidden="true">C</span>
    </div>

    <figure class="wearable-sensing-summary">
      <img src="/assets/img/wearable_intelligence_sensing_summary.png" width="2332" height="1380" alt="Explosives, nerve agent, and biohazard sensor materials and microscopy images">
    </figure>
  </div>
</section>

<style>
  .research-paper-link {
    color: inherit;
    text-decoration: none;
  }

  .research-paper-link:hover,
  .research-paper-link:focus-visible {
    color: var(--global-theme-color);
    text-decoration: underline;
  }

  .research-detail {
    padding: 72px 0;
    border-bottom: 1px solid #dddddd;
  }

  .research-anchor {
    scroll-margin-top: 100px;
  }

  .research-detail:first-of-type {
    margin-top: 34px;
    border-top: 1px solid #dddddd;
  }

  .research-detail:last-of-type {
    border-bottom: 0;
  }

  .research-overview-section {
    display: grid;
    grid-template-columns: minmax(0, 1fr) minmax(280px, 0.9fr);
    gap: 64px;
    align-items: center;
  }

  .implantable-research-section {
    grid-template-columns: minmax(0, 760px) minmax(220px, 340px);
    gap: 38px;
    align-items: start;
  }

  .research-detail-copy h2,
  .wearable-copy h2 {
    margin: 0 0 20px;
    font-size: 2.55rem;
    font-weight: 700;
    line-height: 1.15;
  }

  .research-detail-copy p,
  .wearable-copy > p {
    margin: 0;
    color: #333333;
    font-size: 1.08rem;
    line-height: 1.9;
    text-align: justify;
    hyphens: auto;
  }

  .research-detail-media {
    margin: 0;
  }

  .research-detail-media img {
    display: block;
    width: 100%;
    height: auto;
    max-height: 420px;
    object-fit: contain;
  }

  .implantable-media {
    width: 100%;
    max-width: 340px;
    justify-self: end;
  }

  .implantable-media img {
    max-height: none;
  }

  .wearable-research-section {
    display: grid;
    grid-template-columns: minmax(0, 760px) minmax(220px, 340px);
    gap: 38px;
    align-items: start;
  }

  .research-detail-copy h3,
  .wearable-copy h3 {
    margin: 0 0 18px;
    color: #4f4f4f;
    font-size: 1.35rem;
    font-weight: 600;
    line-height: 1.4;
  }

  .research-video {
    display: block;
    width: 100%;
    max-width: 680px;
    aspect-ratio: 16 / 9;
    margin-top: 24px;
    background: #000000;
    border-radius: 6px;
    object-fit: contain;
  }

  .research-video-shell {
    position: relative;
    width: 100%;
    max-width: 680px;
    margin-top: 24px;
  }

  .research-video-shell .research-video {
    max-width: none;
    margin-top: 0;
  }

  .research-video-start {
    position: absolute;
    top: 50%;
    left: 50%;
    display: grid;
    place-items: center;
    width: 64px;
    height: 64px;
    padding: 0;
    transform: translate(-50%, -50%);
    border: 0;
    border-radius: 50%;
    background: rgba(0, 0, 0, 0.72);
    color: #ffffff;
    cursor: pointer;
    font-size: 1.35rem;
  }

  .research-video-start:hover,
  .research-video-start:focus-visible {
    background: var(--global-theme-color);
  }

  .research-video-start[hidden] {
    display: none;
  }

  .wearable-visuals {
    width: 100%;
  }

  .wearable-overview {
    position: relative;
    width: 100%;
    container-type: inline-size;
  }

  .wearable-overview img,
  .wearable-sensing-summary img {
    display: block;
    width: 100%;
    height: auto;
    max-width: 100%;
    border-radius: 4px;
  }

  .wearable-subfigure-label {
    position: absolute;
    top: 65.98%;
    width: 3.81%;
    height: 3.39%;
    background: #ffffff;
    color: #000000;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 2.48cqw;
    font-weight: 700;
    line-height: 1;
  }

  .wearable-subfigure-label.label-b {
    left: 0;
  }

  .wearable-subfigure-label.label-c {
    left: 51.08%;
  }

  .wearable-sensing-summary {
    margin: 42px 0 0;
  }

  @media (max-width: 760px) {
    .research-detail {
      padding: 54px 0;
    }

    .research-overview-section,
    .wearable-research-section {
      grid-template-columns: 1fr;
      gap: 32px;
    }

    .wearable-visuals {
      max-width: 420px;
      margin: 0 auto;
    }

    .implantable-media {
      justify-self: center;
    }
  }
</style>

<script>
  (() => {
    const video = document.getElementById('implantable-research-video');
    const startButton = document.querySelector('.research-video-start');

    if (!video || !startButton) return;

    startButton.addEventListener('click', async () => {
      try {
        await video.play();
      } catch (error) {
        startButton.hidden = false;
      }
    });

    video.addEventListener('playing', () => {
      startButton.hidden = true;
    });

    video.addEventListener('pause', () => {
      if (!video.ended) startButton.hidden = false;
    });

    video.addEventListener('ended', () => {
      startButton.hidden = false;
    });
  })();
</script>

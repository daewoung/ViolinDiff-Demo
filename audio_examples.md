---
layout: page
title: Audio Examples
---
<head>
  <style>
    .audio-comparison {
      padding: 20px;
      margin-bottom: 30px;
      border-radius: 10px;
      border: 1px solid #e0e0e0;
      background-color: #f9f9f9;
      width: 100%; /* 가로를 페이지 전체로 설정 */
      max-width: 1200px; /* 최대 너비 제한 */
      margin: 0 auto; /* 가운데 정렬 */
    }

    .audio-container {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .audio-block {
      width: 45%; /* 너비를 45%로 유지 */
      text-align: center;
      margin-bottom: 10px; /* 아래 여백을 줄임 */
    }

    p {
      margin-bottom: 5px; /* 텍스트 아래 간격 줄임 */
    }

    audio {
      width: 100%;
      margin-top: 5px; /* 오디오 태그 위 간격 줄임 */
    }
  </style>
</head>


<div class="page">
  <h2>Vocoder Quality</h2>
  <p> Here, we provide examples to illustrate the quality of the Soundstream vocoder, which sets an upper bound on the quality of our generated performances. </p>


  
  <section class="audio-comparison">
    <div class="audio-container">
      <div class="audio-block">
        <p>Original</p>
        <audio controls>
          <source src="vocoder/Kayser_Op20-36_org_7.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Vocoder</p>
        <audio controls>
          <source src="vocoder/Kayser_Op20-36_vocoder_7.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original</p>
        <audio controls>
          <source src="vocoder/Wohlfahrt_Op45-30_org_0.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Vocoder</p>
        <audio controls>
          <source src="vocoder/Wohlfahrt_Op45-30_vocoder_0.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original</p>
        <audio controls>
          <source src="vocoder/Paganini_Op01-05_org_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Vocoder</p>
        <audio controls>
          <source src="vocoder/Paganini_Op01-05_vocoder_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original</p>
        <audio controls>
          <source src="vocoder/Paganini_Op01-13_org_14.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Vocoder</p>
        <audio controls>
          <source src="vocoder/Paganini_Op01-13_vocoder_14.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
  </section>
  
  <section class="audio-comparison">
    <h2>(Zero Shot) Ysaÿe - Sonata No.3 in D minor</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_ysaye_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>ViolinDiff</p>
        <audio controls>
          <source src="bend_segment_ysaye_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>NoBend Model</p>
        <audio controls>
          <source src="no_bend_segment_ysaye_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Hawth.</p>
        <audio controls>
          <source src="magenta_segment_ysaye_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Maman.</p>
        <audio controls>
          <source src="perfdiff_segment_ysaye_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>GM</p>
        <audio controls>
          <source src="window_gm_segment_ysaye_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </section>
  
  <section class="audio-comparison">
    <h2>Paganini_Op01-13</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_Paganini_Op01-13_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>ViolinDiff</p>
        <audio controls>
          <source src="bend_segment_Paganini_Op01-13_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>NoBend Model</p>
        <audio controls>
          <source src="no_bend_segment_Paganini_Op01-13_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Hawth.</p>
        <audio controls>
          <source src="magenta_segment_Paganini_Op01-13_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Maman.</p>
        <audio controls>
          <source src="perfdiff_segment_Paganini_Op01-13_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>GM</p>
        <audio controls>
          <source src="window_gm_segment_Paganini_Op01-13_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </section>
  
  <section class="audio-comparison">
    <h2>Paganini_Op01-05</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_Paganini_Op01-05_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>ViolinDiff</p>
        <audio controls>
          <source src="bend_segment_Paganini_Op01-05_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>NoBend Model</p>
        <audio controls>
          <source src="no_bend_segment_Paganini_Op01-05_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Hawth.</p>
        <audio controls>
          <source src="magenta_segment_Paganini_Op01-05_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Maman.</p>
        <audio controls>
          <source src="perfdiff_segment_Paganini_Op01-05_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>GM</p>
        <audio controls>
          <source src="window_gm_segment_Paganini_Op01-05_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </section>
  
  <section class="audio-comparison">
    <h2>(Zero Shot) BWV 1005: IV. Allegro assai</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_allegro_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>ViolinDiff</p>
        <audio controls>
          <source src="bend_segment_allegro_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>NoBend Model</p>
        <audio controls>
          <source src="no_bend_segment_allegro_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Hawth.</p>
        <audio controls>
          <source src="magenta_segment_allegro_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Maman.</p>
        <audio controls>
          <source src="perfdiff_segment_allegro_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>GM</p>
        <audio controls>
          <source src="window_gm_segment_allegro_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </section>
  
  <section class="audio-comparison">
    <h2>Paganini_Op01-24</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_Paganini_Op01-24_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>ViolinDiff</p>
        <audio controls>
          <source src="bend_segment_Paganini_Op01-24_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>NoBend Model</p>
        <audio controls>
          <source src="no_bend_segment_Paganini_Op01-24_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Hawth.</p>
        <audio controls>
          <source src="magenta_segment_Paganini_Op01-24_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Maman.</p>
        <audio controls>
          <source src="perfdiff_segment_Paganini_Op01-24_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>GM</p>
        <audio controls>
          <source src="window_gm_segment_Paganini_Op01-24_performer_15.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </section>
  
  <section class="audio-comparison">
    <h2>Wohlfahrt_Op45-60</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_Wohlfahrt_Op45-60_performer_1.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>ViolinDiff</p>
        <audio controls>
          <source src="bend_segment_Wohlfahrt_Op45-60_performer_1.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>NoBend Model</p>
        <audio controls>
          <source src="no_bend_segment_Wohlfahrt_Op45-60_performer_1.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Hawth.</p>
        <audio controls>
          <source src="magenta_segment_Wohlfahrt_Op45-60_performer_1.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Maman.</p>
        <audio controls>
          <source src="perfdiff_segment_Wohlfahrt_Op45-60_performer_1.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>GM</p>
        <audio controls>
          <source src="window_gm_segment_Wohlfahrt_Op45-60_performer_1.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </section>
  
  <section class="audio-comparison">
    <h2>(Zero Shot) Thaïs - Méditation</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_thais_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>ViolinDiff</p>
        <audio controls>
          <source src="bend_segment_thais_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>NoBend Model</p>
        <audio controls>
          <source src="no_bend_segment_thais_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Hawth.</p>
        <audio controls>
          <source src="magenta_segment_thais_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Maman.</p>
        <audio controls>
          <source src="perfdiff_segment_thais_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>GM</p>
        <audio controls>
          <source src="window_gm_segment_thais_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </section>
  
  <section class="audio-comparison">
    <h2>Paganini_Op01-24</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_Paganini_Op01-24_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>ViolinDiff</p>
        <audio controls>
          <source src="bend_segment_Paganini_Op01-24_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>NoBend Model</p>
        <audio controls>
          <source src="no_bend_segment_Paganini_Op01-24_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Hawth.</p>
        <audio controls>
          <source src="magenta_segment_Paganini_Op01-24_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Maman.</p>
        <audio controls>
          <source src="perfdiff_segment_Paganini_Op01-24_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>GM</p>
        <audio controls>
          <source src="window_gm_segment_Paganini_Op01-24_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </section>
  
  <section class="audio-comparison">
    <h2>Paganini_Op01-13</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_Paganini_Op01-13_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>ViolinDiff</p>
        <audio controls>
          <source src="bend_segment_Paganini_Op01-13_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>NoBend Model</p>
        <audio controls>
          <source src="no_bend_segment_Paganini_Op01-13_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Hawth.</p>
        <audio controls>
          <source src="magenta_segment_Paganini_Op01-13_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Maman.</p>
        <audio controls>
          <source src="perfdiff_segment_Paganini_Op01-13_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>GM</p>
        <audio controls>
          <source src="window_gm_segment_Paganini_Op01-13_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </section>

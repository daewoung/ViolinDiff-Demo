---
layout: page
title: Listening Test Examples
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
  <h2>Listening Test - Realism Evaluation</h2>
  <p>We conducted a <strong>realism evaluation</strong> to assess how closely the synthesized audio matches real violin performances. Realism in this context refers to the perceived authenticity of the generated audio, specifically how natural and convincing the synthesized performances sound compared to real violin recordings.</p>

  <p>The evaluation was carried out using the <strong>MUSHRA</strong> methodology, a standardized tool for subjective audio quality assessment. Participants rated multiple models, including:</p>

  <ul>
    <li><strong>Hawthorne et al.</strong> <cite>{multiinst}</cite>: A multi-instrument diffusion-based model focused on synthesizing various instruments in polyphonic contexts.</li>
    <li><strong>Maman et al.</strong> <cite>{performerdiff}</cite>: A model using performer embeddings to better capture timbre and style in orchestral instrument synthesis.</li>
    <li><strong>Bends Model</strong>: Our Proposed model that includes pitch bend information to enhance expressiveness and realism.</li>
    <li><strong>NoBends Model</strong>: Against a version of DiffSynth trained without pitch bend information</li>
    <li><strong>GM Soundfont (Low Anchor)</strong>: The lowest quality baseline, serving as an anchor point for comparison.</li>
  </ul>

  <h3>References</h3>
  <ol>
    <li>Hawthorne, Curtis, et al. "Multi-instrument Music Synthesis with Diffusion Models." In Proceedings of the International Conference on Machine Learning (ICML), 2022.</li>
    <li>Maman, L., et al. "Diffusion Models for Performer Embeddings: Enhancing Timbre and Style in Orchestral Instrument Synthesis." In Advances in Neural Information Processing Systems (NeurIPS), 2023.</li>
  </ol>


  
  <section class="audio-comparison">
    <h2>Kayser_Op20-36</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_Kayser_Op20-36_performer_2.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Bend Model</p>
        <audio controls>
          <source src="bend_segment_Kayser_Op20-36_performer_2.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>NoBend Model</p>
        <audio controls>
          <source src="no_bend_segment_Kayser_Op20-36_performer_2.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Hawth.</p>
        <audio controls>
          <source src="magenta_segment_Kayser_Op20-36_performer_2.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Maman.</p>
        <audio controls>
          <source src="perfdiff_segment_Kayser_Op20-36_performer_2.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>GM</p>
        <audio controls>
          <source src="window_gm_segment_Kayser_Op20-36_performer_2.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
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
        <p>Bend Model</p>
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
        <p>Bend Model</p>
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
        <p>Bend Model</p>
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
        <p>Bend Model</p>
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
        <p>Bend Model</p>
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
        <p>Bend Model</p>
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
        <p>Bend Model</p>
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
    <h2>Paganini_Op01-24.wav</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_Paganini_Op01-24_performer_12.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Bend Model</p>
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
    <h2>Paganini_Op01-13.wav</h2>
    <div class="audio-container">
      <div class="audio-block">
        <p>Original Audio</p>
        <audio controls>
          <source src="original_segment_Paganini_Op01-13_performer_13.wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <div class="audio-block">
        <p>Bend Model</p>
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

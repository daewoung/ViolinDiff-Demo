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
  <p> Here, we provide examples to illustrate the quality of the Soundstream vocoder, which sets an upper bound on the quality of our generated audio. </p>

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
    </div> <!-- Closing audio-container -->
  </section>
</div> <!-- Closing page -->


<div class="page">
  <h2>Synthesized Samples</h2>
  <p> We present long sample comparisons between the NoBend and ViolinDiff to demonstrate their performance differences.  </p>


  
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
  
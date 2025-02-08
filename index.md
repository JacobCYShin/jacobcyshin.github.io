---
layout: default
title: Changyeop Shin
---

{% raw %}
<button onclick="switchLanguage('ko')">🇰🇷 한국어</button>
<button onclick="switchLanguage('en')">🇺🇸 English</button>

<div id="content-ko" style="display: none;">
  <h2>환영합니다!</h2>
  저는 **생성형 AI, 컴퓨터 비전, 실시간 AI 응용**을 연구하는 인공지능 연구원입니다.
  제 연구는 **가상 인간 시스템, 위성영상 분석, AI 기반 과학 기술**과 관련된 솔루션 개발에 중점을 둡니다.  
  저는 **하나금융융합기술원(HIT)**에서 연구원으로 근무하며, **가상 인간 생성 및 AI 기반 영상 합성 연구**를 수행하고 있습니다.  
  이전에는 **한국원자력연구원(KAERI)**에서 실시간 방사선 감지 AI 연구를 수행했으며,  
  **국방과학연구소(ADD)**에서 인공위성 영상 분석과 관련된 컴퓨터 비전 연구를 수행하였습니다.
</div>

<div id="content-en">
  <h2>Welcome!</h2>
  I am an **AI researcher specializing in generative models, computer vision, and real-time AI applications**.
  My expertise lies in **AI-driven virtual human systems, computational imaging, and deep learning for industrial applications**.
  I am currently a researcher at **Hana Institute of Technology (HIT)**, focusing on **AI-driven virtual avatars and motion synthesis**.
</div>

<script>
  function switchLanguage(lang) {
    if (lang === 'ko') {
      document.getElementById('content-ko').style.display = 'block';
      document.getElementById('content-en').style.display = 'none';
    } else {
      document.getElementById('content-ko').style.display = 'none';
      document.getElementById('content-en').style.display = 'block';
    }
  }
  // 기본 언어 설정 (예: English)
  switchLanguage('en');
</script>
{% endraw %}

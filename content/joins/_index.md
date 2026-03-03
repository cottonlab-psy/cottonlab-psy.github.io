---
title: "JOIN US"
layout: "single"
---

<style>
  /* 상단 브레드크럼(Home > MEMBERS) 숨기기 */
  .breadcrumbs {
      display: none !important;
  }

  /* 테마가 자동으로 생성하는 페이지 제목 영역 숨기기 */
  .post-header {
      display: none !important;
  }
  
  /* 모집 공고 박스 */
  .join-recruitment {
    background-color: #f8f9fa;
    border-left: 5px solid #007bff;
    padding: 25px;
    margin-bottom: 40px;
    border-radius: 0 8px 8px 0;
  }
  .join-recruitment h2 {
    margin-top: 0;
    color: #0056b3;
    font-size: 1.4rem;
  }
  .join-recruitment p {
    font-size: 1.1rem;
    line-height: 1.7;
    margin-bottom: 0;
  }

  /* 위치 정보 섹션 */
  .location-container {
    display: flex;
    flex-direction: column;
    gap: 30px;
    margin-top: 20px;
  }
  .address-info {
    font-size: 1.05rem;
    line-height: 1.8;
  }
  .address-info strong {
    color: #222;
    font-size: 1.2rem;
  }

  /* 지도 컨테이너 (반응형) */
  .map-wrapper {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 비율 */
    height: 0;
    overflow: hidden;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }
  .map-wrapper iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
  }

  @media (min-width: 768px) {
    .location-container {
      flex-direction: row;
      align-items: flex-start;
    }
    .address-info {
      flex: 1;
    }
    .map-section {
      flex: 1.5;
    }
  }
</style>

<div class="join-recruitment">
  <h2>Looking for Future Lab Members</h2>
  <p>
    We are considering accepting a new graduate student for the <strong>2026 Fall Semester</strong>. 
    If you are interested in joining the COTTON Lab, please send an email to 
    <a href="mailto:injae.hong@chungbuk.ac.kr" style="color: #0056b3; text-decoration: underline;">injae.hong@chungbuk.ac.kr</a> 
    with a brief description of your academic background and research interests.
  </p>
</div>

<hr style="border: 0; border-top: 1px dashed #ddd; margin: 40px 0;">

<div class="location-container">
  
  <div class="address-info">
    <strong>Location</strong><br>
    N15-462<br>
    Department of Psychology, College of Social Sciences<br>
    Chungbuk National University<br><br>
    1 Chungdae-ro, Seowon-gu, Cheongju-si,<br>
    Chungcheongbuk-do, Republic of Korea<br>
    (Zip: 28644)
  </div>

  <div class="map-section">
    <div class="map-wrapper">
      <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3213.2435728864!2d127.45341257635674!3d36.63255657685161!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x356528994770669b%3A0xc68d24597d8c4c37!2z7Lap67aB64yA7ZWZ6rWQIOyCrO2ajOq8vO2VmeuMgO2VmSAoTjE1KQ!5e0!3m2!1sko!2skr!4v1709450000000!5m2!1sko!2skr" 
        allowfullscreen="" 
        loading="lazy" 
        referrerpolicy="no-referrer-when-downgrade">
      </iframe>
    </div>
  </div>

</div>

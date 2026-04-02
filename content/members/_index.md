---
title: "MEMBERS"
layout: "list"
---

<style>
  /* default: mobile (vertical) */
  .member-card {
    display: flex;
    flex-direction: column;
    align-items: center; 
    gap: 20px;
    margin-bottom: 50px;
    text-align: center;
  }

  .member-photo img {
    width: 200px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }

  .member-info h1 {
    margin-top: 0;
    margin-bottom: 10px;
    font-size: 1.4rem;
  }

  .member-info p {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #333;
    text-align: left; /* 본문은 읽기 편하게 왼쪽 정렬 */
  }

  .member-contact strong {
    color: #222;
    margin-right: 8px;
  }

  /* 아이콘 스타일 */
  .icon-link {
  display: inline-flex;
  align-items: center;
  gap: 5px;
  text-decoration: none;
  color: #555;
  transition: color 0.2s;
  }
  
  .icon-link:hover {
  color: #007bff;
  }
  
  .icon-svg {
  width: 20px;
  height: 20px;
  fill: currentColor;
  }
    
  .recruitment-note {
  margin-top: 20px;
  padding: 15px;
  background-color: #f0f7ff;
  border-left: 4px solid #007bff;
  font-size: 1rem;
  line-height: 1.5;
  color: #0056b3;
  text-align: left;
  }

  /* 상단 브레드크럼(Home > MEMBERS) 숨기기 */
  .breadcrumbs {
      display: none !important;
  }

  /* 테마가 자동으로 생성하는 페이지 제목 영역 숨기기 */
  .post-header {
      display: none !important;
  }
    
  /* desktop: when min-width is 768 px; horizontal */
  @media (min-width: 768px) {
    .member-card {
      flex-direction: row;
      align-items: flex-start;
      text-align: left;
      gap: 30px;
    }
    
    .member-photo {
      flex-shrink: 0;
    }
  }
</style>

<div class="member-card">
  
  <div class="member-photo">
    <img src="/InjaeHong.jpg" alt="Injae Hong">
  </div>

  <div class="member-info">
    <h1><strong>Injae Hong / Principal Investigator</strong></h1>
    <p>
      Injae is an Assistant Professor in the Department of Psychology at Chungbuk National University. Her academic foundation was built at Yonsei University, where she earned her B.A. in Psychology and Philosophy, followed by an M.A. and Ph.D. under the mentorship of Dr. Min-Shik Kim. Prior to joining the faculty in 2026, she completed a postdoctoral fellowship with Dr. Jeremy M. Wolfe at Brigham and Women's Hospital / Harvard Medical School, and (unofficially) worked with Dr. Hakwan Lau at Institute of Basic Science. Outside of research, Injae is a dedicated knitter who loves to craft clothes and dolls. While she is deeply committed to her current field, she's already manifesting her post-retirement plan: opening a little yarn store in town.
    </p>

  <div class="member-contact">
      <strong>Email:</strong> 
      <a href="mailto:injae.hong@chungbuk.ac.kr" style="color: #0056b3; text-decoration: none; border-bottom: 1px solid #0056b3;">
        injae.hong@chungbuk.ac.kr
      </a>
  </div>

  <div style="display: flex; gap: 20px; margin-top: 5px;">
  <a href="https://scholar.google.com/citations?user=gKCDjf0AAAAJ&hl=en&oi=ao" class="icon-link" target="_blank" title="Google Scholar">
  <svg class="icon-svg" viewBox="0 0 24 24"><path d="M12 24a7 7 0 0 1-7-7c0-2.78 1.63-5.12 4-6.12V10c0-1.1.9-2 2-2h2c1.1 0 2 .9 2 2v.88c2.37 1 4 3.34 4 6.12a7 7 0 0 1-7 7m0-2a5 5 0 0 0 5-5c0-2.08-1.28-3.87-3.11-4.6l-1.89 4.31l-1.89-4.31C8.28 13.13 7 14.92 7 17a5 5 0 0 0 5 5M12 2L2 7l10 5l10-5l-10-5z"/></svg>
</a>

<a href="https://www.dropbox.com/scl/fi/hf2efcdqnusq4ojnpqsdm/InjaeHong_CV.pdf?rlkey=2lthdv4lkf0stm1g7c3nqut6r&dl=0" class="icon-link" target="_blank" title="Download CV">
<svg class="icon-svg" viewBox="0 0 24 24"><path d="M14 2H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8l-6-6zm2 16H8v-2h8v2zm0-4H8v-2h8v2zm-3-5V3.5L18.5 9H13z"/></svg>
</a>
</div>

  </div>

</div>

<hr style="margin-top: 50px; border: 0; border-top: 1px solid #eee;">

<div class="recruitment-note">
      <strong>Looking for motivated students!</strong><br>
      We are considering recruiting new graduate students. If you are interested in joining the COTTON Lab, please contact us at <a href="mailto:injae.hong@chungbuk.ac.kr" style="color: #0056b3; text-decoration: underline;">injae.hong@chungbuk.ac.kr</a>.
    </div>

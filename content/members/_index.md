---
title: "MEMBERS"
layout: "list"
---

<style>
  /* 기본 레이아웃 및 모바일 설정 */
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
    text-align: left;
  }

  .member-contact {
    margin-top: 15px;
    font-size: 1rem;
    color: #444;
    text-align: left;
  }

  .member-contact strong {
    color: #222;
    margin-right: 8px;
  }

  .recruitment-note {
    margin-top: 25px;
    padding: 15px;
    background-color: #f0f7ff;
    border-left: 4px solid #007bff;
    font-size: 1rem;
    line-height: 1.5;
    color: #0056b3;
    text-align: left;
  }

  @media (min-width: 768px) {
    .member-card {
      flex-direction: row;
      align-items: flex-start;
      text-align: left;
      gap: 30px;
    }
    .member-photo { flex-shrink: 0; }
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
  </div> 

  <div class="member-contact">
      <strong>Email:</strong> 
      <a href="mailto:injae.hong@chungbuk.ac.kr" style="color: #0056b3; text-decoration: none; border-bottom: 1px solid #0056b3;">
        injae.hong@chungbuk.ac.kr
      </a>
  </div>

  
</div>


<div class="recruitment-note">
      <strong>Looking for motivated students!</strong><br>
      We are considering recruiting new graduate students. If you are interested in joining the COTTON Lab, please contact us via the email above.
</div>

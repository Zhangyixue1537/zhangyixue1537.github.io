---
layout: default
title: Home
header: Welcome to Yixue's personal page!
---

<style>
.about-section h3 {
  font-size: 38px;
}

.bio-section p {
  margin-bottom: 30px;
}

.profile-img {
  width: 400px;
  border-radius: 10px;
  box-shadow: 0 0 5px rgba(0,0,0,0.1);
}

.profile-container {
  flex: 0 0 400px;
  text-align: center;
  margin-left: 10px;
  align-self: center;
}

/* Responsive: only adjust image size, keep layout */
@media (max-width: 768px) {
  .profile-img {
    width: 250px;
  }
  .profile-container {
    flex: 0 0 100%;
    margin-left: 0;
    text-align: center;
    margin-top: 20px; /* 可选：增加与上方简介的间距 */
  }
}

.cv-button {
  display: inline-block;
  padding: 10px 24px;
  background-color: transparent;     /* 背景透明 */
  color: black;                      /* 黑色字体 */
  text-decoration: none;
  border: 1px solid black;           /* 细黑色边框 */
  border-radius: 4px;                /* 稍微圆一点，更现代（可设为0完全方形） */
  font-weight: bold;
  font-size: 18px;
  transition: background-color 0.3s ease, color 0.3s ease;
}

.cv-button:hover {
  background-color: black;           /* 悬停时黑底白字 */
  color: white;
}

</style>

<div style="display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap;">

  <!-- 左侧简介 -->
  <div class="about-section" style="flex: 1; min-width: 250px; margin-right: 20px;">
    <h3>About</h3>
    <p>I am a data scientist specializing in travel behaviour analysis, accessibility, and transportation equity. I hold a Ph.D. in Planning from the University of Toronto, where my research focused on understanding the travel behaviour of people using emerging transportation modes such as ride-sharing and on-demand transit, and evaluating the social impacts of these transportation services. I also hold a Master’s degree in Urban and Regional Planning and a Bachelor’s degree in Economics from Peking University.</p>
    <p>My technical expertise includes machine learning, statistical modeling, and spatial analysis, applied to multi-million-record transportation datasets. I have extensive experience with Python, R, SQL, and spatial analysis tools such as QGIS. Currently, I work as a Research Analyst at the City of Toronto, applying advanced data analytics and predictive modeling to improve urban mobility systems and inform equitable transportation policies.</p>
    <p>I am passionate about leveraging data-driven insights to enhance user experience and mobility access, especially for underserved communities. My work combines rigorous quantitative analysis with a strong commitment to real-world impact.</p>
  </div>

<!-- 右侧头像 -->
<div class="profile-container">
  <img src="{{ '/figures/profile1YZ.jpg' | relative_url }}"
       alt="Yixue Zhang"
       class="profile-img">

  <!-- 下载CV按钮 -->
  <div style="margin-top: 20px;">
    <a href="{{ '/assets/css/YixueZhang_CV_25Jul.pdf' | relative_url }}"
       target="_blank"
       class="cv-button">
       Download CV
    </a>
  </div>
</div>

</div>
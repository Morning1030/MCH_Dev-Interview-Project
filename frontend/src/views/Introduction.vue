<template>
  <div class="introduction">
    <header class="intro-header">
      <div class="personal-image" >
        <img src="/personal_image.jpg" />
      </div>
      <div class="personal-text">
        <h2>自我介紹</h2>
        <p>
          我是清大電資班大三的蔡孟伶，想要累積團隊開發和課外應用的經驗所以來應徵梅竹黑客松開發部的職位。
          之前大二在軟體實驗課有做過網站和連接firebase API，所以我覺得我應該蠻符合開發部的要求的。在團隊工作當中，我覺得我是隨和的人，但如果有想法也敢於向大家開口，並且可以負起開發部的責任完成份內
          的工作。希望如果加入梅竹黑克松的工作會，可以認識更多有想法和特長的人。
          我平常喜歡看小說、看kpop、跳舞等等，最近喜歡吉伊卡哇，如果也喜歡的話可以和我聊這些！
        </p>
      </div>
        
      
    </header>
    <section class="about-section">
      <h3>個人資訊補充</h3>
      <ul>
        <li>我的gitHub有我之前做的chatting room網站</li>
        <li>希望在大三這年可以再挑戰自己！</li>
        <li>拜託錄取我求你了</li>
      </ul>
      
    </section>
  </div>
</template>


<style scoped>
.introduction {
  padding: 40px 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.intro-header {
  font-size: 20px;
  background-color: #f5f5f5;
  padding: 40px;
  border-radius: 20px;
  line-height: 2.0;
  display: flex;
  align-items: flex-start;
  gap: 20px;
  flex-wrap: nowrap;
}

.personal-image {
  border-radius: 50%;
  height: 270px;
  width: 270px;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  flex-shrink: 0;
}
.personal-image img{
  border-radius: 50%;
  height: 80%;
  width: 80%;
  object-fit: cover;
}
.intro-text h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.intro-text p {
  flex: 1;
  font-size: 1.0rem;
  margin-bottom: 20px;
}

.contact-button {
  padding: 10px 20px;
  background-color: #656d73;
  border: none;
  border-radius: 5px;
  color: #fff;
  cursor: pointer;
}

.contact-button:hover {
  background-color: #36383a;
}

.about-section {
  margin-top: 40px;
  padding: 0 40px;
}

.about-section h3 {
  font-size: 1.6rem;
  margin-top: 20px;
  margin-bottom: 10px;
}
.about-section ul {
  font-size: 1.3rem;
  line-height: 2.0;
  font-family: 'Microsoft JhengHei';
}
.about-section p {
  font-size: 1rem;
  line-height: 1.6;
}
</style>

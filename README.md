<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>따뜻한 모던 여아 패션</title>
<style>
  body {
    font-family: 'Noto Sans KR', sans-serif;
    background-color: #fff8f0;
    color: #4a4a4a;
    margin: 0;
    padding: 0;
  }
  header {
    background: #f6e9df;
    padding: 1rem 2rem;
    text-align: center;
    font-size: 1.8rem;
    font-weight: 700;
    color: #7d5a50;
  }
  .container {
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 1rem;
  }
  .intro {
    text-align: center;
    margin-bottom: 3rem;
    font-size: 1.1rem;
    color: #7d5a50;
  }
  .product-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
  }
  .product-item {
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(125, 90, 80, 0.15);
    overflow: hidden;
    transition: box-shadow 0.3s ease;
  }
  .product-item:hover {
    box-shadow: 0 8px 16px rgba(125, 90, 80, 0.3);
  }
  .product-img {
    width: 100%;
    height: 280px;
    object-fit: cover;
  }
  .product-info {
    padding: 1rem 1.5rem;
  }
  .product-title {
    font-size: 1.25rem;
    font-weight: 700;
    color: #5c3d36;
    margin-bottom: 0.5rem;
  }
  .product-desc {
    font-size: 0.95rem;
    color: #7d5a50;
    margin-bottom: 1rem;
  }
  .product-price {
    font-weight: 700;
    color: #a45b4c;
  }
  footer {
    text-align: center;
    padding: 1rem 0;
    color: #a45b4c;
    font-size: 0.9rem;
  }
</style>
</head>
<body>

<header>
  따뜻한 모던 여아 패션
</header>

<div class="container">
  <div class="intro">
    5세부터 8세 여자아이를 위한 편안하고 트렌디한 옷들을 모았습니다.<br>
    뉴트럴톤과 파스텔 컬러, 친환경 소재에 미니멀한 디자인까지 만나보세요.
  </div>

  <section class="product-list">
    <article class="product-item">
      <img src="modern-girl-model1.jpg" alt="[translate:여자아이 오버핏 티셔츠]" class="product-img">
      <div class="product-info">
        <h3 class="product-title">오버핏 라일락 티셔츠</h3>
        <p class="product-desc">부드러운 친환경 코튼 소재, 활동성을 고려한 디자인</p>
        <p class="product-price">₩25,000</p>
      </div>
    </article>

    <article class="product-item">
      <img src="modern-girl-model2.jpg" alt="[translate:여자아이 베이지색 팬츠]" class="product-img">
      <div class="product-info">
        <h3 class="product-title">베이지 오버핏 팬츠</h3>
        <p class="product-desc">내추럴한 뉴트럴 컬러, 넉넉한 사이즈로 편안한 착용감</p>
        <p class="product-price">₩30,000</p>
      </div>
    </article>

    <article class="product-item">
      <img src="modern-girl-model3.jpg" alt="[translate:여자아이 동물 캐릭터 프린트 스웨터]" class="product-img">
      <div class="product-info">
        <h3 class="product-title">귀여운 동물 캐릭터 스웨터</h3>
        <p class="product-desc">아이들이 좋아하는 아기자기한 프린트와 친환경 원단</p>
        <p class="product-price">₩28,000</p>
      </div>
    </article>
  </section>
</div>

<footer>
  &copy; 2025 따뜻한 모던 여아 패션. All rights reserved.
</footer>

</body>
</html>

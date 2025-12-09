# Challengeonehour
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>퇴근 후 1시간 지식 숏폼 30일 챌린지</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Apple SD Gothic Neo",
        system-ui, sans-serif;
      background: #050816;
      color: #f9fafb;
      line-height: 1.6;
    }
    .wrapper {
      max-width: 720px;
      margin: 0 auto;
      padding: 20px 16px 40px;
    }
    header {
      padding: 12px 0 24px;
      text-align: center;
    }
    header h1 {
      font-size: 1.7rem;
      font-weight: 800;
      margin-bottom: 8px;
    }
    header p {
      font-size: 0.95rem;
      color: #d1d5db;
    }
    .badge {
      display: inline-block;
      font-size: 0.78rem;
      padding: 4px 10px;
      border-radius: 999px;
      background: rgba(96, 165, 250, 0.16);
      color: #bfdbfe;
      margin-bottom: 10px;
    }
    .card {
      background: radial-gradient(circle at top left, #111827, #020617);
      border-radius: 18px;
      padding: 16px 16px 18px;
      border: 1px solid rgba(148, 163, 184, 0.25);
      box-shadow: 0 18px 40px rgba(15, 23, 42, 0.8);
      margin-bottom: 18px;
    }
    .card h2 {
      font-size: 1.1rem;
      margin-bottom: 8px;
    }
    .card p {
      font-size: 0.9rem;
      color: #e5e7eb;
    }
    .benefits {
      display: grid;
      grid-template-columns: 1fr;
      gap: 10px;
      margin-bottom: 16px;
    }
    @media (min-width: 640px) {
      .benefits {
        grid-template-columns: repeat(3, 1fr);
      }
    }
    .benefit-item {
      background: rgba(15, 23, 42, 0.9);
      border-radius: 14px;
      padding: 10px;
      border: 1px solid rgba(55, 65, 81, 0.9);
      font-size: 0.8rem;
    }
    .benefit-item h3 {
      font-size: 0.86rem;
      margin-bottom: 4px;
    }
    .benefit-item p {
      font-size: 0.78rem;
      color: #d1d5db;
    }
    .steps {
      list-style: none;
      font-size: 0.88rem;
      color: #e5e7eb;
    }
    .steps li {
      margin-bottom: 6px;
    }
    .steps li span {
      display: inline-block;
      width: 22px;
      height: 22px;
      line-height: 22px;
      text-align: center;
      border-radius: 999px;
      background: #f97316;
      color: #0b1120;
      font-size: 0.78rem;
      font-weight: 700;
      margin-right: 6px;
    }
    .cta-group {
      display: flex;
      flex-direction: column;
      gap: 8px;
      margin-top: 8px;
    }
    .btn-primary,
    .btn-kakao {
      border: none;
      border-radius: 999px;
      padding: 12px 16px;
      font-size: 0.96rem;
      font-weight: 600;
      cursor: pointer;
      width: 100%;
    }
    .btn-primary {
      background: linear-gradient(135deg, #f97316, #ec4899);
      color: #0b1120;
    }
    .btn-primary:hover {
      opacity: 0.95;
    }
    .btn-kakao {
      background: #fee500;
      color: #171717;
    }
    .repeat-box {
      font-size: 0.85rem;
      background: rgba(15, 23, 42, 0.9);
      border-radius: 14px;
      padding: 10px;
      border: 1px dashed rgba(148, 163, 184, 0.6);
      margin-top: 8px;
    }
    .price {
      font-weight: 700;
      font-size: 1.1rem;
      margin-top: 4px;
    }
    footer {
      margin-top: 18px;
      font-size: 0.7rem;
      color: #6b7280;
      text-align: center;
    }
    a {
      color: #93c5fd;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div class="wrapper">
    <header>
      <div class="badge">30일 안에 나만의 지식 숏폼 채널</div>
      <h1>퇴근 후 1시간 지식 숏폼 30일 챌린지 키트</h1>
      <p>스크립트 30개 + 촬영 가이드 + 썸네일 템플릿으로,<br />직장인도 얼굴 덜 나오고 조용히 크리에이터 되기.</p>
    </header>

    <section class="card">
      <h2>이 키트로 어떤 변화가 생기나요?</h2>
      <div class="benefits">
        <div class="benefit-item">
          <h3>01. 콘텐츠 걱정 끝</h3>
          <p>그날 바로 찍을 수 있는 지식 숏폼 스크립트 30개 제공.</p>
        </div>
        <div class="benefit-item">
          <h3>02. 퇴근 후 1시간 루틴</h3>
          <p>셋팅·촬영·업로드까지 1시간 안에 끝내는 체크리스트.</p>
        </div>
        <div class="benefit-item">
          <h3>03. 수익 연결 구조</h3>
          <p>무료 체크리스트 → 유료 키트/강의로 이어지는 링크 구조 설계.</p>
        </div>
      </div>
      <div class="price">런칭 특가: 29,000원</div>
    </section>

    <section class="card">
      <h2>핵심 행동 2가지</h2>
      <ul class="steps">
        <li><span>1</span>퇴근 후 1시간, 키트에 있는 스크립트대로 숏폼 영상 1개 촬영·업로드</li>
        <li><span>2</span>영상 설명과 고정 댓글에 무료 체크리스트 + 유료 키트/카톡방 링크 고정</li>
      </ul>
      <div class="repeat-box">
        <strong>30일 반복하면?</strong><br />
        - 최소 1,000명 이상에게 노출<br />
        - 29,000원 키트 35명만 구매해도 ≒ 월 100만 원 수익 구조
      </div>
    </section>

    <section id="buy" class="card">
      <h2>지금 시작하기</h2>
      <p style="font-size:0.86rem; color:#d1d5db; margin-bottom:8px;">
        결제 후, 카카오톡으로 전송되는 링크에서<br />
        ▶ 스크립트 30개 · 촬영 가이드 · Notion 트래커 · 썸네일 문구 템플릿을 바로 받아보세요.
      </p>
      <div class="cta-group">
        <button class="btn-primary" onclick="alert('여기에 결제/폼 링크를 연결하세요.')">
          키트 받기 & 30일 챌린지 시작
        </button>
        <button class="btn-kakao" id="kakao-share-btn">
          카카오톡으로 친구에게 공유하기
        </button>
      </div>
    </section>

    <footer>
      © 2025 퇴근 후 1시간 챌린지. All rights reserved.
    </footer>
  </div>

  <!-- 카카오톡 공유 스크립트 (앱 키를 본인 것으로 교체하세요) -->
  <script src="https://developers.kakao.com/sdk/js/kakao.min.js"></script>
  <script>
    // TODO: 본인 JavaScript 키로 교체
    Kakao.init("YOUR_KAKAO_JAVASCRIPT_KEY");

    document
      .getElementById("kakao-share-btn")
      .addEventListener("click", function () {
        Kakao.Share.sendDefault({
          objectType: "feed",
          content: {
            title: "퇴근 후 1시간 지식 숏폼 30일 챌린지",
            description:
              "스크립트 30개 + 촬영 가이드로 직장인도 조용히 크리에이터 되기.",
            imageUrl: "https://via.placeholder.com/800x400.png?text=30%EC%9D%BC+%EC%B1%8C%EB%A6%B0%EC%A7%80",
            link: {
              mobileWebUrl: window.location.href,
              webUrl: window.location.href,
            },
          },
          buttons: [
            {
              title: "랜딩 페이지 보기",
              link: {
                mobileWebUrl: window.location.href,
                webUrl: window.location.href,
              },
            },
          ],
        });
      });
  </script>
</body>
</html>

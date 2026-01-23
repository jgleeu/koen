---
layout: default
title: KOEN 맞춤챗봇 모음
---

<style>
.link-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 16px;
  margin-top: 24px;
}

.link-card {
  display: block;
  padding: 18px 16px;
  border: 1px solid #e0e0e0;
  border-radius: 10px;
  text-decoration: none;
  color: inherit;
  background-color: #ffffff;
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.link-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 14px rgba(0, 0, 0, 0.08);
}

.link-card-title {
  font-weight: 600;
  font-size: 1rem;
}
</style>



업무 중 반복되는 작업과 고민을 빠르게 해결하기 위해  
**검증된 챗봇들을 한 곳에 정리**했습니다.

---

### 📌 이용 안내

- ▶ 클릭 후 **약 30초 정도 대기**가 필요합니다 (GPT 초기 로딩)
- ▶ 문의/개선 연락 : ☎6812

---


## 링크 목록

<div class="link-grid">
  {% for link in site.data.links %}
    <a class="link-card" href="{{ link.url }}" target="_blank" rel="noopener">
      <div class="link-card-title">{{ link.title }}</div>
    </a>
  {% endfor %}
</div>

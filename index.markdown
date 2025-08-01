---
layout: resume
title: "남궁은선 이력서"
permalink: /
---

<div class="header">
    <div>
      <h1><strong>남궁은선 (Eunsun Namgung)</strong></h1>
    </div>
    <div class="header-right">
      <div><strong>Email:</strong> nammugmuhg@gmail.com</div>
      <div><strong>Phone:</strong> 010-3482-3750</div>
      <div><strong>생년월일:</strong> 1997.12.07</div>
      {% include social_icons.html %}
    </div>
</div>

<div class="content">
  <section id="about">
    <div class="subtitle">프론트엔드 개발자로서 <strong>사용자에게 최적의 경험을 제공하는 것에 몰두</strong>하며 서비스를 만들어왔습니다. 노코드 웹빌더 및 커머스 플랫폼 서비스 개발 경험과, 창업을 통해 사용자 맞춤형 서비스를 직접 기획하고 운영한 경험이 있습니다.<br/>
    <strong>특히, 빠른 로딩과 직관적인 인터페이스를 통해 사용자의 만족도를 높이는 일에 흥미</strong>를 느끼며, 이를 위해 LCP와 같은 핵심 성능 지표 개선을 지속적으로 학습하고 실무에 적용합니다. 얻은 지식을 사람들과 나누고 토론하며 함께 성장하는 것을 즐깁니다.
  </div>
  </section>

  <section id="strengths">
    <h2><strong>핵심 강점</strong></h2>
    <ul>
      <li><strong>사용자 경험(UX) 중심 웹 서비스 개발 및 성능 최적화</strong>: 페이지 로딩 속도, 반응성, 사용 편의성 향상에 기여</li>
      <li><strong>React/TypeScript 기반 웹 서비스 개발 및 릴리즈 경험</strong></li>
      <li><strong>웹 서비스 성능 최적화 경험</strong>: API 호출 수 <strong>60% 감소</strong>, UX 체감 속도 <strong>2배 개선</strong> 등 성능 향상 기여</li>
      <li>CI/CD, 모노레포, 디자인 시스템 도입을 통한 개발 생산성 및 품질 향상 경험</li>
      <li>PHP 레거시 코드를 <strong>React 기반 모던 웹 애플리케이션으로 리빌드</strong>하고, MF(Micro-Frontend) 아키텍처를 도입하여 점진적 마이그레이션 경험</li>
    </ul>
  </section>

  <section id="skills">
    <h2><strong>기술 스택</strong></h2>
    <ul>
      <li><strong>Frontend</strong>: React, TypeScript, Vite, Next.js, Zustand, Jotai, React Query, Zod, Tailwind CSS, Shadcn UI, Storybook</li>
      <li><strong>Infra</strong>: AWS (EC2, S3, CloudFront, Nginx), GitHub Actions, Docker, GitLab Runner</li>
      <li><strong>Testing</strong>: Vitest, React Testing Library</li>
    </ul>
  </section>

  <section id="experience">
    <h2><strong>경력</strong></h2>
    <div class="career-wrapper">
      <div class="career-grid">
        <div>
          <div class="company">
            <div><strong>아임웹</strong></div>
          </div>
          <span class="period">2022.06 ~ 2024.03</span>
          <p>프론트엔드 (정규직)</p>
          <p class="reason-for-leaving">이직 사유: 자기 계발 및 창업 준비 도전</p>
          <p><a href="https://tropical-quartz-3cb.notion.site/1d81311db28780558f41d3fc1afbaa9b" target="_blank">아임웹 포트폴리오</a></p>
        </div>
        <div class="projects-wrapper">
          <div>
            <p>
              <span class="bold"><strong>주문관리 TF</strong></span>
              <span class="role"><strong>사용자(운영자) 경험에 최적화된 주문 관리 시스템 개편에 기여</strong></span>
              <span class="period">2023.03 ~ 2023.12</span>                        
            </p>
            <ul>
              <li>
                  효율적인 데이터 관리 및 서버 부하 감소:
                  <br/>
                  Tanstack Query의 useQuery를 활용하여 데이터를 효율적으로 조회하고 캐싱했습니다. 또한, useMutation을 통해 서버 데이터 변경 작업 시 옵티미스틱 업데이트를 적용하고 불필요한 재요청을 최소화하여, 각 주문 옵션의 상태 변화를 실시간으로 반영하면서도 불필요한 네트워크 호출을 줄이고 서버 부담을 경감했습니다.
              </li>
              <li>shadcn/ui를 기반으로 <strong>초기 디자인 시스템</strong>을 관리하고 사내 라이브러리로 도입하여 인터페이스 일관성 확보 및 개발 효율성 증대</li>
              <li><strong>가상화 기술(Virtualization)</strong>인 react-virtualized을 이용하여 대규모 상품 리스트 추가 모달에 적용,보이는 부분만 렌더링하게 하여 성능 및 사용자 반응성 향상</li>
              <li>
              <strong>Tanstack Query(`useQuery`)의 `enabled` 플래그를 통한 호출 중복 문제 해결:</strong>
                <p>주문 관리 기능은 서버 상태와의 <strong>즉각적인 동기화가 필수적</strong>이어서, `staleTime`을 짧게(혹은 0ms) 유지해야 했습니다. 이로 인해 여러 컴포넌트에서 동일한 주문 관련 데이터를 필요로 할 때, <strong>불필요한 자동 재호출로 인해 실제 네트워크 호출이 중복되는 문제</strong>가 발생했습니다.</p>
                <p>이 문제를 해결하고 <strong>네트워크 호출 수를 줄여 서버 부하를 경감</strong>하기 위해 다음과 같이 Tanstack Query를 최적화했습니다:</p>
                <ul>
                  <li><strong>`enabled` 플래그로 쿼리 실행 시점 제어</strong>: `useQuery`의 `enabled` 옵션을 `false`로 설정해 불필요한 자동 쿼리 실행을 완전히 막았습니다. 데이터를 가져와야 할 특정 사용자 액션(예: 모달 오픈, 필터 적용) 시에만 `enabled`를 `true`로 바꾸거나 `refetch` 함수를 직접 호출하도록 구현하여, <strong>반복적인 네트워크 호출을 근본적으로 차단</strong>했습니다.</li>
                  <li><strong>`select` 옵션으로 렌더링 최적화</strong>: 네트워크 호출과는 별개로, 컴포넌트별로 <strong>필요한 데이터의 특정 부분만 `select` 옵션으로 추출</strong>하여 구독했습니다. 이는 불필요한 리렌더링을 방지하고 애플리케이션의 반응성을 높이는 데 기여했습니다.</li>
                </ul>
              </li>
            </ul>
          </div>
          <div>
            <p>
              <span class="bold"><strong>Integration Squad</strong></span> 
              <span class="role"><strong>PHP 레거시 코드를 React 기반의 모던 웹 애플리케이션으로 리빌드, MF(Micro-Frontend) 모노레포 환경을 구축하여 점진적 마이그레이션 경험</strong></span>
              <span class="period">2023.12 ~ 2024.03</span>                        
            </p>
            <ul>
              <li>GHA 기반 캐시 무효화 자동화로 배포 안정성 및 속도 향상</li>
              <li>소셜 로그인 및 API 연동 관리 페이지 리빌드 및 <strong>UX 개선 (사용자 흐름 최적화)</strong></li>
              <li><strong>마이그레이션 중 iframe 내 코어 서비스 영역의 반응형 디자인 개선</strong>: 
              <br/>화면 너비가 아닌 컨테이너 기준의 디자인을 디자이너에게 제안하여 <strong>개발 효율성 및 협업 용이성 부여</strong></li>
            </ul>
          </div>
          <div>
            <p>
              <span class="bold"><strong>웹빌더 Squad & 프론트엔드 팀</strong></span> 
              <span class="role"><strong>PHP, JavaScript 유지보수 및 웹빌더 기능 개선</strong></span>
              <span class="period">2022.06 ~ 2023.01</span>                        
            </p>
            <ul>
              <li>디자이너 찾기 페이지 리뉴얼 및 <strong>Intersection Observer 도입으로 이미지 및 컴포넌트 지연 로딩 구현:</strong>
              <br/>
              사용자가 화면을 스크롤할 때만 필요한 리소스를 로드하여 <strong>초기 페이지 로딩 속도를 개선</strong>하고 <strong>불필요한 데이터 사용을 줄여 사용자 경험 및 성능 향상</strong></li>
              <li>이모지 asset 자동 생성 스크립트 및 Froala Editor 커스터마이징</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="career-grid">
        <div>
          <div class="company"><strong>엘리스 프론트엔드 파트너</strong></div>
          <span class="period">2025.4.07 ~ 2025.4.30</span>
          <p>프론트엔드, 프로젝트 매니징 (단기 파트너)</p>
          <p>
            <a href="https://tropical-quartz-3cb.notion.site/MediNow-1d71311db28780a988e0c36e17b32929" target="_blank">MediNow 포트폴리오</a>
          </p>
          <p>
            <a href="https://medinow.co.kr/" target="_blank">medinow.co.kr</a>
          </p>
        </div>
        <div>
          <p><span class="role"><strong>React/TypeScript 기반 서비스의 팀장으로서, CI/CD 파이프라인 구축 및 성능 최적화를 통해 서비스 안정성 및 사용자 경험 개선에 크게 기여했습니다.</strong></span></p>
          <ul>
            <li>Epic-Story-Task 기반 협업 구조 도입 및 팀 온보딩 주도</li>
            <li>Turborepo + Docker 기반 모노레포 환경 구축</li>
            <li>GitLab CI/CD 파이프라인 설계 및 최적화를 통해 <span class="underline">배포 시간을 약 40% 단축</span>하여 개발자 경험 향상</li>
            <li><strong>debouncing 기법 적용</strong>으로 지도 이동 최적화를 달성하여 <span class="underline">불필요한 API 호출을 약 60% 감소</span>시켜 성능 및 서버 부하 개선</li>
            <li>Optimistic Update 도입을 통해 <span class="underline">UX 체감 속도를 2배 향상</span>시키고 추가 API 호출 수 감소로 사용자 반응성 및 성능 개선</li>
            <li><strong>Next.js App Router의 서버 컴포넌트 기반 렌더링을 활용</strong>하여 병원 검색 결과 페이지의 초기 로딩 성능 및 SEO 최적화</li>
            <li>병원 즐겨찾기, 후기 작성 기능 개발 및 실시간 채팅 기능 구현</li>
          </ul>
        </div>
      </div>
      <div class="career-grid">
  <div>
    <div class="company"><strong>1인 창업 - DIY KITTEN</strong></div>
    <span class="period">2024.07 ~ 2024.12</span>
    <p>프론트엔드 개발, 사업 기획, 프로젝트 매니징</p>
    <p>구성원: 본인, 백엔드 1명</p>
    <p class="reason-for-leaving">이직 사유: 사업 확장성 및 팀 빌딩의 어려움으로 인한 재정비</p>
    <p>
      <a href="https://tropical-quartz-3cb.notion.site/DIY-KITTEN-1d91311db28780bebd1eca87c03adfb4" target="_blank">DIY KITTEN 포트폴리오</a>
    </p>
  </div>
  <div>
    <p><span class="role"><strong>사용자 커스터마이징 기반 수공예 서비스 런칭 및 운영 (사용자 주도적 경험 설계)</strong></span></p>
    <ul>
      <li>모루인형 캔버스: React-Konva 기반의 직관적인 디자인 커스터마이징 기능 구현</li>
      <li>자동화된 디자인 도구 개발: 이미지 기반 비즈 디자인 및 애니메이션 자동 생성기, CSV 기반 도안화 기능 개발</li>
      <li>
        클라우드 기반 CI/CD 파이프라인 구축 및 운영:
        <ul>
          <li>GitHub Actions와 AWS CodeDeploy를 연동하여 코드 변경 시 자동 빌드, 테스트, 배포가 이루어지는 CI/CD 워크플로우를 구축했습니다.</li>
          <li>AWS EC2 인스턴스에 Nginx 리버스 프록시를 설정하여 프론트엔드 애플리케이션의 안정적인 서비스 환경을 마련했습니다.</li>
          <li>AWS S3를 활용한 정적 파일 호스팅, IAM을 통한 접근 권한 관리, MySQL RDS 인스턴스 설정 등 AWS 클라우드 인프라를 직접 구성하고 관리한 경험이 있습니다.</li>
          <li><a href="https://jamongjjang.tistory.com/314" target="_blank">관련 기술 블로그 (Nginx 리버스 프록시 및 AWS 배포)</a></li>
        </ul>
      </li>
      <li>실제 사용자 피드백 반영: 플리마켓 부스 운영을 통해 약 100명의 사용자에게 직접적인 피드백을 수집하고 서비스 개선에 반영했습니다.</li>
    </ul>
  </div>
</div>
    </div>
  </section>

  <section id="activities">
    <h2><strong>기타 활동</strong></h2>
    <div class="career-wrapper">
      <div>
        <div>
          <div class="company"><strong>기술 세미나 및 모의 면접 스터디 주도</strong></div>
          <span class="period">2025.04 ~ 현재 진행 중</span>
        </div>
        <div>
          <p>
            <span class="role">
              지식 공유 및 동료 성장을 위한 기술 세미나 및 모의 면접 스터디 (주 1회, 온라인 진행)
            </span>
          </p>
          <ul>
            <li>모의 면접 운영: 매주 정기적인 모의 면접 진행과 피드백 교환을 통해 면접 스킬 향상에 기여했습니다.</li>
            <li>기술 서적 스터디 주도: <a href="https://github.com/grapefruitgreentealoe/Modern-React-Deep-Dive" target="_blank">모던 리액트 Deep Dive</a> 서적 스터디를 주도하며 심도 깊은 기술 지식을 공유했습니다.</li>
            <li>기술 세미나 운영: <a href="https://tropical-quartz-3cb.notion.site/1d31311db2878020a34adc91ea5da66d?v=1d31311db2878042b6ef000c6d2958b5&source=copy_link" target="_blank">정기적인 기술 세미나를 통해</a> 최신 기술 트렌드 및 지식 공유를 활성화했습니다.</li>
          </ul>
        </div>
      </div>
      <div>
        <div>
          <div class="company"><strong>타입스크립트 사내 스터디 주도</strong></div>
          <span class="period">2022.07 ~ 2022.09 (3개월)</span>
        </div>
        <div>
          <p>
            <span class="role">
              타입스크립트 서적 스터디 및 발표 (사내 진행)
            </span>
          </p>
          <ul>
            <li>타입스크립트 서적 스터디를 주도하고 발표를 진행하며, 사내 개발 효율성 및 코드 안정성 강화에 기여했습니다.</li>
            <li><a href="https://github.com/im-typescript" target="_blank">GitHub Repository</a></li>
          </ul>
        </div>
      </div>
      <div>
        <div>
          <div class="company"><strong>LeetCode 알고리즘 스터디 참여(5기)</strong></div>
          <span class="period">2025.07 ~ 현재 진행 중</span>
        </div>
        <div>
          <p>
            <span class="role">
              주요 활동 및 성과:
            </span>
          </p>
          <ul>
            <li>LeetCode 문제 해결 전략을 익히고, 효율적인 코드 작성법을 학습했습니다.</li>
            <li>문제 풀이 시 여러 접근 방식을 탐구하며 시간 및 공간 복잡도를 개선하는 방법을 체득했습니다.</li>
            <li>스터디원들의 PR(Pull Request)을 리뷰하며 코드 가독성, 효율성, 유지보수성을 검토하고, 건설적인 피드백을 주고받는 과정을 통해 소통 능력과 협업 역량을 길렀습니다.</li>
          </ul>
          <ul>
            <li><a href="https://github.com/grapefruitgreentealoe/leetcode-study" target="_blank">GitHub Repository</a></li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <section id="detailed-skills" class="next-page">
    <h2><strong>기술적 능력</strong></h2>
    <div class="skills-grid">
        <div class="skill-item">
            <p><strong>Javascript</strong></p>
            <p>실무 경험을 바탕으로 동작 원리(클로저, 호이스팅 등)를 설명할 수 있으며, ES6 이후 최신 문법을 적극적으로 활용합니다.</p>
            <p>VanillaJS를 이용한 DOM 조작 및 이벤트 처리로 <strong>웹 성능과 사용자 반응성을 고려한 개발</strong>이 가능합니다.</p>
        </div>
        <div class="skill-item">
            <p><strong>React</strong></p>
            <p>React의 동작 방식(렌더링 과정, Reconcilation)에 대해 깊이 이해하고 있습니다.</p>
            <p>Fiber 아키텍처를 통해 내부적으로 재조정이 어떻게 발생하는지 설명할 수 있으며, `React.memo`, `useMemo`, `useCallback` 등을 활용하여 <strong>컴포넌트 리렌더링을 최적화</strong>할 수 있습니다.</p>
            <p>복잡한 로직을 <strong>커스텀 훅</strong>으로 만들고 최적화하여 재사용성 및 코드 가독성을 향상시킵니다.</p>
            <p>컴포넌트 언마운트 시 발생하는 이벤트 처리와 같은 복잡한 문제를 <strong>`requestAnimationFrame`</strong> 활용 등 최적의 방식으로 해결하여 애플리케이션 안정성 및 사용자 경험 일관성 확보에 기여합니다.</p>
        </div>
        <div class="skill-item">
            <p><strong>Typescript</strong></p>
            <p>타입스크립트를 활용한 실무경험이 있으며, 타입 정의와 `Pick`과 같은 유틸리티 타입을 효과적으로 활용하여 <strong>코드 안정성과 개발 생산성을 높입니다.</strong></p>
        </div>
        <div class="skill-item">
            <p><strong>Testing</strong></p>
            <p>Vitest와 React Testing Library를 활용하여 컴포넌트의 기능적 정확성을 보장하는 단위 테스트를 작성합니다. <strong>사용자 인터랙션에 따른 상태 변화를 검증하고, 엣지 케이스를 커버하는 테스트를 작성하여 기능적 안정성을 확보합니다.</strong></p>
        </div>
        <div class="skill-item">
            <p><strong>Next.js</strong></p>
            <p>Next.js App Router를 활용하여 서버 컴포넌트, 코드 분할, 이미지 최적화 등을 통해 초기 로딩 속도 및 SEO를 개선할 수 있습니다.</p>
        </div>
       <div class="skill-item">
          <p><strong>상태 관리</strong></p>
          <p>Tanstack Query, Zustand 등 다양한 라이브러리를 활용하여 서버 및 클라이언트 상태를 효율적으로 설계하고 관리합니다. 깊은 컴포넌트 구조에서도 <strong>불필요한 렌더링을 최소화</strong>하는 로직을 작성하여 애플리케이션의 성능을 최적화하고 사용자 경험을 향상시킵니다. <strong>Tanstack Query의 캐싱 전략과 `select` 옵션을 활용하여 대규모 데이터 목록의 리렌더링을 효과적으로 제어했습니다.</strong></p>
      </div>
        <div class="skill-item">
            <p><strong>CSS</strong></p>
            <p>Tailwind CSS, Emotion 등 모던 CSS-in-JS 기법에 익숙하며, <strong>성능을 고려한 스타일링</strong>이 가능합니다.</p>
        </div>
        <div class="skill-item">
            <p><strong>HTML</strong></p>
            <p>접근성을 고려한 시맨틱 HTML 마크업 개발이 가능합니다. (header, nav, main, section, article, aside, footer 등) 이를 통해 <strong>웹 접근성 및 검색 엔진 최적화(SEO)에 기여</strong>합니다.</p>
        </div>
    </div>
  </section>

  <section id="additional-info">
    <h2><strong>기타 정보</strong></h2>
    <ul>
      <li><strong>경력 공백기:</strong> 2024.03 ~ 2024.07 창업 준비 및 자기 계발</li>
    </ul>
  </section>

  <section id="education">
    <h2><strong>교육</strong></h2>
    <ul>
      <li>한양대학교 창업지원단 린스타트업 2단계 수료 (2024.07 ~ 2024.10)</li>
      <li>엘리스 AI 서비스 기획개발 트랙 2기 (2021.06 ~ 2021.12, 데모데이 우수상)</li>
      <li>국민대학교 임산생명공학과 졸업 (2016.03 ~ 2021.02)</li>
    </ul>
  </section>
</div>

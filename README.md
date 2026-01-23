<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:2563EB&height=180&section=header&text=Gwangche%20Lee&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35" alt="header" style="width:100%" />

  <p>
    <a href="https://readme-typing-svg.demolab.com">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=2800&pause=700&color=60A5FA&center=true&vCenter=true&width=720&lines=End-to-end%20Full-stack%20Developer;OAuth%2FAuth%20%7C%20S3%20Presigned%20Upload%20%7C%20Prisma;Product%20flows%20first%2C%20security%20always" alt="typing" />
    </a>
  </p>

  <p>
    <a href="#projects"><img src="https://img.shields.io/badge/Projects-0EA5E9?style=for-the-badge" alt="projects" /></a>
    <a href="#tech"><img src="https://img.shields.io/badge/Tech%20Stack-111827?style=for-the-badge" alt="tech" /></a>
    <a href="#strengths"><img src="https://img.shields.io/badge/Strengths-22C55E?style=for-the-badge" alt="strengths" /></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
    <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
    <img src="https://img.shields.io/badge/Express-111827?style=flat-square&logo=express&logoColor=white" />
    <img src="https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=next.js&logoColor=white" />
    <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
    <img src="https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white" />
  </p>

</div>

<div align="center" style="display: flex; flex-flow: row wrap;">
	<img src="https://github-readme-stats.vercel.app/api?username=kwangche&show_icons=true&theme=tokyonight" alt="github stats" style="height: 200px"/>
	<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kwangche&layout=compact&theme=tokyonight" alt="top langs"  style="height: 200px"/>
</div>

---

<h2 id="about">About</h2>

- 프로젝트에서 OAuth 인가 위임(소셜 로그인)과 S3 Presigned URL 업로드를 중심으로 end-to-end 구현 경험이 있습니다.
- “실패를 두려워하지 않고 코드의 흐름을 빠르게 읽고 문제점을 파악하여 바로 개선할 수 있는 개발자입니다."

<h2 id="career">Career</h2>

- **대우직업능력개발원** | 반응형웹디자인전문가 양성과정 (수료) — 2023.10 ~ 2024.03
- **주식회사 한국교육평가원** | 운영지원 사원 (프론트엔드) — 2024.05 ~ 2025.06
- **코드잇 스프린트** | 풀스택 트랙 8기 (수료) — 2025.07 ~ 2026.01

<h2 id="tech">Tech Stack</h2>

<div align="left">
	<img src="https://skillicons.dev/icons?i=ts,nodejs,express,nextjs,react,prisma,postgres,aws&perline=8" alt="skills" />
</div>

<h2 id="strengths">Strengths</h2>

- **Auth/OAuth 설계 감각**: 타입(USER/DRIVER) 일관성 유지, state 기반 복원, 리다이렉트 보안(allowlist) 같은 실전 이슈를 구조로 해결
- **파일 업로드 최적화**: 서버 중계 없이 Presigned URL로 트래픽/비용 절감 + private bucket 전제의 key 저장 전략
- **품질/협업**: 프론트와 백엔드 동시에 컨벤션에 맞추어 개발하는 경험, 명세 중심 커뮤니케이션, 재사용 가능한 UI/공통 로직 분리

---

<h2 id="projects">Projects</h2>

<table>
	<tr>
		<th align="left">Level</th>
		<th align="left">Project</th>
		<th align="left">What I shipped</th>
		<th align="left">Links</th>
	</tr>
	<tr>
		<td><b>고급</b></td>
		<td><b>무빙</b> (이사 매칭 플랫폼)</td>
		<td>
			OAuth(구글/카카오/네이버) 인가 위임 흐름을 <b>USER/DRIVER 타입 분리 정책</b>에 맞게 설계/구현<br/>
			redirectOrigin allowlist를 <b>start/callback 2중 검증</b>하여 오픈 리다이렉트 위험 완화<br/>
			S3 Presigned URL로 <b>직접 업로드</b> 플로우 구성(짧은 만료, key 저장 전략)
		</td>
		<td>
			BE: https://github.com/fs08-moving-f5/fs08-moving-f5-be<br/>
			FE: https://github.com/fs08-moving-f5/fs08-moving-f5-fe
		</td>
	</tr>
	<tr>
		<td><b>중급</b></td>
		<td><b>포토카드</b> (생성/거래)</td>
		<td>
			마이갤러리 조회·생성·관리 API 구현 및 이미지 처리(리사이즈/워터마크) 최적화<br/>
			거래 수량 검증 미들웨어 분리로 <b>초과 판매글 생성 방지</b><br/>
			프론트 초기 세팅 및 공통 컴포넌트/상태관리 구조 정리
		</td>
		<td>
			BE: https://github.com/FS-PART-3/8-PHOTO-BE<br/>
			FE: https://github.com/FS-PART-3/8-PHOTO-FE
		</td>
	</tr>
	<tr>
		<td><b>초급</b></td>
		<td><b>공부의 숲</b> (습관/커뮤니티)</td>
		<td>
			스터디 CRUD 및 포인트 집계 로직 구현, 이모지 토글 기능 개발<br/>
			UI/UX 이슈(오버플로우/유효성/반응형) 개선 경험
		</td>
		<td>
			BE: https://github.com/MinJun916/fs08-studyforest-team1-be<br/>
			FE: https://github.com/MinJun916/fs08-studyforest-team1-fe
		</td>
	</tr>
</table>

<br/>
<div>
	<summary><b>그 외 작업들</b></summary>
	<ul>
		<li>
			웹 퍼블리셔로서 제작한 작업물 <a href="https://kwangche.github.io">kwangche.github.io</a>
		</li>
		<li>
			프론트엔드로서 리뉴얼한 모바일 페이지 <a href="https://www.lei.or.kr/m/index.asp">https://www.lei.or.kr/m/index.asp</a>
		</li>
	</ul>
</div>

---

<h2 id="contact">Contact</h2>

- Email: dlrhkdcp11@gmail.com

---

<div align="center">
	<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,100:111827&height=130&section=footer" alt="footer" style="width:100%" />
</div>


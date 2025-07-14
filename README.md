# 👕 ColorMatch: 옷 색상 매칭 추천 웹 서비스

패션에 어울리는 색상 조합을 찾기 어려우셨나요?  
**ColorMatch**는 옷 사진을 업로드하면 주요 색상을 자동으로 추출하고,  
그에 어울리는 색상을 추천해주는 웹 기반 서비스입니다.

---

## 🌟 주요 기능

- 📷 **사진 업로드**: 사용자가 옷 사진을 업로드
- 🎨 **색상 추출**: 이미지에서 주요 색상 자동 추출 (OpenCV + KMeans)
- 💡 **색상 추천**: 추출된 색상에 어울리는 색상 자동 추천
- 🌐 **웹 서비스**: 누구나 설치 없이 웹에서 바로 사용 가능

---

## 🛠 기술 스택

| 프론트엔드 | Next.js, Tailwind CSS |
| 백엔드 | FastAPI, Python, OpenCV, scikit-learn |
| 배포 | Vercel (프론트), Render or Railway (백엔드) |

---

## 📂 프로젝트 구조

```bash
colormatch/
├── frontend/         # Next.js 프론트엔드
│   └── pages/...
├── backend/          # FastAPI 백엔드
│   └── main.py
├── README.md

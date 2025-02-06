# 다크 트레저 헌터 게임 기획서

## 1. 게임 개요

### 1.1 게임 제목
- **Dark Treasure Hunter (다크 트레저 헌터)**

### 1.2 게임 장르
- **탐험 + 로그라이트 + 서바이벌 + 액션 어드벤처**

### 1.3 플랫폼
- ** Mobile(Android) ** (추후 콘솔 확장 가능)

### 1.4 게임 시점
- **탑다운(Top-down) 뷰, 약간 기울어진 시점(Isometric-like)**

### 1.5 주요 특징
- 어두운 밤을 배경으로 보물을 찾아 교환소에 가져가는 게임.
- 다양한 등급의 장비를 활용해 효율적으로 보물을 찾고 생존.
- 몬스터의 방해를 피해 최종적으로 10개의 진품 보물을 모아 클리어.
- 가품을 교환소에서 판매하여 장비 업그레이드 가능.
- **고정된 맵에서 플레이할 때마다 보물 위치와 몬스터 스폰이 랜덤 변경.**
- **서서히 난이도가 증가하는 동적 환경 적용.**

---

## 2. 기획 의도

### 2.1 주요 목표
- 플레이어가 탐험과 생존을 동시에 경험할 수 있도록 설계.
- 보물을 찾는 과정에서 장비 업그레이드와 전략적 선택을 강조.
- 단순한 반복 플레이가 아닌, 플레이할 때마다 새로운 도전 요소 제공.
- 플레이 스타일에 따라 다양한 공략법이 가능하도록 자유도 제공.

### 2.2 핵심 재미 요소
- **탐색과 생존**: 어두운 맵에서 보물을 찾고, 몬스터의 방해를 피하는 과정.
- **장비 업그레이드**: 탐지기, 삽, 등불, 무기 등을 강화하여 더 효율적인 탐험 가능.
- **랜덤성**: 보물과 몬스터의 위치가 매번 달라지는 리플레이성 높은 게임 디자인.
- **서바이벌 요소**: 시간이 지날수록 난이도가 점점 상승하는 긴장감.

### 2.3 차별화 포인트
- 기존 로그라이트 탐험 게임과 달리 **탐색 및 보물 감정 시스템** 도입.
- **맵이 고정적이지만 내부 요소(보물 위치, 몬스터 스폰)가 랜덤화**되어 새로운 도전 제공.
- **보물의 진품/가품 시스템**을 활용한 전략적 판단 필요.

---

## 3. 게임플레이 메커니즘

### 3.1 기본 흐름
1. **탐색:** 어두운 맵에서 탐지기와 등불을 활용해 보물 위치 확인.
2. **발굴:** 삽을 사용하여 땅을 파고 보물 획득.
3. **위험 요소:** 몬스터를 피해 도망치거나 무기로 격퇴.
4. **교환소 방문:** 보물을 감정 후 진품 수집, 가품 판매.
5. **장비 업그레이드:** 탐색 효율을 높이기 위해 장비 강화.
6. **최종 목표 달성:** 진품 10개 획득 후 게임 클리어.
7. **게임 진행에 따라 점점 난이도가 상승하며 더 강한 몬스터가 등장.**

### 3.2 게임 규칙
- 플레이어는 동시에 **5종류의 장비**를 보유할 수 있음.
- 탐지기와 등불을 활용하여 보물을 찾는 과정에서 **제한된 에너지를 관리해야 함.**
- 몬스터에게 일정 횟수 이상 공격당하면 사망하며, 일부 장비를 잃고 재시작.
- 보물 중 일부는 함정이 포함되어 있어 **해독제나 특정 아이템을 이용해야 안전하게 획득 가능.**

---

## 4. 세계관 및 스토리

### 4.1 배경 설정
- 오래된 저주받은 폐허에서 전설적인 보물들이 묻혀 있음.
- 탐험가는 이를 발굴하여 세상에 알리거나, 개인적인 부를 쌓을 수 있음.
- 보물을 지키는 수호 몬스터들이 존재하며, 보물에는 종종 저주가 걸려 있음.

### 4.2 주요 캐릭터
1. **플레이어(탐험가)**: 보물을 찾아 모험하는 주인공.
2. **교환소 주인**: 보물을 감정하고, 진품과 가품을 구별해주는 NPC.
3. **보물을 지키는 몬스터들**: 탐험가를 방해하는 존재.

---

## 5. 레벨/스테이지 디자인

### 5.1 전체 맵 구조
- 500x500 크기의 고정된 맵.
- 지형 요소: 숲, 바위, 폐허 등 탐험 요소 추가.
- **날씨 변화 시스템:** 안개, 비 등의 요소가 가시성과 난이도에 영향을 줌.

### 5.2 레벨 디자인 예시
- 초반: 적은 수의 몬스터, 보물이 비교적 쉽게 발견됨.
- 중반: 몬스터 수 증가, 가짜 보물 비율 증가.
- 후반: 강한 몬스터 등장, 일부 지역이 봉쇄되어 우회 필요.

---

## 6. 캐릭터/아이템 시스템

### 6.1 장비 목록
| 장비      | 설명           | 등급에 따른 변화         |
| ------- | ------------ | ----------------- |
| **등불**  | 주변을 밝히는 역할   | 등급이 높을수록 시야 증가    |
| **탐지기** | 땅 속의 보물을 감지  | 등급이 높을수록 탐지 범위 증가 |
| **삽**   | 보물을 파는 속도 결정 | 등급이 높을수록 발굴 시간 단축 |
| **무기**  | 몬스터 처치용      | 등급이 높을수록 공격력 증가   |
| **나침반** | 교환소의 위치 표시   | 항상 일정 성능          |

### 6.2 보물 시스템
- 보물 총 10종류.
- 각 보물마다 **진품 1개, 가품 2개 존재**.
- 진품 10개를 모으면 게임 클리어.
- 가품은 교환소에서 판매해 업그레이드 재화 획득 가능.

---

## 7. UI 디자인

### 7.1 주요 UI 요소
- **탐색 화면**: 플레이어 상태, 맵, 탐지기 신호 표시.
- **교환소 화면**: 보물 감정 및 장비 업그레이드.
- **인벤토리**: 보유 장비 및 보물 확인 가능.

---

🎯 다크 트레저 헌터 개발 플로우 차트
지금 프로젝트가 아무것도 없는 상태라면, 기본 시스템부터 차근차근 구축해야 해!
아래 순서대로 개발하면 논리적이고 효율적으로 진행할 수 있어.

🛠 1. 프로젝트 구조 설계
✅ 폴더 구조 정리

📁 _Scenes/ → 씬 저장
📁 _Scripts/ → C# 코드 저장
📁 _Prefabs/ → 플레이어, 몬스터, 아이템 프리팹 저장
📁 _Sprites/ → 2D 스프라이트 저장
📁 _UI/ → UI 이미지, 폰트 저장
📁 _Data/ → JSON, CSV 데이터 테이블 저장
✅ GitHub 버전 관리 시작

GitHub에 프로젝트 업로드 후 버전 관리 시작
🔹 2. 게임 기초 시스템 구현
1️⃣ 씬 구조 설계
MainMenuScene (타이틀 화면)
GameScene (실제 게임 플레이)
ResultScene (게임 결과 화면)
2️⃣ 플레이어 이동 시스템
WASD / 가상 조이스틱 입력 처리
Rigidbody2D 활용하여 부드러운 움직임
3️⃣ 맵 & 보물 배치 시스템
타일맵(Tilemap) 활용
보물 & 몬스터 랜덤 스폰 기능 추가
4️⃣ 몬스터 AI
기본적으로 플레이어를 추격하는 AI 구현
몬스터가 보물을 지키도록 설정
🔹 3. 게임 핵심 시스템 개발
5️⃣ 탐색 시스템
탐지기 → 일정 범위 내 보물 감지
등불 → 어두운 곳을 밝히는 기능
6️⃣ 발굴 & 보물 감정 시스템
땅을 파서 보물 획득
교환소에서 진품 / 가품 감별 후 재화 획득
7️⃣ 멀티플레이 적용
Photon Fusion 활용
플레이어 동기화, 보물 위치 공유, 몬스터 AI 공유
🔹 4. UI & 최적화
8️⃣ UI 구현
체력바, 스태미나, 인벤토리, 보물 감정 UI
게임 오버 / 승리 UI
9️⃣ 최적화
오브젝트 풀링(Object Pooling) → 몬스터/보물 최적화
네트워크 최적화 → 불필요한 동기화 최소화


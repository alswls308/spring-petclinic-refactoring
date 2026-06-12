# spring-petclinic-refactoring
Refactoring Spring PetClinic with Software Design Patterns &amp; Enhancing Backend Features with Docker Oracle DB and Supabase Social Login
# 🚀 Spring PetClinic Refactoring Project

> **디자인 패턴(Factory Method, Singleton 등)을 적용한 Spring PetClinic 리팩토링 및 Supabase 소셜 로그인 연동 백엔드 고도화 프로젝트**

<br/>

## 📌 소개 (Introduction)
이 프로젝트는 기존의 레거시 **Spring PetClinic** 애플리케이션을 깊이 있게 분석하고, 객체지향 설계 원칙(SOLID)과 다양한 소프트웨어 디자인 패턴을 적용하여 코드의 가독성, 유지보수성, 확장성을 높인 리팩토링 프로젝트입니다. 

팀 단위 협업을 통해 진행되었으며, 데이터베이스 관계 구조 최적화 및 최신 인증 아키텍처(Supabase) 통합을 포함한 백엔드 시스템 고도화에 초점을 맞추었습니다.

<br/>

## ✨ 주요 기능 (Key Features)
* **소프트웨어 디자인 패턴 적용 (Refactoring)**
  * 복잡도를 낮추고 재사용성을 극대화하기 위해 아키텍처 전반에 걸쳐 패턴 구현
  * 주요 패턴: `Factory Method`, `Singleton`, `Prototype`, `Template Method`, `Decorator` 패턴 등 적용 및 UML 시각화
* **데이터베이스 고도화 & 엔티티 모델링**
  * 시스템 안정성을 위해 체계적인 엔티티-관계 모델링(ERD) 수행
  * 데이터 정규화 및 명확한 `1:N` 및 `M:N` 관계 정의를 통한 스키마 최적화
* **Supabase 기반 소셜 로그인 연동**
  * 현대적인 인증 체계 구축을 위해 Supabase API 완벽 통합
  * 사용자의 편의성을 위한 `구글(Google)` 및 `카카오(Kakao)` 간편 소셜 로그인 기능 구현

<br/>

## 🛠️ 개발 환경 및 시작하기 (Getting Started)

### 필수 요구사항 (Prerequisites)
본 프로젝트는 **Apple Silicon (M3 맥북 등)** 환경 및 Docker 기반 인프라에서 유연하게 구동되도록 최적화되어 있습니다. 실행 전 아래 항목들이 로컬에 설치되어 있어야 합니다.
* **Java 17** 이상 (JDK 17)
* **Docker / Docker Desktop**
* **Oracle SQL Developer** (선택 사항, 로컬 DB 관리 및 검증용)

<br/>

### 설치 및 실행 방법 (Installation & Usage)

**1. 저장소 복제 (Clone the repository)**
```bash
git clone [https://github.com/your-team/spring-petclinic-refactoring.git](https://github.com/your-team/spring-petclinic-refactoring.git)
cd spring-petclinic-refactoring

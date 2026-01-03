# Computer Programming Ⅱ Team Project – Pumpkin 🎃

LET’S FLIP THE IMAGE UPSIDE DOWN
C++과 libpng 라이브러리를 사용하여 PNG 이미지를 수직 방향으로 뒤집는 프로그램입니다.

## 목차

- [프로젝트 개요](#-프로젝트-개요)
- [주요 기능](#-주요-기능)
- [기술 스택](#-기술-스택)
- [프로젝트 구조](#-프로젝트-구조)
- [빌드 & 실행](#-빌드--실행)
- [실행 결과](#-실행-결과)
- [환경 및 참고사항](#-환경-및-참고사항)
---

## 📌 프로젝트 개요

- **과목**: Computer Programming Ⅱ
- **프로젝트명**: Pumpkin
- **주제**: PNG 이미지 수직 반전 처리
- **설명**:  
  libpng 라이브러리를 활용하여 입력된 PNG 이미지의  
  행(row) 순서를 반전시켜 **상하가 뒤집힌 이미지(output.png)**를 생성하는 C++ 프로그램

---

## 🎯 주요 기능

- PNG 이미지 파일 입력 처리
- 이미지 행(row) 단위 접근
- 수직 방향 이미지 반전(Vertical Flip)
- 반전된 이미지를 PNG 파일로 출력
- 파일 입출력 및 libpng 오류에 대한 예외 처리

---

## 🛠 기술 스택

```
Language : C++
Library : libpng
Build Tool : Makefile
OS : Ubuntu 20.04
```
---

## 📁 프로젝트 구조

```
├── pumpkin_flip/
├── ├── Reverse_Image.cpp # 메인 소스 코드
├── ├── Makefile # 빌드 스크립트
└── └── input.png # 테스트용 입력 이미지
```

---

## 🚀 빌드 & 실행

### 1. libpng 설치
```bash
sudo apt update
sudo apt install libpng-dev
```

### 2. 빌드

```bash
cd pumpkin_flip
make
```

### 3. 실행

```bash
./Result
```
실행 후, 입력 이미지(input.png)가 수직 반전된 결과 파일 output.png가 생성됩니다.

---

## 🖼 실행 결과

### 1. 자세 추적 및 각도 계산

```
- 입력: input.png
-출력: output.png (상하 반전된 이미지)

이미지의 모든 행(row)을 역순으로 재배치하여 정확한 수직 반전이 수행됩니다.
```
---

### ⚙ 환경 및 참고사항

```
- Ubuntu 20.04 환경 기준
- VS Code 사용 권장
- libpng-dev 필수 설치
- Makefile 기반 빌드 방식
```
---





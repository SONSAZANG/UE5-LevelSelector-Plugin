# 🎮 LevelSelector - Unreal Engine Editor Plugin

[English](#english) | [한국어](#korean)

---

# English

A UE plugin that adds a level selection dropdown to the editor toolbar and allows you to run the selected level with a single button click.

![Image](https://github.com/user-attachments/assets/a8ea5621-d5b4-4135-959f-730b0fe58846)

---

## 🔗 Available on Fab

You can download this plugin directly from Fab Marketplace:  
👉 [Level Selector on Fab](https://www.fab.com/ko/listings/118a0d2b-231b-458f-bb1c-3e504ca8bc4c)

---

## 🧩 Features

- **Level Selection Dropdown** in the toolbar
- **Instant Play** of selected level in editor viewport
- Intuitive and simple workflow

---

## 🖥️ Usage Example

### 1. Dropdown appears in editor toolbar
<img width="368" alt="Image" src="https://github.com/user-attachments/assets/5d1301f1-f931-4b79-bfbc-d6704558f8e2" />

### 2. Click "Play Level" button to run selected level
<img width="256" alt="Image" src="https://github.com/user-attachments/assets/2001e84e-8ccf-459a-9232-a3e57b21f95c" />

---

## 🛠️ Installation & Setup
### 1. Install Plugin
Copy to Plugins folder
[Level Selector Google Drive Link](https://drive.google.com/file/d/1Ux5u92xQaQ-p97e6jQ8GNNgVBN3DT9If/view?usp=sharing) <br>
YourProject/Plugins/LevelSelector/

### 2. Enable Plugin
Open `.uproject` and enable the plugin
`Edit > Plugins > Installed > LevelSelector` → Check and restart editor

### 3. Add Map to Required Path
For the plugin to work properly, make sure your maps are placed in the following folder:
/Game/Content/Maps/

The plugin currently looks for maps only in this path, so please create the folder if it doesn’t exist and place your map files there.
Custom map path configuration is not supported yet, but may be added in future updates.

---

## 📁 Basic Structure

```plaintext
LevelSelector/
├── Source/
│   └── LevelSelector/
│       ├── LevelSelector.h
│       ├── LevelSelector.cpp
│       └── ...
├── Resources/
│   └── Icon128.png
└── README.md
```

---

# Korean

에디터 툴바에 드롭다운으로 레벨을 선택하고, 버튼 클릭 한 번으로 해당 레벨을 실행할 수 있는 UE 플러그인입니다.

![Image](https://github.com/user-attachments/assets/a8ea5621-d5b4-4135-959f-730b0fe58846)

---

## 🔗 Fab에서 다운로드 가능

이 플러그인은 Fab 마켓에서 바로 다운로드할 수 있습니다.  
👉 [Fab에서 Level Selector 보기](https://www.fab.com/ko/listings/118a0d2b-231b-458f-bb1c-3e504ca8bc4c)

---

## 🧩 기능 요약

- 툴바에 **레벨 선택 드롭다운** 추가
- 선택된 레벨을 에디터 뷰포트에서 **즉시 Play**
- 직관적이고 심플한 워크플로우

---

## 🖥️ 사용 예시

### 1. 에디터 툴바에 드롭다운 추가됨
<img width="368" alt="Image" src="https://github.com/user-attachments/assets/5d1301f1-f931-4b79-bfbc-d6704558f8e2" />

### 2. "Play Level" 버튼 클릭 시 선택된 레벨 실행
<img width="256" alt="Image" src="https://github.com/user-attachments/assets/2001e84e-8ccf-459a-9232-a3e57b21f95c" />
---

## 🛠️ 설치 및 설정
### 1. 플러그인 설치 Plugins 폴더에 복사
[Level Selector Google Drive Link](https://drive.google.com/file/d/1Ux5u92xQaQ-p97e6jQ8GNNgVBN3DT9If/view?usp=sharing) <br>
YourProject/Plugins/LevelSelector/

### 2. `.uproject` 열고 플러그인 활성화  
`Edit > Plugins > Installed > LevelSelector` → 체크 후 에디터 재시작

### 3. 필수 경로에 맵 추가
플러그인이 정상 작동하려면, 맵 파일이 아래 경로에 위치해야 합니다:
/Game/Content/Maps/

현재 플러그인은 해당 경로만 인식하도록 되어 있으므로, 경로가 존재하지 않는 경우 직접 생성하고 그 안에 맵 파일을 넣어주세요.
아직 커스텀 맵 경로 설정은 지원되지 않지만, 추후 업데이트에서 추가될 수 있습니다.

---

## 📁 기본 구조

```plaintext
LevelSelector/
├── Source/
│   └── LevelSelector/
│       ├── LevelSelector.h
│       ├── LevelSelector.cpp
│       └── ...
├── Resources/
│   └── Icon128.png
└── README.md
```

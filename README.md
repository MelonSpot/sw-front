```
npm install -g yarn

yarn create react-app .

yarn start

sw-front/
├── public/
│   └── index.html
├── src/
│   ├── assets/
│   │   ├── images/      # 이미지 파일
│   │   └── styles/      # 전역 스타일시트
│   ├── components/      # 재사용 가능한 UI 컴포넌트
│   │   ├── Button/
│   │   ├── Navbar/
│   │   └── ...
│   ├── pages/           # 각 페이지 컴포넌트 (예: 홈페이지, 검색 페이지)
│   │   ├── Home/
│   │   ├── Search/
│   │   └── ...
│   ├── services/        # API 호출 및 기타 서비스
│   │   ├── api.js       # API 호출을 관리하는 파일
│   │   └── ...
│   ├── utils/           # 유틸리티 함수
│   ├── App.js           # 앱의 메인 컴포넌트
│   └── index.js         # 앱의 엔트리 포인트
├── package.json
└── yarn.lock


# commit message setting
code ~/.gitmessage.txt
# 커밋 메시지 설정 및 저장

git config --global commit.template ~/.gitmessage.txt
git config --global core.editor code --wait

git commit -a

git add <수정된파일>
git commit
```

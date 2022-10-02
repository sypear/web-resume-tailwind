# Tailwind CSS를 이용한 웹 이력서 만들기
* HTML과 Tailwind CSS를 이용해서 만든 웹 이력서입니다.
  * **`input.css`, `dist/output.css 파일`은 Tailwind CSS 설치 시 생성된 파일로 스타일을 위해 사용한 CSS 파일이 아닙니다.**

<br>

* 데모 페이지 : https://sypear.github.io/web-resume-tailwind/

<br>

## Tailwind CSS 설치 방법 (<a href="https://tailwindcss.com/docs/installation">공식 문서</a>)
1. 터미널에 아래 명령어를 입력하여 Tailwind CSS를 설치하고 `tailwind.config.js` 파일을 만듭니다.
> npm install -D tailwindcss<br>
> npx tailwindcss init

<br>

2. 생성된 `tailwind.config.js` 파일에 템플릿 파일에 대한 경로를 추가합니다. 

<br>

3. 기본 CSS 파일(`input.css`)에 @tailwind 지시문을 추가합니다.
> @tailwind base;<br>
> @tailwind components;<br>
> @tailwind utilities;

<br>

4. 터미널에 아래 명령어를 실행하여 CSS 파일을 빌드합니다.
> npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch

<br>

5. 컴파일된 CSS 파일을 HTML 파일 <head> 태그 내에 추가하고 Tailwind CSS를 사용합니다.

`<link href="/dist/output.css" rel="stylesheet">`

<br>

## 이미지 출처
프로필, 배경 이미지는 Unsplash의 무료 이미지를 사용하였습니다.
* 프로필 이미지 출처 : <a href="https://unsplash.com/photos/n5aE6hOY6do">Oladimeji Odunsi(Unsplash)</a>
* 배경 이미지 출처 : <a href="https://unsplash.com/photos/4ELcmuV3osk">Presetbase Lightroom Presets(Unsplash)</a>

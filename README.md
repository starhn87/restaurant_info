## ๐ ํ๋ก์ ํธ ์๊ฐ

์์์  ๋ชฉ๋ก๊ณผ ์์ธ์ ๋ณด๋ฅผ ๋ณด์ฌ์ฃผ๋ ์ดํ๋ฆฌ์ผ์ด์์๋๋ค.

<br>

## ๐ ์คํ ๋ฐฉ๋ฒ

```bash
  git clone https://github.com/starhn87/purpleio.git
  yarn install
  npx json-server -p 9000 db.json # json-server ์คํ
  yarn dev # Next ์ดํ๋ฆฌ์ผ์ด์ ์คํ
  # http://localhost:3000 ์ด๋
```

## โจ ์ฃผ์ ๊ธฐ๋ฅ

- ๋ฉ์ธ ํ์ด์ง
  - ์์์  ๋ชฉ๋ก์ ํ์ธํ  ์ ์์ต๋๋ค.
  - ์์์  ์์ดํ์ ํด๋ฆญํ์ฌ ๋ชจ๋ฌ ์์์ ์์ธ์ ๋ณด๋ฅผ ๋ณผ ์ ์์ต๋๋ค.
- About ํ์ด์ง
  - ํ๋ก์ ํธ ์ค๋ช์ ํ์ธํ  ์ ์์ต๋๋ค.
- ์๋ฌ ํ์ด์ง
  - ์ ํจํ์ง ์์ ๊ฒฝ๋ก ์ ๊ทผ์ ์๋ฌ ํ์ด์ง๋ฅผ ๋ณด์ฌ์ฃผ๊ณ  5์ด ๋ค ์๋์ผ๋ก ๋ฉ์ธ ํ์ด์ง๋ก ์ด๋ํฉ๋๋ค.

<br>

## ๐ง ๋ฉ์ธ

<br>

1-1. ๋ฉ์ธ ํ์ด์ง

<img src="https://user-images.githubusercontent.com/36434219/162666740-05dc6e85-3fc2-4fb6-9c01-77ab56acb7f9.png" alt="๋ฉ์ธ ํ์ด์ง" width="700px" height="400px">

<br>

1-2. ์์ธ์ ๋ณด ๋ชจ๋ฌ

<img src="https://user-images.githubusercontent.com/36434219/162666857-c9b12949-f32b-4c79-b095-13ef4e8be0ee.png" alt="์์ธ์ ๋ณด ๋ชจ๋ฌ" width="700px" height="400px">

<br>

2. About ํ์ด์ง

<img src="https://user-images.githubusercontent.com/36434219/162667076-60f44fb0-1c10-4f64-b212-ad768dd05cbf.png" alt="about ํ์ด์ง" width="700px" height="400px">

3. ์๋ฌ ํ์ด์ง

<img src="https://user-images.githubusercontent.com/36434219/162728056-395d649d-ee4d-4cd0-bec3-07d9a756a7f8.png" alt="์๋ฌ ํ์ด์ง" width="700px" height="400px">

<br>
<br>

## โญ๏ธ ๊ตฌํํ ๊ธฐ๋ฅ ๋ชฉ๋ก ๋ฐ ์ด๋ ค์ ๋ ์ 

- ๊ตฌํ ๋ด์ฉ & ๋ฐฉ๋ฒ

  - Next.js + Typescript๋ก ๊ตฌ์ฑํ์์ต๋๋ค.
  - getStaticProps๋ก SSR์ ์ ์ฉํ์์ต๋๋ค.
  - React query๋ก API ํธ์ถ์ ์บ์ฑ์ ์ ์ฉํ์์ต๋๋ค.
  - json-server๋ก API ์๋ฒ๋ฅผ ๋ง๋ค๊ณ  ํธ์ถํ์ฌ ๊ฐ์ ธ์์ต๋๋ค.
  - ๋ฐ์ํ ๋์์ธ์ ๋์ํ์์ต๋๋ค. (๋ฐ์คํฌํ, ๋ชจ๋ฐ์ผ)
  - ๋ ๋๋ง์ ์ต์ ํํ์์ต๋๋ค.
  - mui๋ฅผ ์ฌ์ฉํ์ฌ ๋ชจ๋ฌ์ฐฝ์ ๊ตฌํํ์๊ณ  ์ ์ฒด์ ์ธ ์คํ์ผ๋ง์ emotion์ ์ฌ์ฉํ์์ต๋๋ค.
  - Yarn berry๋ก ์์กด์ฑ ๊นจ์ง ์์ด zero install๋ก ํจํค์ง๋ฅผ ๊ด๋ฆฌํ์์ต๋๋ค.
  - ์ ์ฒด์ ์ผ๋ก ์ปดํฌ๋ํธ ๋จ์๋ก ๊ฐ๋ฐํ์์ต๋๋ค.

- ๊ตฌํํ๋ฉด์ ์ด๋ ค์ ๋ ์ 
  - React 18๋ก ๋ฒ์ ์์ด ๋๋ฉด์ React query์ QueryClientProvider์ ์ธํฐํ์ด์ค๊ฐ ํธํ๋์ง ์์์ ๋๋ฒ๊น์ ์๊ฐ์ด ์์๋์์ต๋๋ค.
    (์๋ฌ ํด๊ฒฐ ํ ๋ธ๋ก๊น์ ํ์์ต๋๋ค.
    https://velog.io/@dkdlel102/Next.js-React-18-TS-React-query์์-QueryClientProvider์-IntrinsicAttributes-์๋ฌ๊ฐ-๋ฐ์ํ -๋-ํด๊ฒฐ-๋ฐฉ๋ฒ)

<br>

## ๐ ํ๋ก์ ํธ ๊ตฌ์กฐ

```
โโโ README.md
โโโ components
โ   โโโ Detail.tsx
โ   โโโ Footer.tsx
โ   โโโ Header.tsx
โ   โโโ Loading.tsx
โ   โโโ Tabs.tsx
โโโ db.json
โโโ index.d.ts
โโโ next-env.d.ts
โโโ next.config.js
โโโ package.json
โโโ pages
โ   โโโ 404.tsx
โ   โโโ _app.tsx
โ   โโโ about.tsx
โ   โโโ api
โ   โ   โโโ index.ts
โ   โโโ index.tsx
โโโ public
โ   โโโ favicon.ico
โ   โโโ vercel.svg
โโโ tsconfig.json
โโโ yarn.lock
```

<br>

## ๐  ์ฌ์ฉ ๊ธฐ์ 

front-end

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

package manage

![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white)

community

![Discord](https://img.shields.io/badge/DISCORD-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Apple](https://img.shields.io/badge/-APPLE-black?style=for-the-badge&logo=apple)
![Ubuntu](https://img.shields.io/badge/-UBUNTU-gray?style=for-the-badge&logo=Ubuntu)

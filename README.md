# π° New York Times Client

New York Times APIλ₯Ό νμ©ν κΈ°μ¬ κ²μ μΉ μ΄νλ¦¬μΌμ΄μ

## π¬ Getting Started

κ°λ° νκ²½μ κ΅¬μΆνλ λ°©λ²μ λ€μκ³Ό κ°μ΅λλ€.

### βοΈ Requirements

- Node.js ν¨ν€μ§ λ§€λμ  (yarn or npm)

### βοΈ Installation

1. ν΄λΉ λ ν¬μ§ν λ¦¬λ₯Ό ν΄λ‘ ν©λλ€.

```
git clone https://github.com/eunsukimme/New-York-Times-Client
```

2. ν΄λ‘ ν ν΄λλ‘ μ΄λν λ€ package.jsonμ λͺμλ dependenciesλ₯Ό λͺ¨λ μ€μΉν΄ μ€λλ€

```
cd New-York-Times-Client
yarn λλ npm install
```

## π€© Usage

ν°λ―Έλμ `yarn start` λλ `npm start` λͺλ Ήμ μ€ννμ¬ development μλ²λ₯Ό μ€νν©λλ€. λΈλΌμ°μ  μ£Όμμ°½μ [http://localhost:3000](http://localhost:3000) μ μλ ₯νλ©΄ λ€μκ³Ό κ°μ΄ New-York-Times ν΄λΌμ΄μΈνΈ νμ΄μ§λ₯Ό λ³Ό μ μμ΅λλ€.

<img width="1680" alt="new york times client" src="https://user-images.githubusercontent.com/31213226/72910824-6d775e80-3d7c-11ea-934b-f4ae53f75863.png">

## β¨ Features

New York Times Clientλ λ€μ κΈ°λ₯λ€μ μ κ³΅ν©λλ€.

### π κΈ°μ¬ κ²μ

νΉμ  ν€μλλ₯Ό λ°νμΌλ‘ New York Times κΈ°μ¬λ₯Ό κ²μν  μ μμ΅λλ€. ν λ²μ μ΅λ 20κ°μ κΈ°μ¬λ₯Ό λΆλ¬μ΅λλ€.

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/31213226/72914247-be3d8600-3d81-11ea-80c1-a53e9322954d.gif)

### β­οΈ μ¦κ²¨μ°ΎκΈ°

κ° κΈ°μ¬ ν€λλΌμΈμ μλ λ³ λͺ¨μμ λ²νΌμ λλ¬μ μνλ κΈ°μ¬λ₯Ό 'μ¦κ²¨μ°ΎκΈ°'μ λ΄μ μ μμ΅λλ€. μ¦κ²¨μ°ΎκΈ°μ λ΄μ κΈ°μ¬λ μ€λ₯Έμͺ½ μ λ³ λͺ¨μμ λ²νΌμ λλ₯΄λ©΄ νμΈν  μ μμ΅λλ€.

![ezgif com-video-to-gif (1)](https://user-images.githubusercontent.com/31213226/72914790-969aed80-3d82-11ea-8ed5-5926c5cdafe8.gif)

## π Project Structure

src ν΄λμ κ΅¬μ‘°λ λ€μκ³Ό κ°μ΅λλ€.

```
βββ App.test.js
βββ App.tsx
βββ assets/
βββ components
β   βββ UI/
β   βββ button/
β   βββ common/
β   βββ index.ts
βββ containers
β   βββ Favorites.tsx
β   βββ Main.tsx
β   βββ index.ts
βββ hooks
β   βββ index.ts
β   βββ useNews.ts
βββ index.tsx
βββ lib
β   βββ api/
β   βββ styles/
βββ modules
    βββ index.ts
    βββ news
    β   βββ actions.ts
    β   βββ constants.ts
    β   βββ reducer.ts
    β   βββ sagas.ts
    β   βββ utils.ts
    βββ types.ts
```

### π Folders

- `assets` : μ΄λ―Έμ§ λ±μ λ―Έλμ΄ νμΌλ€μ λ³΄κ΄ν©λλ€.
- `components` : button, icon λ± μ¬μ¬μ© κ°λ₯ν UI μ»΄ν¬λνΈλ€μ λ³΄κ΄ν©λλ€.
- `containers` : Stateful ν μ»΄ν¬λνΈλ€μ λ³΄κ΄ν©λλ€.
- `modules` : Redux λͺ¨λλ€μ λ³΄κ΄ν©λλ€.
- `hooks` : React hook λͺ¨λλ€μ λ³΄κ΄ν©λλ€.

## βοΈ License

MIT

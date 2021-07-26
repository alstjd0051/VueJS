# vue 설정

```js
npm i vue@next //vuejs package 설정
npm i -D vue-loader@next vue-style-loader @vue/compiler-sfc
npm i -D file-loader //이미지
```

```js
//확장자 생략하기
module.exports = {
    resolve: {
        extensions: ['.js', '.vue'],
    },
};
```

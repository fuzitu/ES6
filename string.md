# es6 string #
+ 字符串的遍历
```
var string='今天天气不错'
for(var i=0;i<string.length;i++){
    console.log(string[i]);
}
//结果  今 天 天 气 不 错
```
+ 判断字符串以什么开始或者结束
```
const str='今天天气不错';
//startsWith  以什么开头
str.startsWith('今'); //true
//endsWith 以什么结束
str.endsWith('错'); //true
//includes 是否包含 返回布尔值
str.includes('今天'); //true
//indexOf 是否包含 如果包含返回索引即大于-1就包含 Es5 方法
```
+ 开头补全或者结尾补全
```
let str='aaa';
//padStart 开头补全 第一个参数为补全后的长度 第二个为补全的字符
str.padStart(5,'xo'); //"xoaaa"
//padEnd 结尾补全  同上
str.padEnd(5,'xo');  //"aaaxo"
```
+ 重复若干次
```
const str='abc';
//repeat将某个字符串重复若干次 
str.repeat(3); "abcabcabc"
```
+ 字符串模板 特别是标签模板
```
// ` `比起''+''好用很多
let a='ab';
let c='cd';
console.log(`${a}${c}`) //abcd
```
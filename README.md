# hahaha

process.stdin.resume();
process.stdin.setEncoding('utf8');
// 入力値を取得する
var reader = require('readline').createInterface({
  input: process.stdin,
  output: process.stdout
});

reader.on('line', (line) => {
    // 出力する
  console.log(line);
});

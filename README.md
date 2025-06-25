let a = 3;
let b = 4;
let c = 2;

if ((a + b > c) && (a + c > b) && (b + c > a)) {
  if (a === b && b === c) {
    console.log("正三角形");
  } else if (a === b || a === c || b === c) {
    console.log("等腰三角形");
  } else {
    console.log("不等邊三角形");
  }
} else {
  console.log("無法構成三角形");
}

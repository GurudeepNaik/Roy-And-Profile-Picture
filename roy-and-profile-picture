let fs = require("fs");
let data = fs.readFileSync(0, 'utf-8');
let idx = 0;
data = data.split('\n');

function readLine() {
  idx++;
  return data[idx - 1];
}

const L=parseInt(readLine());
const N=parseInt(readLine());
for(let i=0;i<N;i++){
    const [W,H]=readLine().split(" ").map(Number);
    if(W<L || H<L) console.log("UPLOAD ANOTHER");
    else if (W===H) console.log("ACCEPTED");
    else console.log("CROP IT");
}

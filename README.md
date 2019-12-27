[KatasDelivery]

2. Remove First and Last Character

function removeChar(str){
  if(str.length < 2){
  return str;
  }
    let newStr = str.slice(1,str.length-1);
    return newStr;
};
_______________________________________________________________________________
3. Vowel Count

function getCount(str) {
  str = str.toLowerCase();
  var vowels = 'aeiou';
  var vowelCount = 0;
  for(var i = 0; i < str.length; i++) {
    if (vowels.indexOf(str[i]) !== -1) {
      vowelCount++;
    }
  }
  return vowelCount;
}

var solution = getCount('hello');
console.log(solution);



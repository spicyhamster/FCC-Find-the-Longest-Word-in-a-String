//Return the length of the longest word in the provided sentence.
//Your response should be a number.

function findLongestWord(str) {
  var arr = str.split(" ");
  var oldWord = "a";
  for(i=0; i<arr.length; i++) {
    var newWord = arr[i];
    if (newWord.length>oldWord.length){
      oldWord = newWord;
    }
  }
  return oldWord.length;
}

findLongestWord("The quick brown fox jumped over the lazy dog"); // should return 6

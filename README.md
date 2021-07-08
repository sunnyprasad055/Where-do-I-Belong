# Where-do-I-Belong
a javascript program
ffunction getIndexToIns(arr, num) {
  arr.sort((a, b) => a - b);
// To sort the array(arr) in ascending order
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] >= num)
      return i;
  }
// this for will retrun the value where the indexing number(num) is placed. The index will be returned
  return arr.length;
}

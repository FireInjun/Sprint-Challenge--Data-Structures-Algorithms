Add your answers to the Algorithms exercises here.

#Exercise 1.

a) O(n^3 / n^2) = O(n)

b) O(log n)

c) O(sqrt(n))

d) O(n log n)

e) O(n^3)

f) O(n)

g) O(n)?

---

## Exercise II.

a)

Answer_Maker:
function maxDiff(arr) {
let min = arr[0];
let maxDiff = 0;

      arr.forEach(val => {
          min = Math.min(min, val);
          maxDiff = Math.max(maxDiff, val  min);
      });

      return maxDiff;

}

b) binary sectioning. Start at f' = n/2. If egg breaks, set f' = f'/2. If egg does not break, set f' = 3f'/2

## Exercise III.

a) O(n^2)

b) O(n log n)

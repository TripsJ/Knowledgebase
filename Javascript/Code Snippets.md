#Code Snippets Javascript



- Generate a random number

```JS
Math.floor(Math.random() * n)
```

- Randomize arrays in Javascript

```JS
function randomize(array){
    let m = array.length;
    let t;
    let i;

  // While there remain elements to shuffle…
    while (m) {

    // Pick a remaining element…
        i = Math.floor(Math.random() * m--);

    // And swap it with the current element.
        t = array[m];
        array[m] = array[i];
        array[i] = t;
    }

    return series.cast;
}
```
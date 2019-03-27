# illiterate-strings-js
# This is a fuction I designed to illetrate through a string in js (ES6) .

<script>
//declare count to zero
let count = 0 ;

const illetrateString = (string) => {

    for(let i = 0; i < string.length ; i++){
        count += 1;
    }

    return count;
}

console.log(illetrateString("Hyginus"));

</script>

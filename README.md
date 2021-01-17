# in array needle in javascript

<pre>

in_array = (needle, array) => {
    let length = array.length;

    for (let i = 0; i < length; i++) {
        if (array[i] == needle) return true;
    }

    return false;
}

const arr = [1,2,3,4];


in_array(2,arr) // Output true

</pre>

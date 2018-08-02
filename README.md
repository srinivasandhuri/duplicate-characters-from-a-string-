# duplicate-characters-from-a-string-




function sameChar(str) {
var a = {};
for (var i=0; i<str.length;i++) {
    var character = str.charAt(i);
    if (a[character]) {
       a[character]++;
    } else {
       a[character] = 1;
    }
}

return a;
};

sameChar('Apple');

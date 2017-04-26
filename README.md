# EloquentJavaScript
exercises

// Your code here.
var text = '', a = '0', b = '#', n = '\n', size = 8, count = text.length, r = a;
if (count % 2 == 0) {
  r = a;
} else {
  r = b;
}
for (count; count < size; count = count + 1) {
  if (count % 2 == 1) {
  r = a;
  text = text + r;
  } else {
  r = b;
  text = text + r;
  } 
} console.log(text)
if

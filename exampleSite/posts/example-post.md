---
title: "Example post"
date: 2019-03-31T17:49:40+08:00
draft: false
description: "Example of theme"
---

## Lorem

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur vitae commodo ipsum, at vestibulum nulla. Morbi nec diam nibh. Morbi rhoncus, ligula vel molestie auctor, risus ex tincidunt turpis, vel volutpat est metus vitae nibh. In hac habitasse platea dictumst. Etiam erat nisl, egestas hendrerit blandit nec, rhoncus in mi. Suspendisse cursus tortor at quam lacinia lacinia. Mauris imperdiet pharetra tortor, vel pharetra neque imperdiet sed. Donec at ligula eget lectus consectetur fringilla sit amet nec urna. Vivamus hendrerit eleifend erat, vel ultricies orci condimentum eget. Ut blandit feugiat purus, a tristique turpis tincidunt non. Duis feugiat eros vel fermentum pretium.

Quisque nec pretium eros. Morbi vitae ipsum tempor, varius libero ut, vestibulum metus. Mauris rutrum dui eget sollicitudin pellentesque. Aliquam bibendum, arcu in ullamcorper dignissim, dui mi viverra nisl, non porta orci sem quis dolor. Pellentesque bibendum dolor nec elementum consectetur. Cras ultricies erat a quam tincidunt vulputate. Praesent quam erat, maximus quis gravida imperdiet, congue sit amet nisl. Donec condimentum tortor in fringilla dictum. Suspendisse velit ex, finibus at tristique at, dignissim ut urna. Quisque tempor nec augue ut venenatis. Nam et fermentum erat. Vestibulum nunc velit, scelerisque vel erat vitae, ultricies faucibus dolor.

### Lipsum

Pellentesque ante mauris, viverra ut orci ut, porttitor interdum diam. Praesent nec quam ut eros eleifend condimentum vitae sed tellus. Fusce volutpat tortor sit amet quam tempus eleifend. Duis eu cursus enim, et feugiat ligula. Maecenas tristique nunc et sem rutrum gravida. Morbi tortor lectus, pharetra dictum ultricies id, aliquet ut quam. Praesent vehicula ipsum id mauris pellentesque cursus. Phasellus at sollicitudin erat, vitae pretium est. Aenean bibendum eros risus, vel molestie purus consequat eget. Aliquam eu nisl fringilla elit laoreet malesuada eget eu felis. Aliquam vitae velit vitae libero porttitor faucibus. Ut porta urna in suscipit suscipit. Pellentesque cursus, augue vitae ultricies euismod, nisi sapien consequat risus, nec molestie leo libero ac turpis. Nullam quis tellus dui. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nullam laoreet dui ac magna pretium, at scelerisque mauris fermentum.

Curabitur tristique arcu quis ligula suscipit laoreet. Pellentesque cursus, ante vel tempor congue, felis eros vehicula leo, in imperdiet nisi enim eu felis. Aliquam hendrerit elit interdum purus mollis consectetur. Nullam vel sodales felis, non placerat neque. Aliquam volutpat id nibh id tristique. Cras accumsan sapien lectus, ut porta est rhoncus in. Morbi faucibus lectus in risus finibus interdum. Morbi ultricies iaculis neque ut pretium. Sed convallis malesuada elit sagittis fringilla. Fusce commodo convallis magna eget elementum. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.

### Curabitur

Suspendisse eget mauris sit amet orci sodales scelerisque. Ut ac lorem ullamcorper, mattis elit nec, congue nisl. Nam auctor erat at aliquam semper. Aenean tempor mauris at tellus imperdiet bibendum. Quisque nec ante sagittis odio feugiat viverra ut sed ipsum. In non nibh sed elit maximus viverra ut at odio. Nunc sed turpis ac sem elementum mattis non at urna.


```js
function* myGenerator() {
let index = 0;
while (index < 3)
    yield index++;
}

// get the iterator object
const a = myGenerator();

// the iterator object lets us call the next method
console.log(a.next()); // { value: 0, done: false }
console.log(a.next()); // { value: 1, done: false }
console.log(a.next()); // { value: 2, done: false }
console.log(a.next()); // { value: undefined, done: true }
```

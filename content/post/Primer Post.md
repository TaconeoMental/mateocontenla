+++
date = "2020-10-06T03:10:24-03:00"
share = false
slug = "primer-post"
title = "Primer post!"
image = "static/img/fireworks.jpg"
tags = ["es"]
+++

## Bienvenida
Pondría un _lorem ipsum_, pero prefiero escribir un poco de basura primero y luego llenar la página con texto en latín sin sentido.
Usaré esta página para publicar "write-ups" de los CTF a los que asista y también como blog para publicar avances de mis proyectos personales.

Para probar el markdown, acá hay un pedazo de código escrito en el lenguaje que
estoy desarrollando y con un resalatado de syntax que no le corresponde porque
todavía no escribo un parser. Nice.
{{< highlight rust "linenos=table">}}
map: generic<F, A> func(f: ptr F, arr: A) =>
  i: int;
  while i => 0, i < !len<A>(arr), i +> 1 =>
    arr @ i => !->f(arr @ i);
  endwl
endfn

cube :=> m::pow(exp => 3);

chType: generic<OR, NW> func(or: OR[]): NW[] =>
  or_len :=> !len<OR[]>(or);
  new_arr: NW[or_len];
  while i: int = 0, i < or_len, i +> 1 =>
    new_arr @ i => (or @ i)|NW|;
  endwl
  <- new_arr;
endfn
{{< / highlight >}}

Nada más que decir, estimados. 10-4. Aquí tienen su lorem ipsum:


 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam diam mi, condimentum id sagittis nec, faucibus et dolor. Etiam maximus risus felis, eget sodales est maximus et. Aenean id aliquam leo. Mauris velit dui, porta a erat pellentesque, scelerisque consequat sem. Nam tempus interdum velit, gravida tincidunt mi maximus id. Vivamus leo ante, dictum vitae enim non, tempus pulvinar velit. Quisque commodo massa eu nulla dapibus varius. Morbi tellus lacus, iaculis eu facilisis ac, ultricies a orci. Aliquam vel tempus dolor. Proin hendrerit placerat volutpat. Duis eros urna, efficitur quis lorem sed, ultrices maximus dui. Curabitur malesuada nisl a arcu mattis molestie. Sed cursus, purus lacinia convallis blandit, lectus elit eleifend lorem, non rutrum tellus augue ut diam. In gravida aliquet justo eu luctus.

Vivamus erat arcu, tempus ac lectus in, luctus mattis elit. Aliquam egestas malesuada risus, vel fringilla lorem tincidunt non. Integer eu est vitae leo sodales porta eget quis tortor. Aliquam feugiat elit vitae libero bibendum, a consectetur leo pretium. Praesent a eros vel purus faucibus laoreet consectetur id magna. Proin dui velit, tempor vitae lacinia vitae, dignissim vitae magna. Duis nec felis viverra, iaculis arcu at, semper odio. Donec elementum justo risus. Nulla massa justo, convallis a magna at, iaculis consequat ligula. Nullam at justo nisl. In a mauris at metus scelerisque rhoncus. Fusce in consequat massa. Donec mattis congue velit.

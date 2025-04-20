---
title: still doing some more work
description: more projects and updates
---

so i've been working on this other project that allows you to run Micro-Assembly in vr.

it's using godot 4.4.1 and i'm suspecting that the feature compat between this version and the newer ones won't break the project when i upgrade it later on.
you can check it out [here](https://github.com/Fy-nite/MasmVR).

not everythings great in it.
the repo's a mess from the template i used.

but it does run Micro-Assembly code, powered by the great SharpMASM interpreter*.

for now it's using SharpMASM, but when we get the interpreter for C-Masm working then i can properly move 
it over.
though it's SharpMASM it's still v1 spec compliant so it works for anything that doesnt use `enter`, `leave` and the new ones in v2.

i'll update SharpMASM of course, slowly moving the codebase over to use C-Masm in the background.
i'm not going to remove a great project for nothing. though i might have to make a seperate repo for it because making a new branch just to put legacy code on it might not be great.

everything is going great though, i did get into something that's great so i'm gonna have to slow down my work over the weekends but pick up the grunt during the weekdays.

take care!
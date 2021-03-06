---
navhome: /docs/
sort: 1
title: Sand
---

# Sand

`[%sand p=term q=@]`; a constant, warm atom.

### Produces

A warm (variable) atom `q` with aura `a`.

### Syntax by example

Irregular.  A table of examples:

```
@c    UTF-32                   ~-foobar
@da   128-bit absolute date    ~2016.4.23..20.09.26..f27b..dead..beef..babe
                               ~2016.4.23
@dr   128-bit relative date    ~s17          (17 seconds)
                               ~m20          (20 minutes)
                               ~d42          (42 days)
@f    loobean                  &             (0, yes)
                               |             (1, no)
@p                             ~zod          (0)
@rd   64-bit IEEE float        .~3.14        (pi)
                               .~-3.14       (negative pi)
@rs   32-bit IEEE float        .3.14         (pi)
                               .-3.14        (negative pi)
@rq   128-bit IEEE float       .~~~3.14      (pi)
@rh   16-bit IEEE float        .~~3.14       (pi)
@sb   signed binary            --0b10        (2)
                               -0b101        (-5)
@sd   signed decimal           --2           (2)
                               -5            (-5)
@sv   signed base32            --0v68        (200)
                               -0vfk         (-500)
@sw   signed base64            --0w38        (200)
                               -0w7Q         (500)
@sx   signed hexadecimal       --0x2         (2)
                               -0x5          -5
@t    UTF-8 text (cord)        'foobar'
@ta   ASCII text (knot)        ~.foobar
@ub   unsigned binary          0b10          (2)
@uc   bitcoin address          0c1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa
@ud   unsigned decimal         42            (42)
                               1.420         (1420)
@uv   unsigned base32          0v3ic5h.6urr6 
@uw   unsigned base64          0wsC5.yrSZC
@ux   unsigned hexadecimal     0xcafe.babe
```

The `@uv` characters are `0-9`, `a-v`.  The `@uw` characters are 
`0-9`, `a-z`, `A-Z`, `-` and `~`.

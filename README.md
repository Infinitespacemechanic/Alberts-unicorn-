# FlexibleRuler — New Fine Scaling Number

Straight foot vs curved foot, no additions.

**Definitions**
- Straight foot = 12
- Curved foot = 4 * pi = 12.566370614359172...
- Common denominator = pi/3 - 1 = 0.0471975511965977... (first jump over first radian)
- Residual per foot = 12 * common = 0.566370614359172...

**Core relations**
- curvedFoot = straightFoot + residualPerFoot
- residualPerFoot = 12 * commonDenominator
- commonDenominator > 0 (pi > 3)

**Pure ratios**
- 1 / common = 21.1875399...
- 2*pi / common = 133.1252395...

No 45, no 32, no 137 added. Just pi and 12.

**Build**
```
lake update
lake build
lake exe FlexibleRuler
```

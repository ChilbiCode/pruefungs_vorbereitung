[zurück](../README.md)

# Rechnungen

## Inhaltsangabe

1. [MB-MiB, GB-GiB, TB-TiB, usw.](#1-mb-mib-gb-gib-tb-tib-usw)
2. [Dual - Dezimal](#2-dual---dezimal)
3. [Hexadezimal - Dezimal](#3-hexadezimal---dezimal)
4. [Dual - Hexadezimal](#4-dual---hexadezimal)
5. [Elektrische Grundgrößen](#5-elektrische-grundgrößen)

---

## 1. MB-MiB, GB-GiB, TB-TiB, usw.

Aufgabe: Upload von 12 GiB innerhalb von 2h.   
Welche DSL Geschwindigkeit ist nötig?

Internetverbindung | Upload
-|-
DSL 16000 |bis 1000 kbit/s
VDSL 25 |bis 5000 kbit/s
VDSL 50 | bis 10 000 kbit/s
VDSL 100 |bis 20 000 kbit/s

<details><summary>Lösung:</summary> 

$(12 * 2^{30} *8 )\over 7200 * 1000$ $= 14.317 bit/s$

Dementsprechen wird VDSL 100 benötigt.



</details>





PiB 2^50 | TiB 2^40 | GiB 2^30 | MiB 2^20 | KiB 2^10 | B | bit
-:|-:|-:|-:|-:|-:|-:
1| * 1024 | * 1024 | * 1024 |  * 1024 | * 1024 | *8
|||1| 1024 | 1.048.576 | 1.073.741.824 | 8.589.934.592
||1| 1024 | 1.048.576 | 1.073.741.824 | 1.099.511.627.776 | 8.796.093.022.208
1| 1024 | 1.048.576 | 1.073.741.824 | 1.099.511.627.776 | 1.125.899.906.842.624 | 9.007.199.254.740.992

[zum Anfang](#rechnungen)

--- 

# 2. Dual - Dezimal

Dezimal | 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 | Dual
-:|-:|-:|-:|-:|-:|-:|-:|-:|-:
72|0|1|0|0|1|0|0|0|01001000
203|1|1|0|0|1|0|1|1|11001011


[zum Anfang](#rechnungen)

--- 

# 3. Hexadezimal - Dezimal

[zum Anfang](#rechnungen)

--- 

# 4. Dual - Hexadezimal

Dual | Hexa | | Dual | Hexa
-:|-:|-:|-:|-:
0000 | 0 || 1000 | 8 
0001 | 1 || 1001 | 9 
0010 | 2 || 1010 | A 
0011 | 3 || 1011 | B 
0100 | 4 || 1100 | C 
0101 | 5 || 1101 | D 
0110 | 6 || 1111 | F 
0111 | 7|

[zum Anfang](#rechnungen)

--- 

# 5. Elektrische Grundgrößen

Name | Formelzeichen | Einheit | runtergebrochene Einheit | Berechnung 
-|:-:|-:|-:|-
Spannung | $U$ | $1 Volt = 1 V$ | $1 V$ | 
Stromstärke | $I$ | $1 Ampere = 1 A$ | $1 A$ | 
elektrischer Widerstand | $R$ | $ 1\Omega $ | $\frac{1V}{1A}$ | $R=\frac{U}{I}$
Stromdichte | $J$ | $1 A/mm^2$ | $A/mm^2$ | $J=\frac{I}{A}$
Leistung | $P$ | $1 W$ | $1 VA$ | $P=U*A$ oder $P=I²*R$ oder $P=\frac{U²}{R}$
Energie | $E$ | $1 J$ | $ VAs$ | $E=U*I*t$

[zum Anfang](#rechnungen)

# 6. Pixel - Farbtiefe

Bildmaße: 30cm x 18cm  
Auflößung: 300 ppi (Pixel Per inch)  
Farbtiefe: 24 Bit  

Aufgabe Speicherplatz in MiB:
<details>
<summary>
Lösung:
</summary>
</details>

$$\frac{\frac{30 * 18}{2,54^2}*1*300Pixel*24Bit}{8*1024*1024}=21,56MiB$$

--- 

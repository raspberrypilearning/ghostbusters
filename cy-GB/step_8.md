## Ychwanegu Amserydd

Rwyt ti nawr am ychwanegu amserydd fel mai dim ond deg eiliad sydd gan y chwareuwr i ddal cymaint o ysbrydion ag sy'n bosib.

\--- task \---

Creu newidyn newydd o'r enw 'amser'.

\--- /task \---

\--- task \---

Alli di ychwanegu amserydd i'r Llwyfan sydd dim ond yn rhoi 10 eiliad i'r chwareuwr ddal ysbrydion?

Fe ddylai dy amserydd:

+ Gychwyn ar 10 eiliad
+ Gyfrif i lawr bob eiliad

Fe ddylai’r gêm ddod i ben pan mae’r amserydd yn cyrraedd 0.

\--- hints \--- \--- hint \--- `Pan fo'r faner werdd wedi ei glicio`{:class="block3events"}, fe ddylai di newidyn `amser`{:class="block3variables"} fod wedi ei `osod i 10`{:class="block3variables"}. Fe ddylai wedyn `newid wrth -1`{:class="block3variables"} bob eiliad `tan ei fod yn cyrraedd 0`{:class="block3control"}. \--- /hint \--- \--- hint \--- Dyma'r blociau côd rwyt ti eu hangen: ![corlun-ysbryd](images/ghost-backdrop.png)

```blocks3
aros [all]

< [ ] = [ ] >

gosod [amser v] i [10]

newid [amser v] gan (-1)

(amser)

aros (1) eiliad

ailadrodd hyd at < >
end

pan fo'r flag werdd yn cael ei glicio

```

\--- /hint \--- \--- hint \--- Dyma'r côd sydd angen i greu amserydd: ![eicon cefnlen](images/ghost-backdrop.png)

```blocks3
pan fo'r flag werdd yn cael ei glicio
gosod [amser v] i [10]
ailadrodd hyd at < (amser) = [0] >
 aros (1) eiliad
 newid [amser v] gan (-1)
end
aros [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Gofyna i ffrind brofi dy gêm. Faint o bwyntiau mae nhw'n gallu sgorio?

\--- /task \---

Os yw dy gêm yn rhy hawdd, mae modd iti:

+ Rhoi llai o amser i’r chwareuwr
+ Gwneud i’r ysbrydion ymddangos yn llai aml
+ Gwneud yr ysbrydion yn llai

\--- task \---

Profa dy gêm nifer o weithiau tan dy fod yn hapus gyda pa mor anodd yw e.

\--- /task \---
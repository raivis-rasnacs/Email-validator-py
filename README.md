# Email-validator-py
Uzdevums par e-pasta adreses validāciju
---
**Problēmas apraksts:**
Lai autorizētos interneta vietnēs, dažkārt nepieciešams norādīt savu e-pasta adresi. Lai pārliecinātos, vai norādītā adrese ir derīga, veic tās validāciju. Tiek ņemti vērā vairāki kritēriji:<br>
* Tajā ir atrodams @ simbols
* Adrese beidzas ar kādu no domēniem, kas doti failā domains.py. Domēnvārdi no šī faila ir importēti kā saraksts **domains**, kas tev būs jāizmanto algoritmā.
* Adresē nav sastopami tādi simboli kā / \ ? ! < > * - +

**Realizācija:**<br>
1. No adreses jāatdala domēnvārds un jāsaglabā jaunā mainīgajā
2. Lai pārbaudītu domēnvārda atbilstību, vari izmantot pierakstu **if ... in domains**.
3. Lai pārbaudītu aizliegtos simbolus, veido zarojumu ar operatoru *and* vai deklarē jaunu sarakstu (kā domēniem)

**Specifikācija:**<br>
Sastādi algoritmu, kas ievadītai e-pasta adresei veic validāciju, ievērojot visus iepriekšminētos kritērijus.<br>
Ja visi kritēriji ir ievēroti, programma izvada ziņojumu **"Adrese derīga!"**, citādi izvada paziņojumu **"Nederīga adrese!"**<br>
Atceries komentēt kodu!<br>
**Pēdējā rindā pievieno komentāru ar savu uzvārdu un klasi!**

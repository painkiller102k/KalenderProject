# 📅 KalenderProject MicrosoftProject

## 📑 Sisukord
- [📌 Projekti kirjeldus](#-projekti-kirjeldus)
- [✅ Ülesannete nimekiri](#-ülesannete-nimekiri)
- [🚀 Põhifunktsionaalsus](#-põhifunktsionaalsus)
- [🖼️ Ekraanipildid](#️-ekraanipildid)
- [🛠️ Kasutatud tehnoloogiad](#️-kasutatud-tehnoloogiad)
- [📂 Projekti struktuur](#-projekti-struktuur)
- [💡 Märkused ja hoiatused](#-märkused-ja-hoiatused)
- [💻 Koodinäited](#-koodinäited)
- [🔗 Lingid](#-lingid)
- [📝 Footnotes](#-footnotes)

---

## 📌 Projekti kirjeldus

KalenderProject on õppeotstarbeline veebiprojekt, mis kujutab endast juhendit Microsoft Projecti kasutamiseks.

Projekt aitab kasutajal samm-sammult aru saada:

- 📆 kalendrite loomisest  
- 📊 diagrammide kasutamisest  
- 🧮 arvutusväljade (Custom Fields) kasutamisest  

Kõik juhised on vormistatud mugava veebilehena koos visuaalsete näidete ja ekraanipiltidega[^2].

---

## ✅ Ülesannete nimekiri

- [x] HTML lehed loodud
- [x] CSS disain valmis
- [x] Navigatsioon töötab
- [x] Ekraanipildid lisatud
- [ ] JavaScript funktsionaalsus
- [ ] Andmete salvestamine

---

## 🚀 Põhifunktsionaalsus

Projekt sisaldab mitut lehekülge:

### 📆 Kalender (index.html)
- Uue kalendri loomine  
- Tööpäevade ja tööaja seadistamine  
- Kalendri rakendamine projektile  

### 🧮 Arvutusväli (valem.html)
- Custom Fields kasutamine  
- Kasutajaväljade loomine  
- Valemite ja andmete lisamine  

### 📊 Diagrammid (diagramm.html)
- Report vahekaardi kasutamine  
- Diagrammide koostamine  
- Ressursside ja kulude analüüs[^1]

---

## 🖼️ Ekraanipildid

### 📆 Kalendri loomine
<img width="1901" height="657" alt="{A319B13B-8154-4B32-B45D-6E424C39D73B}" src="https://github.com/user-attachments/assets/8150935a-a9b9-4e04-bdbc-d60dfb979154" />

### 🧮 Custom Fields
<img width="1904" height="907" alt="{94529A90-1BDD-4521-B934-56B96CADE0E3}" src="https://github.com/user-attachments/assets/ea1133e8-3ecc-454e-b97e-2576db0a54a3" />

---

## 🛠️ Kasutatud tehnoloogiad

Projekt on loodud kasutades põhilisi veebitehnoloogiaid:

- 🌐 HTML5 — lehekülgede struktuur  
- 🎨 CSS3 — kujundus ja animatsioonid  
- 📁 Lokaalsed pildid (kaust images/)  

---

## 📂 Projekti struktuur

```text
KalenderProject/
├── 📄 index.html        # Kalenderi leht
├── 📄 valem.html        # Arvutusväli leht
├── 📄 diagramm.html     # Diagrammide leht
├── 📄 style.css         # Stiilid ja animatsioonid
└── 🖼️ images/          # Kõik ekraanipildid ja graafika
```

---

## 💡 Märkused ja hoiatused

>[!WARNING]
>Projekt töötab otse brauseris ega vaja serverit.

>[!NOTE]
>Soovitatav avada projekt Google Chrome või Edge brauseris.

>[!IMPORTANT]
>Mõned funktsioonid võivad vanemates brauserites mitte töötada.

---

## 💻 Koodinäited
Kuidas on sektsioonid ja astmed tehtud:

```html
 <section class="intro">
        <h2>Mis on MS Project ja kalendrid</h2>
        <p>Microsoft Project on projektijuhtimise tarkvara, mis aitab planeerida, jälgida ja hallata projekte. Kalendrid võimaldavad määrata tööajad, puhkeajad ja eripäevad, et tagada realistlik ja täpne ajakava.</p>
        <p>Kasutades kalendreid projektis, saate automaatselt arvutada ülesannete kestuse, jälgida tähtpäevi ja vältida ajakava konflikte, tagades, et kõik projektis osalejad töötavad õigel ajal.</p>
    </section>
```
Kuidas on CSS animatsioonid tehtud:
```css
.nav a.active[href$="diagramm.html"] {
    background: linear-gradient(135deg, #00e6a8, #5affc2);
    color: #00291f;
    box-shadow: 0 6px 22px rgba(0, 230, 150, 0.5);
}

.card:nth-child(1) { animation-delay: 0.2s; }
.card:nth-child(2) { animation-delay: 0.4s; }
.card:nth-child(3) { animation-delay: 0.6s; }
.card:nth-child(4) { animation-delay: 0.8s; }
.card:nth-child(5) { animation-delay: 1s; }
.card:nth-child(6) { animation-delay: 1.2s; }

.card:hover {
    transform: translateY(-6px) scale(1.02);
    box-shadow: 0 0 25px rgba(0,255,170,0.25),
    0 20px 60px rgba(0,0,0,0.6);
}
```
## 🔗 Lingid
- [GitHub](https://github.com/painkiller102k/KalenderProject)
- [Microsoft Project](https://www.microsoft.com/en/microsoft-365/project/project-management-software)[^3]
- [GitHub Pages](https://painkiller102k.github.io/KalenderProject/)

---


## 📝 Footnotes 
[^1]: Projekti raames kulutatud raha graafiku vaatamine töötaja ja eseme kaupa.  
[^2]: Ekraanipildid on tehtud iseseisvalt rakenduses Microsoft Project.  
[^3]: Microsoft Project ametlik veebileht.
    

# 🗺️ GOS – Gaude okoli Slovenije

## Overview
**GOS** je centralizirana aplikacija za dogodke po Sloveniji. Njena naloga je združiti vse zabave, koncerte, festivale in druge dogodke na enem mestu – tako, da uporabnik vedno ve, kam lahko gre.

Aplikacija bo najprej razvita za **mobilne naprave** z uporabo **Flutterja** in **Firebase** (Auth + Firestore). V1 bo vsebovala osnovne funkcionalnosti in zasnovo, pripravljeno za kasnejše razširitve.

---

## Namen aplikacije
Slovenci pogosto ne vedo, kaj se dogaja v njihovi okolici – dogodki so razpršeni po različnih spletnih straneh in družbenih omrežjih.  
**GOS** rešuje ta problem s tem, da ponuja **enoten pregled vseh dogodkov po regijah** v Sloveniji.

---

## Ciljna skupina
- Mladi, ki radi hodijo na zabave, koncerte in festivale  
- Družine, ki iščejo izlete ali dogodke v bližini  
- Turisti in obiskovalci Slovenije, ki želijo hitro najti aktualne dogodke  

---

## Glavni cilji verzije 1
- Osnovna prijava uporabnika (Firebase Authentication)  
- Prikaz glavne strani z **zemljevidom Slovenije (SVG)**  
- Klik na regijo prikaže dogodke v njej  
- Dogodki so za zdaj **hardkodirani**, kasneje pa bodo pridobljeni iz **Firebase Firestore**  
- Osnovna struktura pripravljena za razširitve (profil, iskanje, filtriranje ipd.)  

---

## Struktura aplikacije

### Glavne strani
1. **Login Page**  
   - Prijava/registracija prek Firebase Auth  
   - Minimalen dizajn s prijaznim tonom

2. **Home Page**  
   - Glavni zemljevid Slovenije (SVG)  
   - Klik na regijo → seznam dogodkov v tej regiji  
   - Možnost kasnejšega iskanja in filtriranja  

---

## Ključni widgeti
- **Profile Widget** – prikaz osnovnih informacij uporabnika  
- **Event Widget** – kartica z imenom dogodka, datumom, lokacijo in opisom  
- (Dodatni widgeti bodo dodani v kasnejših verzijah)  

---

## Uporabniška izkušnja (UI/UX)
- **Vibe:** zabaven, čist, intuitiven  
- **Barve:** bela osnova z **gradientom modra–roza–vijolična**  
- **Način:** samo light mode  
- **Tipografija:** moderna in lahkotna  
- **Jezik:** samo slovenski  

---

## Tehnologije
- **Frontend:** Flutter  
- **Backend:** Firebase  
  - Firebase Authentication (za prijavo)  
  - Firestore Database (za dogodke, kasneje)  
- **Mapa:** Custom SVG mapa Slovenije (klikabilne regije)  

---

## Načrt razvoja
**Faza 1:**  
- Ustvarjanje projekta v Flutterju  
- Nastavitev Firebase Auth  
- Osnovni UI za login stran  

**Faza 2:**  
- Dodajanje SVG zemljevida  
- Uporabniški vmesnik za prikaz regij  
- Hardkodirani dogodki za vsako regijo  

**Faza 3:**  
- Dodajanje osnovnih widgetov (event, profil)  
- Dodelava dizajna (gradient, animacije)  

**Faza 4:**  
- Priprava na Firestore integracijo  
- Optimizacija kode in strukture projekta  

---

## Vizija za prihodnost
- Prikaz dogodkov v realnem času iz Firestore  
- Iskanje dogodkov po ključnih besedah ali datumu  
- Dodajanje uporabniških profilov in priljubljenih dogodkov  
- Možnost dodajanja dogodkov s strani organizatorjev  
- Podpora za angleški jezik in spletno različico  

---

## Povzetek
**GOS** je zasnovan kot preprost, zabaven in uporaben začetek centralizirane platforme za dogodke po Sloveniji.  
Cilj prve verzije ni popolnost, ampak trdna osnova – funkcionalna mapa, osnovni dogodki in prijeten uporabniški vmesnik.  
Kasnejše verzije bodo gradile na teh temeljih in aplikacijo razširile v pravo slovensko platformo za dogodke.

---


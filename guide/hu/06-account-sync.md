# 6. Fiók és szinkronizálás

[← Tartalom](./README.md)

---

## Nincs szüksége fiókra

A To-do Calendar **offline-first**. Minden létrehozott esemény először az eszközére íródik, így az alkalmazás azonnal megnyílik, működik a repülőn, és sosem kell megvárnia a hálózatot.

Ez nem egy korlátozott mód — az események létrehozása, az ismétlési szabályok, az értesítések, az eseménytípusok, az ünnepek, a widgetek és a külső naptárak mind működnek fiók nélkül. Semmi sincs zárolva addig, amíg nem regisztrál.

---

## Mit ad hozzá a bejelentkezés

Jelentkezzen be **Google**- vagy **Apple**-fiókkal, és ezeket is megkapja:

- **Biztonsági mentés** — az eseményei a fiókjában élnek, nem csak ezen a telefonon
- **Szinkronizálás az eszközei között** — ugyanaz a naptár minden iOS-eszközön, amelyen be van jelentkezve
- **[AI gyorsbevitel](./02-ai-input.md)** — az egyetlen funkció, amelyhez fiók kell, mert a kérés kiszolgálón fut

---

## A már létrehozott események

Ha eddig fiók nélkül használta az alkalmazást, a bejelentkezés nem hagyja hátra ezt a munkát. Minden, amit korábban létrehozott, **automatikusan átkerül a fiókjába** — előbb az eseménytípusok, majd a feladatok, a programok, az eseményrészletek és a befejezett feladatok —, és az alkalmazás megmondja, hány eseményt mozgat, és mikor végzett.

Semmit sem kell tennie, és útközben semmi sem törlődik.

---

## Szinkronban maradni

A szinkronizálás magától fut a háttérben — módosítások után, amikor az alkalmazás visszatér az előtérbe, és időnként a kettő között. Amint kész, a widgetek is frissülnek.

Ha valami elavultnak tűnik, a **Szinkronizálás kényszerítése** az eseménybeállításokban törli azt, amit az alkalmazás már szinkronizált, és mindent újra letölt a nulláról.

Ahol ugyanazt az eseményt két helyen módosították, a kiszolgáló verziója győz.

---

## A fiók kezelése

A **Beállítások › Fiók** menüpontban láthatja, hogyan jelentkezett be, milyen e-mail-cím tartozik a fiókhoz, és mikor jelentkezett be utoljára.

- **Kijelentkezés** — az alkalmazás visszatér offline módba, és a helyi adatokkal működik tovább.
- **Fiók törlése** — eltávolítja a fiókját és annak adatait. Ez nem vonható vissza, és az alkalmazás megerősítést kér, mielőtt továbblép.

---

[← Tartalom](./README.md)

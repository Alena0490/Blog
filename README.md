# Blog – administrativní rozhraní

![Mockup administrace](admin-mockup.jpg)

Tato React aplikace slouží jako jednoduchý systém pro správu článků s přehlednou administrací. Uživatelé mohou články přidávat, upravovat, archivovat a mazat. Veřejná část zobrazuje publikované články.

## Funkce

- Vícestránkový web pomocí **React Router**
- **Přihlášení** přes Firebase Auth
- **Formulář** pro přidávání a úpravu článků
- Možnost **archivace**, **obnovení** a **trvalého smazání**
- **Realtime synchronizace** dat přes Firestore
- **Upload obrázků** do Firebase Storage s průběhem nahrávání
- Zobrazení data poslední úpravy článku

## Technologie

- React (CRA)
- React Router DOM
- Firebase (Auth, Firestore, Storage)
- CSS Modules

## Struktura stránek

- `/` – hlavní stránka
- `/all-articles` – seznam článků
- `/one-article/:id` – detail článku
- `/form` – administrace (vyžaduje přihlášení)

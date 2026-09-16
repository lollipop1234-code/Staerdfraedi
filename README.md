# Hagnýt stærðfræði – Útskrift 2026

Þetta repo er vinnusvæði fyrir markvissa yfirferð í áfanganum **Hagnýt stærðfræði (HSTA)**.

## Markmið
Að byggja upp nægilega öruggan grunn og verklag til að standast áfangann. Áherslan er á að kunna að **leysa dæmi sjálfstætt**, velja rétta aðferð og halda færninni milli daga – ekki bara þekkja formúlur.

## Kennslukerfið
Repo-ið notar aðlagað agentakerfi sem er skilgreint í `AGENTS.md`.

Kerfið hefur eitt aðalstjórnunarhlutverk og fjögur sérhæfð hlutverk:

1. **Námsstjóri** – velur næsta skynsamlega skref út frá færni og kennsluáætlun.
2. **Kennari** – kennir eitt atriði í einu með stigvaxandi dæmum.
3. **Greiningaragent** – finnur nákvæmlega hvers konar villa á sér stað og uppfærir villumynstur.
4. **Upprifjunar- og prófari** – prófar færni síðar án vísbendinga og blandar efni saman.
5. **Prófundirbúningur** – byggir smám saman upp dæmagerðir, formúlublöð og prófæfingar.

Aðeins eitt hlutverk leiðir kennsluna í einu svo námið verði ekki óþarflega flókið.

## Vinnuaðferð
- Eitt atriði í einu.
- Eitt reikniskref í hverri línu.
- Ekki fara áfram fyrr en grunnmynstrið situr.
- Nemandinn reynir áður en lausn er sýnd.
- Við villu er fyrsta ranga skrefið greint, ekki bara lokasvarið.
- Ef eitthvað er óljóst er betra að merkja það sem óvissu en að giska.
- Atriði telst ekki `🟢 Situr` eftir eitt rétt dæmi; það þarf endurtekningu, breytt dæmi og síðar upprifjun.
- Grunnfærni og núverandi kennsluvika eru rekin sem tvær samhliða brautir.

Nákvæmt verklag námslota er í `STUDY_PROTOCOL.md`.

## Stöðumerkingar
- `⬜` Ekki byrjað
- `🟡` Í þjálfun
- `🟢` Situr
- `🔁` Þarf upprifjun
- `⚠️` Algeng villa / sérstakt áhersluatriði

## Uppbygging
- `AGENTS.md` – reglur fyrir kennslu-, greiningar-, upprifjunar- og prófhlutverk.
- `STUDY_PROTOCOL.md` – nákvæm uppbygging námslota, mastery og upprifjunar.
- `MASTER_CHECKLIST.md` – aðalstöðuborð yfir alla færni námskeiðsins.
- `KENNSLUAAETLUN.md` – tímalína og efni námskeiðsins.
- `sources/` – heimildakort, m.a. kennslubókin.
- `progress/` – dagsettar námslotur og `SESSION_TEMPLATE.md`.
- `notes/` – stuttar, hagnýtar glósur eftir efnisflokkum.
- `practice/VILLULISTI.md` – endurtekin villumynstur og vinnureglur.
- `practice/UPPRIFJUN.md` – biluð upprifjun á færni sem á að haldast.
- `practice/LEYST_DAEMI.md` – dæmi sem hafa verið unnin og greind.
- `exam/` – efni sem verður smám saman unnið í prentanlegt prófpakkaefni.

## Heimildir
Kennsla byggir fyrst á fyrirlestrum, æfingadæmum og lausnum kennara í ChatGPT Project Sources. Kennslubókin er síðan notuð samkvæmt kaflakorti í `sources/KENNSLUBOK.md`.

## Núverandi áhersla
Brot: deiling, stytting og jöfnur með brotum. Síðan verður grunnurinn prófaður aftur í blandaðri upprifjun áður en farið er markvisst áfram í línur og föll.

## Meginregla
**Repo-ið er námstjórnarkerfi, ekki geymsla fyrir allt sem sagt er í spjalli.** Aðeins gagnleg staða, reglur, villumynstur, framvinda og prófefni eiga að lifa hér.
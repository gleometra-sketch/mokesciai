MOKESČIŲ ASISTENTAS – atskira versija (be Claude)

0) Cloudflare Pages: Workers & Pages -> Create application -> Get started -> Drag and drop your files; ikelkite sį ZIP (failai yra archyvo viršuje, ne aplanke).
1) Talpinimas (nemokamai): įkelkite visą šį aplanką į Netlify Drop (app.netlify.com/drop), Cloudflare Pages arba GitHub Pages.
   PWA ir veikimas be interneto reikalauja HTTPS – šios paslaugos jį suteikia.
2) Telefone: atidarykite gautą nuorodą -> naršyklės meniu -> „Pridėti į pradžios ekraną“.
3) Duomenys saugomi tos naršyklės atmintyje. Darykite JSON atsarginę kopiją (Daugiau -> Eksportuoti).
4) PDF sąskaitos nuskaitomos pagal taisykles (tekstiniai PDF). Skenuotų PDF ir nuotraukų be Claude neperskaito – įveskite ranka.
5) Gmail importas ir „Rasti laišką“ šioje versijoje paslėpti (jiems reikia Claude).

GOOGLE (Gmail importas): Google Cloud Console -> projektas -> Gmail API ijungtas -> OAuth consent (Testing) + jusu el. pastas kaip Test user -> Credentials -> OAuth client ID (Web) -> Authorized JavaScript origins: jusu https://...pages.dev adresas.

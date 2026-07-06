# Grillgilde — content-first site (zonder shop)

Doel van deze fase: **verkeer bewijzen en een mailinglijst opbouwen.** Geen shop, geen voorraad.

## Wat erin zit
- **Home, Recepten (filter), 24 receptpagina's, Techniek, Over, Contact, Nieuwsbrief.** Geen shop.
- **Filter met 4 dimensies:** vleessoort, techniek, gildegraad én **herkomst** (long-tail SEO: "koreaanse bbq", "argentijns asado").
- **Aparte pagina per recept** met eigen URL, `<title>`, meta-description en canonical.
- **Recipe-schema (JSON-LD)** op elk recept → kans op sterren/kooktijd in Google. Plus BreadcrumbList-schema.
- **Open Graph-afbeelding** voor mooie previews bij delen.
- **Nieuwsbrief-blokken** op home, elk recept, techniek, over en een aparte nieuwsbrief-pagina.
- **Interne links** (gerelateerde recepten + "meer [vleessoort/techniek/herkomst]").
- **sitemap.xml** en **robots.txt** aanwezig.

## Zo krijg je zo snel mogelijk verkeer
1. **Search Console** koppelen zodra live → dien `sitemap.xml` in.
2. **Publiceer consequent** — de losse recepten zijn je zoekingangen. Meer recepten = meer kansen.
3. **Recipe-schema laten staan** (zit er al in) — cruciaal voor doorklik.
4. **Snelle pagina's** — gebruik WebP (zie eerdere conversie) en lazy-load foto's.
5. **Herkomst benutten** — schrijf originele wereldrecepten; die long-tail termen hebben minder concurrentie.

## Mailinglijst
De nieuwsbrief-formulieren zijn nu demo. In de echte build koppel je ze aan MailerLite, Mailchimp of Web3Forms (1 regel). Dan bouw je vanaf dag één een lijst op — precies de mensen die later je rubs/boxen kopen.

## Belangrijk
- Dit is een **statisch concept**. In de echte WordPress-build worden dit CPT-recepten met dezelfde opzet (schema, filter, nieuwsbrief) — schaalbaar en zelf te beheren.
- De **shop** is bewust weggelaten en kan later moeiteloos worden toegevoegd (WooCommerce), zonder de content over te doen.
- Fonts laden op je eigen machine via Google Fonts; foto's zijn placeholders tot je ze toevoegt.

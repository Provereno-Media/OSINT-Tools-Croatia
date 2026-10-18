# OSINT-Tools-Croatia
<img src="https://flagcdn.com/w320/hr.png" alt="Croatia_FLAG"/>
A list of OSINT resources and tools that may be useful to you when conducting investigations related to Croatia. Most of the resources and tools has versions in Croatian and English. Many Croatian state portals block automated clients (robots.txt or web application firewalls) but work normally in a regular browser. Several e-Građani services, including the beneficial ownership register, require login through NIAS, the national identification system (Croatian e-ID or an eIDAS-recognised foreign eID). Queries to official registers may be logged.

![Last updated](https://img.shields.io/github/last-commit/Provereno-Media/OSINT-Tools-Croatia?label=Last%20updated)

## Contributions
Feel free to join this project — [OSINT For Countries V2.0](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)

## Table of contents:
 - [Open Data portals](#open-data-portals)
 - [Legal Entities](#legal-entities)
 - [Cadastral and other Maps](#maps)
 - [Vehicles](#vehicles)
 - [People, phones, social etc.](#people)
 - [Public procurements](#public-procurement)
 - [WHOIS](#whois)
 - [Appendix](#appendix)

## Open Data portals
(Country Open Data, Stock Exchange, Courts)
- [Portal otvorenih podataka (Open Data Portal of the Republic of Croatia)](https://data.gov.hr/) — national CKAN catalogue with about 3,900 datasets from ministries, agencies, cities and counties (MUP, DZS, State Geodetic Administration, Zagreb, Rijeka, etc.); keyword search, CKAN API. *Lang: HR.* 🏛️
- [Državni zavod za statistiku – podaci (Croatian Bureau of Statistics data portal)](https://podaci.dzs.hr/) — official statistics: PC-Axis tables, STS database, dashboards, microdata, publications and release calendar. *Lang: HR, EN.* 🏛️
- [Narodne novine (Official Gazette)](https://narodne-novine.nn.hr/) — laws and regulations, plus the notices section (company notices, bankruptcies, liquidations, court notices, court register entries, tenders); search by term, date or issue; export to XLSX/CSV. *Lang: HR.* 🏛️
- [e-Oglasna ploča sudova (Electronic Notice Board of Courts)](https://e-oglasna.pravosudje.hr/) — notice boards of all courts and FINA, bankruptcy notices register, consumer bankruptcy, list of blocked legal entities, court experts and interpreters; keyword search. *Lang: HR.* 🏛️
- [Tražilica odluka sudova RH (Croatian Court Decisions Search)](https://odluke.sudovi.hr/) — Ministry of Justice database of about 1.27 million published decisions of Croatian courts; full-text search and browsing by subject index, EuroVoc and statute. *Lang: HR.* 🏛️
- [Portal otvorenih podataka Grada Zagreba (City of Zagreb Open Data Portal)](https://data.zagreb.hr/) — about 200 municipal datasets (geoportal layers, traffic, local government units, etc.). *Lang: HR.* 🏛️
- [Zagrebačka burza (Zagreb Stock Exchange)](https://www.zse.hr/) — list of issuers, issuer announcements (regulated disclosures), investor notices, share, bond and index data with a 15-minute delay. *Lang: HR, EN.*

## Legal Entities
- [Sudski registar (Court Register of Companies)](https://sudreg.pravosudje.hr/) — official register of companies kept by commercial courts; search by company name or identifiers; legal representatives, supervisory board members, shareholders, share capital, activities and filed documents; free viewing and free active/historical extracts, no legal interest required. *Lang: HR.* 🏛️
- [Pretraživač Obrtnog registra (Craft Register Search)](https://pretrazivac-obrta.gov.hr/pretraga.htm) — official register of crafts (sole traders, obrti) in Croatia, covering both active and deregistered crafts. *Lang: HR.* 🏛️
- [Registar stvarnih vlasnika – uvid javnosti (Beneficial Ownership Register, public view)](https://rsv.fina.hr/RSV-javnost/login) — FINA register of beneficial owners of companies and trusts; search by OIB or entity name; shows name, month/year of birth, country of residence, nationality, nature and extent of ownership. Free; per secondary sources, Croatia did not legislatively close public access after the CJEU ruling of 22 Nov 2022 (C-37/20, C-601/20), but login via NIAS/e-Građani is required. *Lang: HR.* 🏛️ 🪪
- [RGFI – javna objava (Register of Annual Financial Statements, public disclosure)](http://rgfi.fina.hr/JavnaObjava-web/jsp/prijavaKorisnika.jsp) — FINA register of annual financial statements (balance sheet, P&L, notes, profit distribution decisions) of companies; reports free of charge; more than 50 documents/day on request to FINA. *Lang: HR.* 🏛️ ⚠️
- [Registar neprofitnih organizacija (Register of Non-profit Organisations)](https://banovac.mfin.hr/rnoprt/) — Ministry of Finance register of associations, foundations and other non-profits; search by OIB; bulk CSV download on the ministry's register page. *Lang: HR.* 🏛️
- [Državni zavod za intelektualno vlasništvo – e-Registri (State Intellectual Property Office e-Registers)](https://www.dziv.hr/hr/e-usluge/e-registri/) — national registers of trademarks, international trademarks, patents and utility models, SPCs, industrial designs, geographical indications and semiconductor topographies. *Lang: HR.* 🏛️
- [Fininfo](https://www.fininfo.hr/) — commercial aggregator: basic data on 740,000+ Croatian legal entities, related persons (current and former), contact data, court register overview; search by company or person. *Lang: HR.* ⚠️ 💲 Freemium: free registration gives basic data; account-blockade history and media feed are subscriber-only

## Maps
(Cadastral Maps if available, GIS etc.)
- [Uređena zemlja – ZIS OSS (Joint Land Registry and Cadastre System, public application)](https://oss.uredjenazemlja.hr/) — official land registry and cadastre: land registry extracts and cadastral data; search by cadastral municipality plus parcel number or land registry folio. *Lang: HR.* 🏛️
- [Geoportal DGU (State Geodetic Administration Geoportal)](https://geoportal.dgu.hr/) — digital cadastral plans, digital orthophoto and topographic maps with overlay options; some high-resolution WMS/WMTS services require a user account. *Lang: HR.* 🏛️
- [ISPU – Informacijski sustav prostornog uređenja (Spatial Planning Information System)](https://ispu.mgipu.hr/) — Ministry of Spatial Planning geoportal: valid spatial plans (ePlanovi), issued building permits (eDozvola) and related modules. *Lang: HR.* 🏛️
- [ZG Geoportal (City of Zagreb Geoportal)](https://geoportal.zagreb.hr/) — Zagreb spatial data: streets and house numbers, urban plans (GUP), land use, orthophoto 2012–2022, terrain models, noise map, utilities, 3D model; WMS services. *Lang: HR.* 🏛️
- [APPRRR – Prostorni podaci i servisi / ARKOD (Paying Agency spatial data, agricultural parcels)](https://www.apprrr.hr/prostorni-podaci-servisi/) — ARKOD agricultural land-use parcels as WMS and weekly GeoPackage download, yearly archives 2011–2024, plus vineyards, landscape features and other layers. *Lang: HR.* 🏛️

## Vehicles
### Land
- [Centar za vozila Hrvatske (Croatian Vehicle Centre)](https://www.cvh.hr/) — national vehicle inspection body; homepage lookups for technical inspection results and for vehicle testing (atest) case status (returns chassis number, make, type, model, case status); list of inspection stations. *Lang: HR.* 🏛️
- [data.gov.hr – vehicle datasets (CVH, DZS and city datasets)](https://data.gov.hr/ckan/dataset?q=vozila) — 35 open datasets on vehicles: fleet age, vehicle types by county and fuel, electric/hybrid vehicles, inspection statistics and defects, make codes; statistics only, no lookup of individual vehicles. *Lang: HR.* 🏛️

### Maritime
- [Elektronička oglasna ploča upisnika brodova (Ship Register Electronic Notice Board)](https://mmpi.gov.hr/default.aspx?id=22581) — Ministry of the Sea, Transport and Infrastructure: registry decisions on boats, yachts and ships (ownership entries, mortgages, deletions, enforcement), with registration numbers, owners' names and a list of vessels with unpaid fees. *Lang: HR.* 🏛️
- [Hrvatski registar brodova – Ships data online (Croatian Register of Shipping)](https://www.crs.hr/services-and-r-d/ships-data-online/type-of-ship-status) — classification society: definitions of class status and links to the register of ships / survey status, e-certificate validity check, targeted vessels, transfer-of-class and suspension/withdrawal lists. *Lang: EN, HR.*

### Aviation
- [Zračna luka Franjo Tuđman Zagreb (Zagreb Airport)](https://www.zagreb-airport.hr/) — live arrivals and departures board, flight schedule and list of airlines at Croatia's main airport. *Lang: HR, EN.*
- [Flightradar24 – Zagreb Airport (ZAG/LDZA)](https://www.flightradar24.com/data/airports/zag) — live departures/arrivals, aircraft on ground, delays and top routes for Croatia's main airport. *Lang: EN.* 💲 Freemium: live boards and map free; some data (e.g. runway details, extended features) on paid plans
- [ADS-B Exchange](https://globe.adsbexchange.com/) — live aircraft tracking map (tar1090 interface) with flight history, covering Croatian airspace. *Lang: EN.* 💲 Freemium: map free with ads; premium login removes ads and adds satellite layer

## People
(Names, Addresses, Yellow Pages, White Pages etc.)
- [Povjerenstvo za odlučivanje o sukobu interesa – pretraga imovinskih kartica (Conflict of Interest Commission – asset declaration search)](https://www.sukobinteresa.hr/hr/napredna-pretraga-ik) — advanced search of officials' asset declarations by section: real estate, vehicles and movables, business shares, savings, liabilities, other jobs, spouse income. *Lang: HR.* 🏛️
- [Registar obveznika (Register of Officials Subject to Conflict of Interest Rules)](https://www.sukobinteresa.hr/hr/registar-duznosnika) — about 2,600 officials with position, institution, start/end dates; filters by name, position and legal entity; downloadable. *Lang: HR.* 🏛️
- [Registar lobista (Register of Lobbyists)](https://www.sukobinteresa.hr/hr/lobiranje) — lobbying section of the Commission with the register of lobbyists (PDF) kept under the Lobbying Act (NN 36/24), opinions and statements. *Lang: HR.* 🏛️
- [Nestali (Missing Persons – Ministry of the Interior)](https://nestali.gov.hr/) — official list of about 2,860 missing persons with photo, name, date and place of disappearance; browse by initial letter. *Lang: HR, EN.* 🏛️
- [Hrvatski sabor – Zastupnici (Croatian Parliament – Members)](https://www.sabor.hr/hr/zastupnici) — all 150 MPs with profiles, party, electoral unit and mandate status, by convocation. *Lang: HR, EN.* 🏛️
- [HAKOM e-Prenosivost (Number Portability Lookup)](https://www.hakom.hr/hr/e-prenosivost/216) — regulator's tool showing which network a Croatian phone number is currently on (useful for ported numbers); input in format 385XXXXXXXX, captcha. *Lang: HR.* 🏛️
- [Imenik – tportal (Croatian Telephone Directory)](https://imenik.tportal.hr/) — Hrvatski Telekom directory with 10+ million records: persons, legal entities, reverse number search, 06X and info numbers; search by who/what/where. *Lang: HR.*
- [Imenik odvjetnika – Hrvatska odvjetnička komora (Croatian Bar Association Directory)](https://www.hok-cba.hr/imenik) — lawyers, trainees, law firms and joint offices; search by name, category, address, city, language; XLS/PDF download. *Lang: HR.*
- Try [OSINT Industries](https://app.osint.industries) and don't forget about the [Digital Profiler's Toolkit](https://github.com/paulpogoda/Digital-Profiler-s-Toolkit)

## Public procurement
- [Elektronički oglasnik javne nabave RH – EOJN RH (Electronic Public Procurement Classifieds)](https://eojn.hr/) — national procurement platform: tenders, notices, award and cancellation decisions, contracts register, framework agreements, procurement plans, appeal decisions. *Lang: HR, EN.* 🏛️
- [Državna komisija za kontrolu postupaka javne nabave – DKOM (State Commission for Supervision of Public Procurement Procedures)](https://www.dkom.hr/javna-objava-odluka/10) — appeal cases and decisions since 2000 (procurement, concessions, PPP) with contracting authority, appellant and PDF decisions; filters by year, type and register, decision text search. *Lang: HR.* 🏛️
- [Upit o trošenju sredstava državnog proračuna (State Budget Spending Query)](https://www.drzavna-riznica.hr/trosenje_sredstava_DP/) — Ministry of Finance application showing payments from the state treasury single account: recipient (OIB for legal entities), paying budget user, amount, expenditure type, project; updated daily; by year or month. *Lang: HR.* 🏛️
- [Registar koncesija (Register of Concessions)](http://servisi.fina.hr/regkonc/index.do) — Ministry of Finance register run by FINA: search by OIB or name of grantor or concessionaire, concession type, administrative unit and start date; download of all data. *Lang: HR.* 🏛️
- [APPRRR – Baza korisnika potpora (Agricultural and Fisheries Subsidies Beneficiaries)](https://www.apprrr.hr/baza-korisnika-potpora/) — beneficiaries of EU agricultural and fisheries funds per financial year: name, municipality, amounts per measure; Power BI search and Excel download (payments below EUR 1,250 not shown). *Lang: HR, EN.* 🏛️
- [TED – Tenders Electronic Daily](https://ted.europa.eu/en/) — EU Official Journal procurement notices, including Croatian contracting authorities; advanced search and browsing by place of performance. *Lang: EN, HR and other EU languages.*

## WHOIS
- [Domene.hr – WHOIS (.hr Registry, CARNET)](https://www.domene.hr/portal/about/whois) — official WHOIS for .hr domains (web search and `whois.dns.hr`): registrant (shown for legal entities), registrar, creation/expiry dates, name servers; rate-limited. *Lang: HR, EN.* 🏛️
- [Domene.hr – Popis registrara (List of .hr Registrars)](https://www.domene.hr/portal/home/registrars) — the 30 registrars authorised to register .hr domains, with links. *Lang: HR, EN.* 🏛️
- [CIX – Popis članica (Croatian Internet eXchange members)](https://www.cix.hr/index.php/clanice/popis) — 39 networks peering at CIX with AS numbers, CIX location and contact; also looking glass and peering matrix. *Lang: HR.*
- [Hurricane Electric BGP Toolkit – Croatia](https://bgp.he.net/country/HR) — 147 autonomous systems associated with Croatia with IPv4/IPv6 route counts and adjacencies. *Lang: EN.*
- [ICANN Lookup](https://lookup.icann.org/en) — current registration data for domain names and Internet number resources; for .hr domains use the domene.hr WHOIS above. *Lang: EN.*

## Appendix
- [Imamo pravo znati (We Have the Right to Know)](https://imamopravoznati.org/) — volunteer-run freedom-of-information platform supported by Gong and Code for Croatia; searchable archive of about 12,900 FOI requests and responses to 6,860 public bodies. *Lang: HR, EN.*
- [Hrvatski arhiv weba – HAW (Croatian Web Archive)](https://haw.nsk.hr/) — National and University Library archive of Croatian web publications; search by title, URL, keywords and subject. *Lang: HR.*

---

## Contributing

To contribute to this repository:
1. Verify all links are working and accessible
2. Provide accurate descriptions of database contents
3. Follow the 7-category structure
4. Include official government sources when available
5. Submit pull requests with detailed change descriptions

## Legal Disclaimer

This repository is for educational and legitimate investigative purposes only. Users are responsible for:
- Complying with all applicable laws and regulations
- Respecting terms of service for all databases and tools
- Using information ethically and responsibly
- Obtaining proper authorization when required

The information provided is for informational purposes only and should not be considered legal advice.

---

**Repository maintained by the [OSINT-for-Countries-V2.0 community](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)**

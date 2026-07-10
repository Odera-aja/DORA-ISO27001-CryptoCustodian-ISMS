# Organisationsprofil – GermanCrypto Custody AG

## 1. Unternehmensübersicht

Die GermanCrypto Custody AG ist ein regulierter Anbieter für die Verwahrung 
digitaler Vermögenswerte mit Sitz in Frankfurt am Main. Das Institut ist 
europaweit tätig, mit einer wesentlichen Konzentration des Kundengeschäfts 
im deutschsprachigen und mitteleuropäischen Raum.

- Mitarbeiterzahl: ca. 2.500
- Verwahrtes Kundenvermögen (Assets under Custody, AuC): ca. 15 Mrd. EUR
- Geografische Tätigkeit: europaweit, mit regionalem Schwerpunkt
- Primäres Rechenzentrum: Frankfurt am Main (FDC1)
- Sekundäres Rechenzentrum / Disaster-Recovery-Standort: Leverkusen (FDC2)

## 2. Geschäftstätigkeit

Die GermanCrypto Custody AG bietet sowohl Privatkunden als auch 
institutionellen Kunden (u. a. Fonds und Family Offices) die sichere 
Verwahrung digitaler Vermögenswerte (Kryptowerte) an. Das Kerngeschäft 
umfasst die technische und rechtliche Verwahrung privater kryptographischer 
Schlüssel sowie die sichere Abwicklung von Transaktionen im Auftrag der 
Kunden. Die Kundenbasis ist europaweit verteilt, mit deutlichem regionalem 
Schwerpunkt im deutschsprachigen Raum.

## 3. Regulatorischer Status

Die Gesellschaft verfügt über eine Erlaubnis zum Kryptoverwahrgeschäft 
gemäß § 1 Abs. 1a Nr. 6 KWG, erteilt durch die Bundesanstalt für 
Finanzdienstleistungsaufsicht (BaFin), sowie über eine Zulassung als 
Crypto-Asset Service Provider (CASP) gemäß der EU-Verordnung über Märkte 
für Kryptowerte (MiCA). Die BaFin ist die zuständige nationale 
Aufsichtsbehörde sowohl für die KWG- als auch für die CASP-Zulassung. 
Als Finanzinstitut unterliegt die Gesellschaft zudem den Anforderungen 
der Verordnung (EU) 2022/2554 (DORA) zur digitalen operationalen 
Resilienz.

## 4. IT-Infrastruktur-Übersicht (High-Level)

Die IT-Infrastruktur der GermanCrypto Custody AG ist konsequent 
on-premise ausgerichtet, mit Ausnahme unkritischer Randsysteme.

- Primäres Rechenzentrum (FDC1) in Frankfurt am Main sowie sekundäres 
  Rechenzentrum (FDC2) in Leverkusen im Active-Passive-Betrieb
- Datenreplikation zwischen FDC1 und FDC2: synchron für kritische 
  Transaktions- und Custody-Daten, asynchron für alle übrigen Systeme
- Virtualisierungsplattform: VMware-ESXi-Cluster an beiden Standorten
- Storage: SAN-basierte Speicherinfrastruktur (Storage Area Network) mit 
  Replikation zwischen FDC1 und FDC2
- Hardware Security Module (HSM) an beiden Standorten zur sicheren 
  Erzeugung, Speicherung und Nutzung kryptographischer Schlüssel, um im 
  Falle eines Failovers die Signaturfähigkeit am sekundären Standort 
  sicherzustellen
- Cloud-Nutzung: ausschließlich für nicht-kritische Randsysteme 
  (z. B. Unternehmenswebsite); sämtliche Kernsysteme mit Kunden- und 
  Transaktionsdaten verbleiben strikt on-premise

## 5. Organisationsstruktur

- Mitarbeiterzahl: ca. 2.500
- Hauptsitz und zentraler Bürostandort: Frankfurt am Main
- Geschäftsführung/Vorstand: Vorstandsvorsitzender (CEO), Chief Financial 
  Officer (CFO), Chief Risk Officer (CRO), Chief Information Security 
  Officer (CISO)
- Der CISO berichtet direkt an den Gesamtvorstand und ist fachlich an 
  den CRO angebunden, um sowohl Unabhängigkeit von der operativen IT als 
  auch Einbettung in das unternehmensweite Risikomanagement 
  sicherzustellen (in Anlehnung an ISO/IEC 27001:2022, Kapitel 5.3)
- ISMS-Team: CISO sowie drei weitere Mitarbeitende
- IT-Abteilung, organisiert in folgende Teilbereiche: IT-Betrieb/Support, 
  Softwareentwicklung (eigenes Dev-Team), ITIL-Prozessmanagement, 
  Backup-Team, Firewall-Team, Virtualisierungs-Team (VM-Team)

## 6. Stakeholder-Übersicht

**Kunden**
- Retail-Kunden (Privatpersonen)
- Institutionelle Kunden (u. a. Fonds, Family Offices)

**Aufsichtsbehörden und regulatorische Stakeholder**
- BaFin – nationale Aufsichtsbehörde für KWG- und CASP-Zulassung, 
  zuständige Behörde im Sinne von DORA Art. 46
- ESMA – europäische Wertpapier- und Marktaufsichtsbehörde, zuständig 
  für EU-weite Leitlinien unter MiCA
- BSI (Bundesamt für Sicherheit in der Informationstechnik) – aktuell 
  kein verpflichtendes Aufsichtsverhältnis; relevant als Herausgeber des 
  IT-Grundschutz-Standards (freiwillige methodische Referenz) sowie als 
  potenzieller Ansprechpartner im Falle einer künftigen 
  KRITIS-Einstufung

**Kritische Drittanbieter** (grobe Übersicht, Detailerfassung im 
Third-Party-Register unter DORA Pillar 4)
- Blockchain-Node-Infrastruktur-Anbieter
- HSM-Hersteller (Wartung/Support)
- ESXi-/Virtualisierungsanbieter
- Firewall-Anbieter
- Cloud-Anbieter (für die Unternehmenswebsite)
- ServiceNow (Ticketing und Governance-Workflows)
- Physisches Sicherheitsunternehmen (Zutrittskontrolle Rechenzentren)
- Wirtschaftsprüfer

**Interne Stakeholder**
- Vorstand
- ISMS-Team
- IT-Abteilung
- Compliance-Abteilung

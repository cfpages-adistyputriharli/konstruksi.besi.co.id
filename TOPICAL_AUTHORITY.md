# Topical Authority — konstruksi.besi.co.id

## Role and boundary

`konstruksi.besi.co.id` is an Indonesian knowledge and commercial-support property for steel construction: translating a project need into requirements, engineering, estimating, procurement, fabrication, erection, inspection, maintenance, and a defensible handover. The existing site presents design, structural-frame construction, RAB, welding, canopies, gates, grilles, railings, playground equipment, emergency stairs, and steel-tank fabrication.

The editorial role is educational. It must help owners, designers, buyers, contractors, fabricators, supervisors, and facility teams ask better questions and verify work without pretending that an article replaces project-specific calculations, drawings, permits, qualified engineering, welding procedures, inspection, or statutory approval. Commercial service routes remain separate conversion pages; neutral knowledge pages may link to them only where the reader has reached a relevant project decision.

This plan is non-geographic. City/regency swaps are not distinct editorial intent. Related Syamsul-owned domains may independently cover the same query because cross-domain overlap is not cannibalization; boundaries below prevent overlap among pages on this domain.

## Evidence audited

- Canonical repository: `cfpages-adistyputriharli/konstruksi.besi.co.id`, branch `main`, selected as the newer non-backup candidate.
- Static WordPress export: 6,034 tracked files, including 5,025 HTML files, 43 XML files, 273 JavaScript files, and 200 CSS files.
- `README.md` and `sitemap-complete.xml`: 5,021 URLs.
- Sitemap structure: one index, 25 post sitemaps, and one page sitemap with 17 service/about/contact URLs.
- Ten mass-generated root families contain 4,908 geographic pages: 491 each for design, steel tanks, canopies, gates, playgrounds, structural frames, and grilles; 490 each for emergency stairs, RAB, and railings.
- Archive surfaces: 51 category pages and 41 `berita` pagination pages, plus author, feed, results, and 404 routes. These are navigation/index artifacts, not proof of 94 editorial assets.
- Substantive service architecture observed at `/desain/`, `/konstruksi/`, `/konstruksi/rangka/`, `/konstruksi/struktur/`, `/rab/`, `/las/` and its five children, and `/fabrikasi/` with emergency-stair and tank children.
- One non-geographic legacy article exists: `/keunggulan-dan-beragam-kegunaan-besi-dalam-kehidupan-sehari-hari/`.
- Data-quality defects observed: duplicate `/konstruksi/` and misspelled `/konstruski/` branches, a redirect-only `/konstruksi/tangga-darurat/`, and corrupted wording such as `drizal` in page titles/descriptions/content. These claims require a full crawl before remediation quantities are finalized.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Broad commercial homepage for steel construction | keep | Homepage owns brand/service overview | Verify live canonical, indexability, contacts, and supported claims |
| `/desain/` | Design-service landing page | keep | Commercial design route; educational workflow belongs to KBI-06 | Replace unsupported superlatives; add evidence and contextual knowledge links |
| `/konstruksi/`, `/konstruksi/rangka/`, `/konstruksi/struktur/` | Overlapping construction/frame/structure service pages | manual review | Keep one hierarchy or redraw distinct service scopes; KBI-14 owns neutral system education | Compare live traffic/backlinks and page outlines before merge or redirect |
| `/konstruski/`, `/konstruski/rangka/`, `/konstruski/struktur/` | Misspelled duplicate branch present in sitemap/export | redirect | Corresponding correctly spelled `/konstruksi/` route | Confirm canonical tags and external links before permanent redirects |
| `/konstruksi/tangga-darurat/` | Redirect-only file | redirect | `/fabrikasi/tangga-darurat/` commercial route | Verify current target and prevent redirect chains |
| `/rab/` | Commercial RAB/calculation service | keep | Service route; KBI-07 owns educational estimating intent | Verify examples are anonymized and do not imply universal prices |
| `/las/` and `/las/{kanopi,pagar,playground,railing,teralis}/` | Welding/service hierarchy mixed with product-system intents | keep | Commercial service pages; KBI-05 owns connection knowledge and KBI-15/16/19 own system education | Ensure each child has unique service scope and does not duplicate its knowledge hub |
| `/fabrikasi/`, `/fabrikasi/tangga-darurat/`, `/fabrikasi/tangki/` | Fabrication service hierarchy | keep | Commercial routes; KBI-09, KBI-17, and KBI-18 own education | Add verifiable process, QA, and scope evidence |
| `/{family}-{place}/` across ten families | 4,908 location-swapped pages with little evidence of unique local substance | manual review | Consolidate toward system/service owners; retain only pages with real local proof | Crawl canonicals, indexation, impressions, backlinks, leads, and content similarity before redirects/noindex |
| `/category/**`, `/berita/page/**`, `/author/**`, `/feed/**`, `/results/**` | Archive, pagination, author, feed, and search artifacts | noindex | Hubs and individual useful articles own discovery | Verify templates, canonicals, internal links, and whether any archive has independent user value |
| `/keunggulan-dan-beragam-kegunaan-besi-dalam-kehidupan-sehari-hari/` | Very broad material article, also showing corrupted wording | merge | KBI-01-01 and KBI-01-02 after traffic/backlink review | Preserve useful history; repair only after content and performance audit |

Key risks are doorway-like geographic scale, same-domain service-page overlap, thin archive indexation, corrupted copy, unsupported “#1/best/strongest/cheapest” claims, and safety-critical advice published without calculations, current primary standards, qualified review, or stop conditions.

## Coverage matrix

| Completeness lens | Topic owner(s) | Coverage decision |
|---|---|---|
| Definition, vocabulary, taxonomy, materials, history, measurement | KBI-01, KBI-04 | Establish steel-construction language, properties, profiles, units, tolerances, and traceability without turning the site into a merchant catalog |
| Need recognition, survey, diagnosis, requirements | KBI-02 | Separate feasibility inputs and survey evidence from engineering calculations |
| Structural mechanisms, loads, stability, design decisions | KBI-03, KBI-14, KBI-15 | Explain load paths and system trade-offs; project designs remain engineer-owned |
| Parts, interfaces, connections | KBI-04, KBI-05 | Members and their selection are separate from weld/bolt/base-plate connection decisions |
| Design, coordination, documentation | KBI-06 | Own design briefs, models, drawings, revisions, and coordination deliverables |
| Budget, quantity, procurement, contracts | KBI-07, KBI-08 | RAB methodology is separate from vendor evaluation and commercial controls |
| Fabrication, installation, commissioning | KBI-09, KBI-10 | Workshop production and field erection have distinct QA and hazards |
| Durability and fire | KBI-11, KBI-12 | Corrosion protection and fire performance remain separate technical disciplines |
| Inspection, maintenance, troubleshooting, repair, replacement | KBI-13 | Own in-service condition decisions; emergency safety actions remain explicit |
| Building/site types, scale, new build/retrofit | KBI-14 | Compare frame systems by use and constraints without claiming universal spans or capacities |
| Canopies and roof-support steel | KBI-15 | System-specific architecture, drainage, movement, and interfaces |
| Gates, grilles, and railings | KBI-16 | Architectural metalwork grouped by user/safety function, with separate owner pages per object |
| Emergency stairs and egress steel | KBI-17 | Life-safety-sensitive planning, fabrication, inspection, and retrofit |
| Steel tanks | KBI-18 | Containment-specific requirements; excludes unsupported process/pressure-vessel engineering |
| Playground steel | KBI-19 | User safety, layout, fabrication, inspection, and repair; no fabricated compliance claims |
| Stakeholders, K3, quality governance, handover, environmental/end-of-life | KBI-08, KBI-10, KBI-20 | Integrate project controls and lifecycle evidence without mixing them into product sales pages |
| Geography and climate | KBI-02, KBI-11, KBI-15 | Cover substantive exposure conditions such as coast, rain, heat, and pollution; no city swaps |
| DIY versus professional | All technical topics | Explain inspection questions and safe owner actions; calculations, structural changes, hot work, lifting, and life-safety work require competent professionals |
| Evidence formats: visual, calculator, checklist, case study | All topics | Use diagrams, decision tables, calculators, checklists, certificates, photos, and only documented real cases |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| KBI-01 | Steel-construction fundamentals | Use correct terms and understand what material evidence matters before discussing a project | iron versus steel; structural versus non-structural work; strength, stiffness, ductility, toughness; carbon and alloying; units; tolerances; traceability | glossary; property diagrams; sourced comparison; certificate anatomy | Does not choose member sizes (KBI-04), calculate structures (KBI-03), or sell individual stock items (`besi.co.id`) | 6 |
| KBI-02 | Survey, requirements, and feasibility | Prepare a usable project brief and know which site facts can invalidate an early assumption | use, loads, dimensions, interfaces, soil/foundation information, access, utilities, occupancy, climate/exposure, retrofit constraints, evidence gaps | survey checklist; photo plan; requirement matrix; go/no-go tree | Does not perform engineering calculations (KBI-03), create design deliverables (KBI-06), or quote work (`/kontak/`) | 6 |
| KBI-03 | Structural behavior and engineering decisions | Understand load paths, stability, deflection, vibration, robustness, and why project-specific design is required | dead/live/environmental loads; combinations; member and global stability; bracing; serviceability; fatigue; seismic context; verification | load-path diagrams; conceptual examples; engineer review; primary standards | Does not issue project sizes or stamped designs; profiles belong to KBI-04 and building systems to KBI-14 | 6 |
| KBI-04 | Profiles, members, and material selection | Compare member families and specify procurement inputs without guessing capacity from appearance | I/H profiles, channels, angles, hollow sections, plate, bars; hot/cold-formed distinctions; orientation; slenderness concept; dimensions, mass, tolerances; certificates | profile diagrams; selection table; calculation concepts; certificate checklist | Does not design connections (KBI-05), perform whole-frame analysis (KBI-03), or replace product catalogs on related domains | 6 |
| KBI-05 | Welded, bolted, and anchored connections | Recognize connection functions, documentation needs, inspection points, and failure warnings | weld types; bolt assemblies; base plates/anchors; gussets; load transfer; fit-up; accessibility; dissimilar metals; repair limits | detail diagrams; defect photo guide; inspection checklist; qualified review | Does not teach unqualified structural welding or prescribe project connection sizes; fabrication workflow belongs to KBI-09 | 6 |
| KBI-06 | Design workflow, drawings, and coordination | Commission and review a coordinated steel-design package from brief through approved shop drawings | design basis; concept to detailed design; GA/shop/erection drawings; BIM/model coordination; MEP/envelope interfaces; revision control; RFIs; as-built record | deliverable matrix; drawing examples; coordination checklist; revision workflow | Does not calculate RAB (KBI-07), select vendors (KBI-08), or act as the `/desain/` sales page | 6 |
| KBI-07 | Quantity takeoff, RAB, and cost control | Build and compare transparent steel-work estimates while separating quantity, rate, risk, and change | takeoff units; waste/allowance; fabrication, coating, transport, lifting, erection; preliminary versus detailed estimate; bid leveling; variations; lifecycle cost | worked method; spreadsheet template; cost-breakdown diagram; checklist | Does not publish volatile universal prices, negotiate contracts (KBI-08), or replace `/rab/` commercial intent | 6 |
| KBI-08 | Procurement, contractor selection, and contracts | Choose a capable delivery team and write evidence-based commercial controls | scope packages; prequalification; certificates; welding/QA capability; bid comparison; schedule; warranty; exclusions; payment; change control; red flags | scorecard; tender checklist; contract-scope matrix; evidence register | Does not endorse named vendors without evidence, estimate quantities (KBI-07), or manage site execution (KBI-10) | 6 |
| KBI-09 | Workshop fabrication and quality assurance | Understand how drawings become traceable components and where workshop defects are prevented | material receipt; identification; cutting; forming; fit-up; welding controls; dimensional checks; trial assembly; surface preparation; release dossier | process map; ITP example; hold-point checklist; original workshop evidence | Does not provide welding qualification instructions (KBI-05), field erection procedures (KBI-10), or sell `/fabrikasi/` services | 6 |
| KBI-10 | Transport, erection, site safety, and handover | Plan safe logistics and verify that installed steel matches approved documents | transport frames; delivery sequence; lifting plans; temporary stability; access/work at height; bolting/welding on site; survey; punch list; commissioning; as-built dossier | sequence diagram; lift-plan input checklist; ITP; handover index | Does not authorize lifting or site work; fabrication belongs to KBI-09 and governance to KBI-20 | 6 |
| KBI-11 | Corrosion exposure and protective systems | Match protection and maintenance logic to actual exposure and detail conditions | corrosion mechanism; indoor/outdoor/coastal/industrial exposure; drainage and crevices; paint systems; galvanizing; compatibility; preparation; inspection; touch-up | exposure decision tree; coating-system anatomy; defect photos; manufacturer/standard evidence | Does not promise service life without verified system/environment data; fire protection belongs to KBI-12 | 6 |
| KBI-12 | Fire performance and passive protection | Understand how fire changes steel behavior and how protection is selected, detailed, inspected, and repaired | temperature effects; required performance; boards, sprays, encasement, intumescent systems; section factor concept; interfaces; inspection; post-fire assessment | mechanism diagram; system comparison; inspection checklist; fire engineer review | Does not state a fire rating from coating thickness alone or replace code/project fire engineering; corrosion belongs to KBI-11 | 6 |
| KBI-13 | Inspection, maintenance, defects, repair, and retrofit | Triage visible symptoms, collect useful evidence, and decide whether to maintain, repair, strengthen, or replace | inspection levels; corrosion, distortion, cracks, loose bolts, coating failure; water traps; monitoring; repair design; strengthening; post-event checks; records | symptom-to-action table; photo protocol; maintenance register; engineer stop conditions | Does not authorize structural repair from photos; connection defects link to KBI-05 and protection defects to KBI-11/KBI-12 | 6 |
| KBI-14 | Steel building and frame systems | Compare structural system concepts for warehouses, factories, homes, additions, and retrofits | portal/braced/moment/truss concepts; grids and spans; cranes/equipment; envelope/MEP; expansion; prefab/modular; occupied retrofit; system selection | system diagrams; decision matrix; documented case template; engineer review | Does not provide universal member sizes; KBI-03 owns behavior and `/konstruksi/` owns commercial conversion | 6 |
| KBI-15 | Canopies and steel roof-support systems | Define a canopy/roof brief that coordinates structure, cover, drainage, movement, durability, and maintenance | free-standing versus attached; cantilevers; hollow/light steel concepts; roof-cover interfaces; slope/drainage; wind/uplift; thermal movement; leaks; access | section diagrams; requirement checklist; failure gallery; interface matrix | Does not design roof members, sell roof sheets, or duplicate `/las/kanopi/`; whole-building frames belong to KBI-14 | 6 |
| KBI-16 | Gates, grilles, and railings | Choose and inspect architectural metalwork by function, user safety, operation, security, and maintainability | gate movement/support; grille egress and security; railing geometry/load concept; infill and climbability; child/accessibility concerns; finishes; anchors; repair | object-specific diagrams; decision tables; inspection checklists; original photos | Each object has a distinct owner article; welding theory belongs to KBI-05 and service conversion to `/las/{pagar,teralis,railing}/` | 6 |
| KBI-17 | Emergency stairs and steel egress structures | Scope, coordinate, fabricate, inspect, and maintain an emergency-stair system without confusing it with an ordinary stair | egress role; geometry inputs; landings; guards/handrails; structural support; interfaces; exposure; fabrication/erection; inspection; retrofit | egress-path diagram; coordination checklist; inspection register; qualified code review | Does not set code dimensions or certify compliance without current jurisdiction/project review; `/fabrikasi/tangga-darurat/` owns sales | 6 |
| KBI-18 | Fabricated steel tanks | Translate stored-medium, capacity, site, cleaning, corrosion, and support needs into a safe fabrication brief | atmospheric versus other service; medium compatibility; geometry; nozzles; vent/overflow/drain; supports; access; lining/coating; testing; inspection; repair | requirement sheet; anatomy diagram; test/dossier checklist; specialist review | Excludes pressure vessels and hazardous-process design unless separately qualified; `/fabrikasi/tangki/` owns sales | 6 |
| KBI-19 | Steel playground structures | Plan durable playground metalwork around users, movement, layout, fabrication, inspection, and maintenance | age/use brief; layout and circulation; fall/entrapment concepts; moving parts; welds/fasteners; coatings; foundations; inspection; closure and repair | hazard map; inspection checklist; component diagrams; qualified safety review | Does not invent certification, impact criteria, or safe dimensions; `/las/playground/` owns commercial service | 6 |
| KBI-20 | Project governance, evidence, lifecycle, and sustainability | Run steel work with accountable roles, records, change control, acceptance evidence, and end-of-life decisions | responsibility matrix; ITP/NCR; document control; K3 governance; progress evidence; acceptance; warranty; operation records; reuse, recycling, deconstruction; post-project review | RACI; evidence register; handover checklist; lifecycle decision tree | Does not replace procurement contracts (KBI-08), site method statements (KBI-10), or technical design approval | 6 |

## Related-domain opportunities

- `besi.co.id` can own material/product availability and merchant-oriented specifications while this domain explains construction-system decisions.
- `atap.besi.co.id` and `bajaringan.besi.co.id` can provide roof-cover and light-gauge product viewpoints; KBI-15 remains the steel-canopy/roof-support coordination owner here.
- `hollowpipa.besi.co.id`, `batang.besi.co.id`, `batangan.besi.co.id`, `grating.besi.co.id`, and `kawat.besi.co.id` may supply product-family references; KBI-04 keeps the project-selection viewpoint.
- `bengkel-las.co.id`, `cutting.co.id`, and `pabrikasi.id` may cover trade/process depth; KBI-05 and KBI-09 retain construction QA and interface decisions.
- `firesafety.co.id`, `safety.co.id`, and `tukang.co.id` may provide independent specialist perspectives. Cross-domain links should be editorially useful and should not imply shared authorship, certification, or endorsement without evidence.

## Consolidation plan

1. Export live Search Console, analytics, backlink, canonical, and lead evidence for all 5,021 sitemap URLs before bulk URL decisions.
2. Freeze creation of new location-swapped pages. Sample each of the ten 490–491-page families for similarity, local proof, indexation, impressions, links, and conversions.
3. Preserve any genuinely valuable URL history, but consolidate unsupported location variants into the correct service or knowledge owner through a reviewed redirect/canonical/noindex plan. Do not redirect unrelated intent merely to reduce URL count.
4. Resolve `/konstruksi/` versus `/konstruski/` and the redirect-only emergency-stair path, then generate one clean sitemap from final canonical URLs.
5. Noindex or remove low-value archive/search/feed surfaces from XML sitemaps while keeping crawl paths to useful articles and hubs.
6. Run a repository-wide language repair audit for corrupted substitutions such as `drizal`; repair titles, descriptions, headings, body copy, structured data, and alt text together.
7. Rebuild service hubs around verifiable scope, process, QA evidence, and boundaries. Publish the bounded knowledge cluster before expanding later waves.

## Internal-link architecture

- `/` links to the commercial service hierarchy and a central steel-construction knowledge hub represented by KBI-01-01.
- Every article links to its parent-topic hub; each hub links to all six children and one appropriate next-stage hub.
- Lifecycle path: KBI-01 → KBI-02 → KBI-03/KBI-04 → KBI-06 → KBI-07/KBI-08 → KBI-09 → KBI-10 → KBI-13 → KBI-20.
- Connection, corrosion, and fire diagnostic pages link to prevention, inspection, repair, and professional stop conditions.
- System hubs KBI-14 through KBI-19 link laterally only to the applicable fundamentals, design, estimating, fabrication, erection, protection, and maintenance articles.
- Commercial routes receive links from relevant decision pages only after the educational intent is satisfied; service pages link back to neutral prerequisites and QA checklists.
- Redirected geographic/archive URLs must not become orphan-generating dead ends. Recalculate internal links and crawl depth after consolidation.

## Evidence and editorial standards

- Verify current laws, standards, permits, safety requirements, and manufacturer instructions from primary sources at publication time. Do not invent clause numbers, universal spans, loads, dimensions, coating thicknesses, fire ratings, prices, or service-life claims.
- Structural design, fire engineering, welding procedure/qualification, lifting, work at height, hazardous media, and life-safety content requires review by a demonstrably competent Indonesian professional for the specific discipline.
- Label concepts, examples, and project requirements distinctly. Calculators must show assumptions, units, limitations, and when professional calculation is mandatory.
- Use original diagrams and properly licensed images. Case studies require real project records, consent, constraints, decisions, dates, and measured results; never fabricate experience.
- Commercial claims require traceable proof. Avoid `#1`, “best,” “strongest,” “cheapest,” “SNI,” or warranty language unless the exact scope and evidence are current.
- Every article receives an owner, reviewer, evidence date, update trigger, and internal-link check. Safety-critical pages have a scheduled review cycle and visible stop conditions.

## First bounded publication cluster

Publish 14 Wave-1 assets: KBI-01-01, KBI-01-02, KBI-02-01, KBI-02-02, KBI-03-01, KBI-04-01, KBI-05-01, KBI-06-01, KBI-07-01, KBI-08-01, KBI-09-01, KBI-10-01, KBI-11-01, and KBI-13-01.

This cluster is coherent because it follows one project from vocabulary and brief through engineering concepts, profiles, connections, design documents, cost, procurement, fabrication, erection, protection, and inspection. The fundamentals hub links down the lifecycle; each specialist asset links backward to required inputs and forward to verification or maintenance.

Measure valid indexation, impressions grouped by distinct intent, clicks into next-stage checklists, scroll/task completion, assisted visits to relevant service pages, qualified contacts, answered contacts, conversions/commission, and collected revenue. Review query/page pairs monthly for same-domain cannibalization. Do not publish later waves merely because drafts exist.

## Definition of done

- All 20 parent topics retain six mutually distinct, reviewed briefs and correct counts in `ARTICLE_CATALOG.md`.
- Every planned article has a unique title, slug, primary intent, coverage promise, explicit owner boundary, evidence format, related IDs, priority, and wave.
- Proposed slugs have no collision with current repository routes; later production routes repeat the check immediately before publication.
- The ten geographic families and archive surfaces have an evidence-based keep/consolidate/noindex decision, not a blanket deletion.
- Misspelled/redirect branches, corrupted copy, canonicals, sitemaps, and internal links are reconciled.
- Wave 1 is expert-reviewed, internally connected, crawlable, measured across search and commercial outcomes, and checked for cannibalization before scale-up.

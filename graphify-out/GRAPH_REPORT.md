# Graph Report - pergioco-v41.19  (2026-11-24)

## Corpus Check
- 224 files · ~149,552 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 7 file(s) not represented in the graph (top: (none) 4, .csv 2, .css 1)

## Summary
- 2598 nodes · 6384 edges · 166 communities (118 shown, 48 thin omitted)
- Extraction: 90% EXTRACTED · 10% INFERRED · 0% AMBIGUOUS · INFERRED: 652 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `794b5b4f`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- make_xlsx_lib
- A
- Ra
- N
- ct
- appver.js
- libri.js
- schema.sql
- bgg.ts
- public
- sondaggi.js
- app.js
- consigliere.js
- migrate-v41.13.sql
- public.tables
- v41.15-gdr-unit.test.js
- ref_playwright_core
- xe
- setup
- v41.12-gdr-unit.test.js
- B
- migrate-v41.17.sql
- migrate-v35.sql
- migrate-v32.sql
- public.member_xp_base
- giochi.js
- ref_fs
- v41.13.1-header-unit.test.js
- ref_path
- v41.16-unit.test.js
- v41.14-password-unit.test.js
- import-bgg.js
- public.members
- v41.14-tavolo-testo-unit.test.js
- tests_appver_app_version
- fv
- eventi.js
- tavoli-tipi.js
- v41.12.1-foto-unit.test.js
- v41.14.3-host-miepartite-unit.test.js
- esc
- games
- xk
- wrapped.js
- migrate-v36.sql
- v41.8.1.test.js
- xp.js
- migrate-v12.sql
- sicurezza.js
- v41.17-unit.test.js
- config2.js
- Esempi di motivazioni (v25, generati dal codice reale)
- v41.12.1-foto.test.js
- v41.10-bgg-api-unit.test.js
- errori.js
- t
- v41.10.2-bgg-user-unit.test.js
- v41.14.2-rpg-search-unit.test.js
- public.games
- v39.test.js
- altro.js
- go
- header.js
- migrate-v7.sql
- v41.13.3-agenda.test.js
- v41.14-config.test.js
- v41.18.2-elimina-unit.test.js
- v41.18.3-mostra.test.js
- mie-partite.js
- profilo.js
- v41.13-sondaggi-unit.test.js
- v41.14.3-mie-partite.test.js
- v41.19-bp1-unit.test.js
- migrate-v26.sql
- v41.1-identico.test.js
- ref_http
- v40.test.js
- v41.11.1-tavoli.test.js
- v41.11.1-tavoli-unit.test.js
- v41.11-tavoli-unit.test.js
- v41.12-gdr.test.js
- v41.13.1-header.test.js
- v41.13.2-sondaggi.test.js
- v41.13.2-sondaggi-unit.test.js
- v41.13-sondaggi.test.js
- v41.14.3-host-non-lascia.test.js
- v41.14-tavolo-testo.test.js
- stats.js
- picker.test.js
- v41.14-config-unit.test.js
- v41.18-unit.test.js
- agSheet
- desideri.js
- manifest.json
- v41.8-giochi.test.js
- v41.2-partita.test.js
- v39.2.test.js
- coppa.js
- migrate-v9.sql
- antero.js
- authForm
- pfHtml
- brand.js
- migrate-v25.sql
- public.record_assoluti
- v41.18.test.js
- Ia
- v39.1.test.js
- equilibrio.js
- gdr-rec.js
- package.json
- picker.js
- sb.js
- v40.5.1.test.js
- Procedura di rilascio
- test-all.sh
- migrate-v29.sql
- v40.1b.test.js
- v40.5.test.js
- public.wrapped_set
- test-v41.1b.sql
- v40.3.test.js
- v41.test.js
- migrate-v41.10.sql
- test-v40.6.sql
- test-v41.sql
- ux40.js
- accesso.js
- gdr-coll.js
- ig.js
- ricompense.js
- publish-test.sh
- sw.js
- v41.14.5-poll-rpc.sql

## God Nodes (most connected - your core abstractions)
1. `make_xlsx_lib()` - 540 edges
2. `Ra()` - 123 edges
3. `A()` - 101 edges
4. `public.members` - 87 edges
5. `N()` - 73 edges
6. `s()` - 68 edges
7. `o()` - 66 edges
8. `i()` - 62 edges
9. `f()` - 51 edges
10. `sk()` - 45 edges

## Surprising Connections (you probably didn't know these)
- `Ci()` --indirect_call--> `at()`  [INFERRED]
  vendor/xlsx.full.min.js → tests/v40.1.test.js
- `eh()` --indirect_call--> `at()`  [INFERRED]
  vendor/xlsx.full.min.js → tests/v40.1.test.js
- `um()` --indirect_call--> `at()`  [INFERRED]
  vendor/xlsx.full.min.js → tests/v40.1.test.js
- `Ai()` --indirect_call--> `at()`  [INFERRED]
  vendor/xlsx.full.min.js → tests/v40.1.test.js
- `Cc()` --indirect_call--> `at()`  [INFERRED]
  vendor/xlsx.full.min.js → tests/v40.1.test.js

## Import Cycles
- None detected.

## Communities (166 total, 48 thin omitted)

### Community 0 - "make_xlsx_lib"
Cohesion: 0.03
Nodes (118): make_xlsx_lib(), Al(), as(), Ba(), bf(), bl(), Br(), bs() (+110 more)

### Community 1 - "A"
Cohesion: 0.06
Nodes (85): at(), A(), aA(), Ai(), ap(), bk(), bo(), bt() (+77 more)

### Community 2 - "Ra"
Cohesion: 0.06
Nodes (72): ab(), an(), av(), bb(), cb(), cf(), Ci(), cp() (+64 more)

### Community 3 - "N"
Cohesion: 0.16
Nodes (67): ak(), ar(), bu(), c(), Cs(), d(), dl(), E() (+59 more)

### Community 4 - "ct"
Cohesion: 0.07
Nodes (63): ah(), bc(), bg(), bh(), bm(), bn(), bp(), cm() (+55 more)

### Community 5 - "appver.js"
Cohesion: 0.05
Nodes (41): cssBlock(), esc(), fs, hasAsset(), idxTxt(), path, read(), ROOT (+33 more)

### Community 6 - "libri.js"
Cohesion: 0.08
Nodes (48): BADGES, DB, isBoardGamePlay(), isGdrPlay(), LocalAdapter, memberName(), Profile, SEED_GAMES (+40 more)

### Community 7 - "schema.sql"
Cohesion: 0.07
Nodes (38): public.des_arrivato(), moderators_user_id_uidx, public.admin_admins(), public.admin_moderators(), public.admin_set_moderator(), public.admin_set_moderator_member(), public.is_moderator(), admins_guard_super (+30 more)

### Community 8 - "bgg.ts"
Cohesion: 0.10
Nodes (41): cleanUsername(), ORIGINS, cacheGet(), cacheSet(), cercaBgg(), cercaRpg(), clipIntArr(), clipTxtArr() (+33 more)

### Community 9 - "public"
Cohesion: 0.10
Nodes (24): public.tables_host_guard(), public.evento_staff(), public.set_stats_pubbliche(), public.update_my_profile(), public.tables_host_guard(), public.tables_type_guard(), tables_type_guard, public.tables_host_guard() (+16 more)

### Community 10 - "sondaggi.js"
Cohesion: 0.12
Nodes (24): record(), bind(), byline(), cercaGioco(), collectVote(), cover(), detailHtml(), doAct() (+16 more)

### Community 11 - "app.js"
Cohesion: 0.07
Nodes (26): ask(), askText(), badgeCtx(), badgeNew(), badgeSnap(), _bk, confirmLogout(), GIORNI (+18 more)

### Community 12 - "consigliere.js"
Cohesion: 0.07
Nodes (32): CATM, CATN, cBook(), CC, cChoose(), CCIT, CDET, CFLOW (+24 more)

### Community 13 - "migrate-v41.13.sql"
Cohesion: 0.13
Nodes (20): poll_ballots_poll_idx, poll_options_poll_idx, public.member_xp(), public.poll_aggiungi_opzione(), public.poll_azione(), public.poll_badge_grant, public.poll_ballots, public.poll_chiudi_scaduti() (+12 more)

### Community 14 - "public.tables"
Cohesion: 0.08
Nodes (26): public.tables_host_guard(), tables_host_guard, public.tables_no_past(), tables_no_past, public.evening_from_date(), zz_plays_evening, zz_tables_evening, public.table_seat() (+18 more)

### Community 15 - "v41.15-gdr-unit.test.js"
Cohesion: 0.05
Nodes (33): app, auto, bgg, br, brand, coll, dnd, fs (+25 more)

### Community 16 - "ref_playwright_core"
Cohesion: 0.06
Nodes (16): pw, pw, pw, N, pw, N, pw, eq (+8 more)

### Community 17 - "xe"
Cohesion: 0.18
Nodes (34): ae(), ag(), be(), ce(), De(), dr(), Ee(), fe() (+26 more)

### Community 18 - "setup"
Cohesion: 0.08
Nodes (19): altro(), pw, cod(), pw, hdr(), pw, csv, fs (+11 more)

### Community 19 - "v41.12-gdr-unit.test.js"
Cohesion: 0.06
Nodes (26): app, b2, bad, bl, brand, data, fs, guest (+18 more)

### Community 20 - "B"
Cohesion: 0.30
Nodes (31): aw(), B(), bw(), cw(), dw(), ew(), fw(), gw() (+23 more)

### Community 21 - "migrate-v41.17.sql"
Cohesion: 0.09
Nodes (16): public.libro_audit, public.libro_import_report, public.libro_log(), public.libro_quote, public.libro_soci, public.libro_volontari, libro_soci_link, public.libro_soci_link() (+8 more)

### Community 22 - "migrate-v35.sql"
Cohesion: 0.16
Nodes (18): cp_tavolo_chk, ct_coppa, ct_no_tavolo_uguale, ct_un_bye, public.coppa_apri(), public.coppa_avanza(), public.coppa_avvia(), public.coppa_lista() (+10 more)

### Community 23 - "migrate-v32.sql"
Cohesion: 0.18
Nodes (25): ci_no_rivincita, ci_turno_a, ci_turno_b, ci_un_bye, cp_incontro_chk, public.coppa_apri(), public.coppa_avanza(), public.coppa_avvia() (+17 more)

### Community 24 - "public.member_xp_base"
Cohesion: 0.12
Nodes (12): game_ratings_game, public.game_ratings, public.member_xp(), public.rate_game(), public.rating_moderate(), public.member_xp(), public.plays_sfida_check(), public.cp_gioco() (+4 more)

### Community 25 - "giochi.js"
Cohesion: 0.10
Nodes (15): CAT_IT, gAdminSave(), GB, gBggBind(), gBggPick(), gCats(), gClamp(), gFill() (+7 more)

### Community 26 - "ref_fs"
Cohesion: 0.07
Nodes (14): C, fs, p, r, el, fs, h, q (+6 more)

### Community 27 - "v41.13.1-header-unit.test.js"
Cohesion: 0.08
Nodes (19): app, assert, brand, css, fs, idx, js, path (+11 more)

### Community 28 - "ref_path"
Cohesion: 0.08
Nodes (15): fs, http, path, pw, ROOT, srv, T, acts (+7 more)

### Community 29 - "v41.16-unit.test.js"
Cohesion: 0.08
Nodes (23): altro, app, css, data, e, fs, hdr, html (+15 more)

### Community 30 - "v41.14-password-unit.test.js"
Cohesion: 0.08
Nodes (17): app, cases, ctx, fs, m, path, ROOT, sb (+9 more)

### Community 31 - "import-bgg.js"
Cohesion: 0.22
Nodes (23): act(), attrib(), counts(), detail(), doImport(), draw(), enrichStatus(), fileStep() (+15 more)

### Community 32 - "public.members"
Cohesion: 0.14
Nodes (20): public.search_members(), public.ricompensa_scegli(), members_no_dup_trg, members_tessera_trg, public.admin_admins(), public.admin_member_remove(), public.admin_member_remove_info(), public.admin_set_admin() (+12 more)

### Community 33 - "v41.14-tavolo-testo-unit.test.js"
Cohesion: 0.08
Nodes (17): cm, css, d, eq, fs, path, s, tt (+9 more)

### Community 34 - "tests_appver_app_version"
Cohesion: 0.08
Nodes (15): app, brand, css, fs, i0, i1, idx, path (+7 more)

### Community 35 - "fv"
Cohesion: 0.11
Nodes (23): am(), At(), co(), Cv(), dh(), ev(), fv(), Gv() (+15 more)

### Community 36 - "eventi.js"
Cohesion: 0.22
Nodes (21): ATTIVE, bindSeg(), card(), euro(), EV, evCosto(), evData(), evDetail() (+13 more)

### Community 37 - "tavoli-tipi.js"
Cohesion: 0.14
Nodes (12): byId(), capacity(), countOpen(), cov(), fetchThumb(), label(), load(), loadThumbs() (+4 more)

### Community 38 - "v41.12.1-foto-unit.test.js"
Cohesion: 0.10
Nodes (19): app, assert, block, brand, ctx, fs, hdr, idx (+11 more)

### Community 39 - "v41.14.3-host-miepartite-unit.test.js"
Cohesion: 0.10
Nodes (15): all, app, brand, data, fs, idx, path, plays (+7 more)

### Community 40 - "esc"
Cohesion: 0.19
Nodes (18): adminStatsHtml(), avatarHtml(), badgeDates(), bars(), bdgPop(), esc(), fmt(), gamePage() (+10 more)

### Community 41 - "games"
Cohesion: 0.13
Nodes (14): aa_plays_sfida, plays_sfida_uq, public.plays_sfida_check(), public.sfide, public.sfide_check(), sfide_check, sfide_creator_idx, aa_plays_sfida (+6 more)

### Community 42 - "xk"
Cohesion: 0.13
Nodes (20): ao(), ck(), ek(), gk(), jg(), kb(), lk(), mk() (+12 more)

### Community 43 - "wrapped.js"
Cohesion: 0.23
Nodes (19): anni(), apri(), assoc(), banner(), card(), cl(), condividi(), dati() (+11 more)

### Community 44 - "migrate-v36.sql"
Cohesion: 0.23
Nodes (17): des_bgg_unico, des_una_attiva, dp_uno_aperto, public.des_chiudi_scaduti(), public.des_elimina(), public.des_lista(), public.des_periodo(), public.des_proponi() (+9 more)

### Community 45 - "v41.8.1.test.js"
Cohesion: 0.15
Nodes (9): pw, setup(), lvp(), pw, fs, pw, pw, fs (+1 more)

### Community 46 - "xp.js"
Cohesion: 0.19
Nodes (18): champH(), cpCamp(), lbH(), lv(), LV_T, lvInfo(), nmH(), RA (+10 more)

### Community 47 - "migrate-v12.sql"
Cohesion: 0.25
Nodes (16): ev_pren_trg, eventi_guard, evento_pren_uno, public.ev_log(), public.ev_occupati(), public.ev_pren_trg(), public.ev_promuovi(), public.eventi (+8 more)

### Community 48 - "sicurezza.js"
Cohesion: 0.16
Nodes (14): COL_MAX, fotoOrigin(), fotoTipo(), isTxt(), photoUrlOk(), processAvatar(), rowClean(), safeUrl() (+6 more)

### Community 49 - "v41.17-unit.test.js"
Cohesion: 0.11
Nodes (14): acc, app, brand, css, data, fs, idx, path (+6 more)

### Community 50 - "config2.js"
Cohesion: 0.26
Nodes (16): build(), count(), dirtyN(), fieldErrors(), gdr(), logo(), moduli(), mount() (+8 more)

### Community 51 - "Esempi di motivazioni (v25, generati dal codice reale)"
Cohesion: 0.12
Nodes (16): Esempi di motivazioni (v25, generati dal codice reale), Esperto: 2 ideale, controllo, economia, medio, Esperto: 2, leggero, tessere, nessun testo, 8 anni, Esperto: 3 ideale, medio-pesante, piazzamento lavoratori, Esperto: 4, dadi + rischia, 10 anni, Esperto: 4, draft + set, fantasy, Esperto: 4, fantascienza, pesante, serata, Esperto: 5, aste, interazione diretta, poca fortuna (+8 more)

### Community 52 - "v41.12.1-foto.test.js"
Cohesion: 0.13
Nodes (15): BUG-FOTO-BARRA — foto profilo che non carica, in barra, Bug noti (la suite li segnala, non li nasconde), BUGS, chk(), fs, http, path, PNG (+7 more)

### Community 53 - "v41.10-bgg-api-unit.test.js"
Cohesion: 0.12
Nodes (12): brand, coll, cons, des, fs, giochi, imp, meta (+4 more)

### Community 54 - "errori.js"
Cohesion: 0.20
Nodes (13): azione(), ERR_AREE, ERR_AZIONI, ERR_SCHERMI, ERR_TIPI, errApplicativo(), errCodice(), errCtx() (+5 more)

### Community 55 - "t"
Cohesion: 0.15
Nodes (8): public.coppa_crea(), public.coppa_risultato(), public.coppa_risultato_t(), public.mod_nome(), public.coppa_crea(), public.coppa_risultato(), public.coppa_risultato_t(), public.mod_nome()

### Community 56 - "v41.10.2-bgg-user-unit.test.js"
Cohesion: 0.12
Nodes (12): brand, cm, coll, cons, des, fs, giochi, imp (+4 more)

### Community 57 - "v41.14.2-rpg-search-unit.test.js"
Cohesion: 0.14
Nodes (12): first(), fs, ids(), meta, onlyItems, parsed, {parseSearch,rpgNorm,rankRpgSearch}, path (+4 more)

### Community 58 - "public.games"
Cohesion: 0.14
Nodes (4): public.games_import_bgg(), public.admin_game_remove(), public.admin_game_remove_info(), public.games

### Community 59 - "v39.test.js"
Cohesion: 0.13
Nodes (11): A, C, D, fs, G, I, l, ps (+3 more)

### Community 60 - "altro.js"
Cohesion: 0.36
Nodes (12): accRow(), clean(), foot(), infoCard(), markReq(), proc(), row(), soci() (+4 more)

### Community 61 - "go"
Cohesion: 0.18
Nodes (14): adminMode(), drawModeBtn(), drawOutBtn(), go(), isMod(), norm(), openProfile(), pickMembers() (+6 more)

### Community 62 - "header.js"
Cohesion: 0.29
Nodes (11): av(), avColor(), avEmoji(), closeMenu(), face(), items(), openMenu(), paintAv() (+3 more)

### Community 63 - "migrate-v7.sql"
Cohesion: 0.23
Nodes (11): pergioco_signup_check, pergioco_signup_link, pergioco_strip_code, public.admin_codes(), public.admin_delete_code(), public.admin_new_code(), public.member_codes, public.reset_password_with_code() (+3 more)

### Community 64 - "v41.13.3-agenda.test.js"
Cohesion: 0.14
Nodes (9): fs, http, path, pw, ROOT, srv, T, TYPES3 (+1 more)

### Community 65 - "v41.14-config.test.js"
Cohesion: 0.14
Nodes (8): fs, http, NEW, path, pw, SET, T, TYPES

### Community 66 - "v41.18.2-elimina-unit.test.js"
Cohesion: 0.14
Nodes (11): app, cons, data, fs, gio, path, root, sb (+3 more)

### Community 67 - "v41.18.3-mostra.test.js"
Cohesion: 0.14
Nodes (6): fs, http, MIME, path, pw, ROOT

### Community 68 - "mie-partite.js"
Cohesion: 0.35
Nodes (11): draw(), esitoMine(), filterPlays(), line(), periodRange(), playerLabel(), playName(), playTypeId() (+3 more)

### Community 69 - "profilo.js"
Cohesion: 0.40
Nodes (12): apply(), badges(), head(), hero(), hist(), mates(), more(), perFrom() (+4 more)

### Community 70 - "v41.13-sondaggi-unit.test.js"
Cohesion: 0.15
Nodes (11): brand, cm, css, fs, idx, js, low, path (+3 more)

### Community 71 - "v41.14.3-mie-partite.test.js"
Cohesion: 0.17
Nodes (10): fs, http, makePlays(), MIME, path, pw, ROOT, seed() (+2 more)

### Community 72 - "v41.19-bp1-unit.test.js"
Cohesion: 0.15
Nodes (10): app, ctx, data, fs, libri, path, root, sb (+2 more)

### Community 73 - "migrate-v26.sql"
Cohesion: 0.33
Nodes (10): antero_albo_created_idx, antero_albo_fill, antero_albo_trim, antero_mecc_norm, antero_meccaniche_nome_uq, public.antero_albo, public.antero_albo_fill(), public.antero_albo_trim() (+2 more)

### Community 74 - "v41.1-identico.test.js"
Cohesion: 0.17
Nodes (7): {execSync}, fs, http, path, pw, srv, T

### Community 75 - "ref_http"
Cohesion: 0.18
Nodes (9): fs, http, MIME, path, pw, ROOT, seed(), srv (+1 more)

### Community 76 - "v40.test.js"
Cohesion: 0.17
Nodes (8): app, css, ev, fs, idx, sb, sw, ux

### Community 77 - "v41.11.1-tavoli.test.js"
Cohesion: 0.17
Nodes (8): fs, http, path, PNG1, pw, ROOT, srv, T

### Community 78 - "v41.11.1-tavoli-unit.test.js"
Cohesion: 0.17
Nodes (9): app, brand, data, fs, js, mig, path, root (+1 more)

### Community 79 - "v41.11-tavoli-unit.test.js"
Cohesion: 0.17
Nodes (9): brand, fs, ix, js, meta, mig, path, root (+1 more)

### Community 80 - "v41.12-gdr.test.js"
Cohesion: 0.17
Nodes (8): fs, gdrPlays, http, path, pw, ROOT, srv, T

### Community 81 - "v41.13.1-header.test.js"
Cohesion: 0.17
Nodes (7): fs, http, path, pw, ROOT, srv, T

### Community 82 - "v41.13.2-sondaggi.test.js"
Cohesion: 0.17
Nodes (8): fs, http, path, POLL, pw, ROOT, srv, T

### Community 83 - "v41.13.2-sondaggi-unit.test.js"
Cohesion: 0.17
Nodes (9): brand, cm, css, fs, idx, js, path, ROOT (+1 more)

### Community 84 - "v41.13-sondaggi.test.js"
Cohesion: 0.17
Nodes (8): fs, http, path, POLL, pw, ROOT, srv, T

### Community 85 - "v41.14.3-host-non-lascia.test.js"
Cohesion: 0.17
Nodes (8): fs, http, MIME, path, pw, ROOT, srv, TYPES

### Community 86 - "v41.14-tavolo-testo.test.js"
Cohesion: 0.18
Nodes (9): fs, http, MIME, openSheet(), path, pw, ROOT, srv (+1 more)

### Community 87 - "stats.js"
Cohesion: 0.36
Nodes (10): calc(), from(), gameAssoc(), gameMine(), gameMount(), html(), months12(), mount() (+2 more)

### Community 88 - "picker.test.js"
Cohesion: 0.18
Nodes (7): app, fs, gs, html, ps, sc, src

### Community 89 - "v41.14-config-unit.test.js"
Cohesion: 0.18
Nodes (8): br, css, fs, idx, js, path, R, sw

### Community 90 - "v41.18-unit.test.js"
Cohesion: 0.18
Nodes (8): app, css, fs, path, root, sb, sch, sql

### Community 91 - "agSheet"
Cohesion: 0.27
Nodes (10): agLbl(), agSheet(), backClose(), _bkPush(), condividiTavolo(), dayLbl(), dayName(), isoOk() (+2 more)

### Community 92 - "desideri.js"
Cohesion: 0.44
Nodes (9): DS, dsBind(), dsData(), dsDo(), dsDraw(), dsHtml(), dsInfo(), dsMsg() (+1 more)

### Community 93 - "manifest.json"
Cohesion: 0.20
Nodes (9): background_color, display, icons, lang, name, scope, short_name, start_url (+1 more)

### Community 94 - "v41.8-giochi.test.js"
Cohesion: 0.24
Nodes (5): pw, gio(), pw, fs, pw

### Community 95 - "v41.2-partita.test.js"
Cohesion: 0.27
Nodes (6): pw, fill(), pw, setup(), fs, pw

### Community 96 - "v39.2.test.js"
Cohesion: 0.20
Nodes (6): css, f, fs, h, nt, src

### Community 97 - "coppa.js"
Cohesion: 0.33
Nodes (8): CP, cpBind(), cpCard(), cpD(), cpDur(), _cpMs, cpMsg(), cpNome()

### Community 98 - "migrate-v9.sql"
Cohesion: 0.33
Nodes (6): public.admin_codes(), public.admin_moderators(), public.admin_new_code(), public.admin_set_moderator(), public.is_moderator(), public.moderators

### Community 99 - "antero.js"
Cohesion: 0.32
Nodes (7): ANT, ANTDB, antModal(), antToast(), FRASI_GIUDIZIO, FRASI_SANTINO, openAntero()

### Community 100 - "authForm"
Cohesion: 0.25
Nodes (8): authForm(), bindPwShow(), gate(), normEmail(), okEmail(), pwChangeVal(), pwProfilo(), revealPw()

### Community 101 - "pfHtml"
Cohesion: 0.29
Nodes (8): pf(), pfGet(), pfHtml(), pfIn(), pfRange(), pfSet(), playWarn(), romeEveningDate()

### Community 102 - "brand.js"
Cohesion: 0.25
Nodes (6): BRAND, BRAND_DEF, MOD, MOD_DEF, TXT, TXT_DEF

### Community 103 - "migrate-v25.sql"
Cohesion: 0.46
Nodes (7): game_meta_check, game_meta_on_game, game_meta_status_idx, public.game_meta, public.game_meta_check(), public.game_meta_on_game(), public.staff_meta_pending()

### Community 105 - "v41.18.test.js"
Cohesion: 0.32
Nodes (6): boot(), fs, openMods(), path, pw, W()

### Community 106 - "Ia"
Cohesion: 0.54
Nodes (8): Bd(), Gd(), Ia(), Id(), rd(), ud(), wd(), zd()

### Community 107 - "v39.1.test.js"
Cohesion: 0.29
Nodes (4): A, fs, pw, S

### Community 108 - "equilibrio.js"
Cohesion: 0.33
Nodes (4): EQ, EQD, EQP, EQT

### Community 109 - "gdr-rec.js"
Cohesion: 0.33
Nodes (5): GDRB, GDRB_BADGE_DEF, GDRB_MESI, GDRB_REC, GDRB_REC_DEF

### Community 110 - "package.json"
Cohesion: 0.33
Nodes (5): description, name, private, scripts, test

### Community 111 - "picker.js"
Cohesion: 0.60
Nodes (5): gpFilter(), gpImg(), gpMount(), gpNorm(), gpShort()

### Community 112 - "sb.js"
Cohesion: 0.40
Nodes (4): isMissing(), isNet(), MAP, SupabaseAdapter

### Community 113 - "v40.5.1.test.js"
Cohesion: 0.33
Nodes (3): fs, gj, sw

### Community 114 - "Procedura di rilascio"
Cohesion: 0.40
Nodes (4): Ambienti, Procedura di rilascio, Pubblicare in produzione, Pubblicare sul test

### Community 115 - "test-all.sh"
Cohesion: 0.50
Nodes (3): NODE_PATH, runone(), test-all.sh script

### Community 116 - "migrate-v29.sql"
Cohesion: 0.60
Nodes (3): mpg_stamp, public.member_profile_gioco, public.mpg_stamp()

### Community 117 - "v40.1b.test.js"
Cohesion: 0.40
Nodes (3): css, fs, sw

### Community 118 - "v40.5.test.js"
Cohesion: 0.40
Nodes (3): fs, idx, sw

## Knowledge Gaps
- **1 isolated node(s):** `NODE_PATH`
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 1108 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **48 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `x()` connect `N` to `make_xlsx_lib`, `A`, `Ra`, `xe`, `B`, `v41.14-password-unit.test.js`?**
  _High betweenness centrality (0.113) - this node is a cross-community bridge._
- **Are the 170 inferred relationships involving `make_xlsx_lib()` (e.g. with `aA()` and `Ad()`) actually correct?**
  _`make_xlsx_lib()` has 170 INFERRED edges - model-reasoned connections that need verification._
- **What connects `NODE_PATH` to the rest of the system?**
  _1 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `make_xlsx_lib` be split into smaller, more focused modules?**
  _Cohesion score 0.0276464542651593 - nodes in this community are weakly interconnected._
- **Why does `make_xlsx_lib()` connect `make_xlsx_lib` to `A`, `Ra`, `N`, `ct`, `fv`, `xk`, `Ia`, `xe`, `B`?**
  _High betweenness centrality (0.109) - this node is a cross-community bridge._
- **Are the 57 inferred relationships involving `A()` (e.g. with `an()` and `c()`) actually correct?**
  _`A()` has 57 INFERRED edges - model-reasoned connections that need verification._
- **Should `A` be split into smaller, more focused modules?**
  _Cohesion score 0.06358543417366946 - nodes in this community are weakly interconnected._
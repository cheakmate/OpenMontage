# Archive.org Source

> 24 nodes · cohesion 0.12

## Key Concepts

- **archive_org.py** (14 connections) — `tools/video/stock_sources/archive_org.py`
- **._hydrate_candidate()** (10 connections) — `tools/video/stock_sources/archive_org.py`
- **ArchiveOrgSource** (9 connections) — `tools/video/stock_sources/archive_org.py`
- **.search()** (6 connections) — `tools/video/stock_sources/archive_org.py`
- **_safe_int()** (5 connections) — `tools/video/stock_sources/archive_org.py`
- **._build_queries()** (4 connections) — `tools/video/stock_sources/archive_org.py`
- **_parse_length()** (4 connections) — `tools/video/stock_sources/archive_org.py`
- **_pick_video_file()** (4 connections) — `tools/video/stock_sources/archive_org.py`
- **_to_text()** (4 connections) — `tools/video/stock_sources/archive_org.py`
- **_license_from_collection()** (3 connections) — `tools/video/stock_sources/archive_org.py`
- **_looks_like_year()** (3 connections) — `tools/video/stock_sources/archive_org.py`
- **Any** (3 connections)
- **.is_available()** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Archive.org stock video adapter. Targets public-domain film and home-movie…** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Search Archive.org for matching video items. Two-stage: (1) advancedsearch for…** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Build a cascade of Solr queries to try in preference order. Archive.org's Solr…** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Turn a search-doc identifier into a full Candidate. Fetches the item's file…** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **True if token is a bare year or year-with-decade-suffix. Examples: ``"1950"``,…** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Pick the best playable video file from an Archive.org files list. Preference…** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Parse Archive.org's `length` field into seconds. The field is usually…** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Parse a value to int, tolerating strings, None, and garbage.** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Flatten Archive.org's sometimes-list-sometimes-string fields. The search API…** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Infer licence text from a collection name when no licenseurl is set. Prelinger…** (1 connections) — `tools/video/stock_sources/archive_org.py`
- **Adapter for public-domain video on archive.org. Satisfies `StockSource`.…** (1 connections) — `tools/video/stock_sources/archive_org.py`

## Relationships

- [Media Source Adapters](Media_Source_Adapters.md) (9 shared connections)
- [Pexels Source Adapter](Pexels_Source_Adapter.md) (1 shared connections)
- [Wikimedia Media Adapter](Wikimedia_Media_Adapter.md) (1 shared connections)
- [Core Utilities](Core_Utilities.md) (1 shared connections)
- [Tool Testing](Tool_Testing.md) (1 shared connections)

## Source Files

- `tools/video/stock_sources/archive_org.py`

## Audit Trail

- EXTRACTED: 45 (96%)
- INFERRED: 2 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*
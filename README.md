# IPTV Playlist

A merged, deduplicated M3U playlist aggregated from multiple sources — organized so channels with multiple stream URLs are grouped under a single name with server fallbacks.

---

## Contents

| File | Description |
|------|-------------|
| `merged_playlist.m3u` | Main playlist — all channels merged and deduplicated |

**Stats**

- 579 unique channels
- 670 total stream entries
- 66 channels with multiple server fallbacks
- Sources: 3 input playlists merged

---

## Channel Naming Convention

When a channel has more than one stream URL, entries are named as follows:

```
Somoy TV              ← primary stream
Somoy TV 2nd Server   ← fallback 1
Somoy TV 3rd Server   ← fallback 2
```

This makes it easy to switch servers inside any IPTV player if the primary stream goes down.

---

## How to Use

**VLC**
```
Media → Open Network Stream → paste raw URL of merged_playlist.m3u
```

**Kodi / IPTV Simple Client**
```
Settings → PVR & Live TV → IPTV Simple Client → M3U Playlist URL
```

**TiviMate / OTT Navigator / Televizo (Android)**
```
Add Playlist → M3U URL → paste the raw file URL
```

**MPV**
```bash
mpv merged_playlist.m3u
```

---

## Categories

Channels are organized into the following groups:

`News` · `Bangla` · `Entertainment` · `Movies` · `Sports` · `Kids` · `Music` · `Religious` · `Documentary` · `Indian` · `Infotainment` · `Live Event`

---

## Disclaimer

This repository does not host any video content. It only aggregates publicly available stream URLs for personal use. All streams belong to their respective owners. If you are a rights holder and have concerns, please open an issue.

---

## Update

Last merged: 2026-06-06

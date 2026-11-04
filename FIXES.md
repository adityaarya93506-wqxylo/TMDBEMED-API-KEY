# Zylo fixes (TMDB-Embed-API)

- utils/user-config.json: saare 13 providers ON; disable4khdhubUrlValidation=true (4khdhub tez)
- providers/registry.js: har stream normalize (type hls/mp4, resolution, container=mkv, headers)
- utils/aggregate.js (NEW): fast providers ka result turant, slow wale background me; `partial` + `pending`
- apiServer.js: /api/streams?wait=ms&refresh=1, /api/selftest (har provider ka health), /api/config ab login ke peeche
- providers/onetouchtv.js: CDN Referer/Origin/UA fix (HTTP 403)
- providers/zxcstreams.js: type ab output me jaata hai

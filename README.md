# config-backup

Photobooth runtime configuration backups (`photobooth-data/config/`).

| File | Description |
|------|-------------|
| `config.json` | Active booth config |
| `config.json_backup-20260522-202428` | Latest automatic backup before a config save |

Restore on the booth:

```bash
cp config.json ~/instabooth/photobooth-data/config/config.json
cd ~/instabooth/photobooth-data && photobooth
```

**Warning:** Contains booth secrets (e.g. admin password). This repo is public.

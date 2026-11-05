# Module 5 — Part 3: Yarrow-Mullein Bank

## Run on Windows (Docker Desktop)
Open PowerShell in this directory and run:

```powershell
docker compose config
docker compose up --build -d
docker compose ps
```

Open http://localhost and http://localhost/api/register.


## Architecture
NGINX port 80 routes static student portfolio, Flask banking backend and Node.js transactions reporting, backed by MongoDB.

## Notes
The CI and service configuration must be tested on your Windows Docker environment before submission. Screenshots must come from real runs, not simulated output.

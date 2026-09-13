# E2 · Arqueología DNS

**Fecha:** 12 sep 2026
**Herramienta:** nslookup (Git Bash, Windows 10)
**Resolver que respondió:** dns5.emcali.net.co (200.29.96.24)

## Mediciones

| Sitio | Tipo | IP(s) | TTL | Registro |
|---|---|---|---|---|
| eltiempo.com | colombiano | 20.57.95.139 | 300 s (5 min) | A |
| spotify.com | global | 35.186.224.24<br>2600:1901:1:7c5:: | 193 s (3 min 13 s) | A + AAAA |
| asapdaniel00.github.io | mío | 185.199.108.153<br>185.199.109.153<br>185.199.110.153<br>185.199.111.153<br>2606:50c0:8000::153<br>2606:50c0:8001::153<br>2606:50c0:8002::153<br>2606:50c0:8003::153 | 2637 s (43 min 57 s) | A + AAAA |

## Prueba de caché

Misma consulta a eltiempo.com, dos veces:

| Hora | TTL |
|---|---|
| 4:41 pm | 162 |
| 4:42 pm | 100 |
# Estado da CTRLYFE + Family

Página de estado pública da app CTRLYFE + Family: https://gc2026code.github.io/ctrlyfe-estado/

- `.github/workflows/monitor.yml` verifica https://ctrlyfe.app e https://api.ctrlyfe.app/health de 5 em 5 minutos.
  Se falhar 3 vezes seguidas, abre um aviso (issue «incidente»), que chega ao dono por email e pela app GitHub; fecha-o quando a app volta.
- `status.json` guarda o estado e os avisos recentes; `index.html` mostra-os.

Este repositório não tem código da app, segredos nem dados de pessoas.

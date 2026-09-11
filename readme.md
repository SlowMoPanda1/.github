<h1 align="center">⚙️ SlowMoPanda1 — GitHub Health & Workflows</h1>
<p align="center">
  <b>Repositorio Central de Workflows, Actions y Estándares de Código</b><br>
  <i>"Centralizando linters, formateadores y acciones automatizadas para todos los proyectos."</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/GITHUB-CONFIG-00f2ff?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/ACTIONS-WORKFLOWS-blueviolet?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/ENVIRONMENT-STABLE-success?style=for-the-badge&logo=statuspage&logoColor=white" />
</p>

---

### 📌 Propósito del Repositorio

Este repositorio almacena las **configuraciones globales de GitHub** para automatizar el formateo de código, linters, etiquetado automático y flujos de trabajo reutilizables en mis diferentes proyectos.

---

### 🛠️ Contenido del Repositorio

* **`actions/`**: Scripts internos y herramientas auxiliares de Node.js para formateo y versionado automático (`bump-manifest-version.js`, `replacer-for-formatter.js`, etc.).
* **`workflows/`**: Automatizaciones de GitHub Actions en YAML:
  * **Formateadores & Linters:** `formatter-lua.yml`, `formatter-web.yml`, `lua-lint.yml`.
  * **Releases & Sync:** `simple-release.yml`, `simple-release-web.yml`, `sync-labels.yml`.
  * **Gestión:** `automatic-add-issue-to-board.yml` y `config-labels.yml`.
* **Archivos de Configuración:** Reglas de estilo globales como `.prettierrc.json` y `stylua.toml`.
* **`profile/`**: Perfil público de GitHub (`README.md`) y el acuerdo legal de licencias ([`CLA.md`](./profile/CLA.md)).

---

### 📂 Estructura del Proyecto

```text
.github/
├── actions/             # Scripts de Node.js y utilidades internas
├── workflows/           # Workflows reutilizables de CI/CD (Lua, Web, Releases, etc.)
├── profile/
│   ├── README.md        # Perfil público principal de GitHub
│   └── CLA.md           # Acuerdo de Licencia y Propiedad Intelectual
├── .prettierrc.json     # Configuración global de Prettier (JS/TS/Web)
├── stylua.toml          # Configuración global de StyLua
└── readme.md            # Documentación de este repositorio

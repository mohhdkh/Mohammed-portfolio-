# Mohammed Khattab — Developer Portfolio

A responsive portfolio presenting selected mobile and full-stack work, the engineering decisions behind it, and direct evidence that reviewers can inspect.

## Featured engineering evidence

[Secure TaskFlow](https://github.com/mohhdkh/secure-taskflow) is the public, end-to-end code sample connected to this portfolio. It includes:

- React + TypeScript Arabic RTL interface;
- FastAPI and PostgreSQL backend;
- JWT authentication and server-enforced authorization;
- negative-path and cross-user security tests;
- a PostgreSQL-backed GitHub Actions quality gate;
- a documented [technical case study](https://github.com/mohhdkh/secure-taskflow/blob/main/docs/case-study.md) and [measured evidence](https://github.com/mohhdkh/secure-taskflow/blob/main/docs/engineering-evidence.md).

The remaining project cards demonstrate broader product work across mobile, emergency-support, record-management and object-oriented systems without publishing private customer source code.

## Preview locally

No build step is required:

```bash
git clone https://github.com/mohhdkh/Mohammed-portfolio-.git
cd Mohammed-portfolio-
python -m http.server 8080
```

Open `http://localhost:8080`.

## Repository structure

```text
index.html   Semantic portfolio content
style.css    Responsive layout and light/dark themes
script.js    Navigation, reveal effects and saved theme preference
assets/      Project visuals and downloadable CV
```

## Links

- [GitHub profile](https://github.com/mohhdkh)
- [LinkedIn](https://www.linkedin.com/in/mohammed-khattab1/)
- [Secure TaskFlow source](https://github.com/mohhdkh/secure-taskflow)
- [Secure TaskFlow CI](https://github.com/mohhdkh/secure-taskflow/actions)

All portfolio content uses demonstration material. No production credentials, customer records or patient information are included.

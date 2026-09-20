# Territorial Structure Explorer — Interactive Map

Interactive web map for visualizing and comparing territorial structures through a browser-based geographic interface.

The application uses Leaflet to present geographic scenarios and supporting contextual information in a compact static web application.

## Core capabilities

- interactive geographic visualization;
- scenario switching;
- municipality-level territorial inspection;
- contextual legends and notes;
- responsive map and information panels;
- lightweight deployment without a backend.

## Technology stack

| Area | Technologies |
| --- | --- |
| Interface | HTML5, CSS3, JavaScript |
| Mapping | Leaflet |
| Deployment | Static web hosting |
| Data representation | Geographic / territorial datasets |

## Application concept

```text
Territorial data
      │
      ▼
Scenario configuration
      │
      ▼
Leaflet layers
      │
      ├── map
      ├── municipality information
      └── contextual legend
```

## Running locally

Because the project is static, it can be served with any simple HTTP server:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Engineering highlights

This project demonstrates how territorial-analysis outputs can be communicated through a low-complexity web layer. The browser interface remains independent from heavier analytical pipelines, making deployment simple and portable.

## Data responsibility

Territorial and institutional data should be validated before publication. Public versions should exclude information that could expose operationally sensitive details.

---

**Portfolio focus:** geospatial visualization · Leaflet · static web engineering · territorial analysis

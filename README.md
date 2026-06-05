# Apache Zeppelin (apache-zeppelin)

Apache Zeppelin is a web-based notebook that enables data-driven, interactive data analytics and collaborative documents with SQL, Scala, Python, R, and more. It provides built-in data visualization, collaboration features, and interpreter integration with Apache Spark, JDBC, Python, R, Shell, and 20+ other backends. Zeppelin exposes a REST API for notebook management, interpreter configuration, and job execution. It is maintained by the Apache Software Foundation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-zeppelin/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-zeppelin/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Data Analytics
- Interactive Computing
- Notebook
- Visualization
- Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache Zeppelin REST API

The Zeppelin REST API provides HTTP endpoints for managing notebooks, notes, paragraphs, interpreters, and credentials. Key endpoints include: GET/POST /api/notebook for notebook CRUD, GET/POST /api/notebook/{noteId}/paragraph for paragraph management, POST /api/notebook/job/{noteId} for running all paragraphs, GET /api/interpreter/setting for interpreter listing, and POST /api/interpreter/setting/restart for restarting interpreters. Returns JSON responses with status codes.

- **Human URL:** [https://zeppelin.apache.org/docs/latest/usage/rest_api/notebook.html](https://zeppelin.apache.org/docs/latest/usage/rest_api/notebook.html)

#### Tags

- REST
- Notebooks
- Paragraphs
- Interpreter

#### Properties

- [Documentation](https://zeppelin.apache.org/docs/latest/usage/rest_api/notebook.html)
- [Documentation](https://zeppelin.apache.org/docs/latest/usage/rest_api/interpreter.html)
- [OpenAPI](openapi/apache-zeppelin-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-zeppelin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-zeppelin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Repository](https://github.com/apache/zeppelin)
- [Documentation](https://zeppelin.apache.org/docs/latest/)
- [Portal](https://zeppelin.apache.org/)
- [Getting Started](https://zeppelin.apache.org/docs/latest/quickstart/install.html)
- [Release Notes](https://github.com/apache/zeppelin/releases)
- [Support](https://zeppelin.apache.org/community.html)
- [Terms of Service](https://www.apache.org/licenses/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com

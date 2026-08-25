# Repository Guide for Coding Agents

## Mandatory development checklist

Before completing a change, run every gate from `socops/`:

- [ ] Lint/quality: `./mvnw validate`
- [ ] Build: `./mvnw clean package`
- [ ] Tests: `./mvnw test`

## Project and change guidance

- `socops/` is the Spring Boot app; `docs/` is a separate workshop site. `BingoRestController` serves the page and `GET /api/bingo/fresh-board`.
- `BoardAssembler` owns pure board rules; models are in `com/socops/model/`. Browser state/rules are in `game.html`; CSS utilities are in `static/css/app.css`. Keep Java and JavaScript synchronized.
- Boards are 5 x 5 with IDs 0-24; cell 12 is the selected free center. The browser snapshot uses `localStorage` key `socops-bingo-snapshot`; there is no backend persistence.
- Prefer records/static methods for pure Java. Add focused tests under `socops/src/test/java/`, following `BoardAssemblerTests.java`.
- Follow the [CSS](.github/instructions/css-utilities.instructions.md) and [frontend](.github/instructions/frontend-design.instructions.md) instructions; keep game text in English unless translations are requested.
- Use Java 21 and port 8080. Smoke-test browser changes through the running server; opening `game.html` locally is invalid because it fetches the API.

See [README](README.md) for setup and [workshop/GUIDE.md](workshop/GUIDE.md) for lab context.

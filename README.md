# OpenCart Manual QA

Manual testing project for [OpenCart Demo](https://demo.opencart.com).

## Project Structure

| Артефакт | Описание |
|----------|----------|
| `test-plan.md` | Test plan: scope, entry/exit criteria, environment |
| `test-cases/` | 29 test cases across 5 modules |
| `bug-reports/` | 5 bug reports with screenshots |
| `checklists/` | Reserved for checklists |

## Test Coverage

| Модуль | Кейсов | Багов |
|--------|--------|-------|
| Auth | 8 | 3 |
| Catalog | 4 | 0 |
| Cart | 8 | 2 |
| Checkout | 6 | 0 |
| Account | 3 | 0 |
| **Total** | **29** | **5** |

## Bugs Found

| ID | Title | Severity | Status |
|----|-------|----------|--------|
| BUG-001 | Registration accepts single-character first name | Major | Open |
| BUG-002 | Registration accepts special characters in first name | Major | Open |
| BUG-003 | XSS input silently blocks registration with no error | Major | Open |
| BUG-004 | Cart UI broken after invalid quantity input | Major | Open |
| BUG-005 | Stock error shown only at checkout, not at cart update | Minor | Open |

## Environment

| Параметр | Значение |
|----------|----------|
| ОС | Windows 10 |
| Браузер | Chrome (latest) |
| Разрешение | 1920x1080 |

## Tools
Markdown, GitHub, Chrome DevTools
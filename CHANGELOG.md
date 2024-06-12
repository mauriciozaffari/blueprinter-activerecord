### 1.1.1 (2024-06-12)
- [BUGFIX] Fixes an infinite loop when [a Blueprint has an association to itself](https://github.com/procore-oss/blueprinter-activerecord/issues/13)

### 1.1.0 (2024-06-10)
- [FEATURE] Ability to annotate a field or association for extra preloads (e.g. `field :category_name, preload: :category`)

### 1.0.2 (2024-05-21)

- [BUGFIX] Fixes a potentially significant performance issue with `auto`. See https://github.com/procore-oss/blueprinter-activerecord/pull/16.

### 1.0.1 (2024-02-09)

- Fix gem summary

## 1.0.0 (2024-02-09)

- Initial release

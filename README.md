# Spaces

| Bezeichnung / Auflösung | 320 | 768 | 1024 | 1440 | 1920 |
|-------------------------|-----|-----|------|------|------|
| xxxs                    | 4   | 4   | 4    | 4    | 4    |
| xxs                     | 8   | 8   | 8    | 8    | 8    |
| xs                      | 12  | 12  | 12   | 12   | 12   |
| s                       | 16  | 16  | 16   | 16   | 16   |
| ms                      | 24  | 24  | 24   | 24   | 24   |
| m                       | 32  | 32  | 36   | 36   | 42   |
| l                       | 36  | 36  | 42   | 48   | 54   |
| xl                      | 42  | 42  | 54   | 64   | 76   |
| xxl                     | 48  | 54  | 64   | 76   | 96   |
| xxxl                    | 54  | 64  | 76   | 96   | 128  |

## Usage

```--var(space-xxxs)
--var(space-xxs)
--var(space-xs)
--var(space-s)
--var(space-ms)
--var(space-m)
--var(space-l)
--var(space-xl)
--var(space-xxl)
--var(space-xxxl)
```

## Example

.element {
  padding: --var(space-xxxs)
}

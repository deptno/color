# @deptno/color

[![npm](https://img.shields.io/npm/dt/@deptno/color.svg?style=for-the-badge)](https://www.npmjs.com/package/@deptno/color)

color schema

## install
```shell script
npm install @deptno/color
```

## usage
ensure you already have webpack css-loader config
```tsx
/* _app.tsx */
import '@deptno/color/style.css'
```
```tsx
/* ColorComponent */
export const ColorComponent = _ => <div className="d-bg-yellow d-yellow">done!</div>
```

## color palette
![color palette](color-palette.png)

## color class names
### color
```
.d-white
.d-yellow
.d-tomato
.d-rose
.d-green
.d-orange
.d-gold
.d-blue
.d-navy
.d-gray
```
### background-color
```
.d-bg-white
.d-bg-yellow
.d-bg-tomato
.d-bg-rose
.d-bg-green
.d-bg-orange
.d-bg-gold
.d-bg-blue
.d-bg-navy
.d-bg-gray
```
### named color pair sets(background-color/color)
```
.schema-border
.schema-create
.schema-update
.schema-cancel
.schema-delete
.schema-connect
.schema-search
.schema-reset
.schema-action
.schema-move
.schema-external
.schema-expandable1
.schema-expandable2
.schema-disabled
```
### typescriptlang.org color
```typescript jsx
import '@deptno/color/typescriptlang.css'
```
```
.bg-ts-blue-a
.bg-ts-blue-b
.bg-ts-blue-c

.ts-blue-a
.ts-blue-b
.ts-blue-c

.b--ts-blue-a
.b--ts-blue-b
.b--ts-blue-c
```

## contributors
@deptno, @sohee-lee7, @hhaze

## changelog
1.1.0 - typescriptlang.org

## license
MIT

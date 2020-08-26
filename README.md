# @deptno/color

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
- `#f2f2f2` --d-white
- `#f2b705` --d-yellow
- `#f2220f` --d-tomato
- `#bf0404` --d-rose
- `#5C9141` --d-green
- `#F5A502` --d-orange
- `#FCC109` --d-gold
- `#547DBF` --d-blue
- `#243265` --d-navy
- `#555555` --d-gray
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

---
## contributors
@deptno, @sohee-lee7, @hhaze

## license
MIT

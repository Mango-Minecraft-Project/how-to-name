# Tags

## Base Rule

1. Use plural
2. Only `c:tag`

---

- [Tags](#tags)
  - [Base Rule](#base-rule)
  - [list of tag](#list-of-tag)
    - [A little tips](#a-little-tips)
  - [How to use tag set](#how-to-use-tag-set)
    - [Directory](#directory)
    - [Content](#content)

---

## list of tag

- dusts
- dyes
- gears
- gems
- ingots
- nuggets
- plates
- sticks
- logs
- planks
- 

### A little tips

- do not use `rods/iron` or else

## How to use tag set

### Directory

Example File: [example/data/c/tags](../example/data/c/tags/)

```
tags
 ├─ingots
 │  └─iron.json
 └─ingots.json
```

### Content
- `tags/ingots.json`
  ```json
  {
  "values": [
      "#c:ingots/iron"
    ]
  }
  ```

- `tags/ingots/iron.json`
  ```json
  {
    "values": [
      "minecraft:iron_ingot"
    ]
  }
  ```
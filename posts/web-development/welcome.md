---
title: "Testing different elements"
date: "2020-01-23"
description: "This post tests the styling of all the different elements that may appear in a post."
tags:
  - Web Development
---

# A title

Lorem ipsum dolor sit amet consectetur adipisicing elit. **Aliquam laboriosam incidunt porro.** Fuga culpa voluptate expedita _fugiat_ optio ducimus, cum pariatur repellat nisi eveniet omnis ad soluta placeat deleniti aliquam?

## The paragraph below contains a link

Lorem ipsum dolor sit amet, [consectetur](#) adipiscing elit.

## Horizontal Rule

---

## Here are all the headings

## h2

### h3

#### h4

##### h5

###### h6

## Image

![Placeholder](/img/placeholder.png "Placeholder")

## Unordered List

- Item
- Item
- Item
- Item
- Item

## Ordered List

1. Item
2. Item
3. Item
4. Item
5. Item
6. Item

## Table

| Tables        |      Are      |   Cool |
| ------------- | :-----------: | -----: |
| col 3 is      | right-aligned | \$1600 |
| col 2 is      |   centered    |   \$12 |
| zebra stripes |   are neat    |    \$1 |

## Code

```
const username = ''
const password = ''

const token = Buffer.from(`${username}:${password}`, 'utf8').toString('base64')

const url = 'https://...'

axios.post(url, {
  headers: {
  'Authorization': `Basic ${token}`
  }
})
```

## Blockquote

> Somebody said something

---
weight: 999
title: "Example Page"
description: "This is an example"
icon: "article"
date: "2025-09-24T12:43:13+02:00"
lastmod: "2025-09-24T12:43:13+02:00"
draft: false
toc: true
---

# Hello World
This is an example diagram

```mermaid
sequenceDiagram
Alice->>John: Hello John, how are you?
John-->>Alice: Great!
John->>Bob: How about you?
Bob-->>John: Jolly good!
```

# Examples
## More
### More

This is an alert with a **bold** and a code block `code` and some *italic* text.

{{< alert text="This is the default alert. It consists of a default theme colour and icon." />}}

- My list 1
- My list 2
- My list 3

```kotlin
fun test() {
    printLn("Ahhh")
}
```

## Testing
- [ ] Check
- [ ] Check 2

### More
1. a
2. b
3. d

{{% alert context="warning" text="This is an alert." /%}}

## Code Block Examples

Code block language examples

### Go

```go
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```

### HTML

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>
</html>
```

### Markdown

```md
# H1 heading

**Some bold text**

*Italic text example*
```

This is a recursive file finder

## Getting Started

First, install:

```bash
npm i files
```

Then use in your code

```bash
import { find } from "files"


const dir = "/path/to/my/images"
const ext = ["jpg", "jpeg", "png", "webp"]

const images = await find(dir, ext)
console.log(images)
```
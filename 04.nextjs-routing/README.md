# Next JS Routing 
**Next.js has a file system based routing system URLs you can access in your browser are determined by how organize your files and floders in your code**



1. All routes must live inside the app folder
2. Route file must be name either page.js or page.jsx
3. Each folder represents a sagament of the URL path

```
export default function Page() {
    return <h1>This is Page</h1>
}
```

## Creating Link in Next Js

```
import Link from "next/link"

<Link href="/page">Back</Link>
```

## Creating Link Using Button

```
"use client"

import { useRouter } from "next/navigation"

const router = useRouter();

<button onClick={() => router.push('/')}>Back</button>
```


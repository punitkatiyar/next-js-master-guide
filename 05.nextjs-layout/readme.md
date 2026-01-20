# Next Js Layout 
```
"use client"
import Link from "next/link";
export default function Layout({
    children
}) {
    return (
        <>
            <header>
                <h1>This is page</h1>
            </header>
            <nav>
                <ul>
                    <li><Link href="/">Home</Link></li>
                    <li><Link href="/page">Page</Link></li>
                    <li><Link href="/page/one">Page One</Link></li>
                </ul>
            </nav>
            {
                children
            }
        </>
    )
}

```

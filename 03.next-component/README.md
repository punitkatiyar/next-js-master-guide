# Nextjs components

> server component : default

## client component : 'use client'

> Render on the Client Side

> UI And events should be writen

```
// import Image from "next/image";
"use client"

import { useState } from 'react';
import styles from './page.module.css'

export default function Home() {

  const [userName, setUserName] = useState("Guest")



  // example 1
  let title = "Next App Title";

  const tab = (data) => {
    alert(`This is Next ${data}`);
  }
  return (

    <>
      <div className={styles.head}>
        <h1>{title}</h1>
      </div>
      <Banner />
      {/* Example Three  */}
      <button onClick={() => alert("Hello Tab")}>Click me</button>
      <button onClick={() => tab("Data Set")}>Click me</button>

      <hr />

      <h1>{userName}</h1>
      <button onClick={() => setUserName("Punit")}>Click me</button>


    </>
  );
}

{/* Example Two */ }
const Banner = () => {
  return (
    <>
      <img src="https://www.techunitbook.com/public/hello.webp" alt="image" />
    </>
  )
}
``` 

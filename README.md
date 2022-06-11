# Code Snippets for VS Code :rocket:

Code snippets for speeding up your workflow :zap:

> <strong>Note :</strong> These are my <strong>custom code snippets</strong> for front-end web development. However, they can be easily edited and more custom snippets can be added too.

These include snippets for :

- [Styled-Components](#styled-components-snippets)
- [Next-JS](#next-js-snippets)
- [React-JS](#react-js-snippets)
- [Javascript-ES6](#javascript-es6-snippets)

## Usage

- Bring up the command palette in VS Code by pressing <code>ctrl + shift + P</code> on linux or windows.
- Search for <code>Configure User Snippets</code> and press <code>Enter</code>
- Then select <code>New Global Snippets file...</code> and enter a name for your file.
- This will open a file with <code>.code-snippets</code> extension in VS Code.
- Just add the contents of <code>global-snippets.code-snippets</code> into your Global Snippets file. You can also edit this file in the future to add/delete snippets.
- Save and exit, now you can start using these snippets globally in all your projects :tada:

### Styled Components snippets

<table>
  <thead>
    <tr>
      <th>prefix</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>imsc</code></td>
      <td><code>import styled from 'styled-components';</code></td>
    </tr>
    <tr>
      <td><code>imscg</code></td>
      <td><code>import { createGlobalStyle } from 'styled-components';</code></td>
    </tr>
    <tr>
      <td><code>imscss</code></td>
      <td><code>import { css } from 'styled-components';</code></td>
    </tr>
    <tr>
      <td><code>imsctp</code></td>
      <td><code>import { ThemeProvider } from 'styled-components';</code></td>
    </tr>
    <tr>
      <td><code>sc</code></td>
      <td>template for a normal styled component</td>
    </tr>
    <tr>
      <td><code>scpd</code></td>
      <td>props(destructured) : <code>${({ props.? }}) => };</code></td>
    </tr>
    <tr>
      <td><code>scpt</code></td>
      <td>props.theme(destructured) : <code>${({ theme }) => theme.?};</code></td>
    </tr>
  </tbody>
</table>

### Next - JS snippets

<table>
  <thead>
    <tr>
      <th>prefix</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>nf</code></td>
      <td>nextJS normal export function with 'next/head' and other title, meta and link tags included</td>
    </tr>
    <tr>
      <td><code>gspr</code></td>
      <td><code>getStaticProps</code> template as async arrow function syntax</td>
    </tr>
    <tr>
      <td><code>gspa</code></td>
      <td><code>getStaticPaths</code> template as async arrow function syntax</td>
    </tr>
    <tr>
      <td><code>gsspr</code></td>
      <td><code>getServerSideProps</code> template as async arrow function syntax</td>
    </tr>
    <tr>
      <td><code>gipr</code></td>
      <td><code>getInitialProps</code> template as async arrow function syntax</td>
    </tr>
    <tr>
      <td><code>nii</code></td>
      <td><code>import Image from 'next/image';</td>
    </tr>
    <tr>
      <td><code>nil</code></td>
      <td><code>import Link from 'next/link';</td>
    </tr>
    <tr>
      <td><code>nih</code></td>
      <td><code>import Head from 'next/head';</td>
    </tr>
    <tr>
      <td><code>niur</code></td>
      <td><code>import {useRouter} from 'next/router';</td>
    </tr>
  </tbody>
</table>

### React - JS snippets

<table>
  <thead>
    <tr>
      <th>prefix</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>imus</code></td>
      <td><code>import { useState } from 'react';
</code></td>
    </tr>
    <tr>
      <td><code>imue</code></td>
      <td><code>import { useEffect } from 'react';
</code></td>
    </tr>
    <tr>
      <td><code>rus</code></td>
      <td>useState boilerplate</td>
    </tr>
    <tr>
      <td><code>rue</code></td>
      <td>useEffect boilerplate with clean-up function</td>
    </tr>
    <tr>
      <td><code>rfc</code></td>
      <td>react function component</td>
    </tr>
    <tr>
      <td><code>rfce</code></td>
      <td>react function component with export</td>
    </tr>
    <tr>
      <td><code>rafc</code></td>
      <td>react arrow function component</td>
    </tr>
    <tr>
      <td><code>rafce</code></td>
      <td>react arrow function component with export</td>
    </tr>
    
  </tbody>
</table>

### Javascript - ES6 snippets

<table>
  <thead>
    <tr>
      <th>prefix</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>clg</code></td>
      <td><code>console.log()</code></td>
    </tr>
    <tr>
      <td><code>cli</code></td>
      <td><code>console.info()</code></td>
    </tr>
    <tr>
      <td><code>fn</code></td>
      <td>javascript function : <code>function functionName() {}</code></td>
    </tr>
    <tr>
      <td><code>afn</code></td>
      <td>javascript arrow function : <code>const functionName = (params) => {}</code></td>
    </tr>
    <tr>
      <td><code>asyncfn</code></td>
      <td>javascript <strong>async</strong> arrow function : <code>const functionName = async(params) => {}</code></td>
    </tr>
  </tbody>
</table>

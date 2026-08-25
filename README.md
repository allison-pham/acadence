# Acadence
<div align="center">
    <strong>Acadence</strong> is a unified notification dashboard - web app + extension that includes notifications from various platforms.
</div>

<div align="center">

[![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/-TypeScript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Firebase](https://img.shields.io/badge/-Firebase-%23FFCA28.svg?style=flat-square&logo=firebase&logoColor=black)](https://firebase.google.com/)

</div>

## Features
Platforms that are possibly pulling notifications from: Canvas, Gradescope, zyBooks, etc.

## Getting Started
| **Step** | **Purpose** | **Instructions** |
|---|---|---|
| Git + GitHub Setup | Source code access | • Ensure Git is installed ([download](https://git-scm.com/install/windows) based on OS)<br>• Clone this GitHub repository using an IDE (e.g. Visual Studio Code)<br>&nbsp;&nbsp;&nbsp;&nbsp;• Click "Code" (green button) > HTTPS > copy the link<br>• Run `git clone "https://github.com/allison-pham/acadence"` |
| Installation | Local development | • Run `npm install` |
| Run locally (frontend) | Local development | • Open up terminal: `npm run dev`<br>• Open http://localhost:3000 |

- Generate a Canvas access token
    - Go to Account → Settings
    - Scroll to "Approved Intergrations" and click "+ New Access Token"
- Test API call
    - In terminal: run `curl -H "Authorization: Bearer CANVAS_TOKEN" https://canvas_url.com/api/v1/courses`
        - Ensure to replace "CANVAS_TOKEN" and "canvas_url.com" with the correct information
    - Upon running the command, it'll list couses